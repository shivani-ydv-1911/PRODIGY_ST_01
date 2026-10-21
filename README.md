# PRODIGY_ST_01
Task 01 - Manual Test Cases and Bug Reports for Simple Calculator Application (Prodigy InfoTech QA Internship)


# Task 01: Test Cases for Simple Calculator Application

**Demo Website:** https://dunizb.github.io/sCalc/  
**Testing Type:** Manual Functional Testing  
**Application:** Simple Calculator (sCalc)  

---

### Test Execution Summary
- **Total Test Cases:** 25
- **Passed:** 22
- **Failed:** 3 (TC_016, TC_017, TC_022)
- **Status:** Testing Completed

---

## TC_001
- **Description:** Verify addition of two positive numbers
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 5
  2. Click +
  3. Enter 3
  4. Click =
- **Expected Result:** Display shows 8.
- **Actual Result:** The calculator correctly displayed the result as 8.
- **Status:** Pass

---

## TC_002
- **Description:** Verify addition of a number with zero
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 15
  2. Click +
  3. Enter 0
  4. Click =
- **Expected Result:** Display shows 15.
- **Actual Result:** The calculator correctly displayed the result as 15.
- **Status:** Pass

---

## TC_003
- **Description:** Verify addition resulting in a negative number
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter -5
  2. Click +
  3. Enter -8
  4. Click =
- **Expected Result:** Display shows -13.
- **Actual Result:** The calculator correctly displayed the result as -13.
- **Status:** Pass

---

## TC_004
- **Description:** Verify subtraction of two positive numbers
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 9
  2. Click -
  3. Enter 5
  4. Click =
- **Expected Result:** Display shows 4.
- **Actual Result:** The calculator correctly displayed the result as 4.
- **Status:** Pass

---

## TC_005
- **Description:** Verify subtraction resulting in zero
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 6
  2. Click -
  3. Enter 6
  4. Click =
- **Expected Result:** Display shows 0.
- **Actual Result:** The calculator correctly displayed the result as 0.
- **Status:** Pass

---

## TC_006
- **Description:** Verify subtraction resulting in a negative value
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 8
  2. Click -
  3. Enter 15
  4. Click =
- **Expected Result:** Display shows -7.
- **Actual Result:** The calculator correctly displayed the result as -7.
- **Status:** Pass

---

## TC_007
- **Description:** Verify multiplication of two positive numbers
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 3
  2. Click *
  3. Enter 2
  4. Click =
- **Expected Result:** Display shows 6.
- **Actual Result:** The calculator correctly displayed the result as 6.
- **Status:** Pass

---

## TC_008
- **Description:** Verify multiplication by zero
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 5
  2. Click *
  3. Enter 0
  4. Click =
- **Expected Result:** Display shows 0.
- **Actual Result:** The calculator correctly displayed the result as 0.
- **Status:** Pass

---

## TC_009
- **Description:** Verify multiplication by one
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 2
  2. Click *
  3. Enter 1
  4. Click =
- **Expected Result:** Display shows 2.
- **Actual Result:** The calculator correctly displayed the result as 2.
- **Status:** Pass

---

## TC_010
- **Description:** Verify division of two positive numbers
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 6
  2. Click /
  3. Enter 3
  4. Click =
- **Expected Result:** Display shows 2.
- **Actual Result:** The calculator correctly displayed the result as 2.
- **Status:** Pass

---

## TC_011
- **Description:** Verify division resulting in a decimal value
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 5
  2. Click /
  3. Enter 2
  4. Click =
- **Expected Result:** Display shows 2.5.
- **Actual Result:** The calculator correctly displayed the result as 2.5.
- **Status:** Pass

---

## TC_012
- **Description:** Verify division by zero
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 4
  2. Click /
  3. Enter 0
  4. Click =
- **Expected Result:** Display shows appropriate error message.
- **Actual Result:** The calculator displayed the result as Infinity.
- **Status:** Pass

---

## TC_013
- **Description:** Verify addition of decimal numbers
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 12.35
  2. Click +
  3. Enter 45.62
  4. Click =
- **Expected Result:** Display shows 57.97.
- **Actual Result:** The calculator correctly displayed the result as 57.97.
- **Status:** Pass

---

## TC_014
- **Description:** Verify subtraction of decimal numbers
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 45.62
  2. Click -
  3. Enter 12.35
  4. Click =
- **Expected Result:** Display shows 33.27.
- **Actual Result:** The calculator correctly displayed the result as 33.27.
- **Status:** Pass

---

## TC_015
- **Description:** Verify multiplication of decimal numbers
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 2.5
  2. Click *
  3. Enter 1.5
  4. Click =
- **Expected Result:** Display shows 3.75.
- **Actual Result:** The calculator correctly displayed the result as 3.75.
- **Status:** Pass

---

## TC_016
- **Description:** Verify % calculation
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 100
  2. Click *
  3. Enter 10
  4. Click %
  5. Press =
- **Expected Result:** Calculator should correctly calculate 10.
- **Actual Result:** The calculator displayed 1000.
- **Status:** Fail

