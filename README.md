<p><h1> Medical records system </h1><br></p>

<p><h3> Features <h3><br></p>
<p>
Role-Based Access Control (RBAC) using Laravel Spatie Permissions<br>
CRUD operations on medical records (diagnosis, medicines, allergies, tests, etc.)<br>
User Management (Admins can create/edit doctors)<br>
Authentication and Authorization with Laravel UI<br>
Audit trail through timestamps<br>
Validation and error handling on forms<br>
</p>

<p><h3> Roles and permissions <h3> <br></p>
<p>
Super Admin	has full system access, including user and role management <br>
Admin can manage doctors and view all records<br>
Doctor	can create, update, and view their own patients' records<br>

</p>

<p><h3> Medical record structure <h1></p>
<p> Each record includes: <br>
Each record includes:
Diagnosis<br>
Medicines<br>
Tests<br>
Allergies<br>
Immunizations<br>
Treatment Plan<br>
</p>

<p><h3> Tech Stack <h3></p>
<p>
Backend: Laravel 10 <br>
Frontend: Blade (with Bootstrap)<br>
Authentication: Laravel Auth<br>
Authorization: Spatie Laravel-Permission<br>
Database: MySQL<br>
Migrations: Laravel Schema Builder<br>
</p>