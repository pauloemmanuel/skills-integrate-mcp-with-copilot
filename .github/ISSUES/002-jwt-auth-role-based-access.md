# Add JWT authentication and role-based access

**Description**

Implement user accounts and JWT login. Support roles: `admin`, `teacher`, `student`, `parent`. Protect admin-only endpoints (create/update/delete activities). Add `/login` and `/login/verify` endpoints and middleware to extract & validate tokens. Document how to create admin/test users.

**Acceptance criteria**

- Users can log in and receive JWTs.
- Protected endpoints return 401 without a valid token.
- Role checks prevent non-admins from modifying activities.

**Labels:** enhancement, security
**Priority:** high
