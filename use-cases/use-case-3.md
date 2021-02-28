# USE CASE: 3 produce a report on the salary of employees in my department so that I can support financial reporting for my department

## CHARACTERISTIC INFORMATION

### Goal in Context

As a *department manager* I want *to produce a report on the salary of employees in my department* so that *I can support financial reporting for my department.*

### Scope

Company.

### Level

Primary task.

### Preconditions

We know the role.  Database contains current employee salary data.

### Success End Condition

A report is available for each department to support financial reporting.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request for finance information is requested from a department.

## MAIN SUCCESS SCENARIO

1. Each Department requests salary information of all employees in their department.
2. Department captures name of department to get salary information for.
3. Department extracts current salary information of all employees in department.
4. Department provides report to finance.

## EXTENSIONS

3. **Role does not exist**:
    1. Department informs finance no role exists.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0