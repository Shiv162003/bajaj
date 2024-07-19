## Dataset Description

This dataset contains patient consultation records. Each row represents a unique consultation with details about the patient and their appointment.

### Columns

- **_id**: Consultation record ID
- **appointmentId**: Appointment identifier
- **phoneNumber**: Patient's contact number
- **patientDetails._id**: Patient ID
- **patientDetails.firstName**: Patient's first name
- **patientDetails.lastName**: Patient's last name
- **patientDetails.emailId**: Patient's email
- **patientDetails.gender**: Patient's gender
- **patientDetails.alternateContact**: Alternate contact number
- **patientDetails.birthDate**: Patient's date of birth
- **consultationData.adviceTemplates**: Advice templates used
- **consultationData.advices**: List of advices
- **consultationData.attachments**: Attachments related to the consultation
- **consultationData.chiefComplaints**: Chief complaints
- **consultationData.disease**: Disease or condition
- **consultationData.doctorNotes**: Doctor's notes
- **consultationData.medicines**: Medicines prescribed
- **consultationData.procedures**: Procedures performed
- **consultationData.prognosis**: Prognosis given
- **consultationData.sharePrescription**: Whether the prescription was shared (TRUE/FALSE)
- **consultationData.updatedAt**: Timestamp of the last update

### Sample Data

| _id    | appointmentId | phoneNumber | patientDetails.firstName | patientDetails.lastName | patientDetails.emailId | patientDetails.gender | consultationData.disease | consultationData.medicines | consultationData.prognosis |
|--------|---------------|-------------|--------------------------|-------------------------|------------------------|-----------------------|--------------------------|----------------------------|-----------------------------|
| T6hf3rb5 | 40d2-9c9f     | 96686896670 | Css                      |                         |                        |                       |                          | [{'medicineId': '619404', 'medicineName': 'A', 'frequency': '1-0-1', 'duration': '90', 'instruction': 'AFTER MEAL', 'isActive': True}] | FALSE                           |
| T65g3rb5 | 40dbtc9f     | 9496368916 | Lokesh                   |                         |                        | M                     |                          | [{'medicineId': '619404', 'medicineName': 'A', 'frequency': '1-0-1', 'duration': '90', 'instruction': 'AFTER MEAL', 'isActive': True}] | FALSE                           |

For additional details, please refer to the full dataset.
