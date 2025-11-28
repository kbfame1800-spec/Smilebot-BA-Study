SmileBot – AI Chatbot for Dental Clinics (Business Analysis Project)

This repository contains a complete end-to-end Business Analysis case study for the SmileBot AI chatbot built for a dental clinic.

* Project Includes

  1. Problem Statement

  2. Stakeholder Analysis

  3. Business Requirements

  4. Functional & Non-Functional Requirements

  5. AS-IS and TO-BE Process Flows

  6. Use Case Documentation

  7. User Stories with Acceptance Criteria

  8. Wireframes

  9. Chatbot Demo Link & Screenshots

* Purpose

This project demonstrates core business analyst skills, including:requirements gathering, documentation, process modeling, structured thinking,
and communication with stakeholders.

* Chatbot Demo Link

#()

* Status

Documentation is being prepared step by step as part of a full BA  project.

* Tools Used

> GitHub

> Voiceflow

> Draw.io / Excalidraw

> Google Docs / Markdown

* Folder Structure

()

* Created by
Kirti Bhalla


## 12. Feature List

### 1. Customer-Facing Features
- Provide clinic timings, address, and available services.
- Answer FAQs like pricing, procedures, insurance, and doctor availability.
- Assist patients in booking appointments.
- Collect patient details (name, phone, service).
- Confirm or modify appointments.
- Guide walk-in patients on peak hours and waiting time.
- Provide emergency assistance guidance.

### 2. System Logic / Functional Features
- Detect intent: FAQ, appointment, follow-up.
- Slot filling for appointment booking.
- Error handling if user enters invalid data.
- Conditional flows based on clinic hours.
- Provide fallback message when intent not recognized.

### 3. Integration & Backend Features (Current + Future Scope)
- (Current) Fully functional conversation flow built in Voiceflow.
- (Current) Data captured within Voiceflow for demo purposes.
- (Future Scope) API integration to clinic calendar.
- (Future Scope) Auto-confirmation via WhatsApp or SMS.
- (Future Scope) Store appointments in a customer database or CRM.



## 13. Non-Functional Requirements (NFRs)

### 1. Usability
- The chatbot should be easy to use for patients of all age groups.
- Conversations must be simple, clear, and guided.
- The chatbot must provide quick reply options for faster navigation.

### 2. Performance
- Responses should be generated within 1–2 seconds.
- The system should handle multiple users at the same time without crashing.

### 3. Reliability
- The chatbot should maintain consistent responses across all supported platforms.
- All conversation flows should have fallback handling to avoid dead ends.

### 4. Availability
- The chatbot should be available 24/7 for answering patient questions.
- If using website embedding, the bot should load even during high-traffic hours.

### 5. Scalability
- System should support adding new intent categories (e.g., cosmetic dentistry, pediatric dentistry).
- Architecture should allow integration with CRM, website, and appointment calendar in future.

### 6. Security
- The chatbot must not store sensitive customer data without encryption.
- Communication between integrations (future API calls) must use HTTPS.
- Any personally identifiable information collected must follow GDPR/DPDP compliance guidelines.

### 7. Maintainability
- Conversation steps should be modular in Voiceflow for easy updates.
- Documentation should be updated whenever flows change.

### 8. Compatibility
- The chatbot should work across laptop, mobile browsers, and embedded website modes.
- The browser-based demo should run without requiring installation.


