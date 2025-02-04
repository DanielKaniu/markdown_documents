# Tracker

This is a system that will aid in tracking our daily activities and assignments.

## The Systems Objectives

1. To monitor assignments given to staff.
2. To keep records of all interns.
3. To monitor day to day operations.

## Tracker in relation to Registrar module

In tracker application we intend to have three role players;The C.E.O of a
company,the staff and the developers of their systems.

### C.E.O  

The C.E.O should be in a position to register.

- His organization.
- His developers.
- His staff.

### Interns

The interns in turn should be able to register.

- The organization they work for.
- The application they are currently working on.
- Their personal details.

## Registrar Agenda

```mermaid
stateDiagram
    Registrar --> INTERN
    Registrar --> CEO
    
    INTERN --> PIQ
    INTERN --> CAQ
    
    CEO --> Batch
```

## Proposal to the existing system

1. Design a new model and add a relationship linking them to their applications
Add the C.E.O to the model.
2. Every developer should have an account in the tracker application in order
to.
3. Add a modules table.

- Receive payment
- Input tea expense receipts

### Proposal to the existing system

1. Change from developer to intern

When registering a new intern, some of the questions to be asked are

- Their full name
- Mobile number
- Type of internship.
- Duration and the institution an intern is currently under
- Previous attachments
- Qualification
- Residence
- Reference[who referred you to this program ?]  

## Assignments

**A** `(15-02-2022)`

1. Ways of authenticating oneself in order to login

   - Login with Google (DK)

   - Login with facebook (PK)


2. Work out a logical order of the questions and sketch a flow chart of the
   login process.(Everyone)

**B** `(22-02-2022)`

1. Design a chart (FN)
2. Design a Paper Image Questionnaire (PIQ) from the chart.(JN)
3. Design a Computer  Assisted Questionnaire (CAQ) individual html pages for the chart.(SW)
4. Ensure the class step is working correctly.(DK)
5. Design the user interface.(FN)
6. Data collection from the PIQ.(PK)

