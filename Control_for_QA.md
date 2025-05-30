# F1 Charity API – Test Plan

## Purpose
This document outlines the quality assurance and performance expectations for the F1 Charity API and details the implementation of tests, alerts, and actions to ensure consistent access to accurate and reliable information. This serves as both an implementation guide and a living reference to ensure ongoing quality.

---

## Quality Objectives

- Ensure all API endpoints return expected responses with valid data
- Maintain fast response times under load
- Detect and alert failures (endpoint down, data corruption, etc.)
- Maintain consistent and secure access to JSON-based data structure

---

## Test Categories

### 1. Functional Testing

We will perform regular endpoint tests using Python and CI pipelines. Each test includes verification of HTTP responses and JSON structure validity.

- **Health Check (`/`)**
  - Confirms API is live and returning health message
  - Frequency: Every deployment

- **GET `/charities`**
  - Ensures the full list of charity entries is returned
  - Frequency: Daily

- **GET `/drivers/<driver_name>/charities`**
  - Confirms correct charities are filtered by driver
  - Frequency: Weekly

- **GET `/teams/<team_name>/charities`**
  - Verifies correct filtering by team
  - Frequency: Weekly

- **GET `/charities/search?focus=`**
  - Checks keyword-based filtering functionality
  - Frequency: Weekly

- **GET `/charities/impact/<charity_name>`**
  - Verifies accurate impact and initiative info per charity
  - Frequency: Monthly

- **POST `/charities/donate`**
  - Simulates a donation and confirms success or failure
  - Frequency: Weekly

---

### 2. Performance Testing

To ensure the API performs well under load, we’ll periodically run stress tests and monitor response time.

- **Target Response Time:** Under 3s for standard requests
- **Throughput Goal:** Sustain 50+ requests/sec
- **Error Rate Threshold:** Below 5% under load
- **Startup Time:** Under 1 second from cold start
- **Test Frequency:**
  - Light-load benchmarks: Every two weeks
  - Full stress test: Monthly

---

## Monitoring & Alarms

We will use basic monitoring tools or manual scripting to track availability and integrity.

- **Uptime Monitoring**
  - Tool: Pingdom, uptime-kuma, or simple ping script
  - Alert if service is unreachable for >30 seconds

- **Data File Integrity**
  - Watch `charities.json` for corruption or deletion
  - Action: Halt deploy, restore from backup, notify team

- **Response Time Monitoring**
  - Flask logs or ngrok inspection for slow endpoints
  - Action: Flag entries >500ms for review

---

## Ongoing QA Strategy

- Use **GitHub Actions** to run test suite on every push
- Ensure all pull requests include test impact checklist
- Encourage user feedback through GitHub Issues

---

## Tools Used

- Python with `unittest` and `requests`
- GitHub for issue tracking and CI/CD automation

---

## Success Criteria

- API endpoints respond with HTTP and valid schema
- Test pass rate of over 95% in CI
- No unhandled outages or corrupted data for 30+ days
- Consistently meet target performance benchmarks

---

## Appendix

- `test.py`: Automated test suite
- `charities.json`: Static dataset for validation
