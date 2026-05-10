# SLPA Windows Application

A C# WinForms desktop application built for the **Sri Lanka Ports Authority (SLPA)** as a university project by Team Syscall (University of Moratuwa, Faculty of IT, Batch 11, Level 2).

## Features

- **Driver management** — search, add, update, and delete driver job records
- **Role-based access** — Administrator and User roles with different permissions
- **Destination tracking** — stores GPS coordinates (latitude/longitude) per destination
- **User management** — add, edit, and remove system users
- **Password management** — users can change their own password

## Tech Stack

- **Language:** C#
- **Framework:** Windows Forms (.NET)
- **Database:** MySQL (local, database name: `syscall`)

## Prerequisites

- Windows OS
- MySQL Server running locally

## Getting Started

1. Clone the repository
2. Set up the MySQL database using the scripts in `SLPA_SETUP/`
3. Open `SLPA.sln` in Visual Studio
4. Build and run
