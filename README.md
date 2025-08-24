# Go Conference Booking App

A command-line application written in Go that allows users to book conference tickets, validates their input, and sends simulated confirmation emails asynchronously.

---

## Features
- Input validation for names, email, and ticket count.
- Concurrent email sending using Goroutines.
- Tracks remaining tickets.
- Displays a list of all booked attendees.
- Graceful exit when all tickets are sold out.

---

## Requirements
- Go 1.16+ installed
- Terminal/command prompt

---

## Installation & Running
Clone the repository and navigate to the project folder:
```bash
git clone https://github.com/meedaycodes/go-conference-booking.git
cd go-conference-booking
