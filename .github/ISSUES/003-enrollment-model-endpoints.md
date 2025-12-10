# Add Enrollment relationship model and endpoints

**Description**

Introduce explicit enrollment endpoints and a model (`POST /enroll`, `DELETE /enroll/{id}`, `GET /activities/{id}/participants`). Store metadata such as signup date and role/position. Use this instead of a participants array on `Activity`.

**Acceptance criteria**

- Enrollments are stored in their own collection/table.
- Endpoints return participant lists with metadata.

**Labels:** enhancement, backend
**Priority:** high
