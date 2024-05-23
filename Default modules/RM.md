# Module Name: Reciprocity/Mutual Licensing (RM)

## 1. Basic Content

If you assert any patent claims against the software or its contributors, your patent license from this software and its contributors terminates automatically. This provision aims to promote mutual licensing and discourage patent litigation.

## 2. Mandatory Inheritance (Section 2) Usage

Can be used in Section 2: Yes

Examples of allowed inheritance structures:
- Originating repository (includes RM) -> Direct fork (must include RM) -> Subsequent forks (must include RM)

## 3. Optional Inheritance (Section 5) Usage

Can be used in Section 5: Yes

Examples of allowed inheritance structures:
- Originating repository (includes RM) -> Direct fork (RM is applied to itself, chooses to INCLUDE RM to derivatives) -> Subsequent forks (RM is applied to itself, can choose to include or exclude RM)
- Originating repository (includes RM) -> Direct fork (RM is applied to itself, chooses to EXCLUDE RM to derivatives) -> Subsequent forks (RM is NOT applied to itself, can choose to include or exclude RM)