---

## TC_017
- **Description:** Verify % with decimal value
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 200
  2. Click *
  3. Enter 2.5
  4. Click %
  5. Press =
- **Expected Result:** Calculator should display 5.
- **Actual Result:** The calculator displayed 500.
- **Status:** Fail

---

## TC_018
- **Description:** Verify CE button clears the current input
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 123
  2. Click CE
- **Expected Result:** Current input 123 should be cleared, and the display should return to 0.
- **Actual Result:** The calculator cleared 123 successfully and displayed 0.
- **Status:** Pass

---

## TC_019
- **Description:** Verify CE button after completing a calculation
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 20
  2. Click +
  3. Enter 10
  4. Click =
  5. Verify that the result 30 is displayed
  6. Press CE button
- **Expected Result:** Completed calculation result should be cleared, and the display should return to 0.
- **Actual Result:** The completed calculation result cleared successfully and displayed 0.
- **Status:** Pass

---

## TC_020
- **Description:** Verify backspace removes the last entered digit
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 1234
  2. Click backspace button
- **Expected Result:** The last entered digit 4 should be removed, and the display should show 123.
- **Actual Result:** The last entered digit 4 was removed successfully and displayed 123.
- **Status:** Pass

---

## TC_021
- **Description:** Verify backspace with a multi digit number
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter multi digit number 123456
  2. Click backspace button
- **Expected Result:** The last digit 6 should be removed, and the display should show 12345.
- **Actual Result:** The last entered digit 6 was removed successfully and display shows 12345.
- **Status:** Pass

---

## TC_022
- **Description:** Verify calculation using multiple operator
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 10
  2. Click +
  3. Enter 5
  4. Click *
  5. Enter 2
  6. Click =
- **Expected Result:** Calculator should follow standard operator rules (BODMAS: 10 + 5 * 2 = 20).
- **Actual Result:** The calculator displayed 30 instead of showing expected result 20.
- **Status:** Fail

---

## TC_023
- **Description:** Verify sequential calculation
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 10
  2. Click +
  3. Enter 5
  4. Click +
  5. Enter 3
  6. Click =
- **Expected Result:** The calculator should perform the calculation sequentially and display 18.
- **Actual Result:** The calculator performed the calculation sequentially and displayed 18.
- **Status:** Pass

---

## TC_024
- **Description:** Verify calculation with zero as an input
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 0
  2. Click /
  3. Enter 8
  4. Click =
- **Expected Result:** Display shows 0.
- **Actual Result:** The calculator correctly displayed 0.
- **Status:** Pass

---

## TC_025
- **Description:** Verify calculator behavior with invalid or unsupported input
- **Precondition:** Calculator is open
- **Test Steps:**
  1. Enter 5.2.3
  2. Click +
  3. Enter 1
  4. Click =
- **Expected Result:** Calculator should ignore subsequent decimal point presses (displaying 5.2).
- **Actual Result:** The calculator displayed 5.2 successfully and ignored subsequent decimal points.
- **Status:** Pass

---

# Bug Reports

### BUG-01
- **Title:** Calculator displays an incorrect result when calculating percentage with a decimal value
- **Precondition:** Calculator is open
- **Severity:** Medium
- **Priority:** Medium
- **Status:** Open
- **Steps to Reproduce:**
  1. Enter 200
  2. Click the * button
  3. Enter 2.5
  4. Click the % button
  5. Press the = button
- **Expected Result:** The calculator should correctly calculate the percentage (expected result: 5).
- **Actual Result:** The calculator displayed 500 instead of 5.
- **Evidence:** https://drive.google.com/file/d/13n1M6JliEyfBLiWLPkn5x9QzIBEF2FrP/view?usp=drive_link

---

### BUG-02
- **Title:** Calculator displays an incorrect result when calculating 10% of 100
- **Precondition:** Calculator is open
- **Severity:** Medium
- **Priority:** High
- **Status:** Open
- **Steps to Reproduce:**
  1. Enter 100
  2. Click the * button
  3. Enter 10
  4. Click the % button
  5. Press the = button
- **Expected Result:** The calculator should display 10 (which is 10% of 100).
- **Actual Result:** The calculator displayed 1000 instead of 10.
- **Evidence:** https://drive.google.com/file/d/1C31tkEs9VkAfN8GKBX2fzQwKaA822U3z/view?usp=drive_link

---

### BUG-03
- **Title:** Calculator displays an incorrect result when performing a calculation using multiple operators
- **Precondition:** Calculator is open
- **Severity:** Medium
- **Priority:** High
- **Status:** Open
- **Steps to Reproduce:**
  1. Enter 10
  2. Click the + button
  3. Enter 5
  4. Click the * button
  5. Enter 2
  6. Click the = button
- **Expected Result:** The calculator should display 20, following standard operator precedence: 10 + (5 * 2) = 20.
- **Actual Result:** The calculator displayed 30 instead of 20.
- **Evidence:** https://drive.google.com/file/d/1pjserh9WLZK9HKvCZMvRG8IFzc-xRf6z/view?usp=drive_link
