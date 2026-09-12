# Greenfield Academy — Automated Student Performance Report

## Project Overview

**Project Type:** Data Analytics & Business Intelligence  
**Industry:** Education  
**Tools:** Microsoft Excel, Spreadsheet Formulas  
**Dataset:** Student academic, attendance, and administrative records

---

## Business Problem

Greenfield Academy relied on manual processes for generating student report cards. This created risks of:

- Data-entry errors
- Incorrect calculations
- Inconsistent pass/fail decisions
- Time-consuming report preparation
- Inconsistent reporting standards

The project focused on developing an automated reporting solution that could retrieve student information and calculate key academic and attendance metrics using a unique **Student ID**.

---

## Project Objective

The objective was to develop an **automated, formula-driven student report card system** that allows users to enter a Student ID and automatically retrieve:

- Student information
- Subject scores
- Average academic performance
- Pass/fail status
- Attendance rate
- Tuition information

The solution was designed to reduce manual data entry and improve reporting accuracy and consistency.

---

## Dataset

The dataset contains student academic and administrative information.

| Category | Variables |
|---|---|
| Student Information | Student ID, Full Name, Grade Level |
| Academic Performance | Mathematics, English, Science, Social Studies |
| Performance Outcome | Average Score, Pass/Fail Status |
| Attendance | Days Present, Total School Days, Attendance % |
| Administration | Tuition Fee, Class Teacher |

**Sample Student:** Halima Ibrahim  
**Student ID:** `GA-2026088`  
**Grade:** JSS2

---

## Analytical Approach

### 1. Dynamic Data Retrieval

A unique **Student ID** was used as the input parameter. Lookup formulas automatically retrieved the corresponding student information.

### 2. Academic Performance Analysis

The four subject scores were analysed to calculate the student's overall average.

| Subject | Score |
|---|---:|
| Mathematics | 88 |
| English | 55 |
| Science | 60 |
| Social Studies | 52 |
| **Average Score** | **63.8** |

### 3. Pass/Fail Evaluation

Conditional logic was used to automatically determine the student's academic status.

**Result:** `PASS`

### 4. Attendance Analysis

Attendance was calculated using:

```text
Attendance % = (Days Present / Total School Days) × 100
