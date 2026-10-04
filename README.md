# Event Ticket Eligibility & Points Checker

A simple, lightweight, and crash-proof Python Command Line Interface (CLI) application to check event ticket eligibility and manage user reward points based on specific criteria.

---

## Repository Details
* **Suggested Repository Title:** `python-ticket-eligibility-checker`
* **Suggested Description:** A Python CLI tool to validate age, check VIP ticket eligibility, and update user reward points with robust error handling.

---

## Project Overview
This application prompts the user for their age and ticket type (`Regular` or `VIP`). It utilizes robust `try-except` error handling to ensure that the age input is a valid, non-negative integer, protecting the program from crashing due to invalid entries. 

## Eligibility Criteria
A user is deemed **Eligible** if all of the following conditions are met simultaneously:
* **Age:** Less than $18$ years old.
* **Ticket Type:** `VIP`.
* **Account Status:** Active (`is_active = True`).

If eligible, an additional $50$ points are added to the baseline $100 points.

## Features
* **Robust Input Validation:** Uses `try-except` blocks to handle invalid text or decimal inputs for age gracefully.
* **Negative Value Protection:** Automatically detects and blocks negative age values.
* **Dynamic Scoring System:** Automatically calculates and updates bonus points for qualified users.
* **Clean & Pythonic Code:** Built using standard Python conditional statements and clear formatting.

## Prerequisites
Ensure you have Python installed on your system. You can verify your installation by running:
```bash
python --version
