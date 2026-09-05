The only AI I used for week 4's activities was Copilot when prompted by the questions. The prompts I used are as follows:

<h2>1.</h2>
<strong>Act as a Python tutor.
I am learning introductory software technology.
Here is a small appointment-booking function.
1. Explain what the code does.
2. Identify three limitations.
3. Suggest improvements.
4. Do not rewrite the whole application.
5. Ask me two questions to test my understanding.For each question write a short response.Code:appointments = []def book_appointment(patient_name, practitioner_name, appointment_time):    if not patient_name:        raise ValueError("Patient name cannot be empty")    appointment = {        "patient": patient_name,        "practitioner": practitioner_name,        "time": appointment_time    }    appointments.append(appointment)def display_appointments():    if not appointments:        print("No appointments recorded.")        return    for appointment in appointments:        print(f"Patient: {appointment['patient']} | Practitioner: {appointment['practitioner']} | Time: {appointment['time']}")print("Welcome to SmartCare: The Clinical Appointment Booking System!")book_appointment('Alice Smith', 'Dr. John Doe', '2024-07-20 10:00 AM')book_appointment('Bob Johnson', 'Dr. Jane Roe', '2024-07-20 11:30 AM')display_appointments()</strong>

<h2>2.</h2>
<strong>Create a simple, beginner-friendly Python function for an appointment booking system. The function should store a patient's name, a practitioner's name, and an appointment time. Use basic Python concepts suitable for an introductory software technology course, such as functions, lists, and dictionaries. Include brief comments explaining the code. Do not use a database, SQL, external libraries, files, classes, or a graphical user interface (GUI). Keep the solution simple and easy for a beginner to understand.</strong>

<h2>3.</h2>
<strong>The system will have functions to create and view bookings, that will take patient data, GP names, and the appointment time.Some issues that might occur are overlapping bookings if there is no check for overlap. Limited error handling could also cause an issue, or if someone closes their browser during booking an appointment, does the appointment remain booked, or become available.

AI request: Act as a tutor. Explain this code and identify potential problems. Do not provide a complete replacement. Ask me questions that help me reason about the solution.​‌

Respond with a short-medium response.</strong>