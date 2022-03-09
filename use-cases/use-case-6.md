# USE CASE: 6 View an employee's details.

## CHARACTERISTIC INFORMATION

### Goal in Context

As a *HR advisor* I want *to view an employee's details* so that the *employee's promotion request can be supported*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee.  Database contains current employee's data.

### Success End Condition

We can view the employee's details.

### Failed End Condition

Employee is not found.

### Primary Actor

HR Advisor.

### Trigger

A request for employee data is sent to HR.

## MAIN SUCCESS SCENARIO

1. Employee data is requested.
2. HR advisor captures name of the employee to get data for.
3. HR advisor extracts data for employee.
4. HR advisor provides data on employee.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor informs finance that employee information is not on the system.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
