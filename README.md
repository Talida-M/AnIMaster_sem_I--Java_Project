# demo

## Endpoints:
(‼️ = main feature)
### Create

‼️1. Adaugare medic si pacient (Add Doctor and Patient): This functionality allows you to add a new doctor or patient to the system. You can provide their details such as name, email, contact information, and other relevant information to create their profiles. 

2. Adaugare reviews (Add Reviews): This functionality enables users to add reviews or feedback about a doctor's services. Users can provide their ratings and comments to review their experiences.

‼️3. Creare consultatie (Create Consultation): This functionality allows for the creation of new medical consultations. It involves scheduling appointments between doctors and patients, specifying the date, time, and purpose of the consultation. 

4. Creare pagina jurnal (Create Journal Page): Users, typically patients, can create journal pages to record their medical history, symptoms, or any other relevant information. These journal pages can serve as a record of their health journey and they can share with the specialist if they choose to do that.

5. Creare plata in sistem (Create Payment in System): This functionality enables users to make payments within the system. It may involve processing payments for medical services, appointments, or other system-related fees.



### Update:

‼️1. Update stare consultatie (Update Consultation Status): This feature allows for the updating of the status of a medical consultation. The specialist is allowed to do this and there are more types of status:    

- In_Asteptare,
- Programare_Acceptata
- Programare_Realizata
- Programare_Respinsa
- Programare_Anulata 

2. Update stare jurnal (Update Journal Status): Users can update the status of their journal pages, possibly making them public or private, or modifying the content within the journal entries.

### Get:

‼️1. Afisare medici/medic dupa nume/email (Display Doctors/Doctor by Name/Email): This functionality allows users to search and display doctors or a specific doctor's information based on their name or email.

2. Afisare user by mail and password (Display User by Email and Password): Users can retrieve their information or authenticate by providing their email and password.

3. Afisare users generali (Display General Users): This feature displays a list of all general users (both doctors and patients) in the system.

‼️4. Afisare lista programari in asteptare (Display List of Pending Appointments): It shows a list of appointments that are pending or waiting for confirmation or completion.

5. Afisare lista programari nerealizate (Display List of Unfulfilled Appointments): This functionality provides a list of appointments that were not completed or realized as planned.

‼️6. Afisare pacienti pentru un medic (Display Patients for a Doctor): Doctors can view a list of their patients' profiles and information.

7. Afisare review-uri medic (Display Doctor Reviews): This feature allows users to view reviews and ratings given to a specific doctor by patients.

8. Afisare pagini jurnal pentru pacient (Display Journal Pages for a Patient): Patients can view their journal pages and entries.

9. Afisare pagini jurnal ale unui pacient pentru medic (Display Journal Pages of a Patient for a Doctor): Doctors can view the journal pages of their patients, but only if they are made public by the patient.

‼️10. Vizualizare consultatii pacient ordonate dupa data (View Patient Consultations Sorted by Date): Patients can view their past and future medical consultations sorted by date.

### Delete:

‼️1. Stergere programari de catre medic (Delete Appointments by Doctor): Doctors can delete or cancel appointments scheduled with them.

2. Stergere user (Delete User): This functionality allows administrators or users to delete a user's profile and data from the system.

3. Stergere review (Delete Review): Users or administrators can delete reviews or feedback that have been submitted about a doctor's services.


## Exceptions

- Handler class
- EmailAlreadyUsedException
- DeletedBookException
- NoSuchElementException
- UserNotLoggedInException
- UnauthorizedUserException
- InvalidTokenException


<details>
<summary>Example of beans for defining repositories to show @Repository annotation and  with JPARepository </b> </summary>
 
![image](https://github.com/Talida-M/demoFinall/assets/75331740/c7ea1484-a8e4-4a0c-9f8e-6feea5451ac1)

</details>



<details>
<summary><b> Unit tests for all REST endpoints and services </b> </summary>

![image](https://github.com/Talida-M/demoFinall/assets/75331740/79d8b602-43e3-4426-a9e3-e42d04a751a3)

</details>


<details>
 <summary>
  <b>
    Present the @Valid annotation
  </b>
 </summary>
 
 ![image](https://github.com/Talida-M/demoFinall/assets/75331740/e9c3dbe8-dc24-4d28-8566-c8dc7bb26730)
 
</details>




<details> 
 <summary>
  <b>
    Present the validation constraints 

  </b>
 </summary>
 
![image](https://github.com/Talida-M/demoFinall/assets/75331740/5a1ddc7f-7073-4ea3-aa13-f751ff313eaf)

</details>
<details>
<summary>
 <b>
  Custom Exceptions
 </b>
</summary>

![image](https://github.com/Talida-M/demoFinall/assets/75331740/79e13c4a-9b75-4d41-89eb-71e24fb01417)

![image](https://github.com/Talida-M/demoFinall/assets/75331740/b418a141-1bd7-47cc-b0bf-b02f4f3f3f25)


 
</details>






When I tested my application, I utilized Postman, a popular API testing tool, and configured Swagger to enhance the overall testing and documentation experience. Postman allowed me to easily send HTTP requests to various endpoints, simulate different scenarios, and inspect the responses, ensuring that my application's APIs functioned correctly. Additionally, by configuring Swagger, I was able to provide a user-friendly and interactive API documentation interface, making it easier for developers and testers to understand and interact with the API endpoints, view request examples, and test various functionalities effectively
<details>
 <summary>
  <b>
   Postman Example
  </b>
 </summary>
 ![image](https://github.com/Talida-M/demoFinall/assets/75331740/db594df0-39a5-491b-85d9-b4dd3ae014fa)
</details>

<details>
 <summary>
  <b>
   Swagger Example
  </b>
 </summary>

![image](https://github.com/Talida-M/demoFinall/assets/75331740/b4a31aa9-652f-483d-9f19-c7cfdf95bdf5)

![image](https://github.com/Talida-M/demoFinall/assets/75331740/0338ed00-c2e4-403e-a6bd-38580f57d3a5)


</details>




<details> 
<summary> 
<b>
 Entity diagram:
</b>
</summary>


![image](https://github.com/Talida-M/demoFinall/assets/75331740/80614490-aafa-4924-b6b2-8c004ba94be2)

</details> 


