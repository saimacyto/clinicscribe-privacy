# Privacy Policy for ClinicScribe Chrome Extension

**Last Updated:** January 18, 2026

## Overview

ClinicScribe ("we", "our", or "us") is committed to protecting your privacy and ensuring HIPAA compliance. This privacy policy explains how our Chrome extension handles data.

## Data Collection

### What We Collect
- **Audio Recordings:** Temporarily captured via your browser's microphone during active recording sessions
- **Transcripts:** Text transcriptions of recorded audio
- **Patient Initials:** Entered by you for note identification
- **Azure Credentials:** Stored locally in Chrome's encrypted storage

### What We DO NOT Collect
- We do NOT store audio recordings permanently
- We do NOT transmit data to our servers
- We do NOT share data with third parties
- We do NOT use cookies or tracking

## Data Processing

### Local Processing
- All speech-to-text processing happens via browser Speech API or Azure Speech Services
- Audio is processed in real-time and NOT saved to disk

### Azure OpenAI Processing
- Transcripts are sent to Azure OpenAI (your configured endpoint) to generate SOAP notes
- Data is processed according to Azure's HIPAA-compliant Business Associate Agreement (BAA)
- Azure does NOT use your data to train models (per Azure OpenAI terms)

### Data Retention
- Audio: NOT stored (discarded immediately after transcription)
- Transcripts: Cleared when you close the extension popup
- Generated Notes: Available until you close the popup or create a new note
- Azure Credentials: Stored in Chrome's local encrypted storage

## HIPAA Compliance

### Covered Entities
- ClinicScribe is designed for use by HIPAA-covered entities
- You are responsible for ensuring your use complies with HIPAA regulations
- We recommend having a Business Associate Agreement with Azure

### Security Measures
- All data transmission uses HTTPS encryption
- Azure credentials stored using Chrome's encrypted storage API
- No patient data persists after extension is closed

## User Rights

You have the right to:
- Access your stored credentials (via Chrome storage)
- Delete the extension and all associated data at any time
- Configure which Azure services are used

## Data Sharing

We do NOT share your data with:
- Third-party analytics services
- Advertising networks
- Other healthcare providers
- Any external parties

The ONLY external service is YOUR configured Azure OpenAI endpoint.

## Children's Privacy

ClinicScribe is intended for healthcare professionals only and is not directed at individuals under 18 years of age.

## Changes to This Policy

We may update this privacy policy. Changes will be posted with an updated "Last Updated" date.

## Contact Us

For privacy concerns or questions:
- Email: privacy@clinicscribe.org
- Website: https://clinicscribe.org

## Your Consent

By using ClinicScribe, you consent to this privacy policy.

## Disclaimer

ClinicScribe is a tool to assist healthcare documentation. You are responsible for:
- Reviewing and editing all generated notes
- Ensuring HIPAA compliance in your practice
- Obtaining appropriate patient consents
- Final clinical judgment and documentation accuracy

---

**ClinicScribe LLC**  
HIPAA-Compliant AI Documentation Assistant  
Secured with Azure Business Associate Agreement
