# UML Validation & Consistency Checklist (v0.1)

## 1. Syntax Check
- diagrams.net:
  - Ensure all arrows and head types match the intended relationship.
  - Use correct notation for associations in the Class diagram.
  - Actor and Use Case symbols are correctly used.

## 2. Naming Consistency
- Class names used in the Class diagram appear in the use-case narrative.
  - Example: “Student registers Course”.
- Naming style is consistent across diagrams (no mismatched terms).

## 3. Association Consistency
- Associations between classes are clearly defined.
- Multiplicities are specified where applicable.
  - Example: Student 1..* Course.

## 4. Traceability Mini-Checklist
- Each use case maps to at least one class responsibility.
- The “Register Course” use case has a corresponding class that performs this responsibility.
- No use case exists without a supporting class in the Class diagram.
