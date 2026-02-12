# I. Chosen Software Architecture Style  

The system follows a **Hybrid Architecture** that combines:

1. Monolithic Modular Architecture  
2. Event-Driven Architecture  

---

# Part 1: Monolithic Modular Architecture

## Definition

Monolithic Modular Architecture is a design style in which:

- The entire system is deployed as a single application.
- The system is internally divided into logically independent modules.
- Each module performs a specific business function.
- Modules share a common codebase and typically a shared database.
- Communication between modules happens through internal method calls.

---

## Granularity of Software Components

Granularity refers to the size and responsibility scope of software components.

In this system:

- The architecture uses **medium-grained modules**.
- Each module encapsulates a complete functional responsibility.
- Modules are logically separated but not independently deployable.
- All modules operate within a single deployment unit.

The granularity is:

- More structured than a tightly coupled monolithic system.
- Less distributed than microservices architecture.
- Organized at the modular level within one executable system.

---

## Application Modules

1. **User Management Module**
   - User registration
   - Login and logout
   - Authentication and authorization
   - Role management

2. **Monitoring Module**
   - Collection of CPU, memory, and disk metrics
   - Storage of performance data

3. **Alert Management Module**
   - Definition of threshold values
   - Evaluation of metrics
   - Generation of alerts

4. **Notification Module**
   - Sending email/SMS notifications
   - Integration with messaging services
   - Maintenance of notification history

5. **Dashboard Module**
   - Display of real-time metrics
   - Graphical visualization
   - System health monitoring

6. **Logging Module**
   - Storage of system logs
   - Maintenance of audit records
   - Recording alert history

---

## Justification

The system qualifies as Monolithic Modular Architecture because:

- It is deployed as a single unit.
- Modules share the same runtime environment.
- Modules are logically separated.
- Internal communication occurs through direct function calls.
- Independent deployment of modules is not required.


