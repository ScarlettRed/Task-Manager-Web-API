# Task Manager Web API


A production-ready REST API for managing tasks, projects, tags, subtasks, comments, and attachments. Built with **OpenAPI 3.1 specification**, it includes best practices like JWT authentication, idempotency, pagination, filtering, sorting, and real-time updates via webhooks and SSE.


---


## 🚀 Features
- **Authentication**: JWT-based (access + refresh tokens)
- **Users**: Registration, login, profile management
- **Projects**: CRUD operations with color labels
- **Tasks**: CRUD operations with filtering, sorting, priorities, due dates
- **Subtasks**: Nested checklists inside tasks
- **Comments**: Discussion threads on tasks
- **Tags**: Custom labels with colors
- **Attachments**: Pre-signed upload flow
- **Bulk Operations**: Bulk create/update for tasks
- **Webhooks**: Event subscription for external integrations
- **Events (SSE)**: Real-time updates on task and comment events
- **Pagination & Sorting**: Standardized query params
- **Error Handling**: RFC7807 Problem Details with validation errors
- **Rate Limiting**: Communicated via headers