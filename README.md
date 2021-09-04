# Medigo

Medigo is an mobile and web-based teleconsultaion platform to bridge the communication gap between doctors and patients. It connects doctors with patients using Text Messaging as well as Audio and Video Calling.
Besides that, it also serves as an Electronic Medical Record System which can be used by the doctors to store patient records, appointments etc and by the users to store their medical reports and prescriptions.

# Technology Stack

1. `Flutter` - Used to build the 2 mobile applications `MedigoUser` and `MedigoDoctor`
2. `React.js` - Used to build the web application `MedigoAdmin`
3. `Firebase` - Serves as the backend of the project
4. `DialogFlow` - Used to record input from the patient for generating medical report
5. `Agora SDK` - For audio and video calling

# Components

This project consists of 3 different applications, 2 `mobile` and 1 `web`.

### 1. Medigo User

* A Mobile Application meant to be used by the patients for booking consultations with doctors as well as storing medical documents in a secure locker.
* It provides the following functionalities -
  * Authentication via `email-password`, `facebook sign-in` and `google sign-in`.
  * Register your clinic where users can book offline appointments.
  * Create appointment slots for the next 7 days which users can book for either offline/online consultations.
  * Consult patients only via `text messaging` or `audio/video calling`.
  * After a consultation, issue a prescription to the patient with your digital signature.
* **Screenshots** -

### 2. Medigo Doctor

* A Mobile Application meant to be used by the patients for booking consultations with doctors as well as storing medical documents in a secure locker.
* It provides the following functionalities -
  * Authentication via `email-password`
  * Register your clinic where users can book offline appointments.
  * Create appointment slots for the next 7 days which users can book for either offline/online consultations.
  * Consult patients only via `text messaging` or `audio/video calling`.
  * After a consultation, issue a prescription to the patient with your digital signature.
* **Screenshots** -


### 3. Medigo Admin
* Web application made using `React.js` for doctors to manage their online consultations and clinic data.
* It provides the following functionalities -
  * Authentication via `email-password`
  * Register your clinic where users can book offline appointments.
  * Create appointment slots for the next 7 days which users can book for either offline/online consultations.
  * Consult patients only via `text messaging` or `audio/video calling`.
  * After a consultation, issue a prescription to the patient with your digital signature.
  * Maintain patient records and medical reports.
* **Screenshots** -

![add_patient](https://user-images.githubusercontent.com/45410599/129363923-c87a7c40-c880-42d1-b507-cd9f4929f816.png)
![clinic](https://user-images.githubusercontent.com/45410599/129363933-5d7f6272-61d6-4e1a-ad7d-59688cfc1a98.png)
![patients](https://user-images.githubusercontent.com/45410599/129363939-ef4949a9-91be-4f6c-bc19-bae3e7d7f0fd.png)
![update_clinic_details](https://user-images.githubusercontent.com/45410599/129363945-01dc67c5-6c57-431d-8fa0-5d6a461b9016.png)
![update_clinic_photo](https://user-images.githubusercontent.com/45410599/129363947-a24f5bb0-3be6-4853-b0ae-702546f4dfeb.png)
![update_password](https://user-images.githubusercontent.com/45410599/129363950-96167f4c-4b8b-4937-afbc-174ddbc7882b.png)


