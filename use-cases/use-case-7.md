# USE CASE: 7 Update employee's details store in the system

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to update an employee's details* so that *employee's details are kept up-to-date.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the details to be updated and the name of the employee that needs their details updated.  We have write permissions for the employee database.

### Success End Condition

The employee's details are successfully updated.

### Failed End Condition

Employee's details are not updated.

### Primary Actor

HR Advisor.

### Trigger

A request for an employee's details to be updated is sent to HR.

## MAIN SUCCESS SCENARIO

1. An employee requests their details to be updated.
2. HR advisor captures details to be updated and the which employee has requested the change.
3. HR advisor updates the employee's details.

## EXTENSIONS

2. **Employee does not exist**:
    1. HR advisor informs the employee they are not on the system.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
