<h1> Medical records system </h1><br>

<h1> Features <h1><br>
<p>
Role-Based Access Control (RBAC) using Laravel Spatie Permissions<br>
CRUD operations on medical records (diagnosis, medicines, allergies, tests, etc.)<br>
User Management (Admins can create/edit doctors)<br>
Authentication and Authorization with Laravel UI<br>
Audit trail through timestamps<br>
Validation and error handling on forms<br>
</p>

<h1> Roles and permissions <h1> <br>
<p>
Super Admin	has full system access, including user and role management <br>
Admin can manage doctors and view all records<br>
Doctor	can create, update, and view their own patients' records<br>

</p>

<h1> Medical record structure <h1>
<p> Each record includes: <br>
Each record includes:
Diagnosis<br>
Medicines<br>
Tests<br>
Allergies<br>
Immunizations<br>
Treatment Plan<br>
</p>

<h1> Tech Stack <h1>
Backend: Laravel 10 <br>
Frontend: Blade (with Bootstrap)<br>
Authentication: Laravel Auth<br>
Authorization: Spatie Laravel-Permission<br>
Database: MySQL<br>
Migrations: Laravel Schema Builder<br>
