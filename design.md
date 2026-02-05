# Design Document

## System Overview
The system is an AI-powered assistant that helps users understand and apply for government schemes using multilingual support.

## Architecture
User → Input Interface (Text/Voice)  
→ NLP Engine  
→ Scheme Recommendation Module  
→ Multilingual Response Generator  
→ User

## Components
- Frontend: Web or Mobile Interface
- Backend: AI processing and scheme database
- AI Models:
  - NLP for intent detection
  - Translation models for regional languages
  - Recommendation logic for eligibility matching

## Data Sources
- Government scheme datasets
- Eligibility criteria documents

## Future Enhancements
- WhatsApp & IVR integration
- State-wise scheme filtering
- Voice-only mode for non-literate users

- ## User Roles
- Citizen: Searches and understands schemes
- Admin: Updates scheme information

## Constraints
- Must work on low-end Android phones
- Should support low internet connectivity
