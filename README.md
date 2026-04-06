# Smart Notes App (DB Workspace)

This repository is part of a fullstack Smart Notes App composed of three containers:

- notes_db (PostgreSQL): data persistence for notes and related entities.
- notes_backend (FastAPI): REST JSON API for note management features.
- notes_frontend (Next.js): dashboard UI for creating, organizing, and searching notes.

The product goals and feature scope are captured in the PRD.

## PRD
- [Smart Notes App PRD](../kavia-docs/CodeWiki/Specs/FeatureSpecs/notes-app-prd.md)

## Workspaces
- DB workspace (this folder): `smart-notes-app-339439/notes_db`
- Backend workspace: `smart-notes-app-339440/notes_backend`
- Frontend workspace: `smart-notes-app-339441/notes_frontend`

## Notes
At the time of writing, this workspace README provides cross-repo navigation and product context. Container-specific run instructions and schemas should live alongside the container code once implemented.
`````

Explanation: Update the backend workspace README to align with the PRD and provide a single source of navigation to the PRD.
````write file="smart-notes-app-339425-339440/README.md"
# Smart Notes App (Backend Workspace)

This repository is part of a fullstack Smart Notes App composed of three containers:

- notes_db (PostgreSQL): data persistence.
- notes_backend (FastAPI): REST JSON API for notes CRUD, tags, pin/favorite, and search; optional sync/auth may be added later.
- notes_frontend (Next.js): dashboard UI.

## PRD
- [Smart Notes App PRD](../kavia-docs/CodeWiki/Specs/FeatureSpecs/notes-app-prd.md)

## Workspace
Backend container root: `smart-notes-app-339440/notes_backend`

## Notes
This README is a navigation and context entrypoint. API endpoints and local run instructions should be documented within the backend container once implemented.
`````

Explanation: Update the frontend workspace README to align with the PRD, including the intended dashboard layout and link to the PRD.
````write file="smart-notes-app-339425-339441/README.md"
# Smart Notes App (Frontend Workspace)

This repository is part of a fullstack Smart Notes App composed of three containers:

- notes_db (PostgreSQL): data persistence.
- notes_backend (FastAPI): REST JSON API for notes CRUD, tags, pin/favorite, and search.
- notes_frontend (Next.js): dashboard-style UI with a sidebar (tags/navigation), a notes list, an editor panel, and a search bar above the notes.

## PRD
- [Smart Notes App PRD](../kavia-docs/CodeWiki/Specs/FeatureSpecs/notes-app-prd.md)

## Workspace
Frontend container root: `smart-notes-app-339441/notes_frontend`

## Notes
This README is a navigation and context entrypoint. UI component structure and local run instructions should be documented within the frontend container once implemented.
