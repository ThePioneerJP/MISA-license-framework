# Module Name: Source Code Disclosure (SCD)

## 1. Basic Content

The source code for the software must be made available to the recipients of the software. This can be achieved by including the source code with the distribution of the software or by providing a means to obtain the source code, such as a link to a repository where the source code is hosted.

## 2. Mandatory Inheritance (Section 2) Usage

Can be used in Section 2: Yes

Examples of allowed inheritance structures:
- Originating repository (includes source code) -> Direct fork (must include source code) -> Subsequent forks (must include source code)

## 3. Optional Inheritance (Section 5) Usage

Can be used in Section 5: Yes

Examples of allowed inheritance structures:
- Originating repository (includes source code) -> Direct fork (source code disclosure is applied to itself, chooses to INCLUDE source code disclosure to derivatives) -> Subsequent forks (source code disclosure is applied to itself, can choose to include or exclude source code disclosure)
- Originating repository (includes source code) -> Direct fork (source code disclosure is applied to itself, chooses to EXCLUDE source code disclosure to derivatives) -> Subsequent forks (source code disclosure is NOT applied to itself, can choose to include or exclude source code disclosure)