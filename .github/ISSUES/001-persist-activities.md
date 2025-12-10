# Persist activities and participants with a database

**Description**

Move the in-memory `activities` data into a persistent database. Add a simple `Activity` model (`name`, `description`, `schedule`, `max_participants`) and an `Enrollment` model (`activity_id`, `student_email`, `signup_date`, `role`). Update endpoints so they read/write from the DB. Provide migration instructions and a simple local dev DB setup (SQLite or MongoDB).

**Acceptance criteria**

- Activities persist across server restarts.
- Existing endpoints `/activities`, `/activities/{name}/signup`, and `/activities/{name}/unregister` use the DB.
- Provide a script or README steps to initialize the DB.

**Labels:** enhancement, backend
**Priority:** high
