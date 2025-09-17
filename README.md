***

# **VIT Q-Less:** *Queue less to stress less*

## Short Description
The **VIT Q-Less** platform is a comprehensive digital solution engineered to resolve the inefficiencies associated with physical queuing and appointment management at Vellore Institute of Technology (VIT). The platform offers a streamlined, user-centric interface for students to manage their engagement with key campus services, thereby converting unproductive waiting time into a period of enhanced academic and personal productivity.

***

## Problem Statement
The core problem is that students at VIT Vellore waste time and face frustration due to inefficient systems for queuing and booking appointments for common campus services. The current campus ecosystem consists of a major flaw: long physical waiting queues at high-traffic service points such as messes, administrative offices, HOD rooms, and Proctor cabins.

***

## Proposed Solution
**VIT Q-Less** is a full-stack web application cum mobile app designed to digitize and optimize campus service interactions. The solution is modular, scalable, and built on a modern technology stack to ensure performance and reliability. This solution adaptively stands as a solution to the given problem statement.

***

## Features

### Unified Service Dashboard
This is the central hub of the application, designed as a **single-screen mobile/web app**. It presents the services offering a queue (messes,sports courts, gyms,etc). Each service is represented by a card that displays a simple status of **"Open" or "Closed,"** without showing live queue data. A button on each card allows the student to proceed to the next step.

### Live Queue and Appointment System
This section outlines the core functionality for managing queues and appointments.

#### Queueing Module (for Messes)
This module provides a straightforward interface for students to join a queue digitally.
* **Token Generation:** A student taps a **"Get a Token"** button to receive a single, sequential number (e.g., #54).
* **Status Display:** The screen shows the student's token number and the **"Now Serving: #[number]"** counter. This counter is **manually updated** by a staff member on their separate interface.
* The module provides notifications and estimated wait times and shows the current queue status.

#### Appointment Module (for Staff)
This module allows students to book a fixed time slot for a meeting.
* **Time Slot Booking:** A basic booking page displays a fixed number of available time slots for the day (e.g., 10:00 AM, 10:30 AM).
* **Confirmation:** The student taps on a slot to book it, which then becomes unavailable. A **confirmation message** with the date and time is provided upon successful booking.
* There is calendar synchronization and automated reminders, keeping the process simple and direct.

### Admin System
This portal is a single web page or a simple app for each service provider, enabling manual queue and appointment management.
* **Queueing Service:** For the mess, the interface displays a list of active tokens with a large **"Serve Next"** button to advance the counter.
* **Appointment Service:** For the admins, the page shows a simple list of all appointments booked for the day.

## Screenshots

![.png](https://github.com/AxonCodez/vitqless/blob/55b24f5b67fd5c41d0753c453555df80dbfc15ee/Screenshot%202025-09-17%20125243.png)
![.png](https://github.com/AxonCodez/vitqless/blob/13ea636312fd8470e55c078da42341e4041c09b5/Screenshot%202025-09-17%20125728.png)
