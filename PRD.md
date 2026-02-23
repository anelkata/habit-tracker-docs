Below is a **blank, LLM-parseable PRD template** designed specifically for generating architecture and implementation prompts for Codex or other coding LLMs.

It is:

* Structured
* Explicit
* Machine-readable
* Section-labeled
* Free of ambiguity
* Easy to fill incrementally

You can paste this into Codex as structured context.

---

# PRODUCT REQUIREMENTS DOCUMENT (PRD)

---

## 1. Product Overview

**Product Name:**
[Insert product name]

**Product Type:**
Web Application

**Product Description (1–3 paragraphs):**
[Describe what the product is, what it does, and who it is for.]

**Primary Problem Statement:**
[Describe the main problem the product solves.]

**Target Audience:**
[Describe user types. Example: busy professionals, students, self-improvement enthusiasts.]

**Core Value Proposition:**
[Why this product is better or different from alternatives.]

---

## 2. Goals and Success Metrics

### 2.1 Business Goals

* [Goal 1]
* [Goal 2]
* [Goal 3]

### 2.2 User Goals

* [User goal 1]
* [User goal 2]

### 2.3 Success Metrics (Quantifiable)

* Metric Name:

  * Definition:
  * Target Value:
* Metric Name:

  * Definition:
  * Target Value:

---

## 3. Scope

### 3.1 In Scope (MVP)

* [Feature]
* [Feature]
* [Feature]

### 3.2 Out of Scope (For Now)

* [Feature not included]
* [Feature not included]

---

## 4. User Personas

### Persona 1

* Name:
* Age Range:
* Occupation:
* Technical Proficiency:
* Primary Motivation:
* Pain Points:
* Device Usage:

### Persona 2

* Name:
* Age Range:
* Occupation:
* Technical Proficiency:
* Primary Motivation:
* Pain Points:
* Device Usage:

---

## 5. User Stories

Format:
"As a [persona], I want to [action], so that [outcome]."

* US-01:
* US-02:
* US-03:

---

## 6. Functional Requirements

Each requirement must be uniquely identifiable.

### FR-01: User Authentication

* Description:
* Inputs:
* Outputs:
* Validation Rules:
* Error Handling:
* Dependencies:

### FR-02: Habit Creation

* Description:
* Inputs:
* Outputs:
* Validation Rules:
* Edge Cases:
* Dependencies:

### FR-03: Habit Tracking

* Description:
* Inputs:
* Outputs:
* Validation Rules:
* Edge Cases:
* Dependencies:

(Add more as needed)

---

## 7. Non-Functional Requirements

### 7.1 Performance

* Maximum page load time:
* Maximum API response time:
* Concurrent users target:

### 7.2 Security

* Authentication type:
* Data encryption:
* Password policy:
* Rate limiting:

### 7.3 Reliability

* Uptime target:
* Backup policy:
* Data recovery requirements:

### 7.4 Scalability

* Expected initial users:
* Expected 12-month growth:
* Horizontal/Vertical scaling preference:

### 7.5 Accessibility

* WCAG level target:
* Keyboard navigation required:
* Screen reader compatibility:

---

## 8. Data Model (Conceptual)

### Entities

#### User

* id:
* email:
* password_hash:
* created_at:
* updated_at:

#### Habit

* id:
* user_id:
* name:
* description:
* frequency_type:
* frequency_value:
* created_at:
* updated_at:

#### HabitLog

* id:
* habit_id:
* date:
* status:
* notes:

(Add additional entities if needed)

---

## 9. Core User Flows

### Flow 1: User Registration

1.
2.
3.
4.

### Flow 2: Create Habit

1.
2.
3.
4.

### Flow 3: Log Habit Completion

1.
2.
3.
4.

---

## 10. UX Requirements

### Design Principles

* Minimal
* Mobile-first
* Fast interaction
* Clear visual progress

### Key Screens

* Landing Page
* Login / Signup
* Dashboard
* Create Habit Modal/Page
* Habit Detail View
* Settings

### Navigation Structure

[Describe menu structure]

---

## 11. Technical Constraints

* Frontend Framework:
* Backend Framework:
* Database:
* Hosting:
* Authentication Provider:
* Third-party Integrations:
* Browser Support:
* Mobile Responsiveness Requirement:

---

## 12. API Requirements

### API Style

* REST / GraphQL:

### Authentication Method

* JWT / Session / OAuth:

### Required Endpoints

#### POST /users

* Description:
* Request Body:
* Response:

#### POST /habits

* Description:
* Request Body:
* Response:

#### POST /habit-logs

* Description:
* Request Body:
* Response:

(Add more endpoints as required)

---

## 13. Analytics & Tracking

* Events to track:
* Retention measurement:
* Funnel definition:
* Tooling:

---

## 14. Risks and Assumptions

### Assumptions

* [Assumption 1]
* [Assumption 2]

### Risks

* Risk:

  * Impact:
  * Mitigation:

---

## 15. Future Enhancements (Post-MVP)

* Feature:
* Feature:
* Feature:

---

## 16. Open Questions

* Question:
* Question:
* Question:

---

# Instructions for Using This PRD with Codex

When prompting Codex:

1. Paste the filled PRD.
2. Then ask:

   * "Generate backend architecture based on this PRD."
   * "Design normalized database schema."
   * "Generate API contracts."
   * "Generate frontend folder structure."
   * "Write production-ready code for FR-02."

---

If you want, I can now:

* Provide a **filled example for a habit tracker MVP**
* Or give you a **PRD optimized specifically for LLM-driven development**
* Or generate a **technical architecture template that pairs with this PRD**

---

You are a senior PHP developer.

I want to build a web application with the following requirements:

1. Tech stack:
- Backend: PHP 8.x (no framework)
- Database: MySQL
- Frontend: HTML5 + CSS3 (no frameworks)
- Minimal JavaScript (vanilla JS only)
- Structure must be simple and beginner-friendly.

2. Goal of the app:
[Describe clearly what the app does.]

3. Features:
- Feature 1:
- Feature 2:
- Feature 3:

4. Database:
Please design the database schema first.
Provide:
- Table names
- Columns
- Data types
- Relationships

5. Project structure:
Provide:
- Folder structure
- File names
- Purpose of each file

6. Code requirements:
- Use PDO for database connection
- Use prepared statements
- Use basic input validation
- Add comments explaining what each part does
- Keep code readable and beginner-friendly

7. Output format:
Provide:
- Step-by-step implementation
- Full code for each file
- Clear instructions where to paste each file
- Instructions for running locally with XAMPP
