#  F1 Charity API – Final Information Product (F1Impact)

## Overview

**F1Impact** is an information product designed and built in the context of *IMT 542: Data Portability* at the University of Washington. The project transforms fragmented and difficult-to-access information about Formula One drivers’ charitable initiatives into a **centralized, structured, and portable API-driven knowledge platform**.
The system is designed for researchers, fans, journalists, and partner organizations to access and understand the social impact of individual F1 drivers through their philanthropic foundations and charitable partnerships.


## JSON structure I created to use in API:

[
  {
    "driver_name": "Lewis Hamilton",
    "team_2024": "Mercedes",
    "foundation_charity_name": "The Hamilton Commission",
    "year_established": "2020",
    "focus_areas": "Education, STEM, Diversity and Inclusion",
    "key_initiatives": "Research on diversity in motorsport, Mission 44 initiative, Ignite partnership with Mercedes",
    "estimated_annual_impact": "£20 million+ (Mission 44)",
    "website": "https://www.hamiltoncommission.org"
  },
  {
    "driver_name": "Lewis Hamilton",
    "team_2024": "Mercedes",
    "foundation_charity_name": "Mission 44",
    "year_established": "2021",
    "focus_areas": "Education, Employment, Social Justice",
    "key_initiatives": "Education grants, Apprenticeship programmes, STEM initiatives",
    "estimated_annual_impact": "£20 million+ (pledged)",
    "website": "https://mission44.org"
  },
  {
    "driver_name": "Sebastian Vettel",
    "team_2024": "Retired (2022)",
    "foundation_charity_name": "Abejas Foundation",
    "year_established": "2022",
    "focus_areas": "Biodiversity, Bee conservation, Environmental education",
    "key_initiatives": "Bee hotel construction workshops, Educational programmes with schools",
    "estimated_annual_impact": "Data not public",
    "website": "N/A"
  },
  {
    "driver_name": "Max Verstappen",
    "team_2024": "Red Bull",
    "foundation_charity_name": "Max Verstappen Foundation",
    "year_established": "2023",
    "focus_areas": "Youth development, Sim racing accessibility",
    "key_initiatives": "Sim racing equipment donations, Mentorship programs for young drivers",
    "estimated_annual_impact": "€500,000+ (estimated)",
    "website": "https://www.maxverstappenfoundation.nl"
  },
  {
    "driver_name": "Charles Leclerc",
    "team_2024": "Ferrari",
    "foundation_charity_name": "Association Monégasque contre les Myopathies",
    "year_established": "Partner",
    "focus_areas": "Medical research, Duchenne muscular dystrophy",
    "key_initiatives": "Annual charity football match, Fundraising events",
    "estimated_annual_impact": "€150,000+ (per event)",
    "website": "N/A"
  },
  {
    "driver_name": "Daniel Ricciardo",
    "team_2024": "RB (VCARB)",
    "foundation_charity_name": "The Shoey Foundation",
    "year_established": "2023",
    "focus_areas": "Mental health, Youth support",
    "key_initiatives": "Mental health awareness campaigns, Youth sports programs",
    "estimated_annual_impact": "Data not public",
    "website": "N/A"
  },
  {
    "driver_name": "Fernando Alonso",
    "team_2024": "Aston Martin",
    "foundation_charity_name": "Fundación Fernando Alonso",
    "year_established": "2005",
    "focus_areas": "Road safety, Karting, Youth development",
    "key_initiatives": "Karting Campus, Museum and Circuit, Road safety education",
    "estimated_annual_impact": "€1 million+ (estimated)",
    "website": "https://www.fernandoalonso.com"
  },
  {
    "driver_name": "Sergio Perez",
    "team_2024": "Red Bull",
    "foundation_charity_name": "Fundación Checo Pérez",
    "year_established": "2012",
    "focus_areas": "Childhood cancer, Orphaned children, Education",
    "key_initiatives": "Hospital support, Educational programs, Emergency relief for natural disasters",
    "estimated_annual_impact": "25+ million pesos (annual)",
    "website": "https://fundacionchecoperez.org"
  },
  {
    "driver_name": "Lando Norris",
    "team_2024": "McLaren",
    "foundation_charity_name": "Mind charity partnership",
    "year_established": "2020",
    "focus_areas": "Mental health awareness, Youth mental health",
    "key_initiatives": "#MINDLANDO campaign, Fundraising streams, Mental health advocacy",
    "estimated_annual_impact": "£500,000+ (estimated)",
    "website": "N/A"
  },
  {
    "driver_name": "Carlos Sainz",
    "team_2024": "Ferrari",
    "foundation_charity_name": "Fundación Ana Carolina Díez Mahou",
    "year_established": "Partner",
    "focus_areas": "Neuromuscular and mitochondrial diseases",
    "key_initiatives": "Fundraising events, Awareness campaigns",
    "estimated_annual_impact": "Data not public",
    "website": "https://www.fundacionanacarolinadiezmahou.com"
  },
  {
    "driver_name": "Lance Stroll",
    "team_2024": "Aston Martin",
    "foundation_charity_name": "Racing Together",
    "year_established": "Partner",
    "focus_areas": "Diversity, Youth access to motorsport",
    "key_initiatives": "Mentorship programs, Go-karting initiatives",
    "estimated_annual_impact": "Data not public",
    "website": "N/A"
  },
  {
    "driver_name": "George Russell",
    "team_2024": "Mercedes",
    "foundation_charity_name": "Starlight Children's Foundation",
    "year_established": "Ambassador",
    "focus_areas": "Children's hospitals, Serious illness",
    "key_initiatives": "Hospital visits, Fundraising events, Awareness campaigns",
    "estimated_annual_impact": "Part of £10 million+ foundation",
    "website": "https://www.starlight.org.uk"
  },
  {
    "driver_name": "Valtteri Bottas",
    "team_2024": "Kick Sauber",
    "foundation_charity_name": "Save the Children Finland",
    "year_established": "Ambassador",
    "focus_areas": "Children's welfare and rights",
    "key_initiatives": "Cycling events, Fundraising campaigns",
    "estimated_annual_impact": "Data not public",
    "website": "https://www.pelastakaalapset.fi"
  },
  {
    "driver_name": "Zhou Guanyu",
    "team_2024": "Kick Sauber",
    "foundation_charity_name": "Uni-Core Children's Foundation",
    "year_established": "Ambassador",
    "focus_areas": "Children's education, Healthcare",
    "key_initiatives": "Fundraising for rural education, Medical assistance programs",
    "estimated_annual_impact": "Data not public",
    "website": "N/A"
  },
  {
    "driver_name": "Alex Albon",
    "team_2024": "Williams",
    "foundation_charity_name": "Wat Sakaew Orphanage",
    "year_established": "Supporter",
    "focus_areas": "Children's welfare, Education",
    "key_initiatives": "Fundraising, Personal support",
    "estimated_annual_impact": "Data not public",
    "website": "N/A"
  },
  {
    "driver_name": "Alex Albon",
    "team_2024": "Williams",
    "foundation_charity_name": "The Race Against Dementia",
    "year_established": "Partner",
    "focus_areas": "Dementia research",
    "key_initiatives": "Fundraising activities, Awareness campaigns",
    "estimated_annual_impact": "Part of £1 million+ foundation",
    "website": "https://www.raceagainstdementia.com"
  },
  {
    "driver_name": "Esteban Ocon",
    "team_2024": "Alpine",
    "foundation_charity_name": "Racing Pride",
    "year_established": "Supporter",
    "focus_areas": "LGBTQ+ inclusion in motorsport",
    "key_initiatives": "Awareness campaigns, Advocacy",
    "estimated_annual_impact": "Data not public",
    "website": "https://racingpride.com"
  },
  {
    "driver_name": "Pierre Gasly",
    "team_2024": "Alpine",
    "foundation_charity_name": "Association Pierre Gasly",
    "year_established": "2020",
    "focus_areas": "Children's welfare, Education",
    "key_initiatives": "School construction projects in Africa, Educational support programs",
    "estimated_annual_impact": "Data not public",
    "website": "N/A"
  },
  {
    "driver_name": "Yuki Tsunoda",
    "team_2024": "RB (VCARB)",
    "foundation_charity_name": "Japanese Red Cross",
    "year_established": "Supporter",
    "focus_areas": "Disaster relief, Healthcare",
    "key_initiatives": "Fundraising campaigns, Awareness for disaster relief",
    "estimated_annual_impact": "Data not public",
    "website": "https://www.jrc.or.jp"
  },
  {
    "driver_name": "Nico Hulkenberg",
    "team_2024": "Haas",
    "foundation_charity_name": "RTL-Wir helfen Kindern",
    "year_established": "Partner",
    "focus_areas": "Children's welfare",
    "key_initiatives": "Charity events, Fundraising activities",
    "estimated_annual_impact": "Data not public",
    "website": "https://wirhelfenkindern.rtl.de"
  },
  {
    "driver_name": "Kevin Magnussen",
    "team_2024": "Haas",
    "foundation_charity_name": "Danish Hospital Clowns",
    "year_established": "Supporter",
    "focus_areas": "Children's healthcare, Mental wellbeing",
    "key_initiatives": "Hospital visits, Awareness campaigns",
    "estimated_annual_impact": "Data not public",
    "website": "https://danskehospitalsklovne.dk"
  },
  {
    "driver_name": "Oscar Piastri",
    "team_2024": "McLaren",
    "foundation_charity_name": "Australian Grand Prix Foundation",
    "year_established": "Supporter",
    "focus_areas": "Children's charities, Medical research",
    "key_initiatives": "Fundraising events, Awareness campaigns",
    "estimated_annual_impact": "Part of AUD$500,000+ foundation",
    "website": "N/A"
  },
  {
    "driver_name": "Logan Sargeant",
    "team_2024": "Williams (2023)",
    "foundation_charity_name": "Racing for Children's",
    "year_established": "Supporter",
    "focus_areas": "Children's healthcare",
    "key_initiatives": "Hospital visits, Fundraising races",
    "estimated_annual_impact": "Part of $1 million+ initiative",
    "website": "https://racingforchildrens.org"
  }
]


