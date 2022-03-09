# USE CASE: 8 Delete employee details.

## CHARACTERISTIC INFORMATION

### Goal in Context

As a *HR advisor* I want *to delete an employee's details* so that *the company is compliant with data retention legislation*.

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the employee.  Database contains current employee data.

### Success End Condition

Employee is delete from the database.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for an employee's data to be deleted is sent to HR.

## MAIN SUCCESS SCENARIO

1. Employee requests data to be deleted.
2. HR advisor captures name of the employee who's data is to be deleted.
3. HR advisor deletes employee's data.

## EXTENSIONS

3. **Employee does not exist**:
    1. HR advisor informs employee they have no data in the system.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
