High-Level System Workflow (End-to-End)
1. Patient Interaction
    Patient initiates conversation through the chatbot.
    Selects one of the options: Book, Cancel, Reschedule, FAQs.

2. Chatbot Layer (SmileBot)
    Collects required user inputs.
    Validates data formats (phone number, appointment ID).
    Sends request to backend appointment system.

3. Backend Appointment System
    Checks availability for appointments.
    Stores, updates, or deletes appointment records.
    Returns confirmation, rejection, or alternative time slots.

4. Chatbot Response
    Shows confirmation message.
    Provides Appointment ID.
    Sends error or alternative suggestions if required.

5. Receptionist (Escalation Layer)
    Handles cases the chatbot cannot resolve:
    Invalid appointment records
    Emergency situations
    Complex service requests

6. Logging & Tracking
    All interactions stored for audit.
    Session or error logs maintained.
