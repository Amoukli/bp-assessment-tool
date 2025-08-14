# Blood Pressure Assessment Tool

A clinical decision support tool that implements the HCA Blood Pressure Algorithm (160/95) flowchart for administrative staff.

## Features

- Simple web interface for BP assessment
- Follows clinical algorithm exactly as per flowchart
- Color-coded results for easy interpretation
- Works on all devices (desktop, tablet, mobile)
- No server required - runs entirely in browser

## Usage

1. Open `bp-assessment-app.html` in any web browser
2. Enter patient's blood pressure reading (systolic/diastolic)
3. Check if patient is diabetic
4. Select any current symptoms (chest pain, palpitations, SOB)
5. Click "Assess Blood Pressure" for instant clinical guidance

## Clinical Algorithm

Based on the HCA BP Algorithm flowchart:
- **Normal**: No further action required
- **Elevated with symptoms**: Discuss immediately with duty doctor
- **Elevated without symptoms**: Book TC with pharmacist/PA
- **≥160/95**: Discuss with duty doctor on the day

## Deployment

This app is deployed as an Azure Static Web App for secure access across multiple healthcare sites.

## Security

- No patient data is stored or transmitted
- Assessment results are displayed locally only
- HTTPS encryption when deployed to Azure