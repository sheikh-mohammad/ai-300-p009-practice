# Cozy Café Project

## Project Overview

Build a Cozy Café where students can study quietly. This project focuses on creating a peaceful, study-friendly environment with a minimal and clean design.

## Key Directives (Goals)

### Primary Goal
Create a cozy café environment specifically designed for students who need a quiet place to study and work.

### Style Goal
Maintain a minimal, clean aesthetic with soft colors and warm lighting to promote a calm and focused atmosphere.

## Constraints

- The café must have only 10–15 seats
- The theme must be "quiet / study-friendly"
- Only soft colors allowed in design
- Wooden furniture only
- Warm lights instead of bright white lights

## Design Rules

- The style must be minimal and clean
- Wooden furniture only
- Warm lights instead of bright white lights

## Key Components

### Menu
A carefully curated menu with quality beverages and light snacks that cater to students' needs during study sessions.

### Sitting Area Layout
Strategically designed seating arrangement for 10-15 people, ensuring each seat provides a comfortable and quiet study environment with adequate workspace.

### Staff Schedule
Efficient scheduling system to maintain the quiet, study-friendly atmosphere while ensuring quality service.

### Cash Counter Setup
Minimal and efficient counter design that doesn't disrupt the calm ambiance of the café.

## Example Request

"Design the seating layout."

→ Claude will keep it small because the Project Brief specifies only 10–15 seats.

## How This Project Brief Helps

This document serves as a reference for maintaining consistency with the core vision of the cozy café. All decisions regarding design, functionality, and implementation should align with the constraints and goals outlined above. This ensures that the final result remains true to the intended quiet, study-friendly atmosphere with the appropriate aesthetic and capacity limitations.

## Git Workflow for Claude

When Claude works on this project, the following Git workflow should be followed to ensure proper version control and collaboration:

### Single Iteration Workflow
1. **Analyze the codebase** - Before making changes, examine all relevant files to understand the current state
2. **Stage changes** - Use `git add` to stage only the files that were modified in the current iteration
3. **Create descriptive commit** - Make a commit with a clear message describing the changes made
4. **Push to remote** - Push changes to the remote repository to maintain an up-to-date history

### Commit Message Guidelines
- Start with a brief summary of the changes (imperative mood)
- Include reference to which part of the café project was modified
- Follow with details if necessary

### Example Workflow Commands
```bash
# After making changes to project files
git status                    # Check which files were modified
git add .                     # Stage all modified files
git commit -m "Update seating layout design following project constraints"  # Commit with descriptive message
git push origin main          # Push changes to remote repository
```

### Best Practices
- Always analyze the entire codebase before committing to ensure consistency with project goals
- Keep commits focused on specific aspects of the café project
- Ensure each commit maintains the core vision of the cozy, study-friendly café
- Verify that changes align with the constraints (seating capacity, color scheme, etc.)

## Project Structure

The project is organized into the following folder structure for better maintainability:

```
├── CLAUDE.md (this file)
├── claude_planning.txt
└── docs/
    ├── branding/
    │   ├── CLAUDE.md (original branding documents)
    │   └── claude_planning.txt
    ├── design/
    │   ├── cafe_architecture.md
    │   └── seating_layout.md
    ├── menu/
    │   └── menu.md
    └── operations/
        ├── cash_counter_setup.md
        └── staff_schedule.md
```

### Folder Descriptions:
- **Root directory**: Contains main project overview files
- **docs/branding/**: Brand identity and project planning documents
- **docs/design/**: Architectural and layout design documents
- **docs/menu/**: Menu planning and food/beverage specifications
- **docs/operations/**: Operational procedures and staff management