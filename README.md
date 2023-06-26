# hospital-api.github.io

API for a doctors to manage patient records and creating a Report according to status and keep a record of all petients.

#### Setup the Project

1.  Download the Repo.
2. `cd covid19-api` goto the Repo using Terminal.
3. Run `mongod` to start the MongoDB Database.
4. Run `npm start` to ignite the project.
5. Use **Postman** to test the api.

#### Routes
1. **Register a Doctor:** `[POST]: /api/v1/doctors/register`
2. **Login for Doctor:** `[POST]: /api/v1/doctors/login`
3. **Register a patient:** `[POST]: /api/v1/patients/register`
4. **Create Patient report:** `[POST]: /api/v1/patients/:id/create_report`
5. **Fetch All Reports of a Patient** `[GET]: /api/v1/patients/:id/all_reports`
6. **Fetch All Reports Based on a Status:** `[GET]: /api/v1/reports/:status`
