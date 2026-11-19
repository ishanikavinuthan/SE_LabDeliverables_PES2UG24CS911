# Lab 7 – Fuzz Testing for Input Validation Bugs

**Student:** Ishanika Vinuthan  
**SRN:** PES2UG24CS911  
**Class:** 5B  
**University:** PES University

## Project Description

This lab focuses on identifying and fixing input validation bugs using fuzz testing with Python's Hypothesis library.

The Marathon Registration Parser application is tested using automatically generated inputs to identify unexpected crashes and edge cases. The application is then modified to handle invalid inputs safely.

## Functions Tested

| Function | Description |
|---|---|
| `format_bib_name()` | Formats runner names for marathon bibs |
| `parse_finish_time()` | Converts marathon finish times into seconds |
| `average_split()` | Calculates the average of split times |

## Testing Tools

- Python
- pytest
- Hypothesis

## Deliverables

- Lab 7 report PDF
- Fixed `marathon_registration_parser.py`
- Updated `test_marathon_registration_parser.py`
- Screenshot 1 – Original buggy application output
- Screenshot 2 – Failing fuzz tests
- Screenshot 3 – Fixed application output
- Screenshot 4 – Passing fuzz tests

## Source Code Repository

[Lab 6 and Lab 7 – Marathon Registration Repository](https://github.com/ishanikavinuthan/L6_L7_60_marathon_registration)