## Code Utilized in API creation (app.py):

from flask import Flask, jsonify, request
import json

app = Flask(__name__)


with open('data/charities.json', encoding='utf-8') as f:
    charities = json.load(f)

@app.route('/')
def health_check():
    return jsonify({'message': 'F1 Charity API is running', 'status': 'healthy'})

@app.route('/charities', methods=['GET'])
def get_all_charities():
    return jsonify(charities)

@app.route('/drivers', methods=['GET'])
def get_all_drivers():
    drivers = sorted({c['driver_name'] for c in charities})
    return jsonify(drivers)

@app.route('/drivers/<driver_name>/charities', methods=['GET'])
def get_charities_by_driver(driver_name):
    result = [c for c in charities if c['driver_name'].lower() == driver_name.lower()]
    if not result:
        return jsonify({"error": "Driver not found"}), 404
    return jsonify(result)

@app.route('/teams/<team_name>/charities', methods=['GET'])
def get_charities_by_team(team_name):
    result = [c for c in charities if c['team_2024'].lower() == team_name.lower()]
    if not result:
        return jsonify({"error": "Team not found"}), 404
    return jsonify(result)

@app.route('/teams/<team_name>/charity-summary', methods=['GET'])
def team_charity_summary(team_name):
    team_charities = [c for c in charities if c['team_2024'].lower() == team_name.lower()]
    if not team_charities:
        return jsonify({"error": "Team not found"}), 404

  estimated_count = sum(
        1 for c in team_charities if 'estimated' in c['estimated_annual_impact'].lower() or '£' in c['estimated_annual_impact'] or '€' in c['estimated_annual_impact']
    )

  return jsonify({
        "team": team_name,
        "total_charities": len(team_charities),
        "estimated_impact_mentions": estimated_count
    })

