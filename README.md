# demo

## Endpoints:

### Create
 
Adaugare medic si pacient (Add Doctor and Patient): This functionality allows you to add a new doctor or patient to the system. You can provide their details such as name, email, contact information, and other relevant information to create their profiles.

Adaugare reviews (Add Reviews): This functionality enables users to add reviews or feedback about a doctor's services. Users can provide their ratings and comments to review their experiences.

Creare consultatie (Create Consultation): This functionality allows for the creation of new medical consultations. It involves scheduling appointments between doctors and patients, specifying the date, time, and purpose of the consultation.

Creare pagina jurnal (Create Journal Page): Users, typically patients, can create journal pages to record their medical history, symptoms, or any other relevant information. These journal pages can serve as a record of their health journey and they can share with the specialist if they choose to do that.

Creare plata in sistem (Create Payment in System): This functionality enables users to make payments within the system. It may involve processing payments for medical services, appointments, or other system-related fees.



### Update:

Update stare consultatie (Update Consultation Status): This feature allows for the updating of the status of a medical consultation. The specialist is allowed to do this and there are more types of status:   
    -- In_Asteptare,
    --  Programare_Acceptata,
    -- Programare_Realizata,
    -- Programare_Respinsa,
    -- Programare_Anulata 

Update stare jurnal (Update Journal Status): Users can update the status of their journal pages, possibly making them public or private, or modifying the content within the journal entries.

### Get:

Afisare medici/medic dupa nume/email (Display Doctors/Doctor by Name/Email): This functionality allows users to search and display doctors or a specific doctor's information based on their name or email.

Afisare user by mail and password (Display User by Email and Password): Users can retrieve their information or authenticate by providing their email and password.

Afisare users generali (Display General Users): This feature displays a list of all general users (both doctors and patients) in the system.

Afisare lista programari in asteptare (Display List of Pending Appointments): It shows a list of appointments that are pending or waiting for confirmation or completion.

Afisare lista programari nerealizate (Display List of Unfulfilled Appointments): This functionality provides a list of appointments that were not completed or realized as planned.

Afisare pacienti pentru un medic (Display Patients for a Doctor): Doctors can view a list of their patients' profiles and information.

Afisare review-uri medic (Display Doctor Reviews): This feature allows users to view reviews and ratings given to a specific doctor by patients.

Afisare pagini jurnal pentru pacient (Display Journal Pages for a Patient): Patients can view their journal pages and entries.

Afisare pagini jurnal ale unui pacient pentru medic (Display Journal Pages of a Patient for a Doctor): Doctors can view the journal pages of their patients, but only if they are made public by the patient.

Vizualizare consultatii pacient ordonate dupa data (View Patient Consultations Sorted by Date): Patients can view their past and future medical consultations sorted by date.

### Delete:

Stergere programari de catre medic (Delete Appointments by Doctor): Doctors can delete or cancel appointments scheduled with them.

Stergere user (Delete User): This functionality allows administrators or users to delete a user's profile and data from the system.

Stergere review (Delete Review): Users or administrators can delete reviews or feedback that have been submitted about a doctor's services.


When I tested my application, I utilized Postman, a popular API testing tool, and configured Swagger to enhance the overall testing and documentation experience. Postman allowed me to easily send HTTP requests to various endpoints, simulate different scenarios, and inspect the responses, ensuring that my application's APIs functioned correctly. Additionally, by configuring Swagger, I was able to provide a user-friendly and interactive API documentation interface, making it easier for developers and testers to understand and interact with the API endpoints, view request examples, and test various functionalities effectively
![image](https://github.com/Talida-M/demoFinall/assets/75331740/db594df0-39a5-491b-85d9-b4dd3ae014fa)
![image](https://github.com/Talida-M/demoFinall/assets/75331740/69a3b015-f558-4778-b6be-550840e48ab8)
![image](https://github.com/Talida-M/demoFinall/assets/75331740/0338ed00-c2e4-403e-a6bd-38580f57d3a5)


### Entity diagram:
![image](https://github.com/Talida-M/demoFinall/assets/75331740/80614490-aafa-4924-b6b2-8c004ba94be2)