@app.route('/charities/impact/<charity_name>', methods=['GET'])
def get_charity_impact(charity_name):
    for c in charities:
        if c['foundation_charity_name'].lower() == charity_name.lower():
            return jsonify({
                "charity": c['foundation_charity_name'],
                "estimated_annual_impact": c['estimated_annual_impact'],
                "key_initiatives": c['key_initiatives']
            })
    return jsonify({"error": "Charity not found"}), 404

@app.route('/charities/search', methods=['GET'])
def search_charities():
    focus = request.args.get('focus')
    results = [c for c in charities if focus and focus.lower() in c['focus_areas'].lower()]
    return jsonify(results)

@app.route('/charities/donate', methods=['POST'])
def donate():
    data = request.get_json()
    charity_name = data.get('charity_id')
    amount = data.get('amount')

  for c in charities:
        if c['foundation_charity_name'].lower() == charity_name.lower():
            return jsonify({
                "message": f"Donation of ${amount} to '{c['foundation_charity_name']}' successful.",
                "note": "Impact not updated (static dataset)"
            })
    return jsonify({"error": "Charity not found"}), 404

if __name__ == '__main__':
    app.run(debug=True)


## Test for API in test.py file:

import requests

BASE = "http://localhost:5000"

print("1. Health check:")
print(requests.get(f"{BASE}/").json())

print("\n2. All charities:")
print(requests.get(f"{BASE}/charities").json())

print("\n3. Charities by driver (Lewis Hamilton):")
print(requests.get(f"{BASE}/drivers/Lewis Hamilton/charities").json())

print("\n4. Charities by team (Mercedes):")
print(requests.get(f"{BASE}/teams/Mercedes/charities").json())

print("\n5. All drivers:")
print(requests.get(f"{BASE}/drivers").json())

print("\n6. Impact for 'hamilton_commission':")
print(requests.get(f"{BASE}/charities/impact/hamilton_commission").json())

print("\n7. Team summary for Mercedes:")
print(requests.get(f"{BASE}/teams/Mercedes/charity-summary").json())

print("\n8. Search (region=Africa, focus=education):")
print(requests.get(f"{BASE}/charities/search?region=africa&focus=education").json())

print("\n9. Donate $100 to hamilton_commission:")
print(requests.post(f"{BASE}/charities/donate", json={
    "charity_id": "hamilton_commission",
    "amount": 100
}).json())

