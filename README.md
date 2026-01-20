 Contact List Management
 
 Overview
 
Contact List is a desktop application built with C# Windows Forms, designed to help users manage personal contact information efficiently and intuitively. This project was developed to demonstrate and practice GUI programming, event handling, and data manipulation within the .NET environment.

The application provides essential CRUD (Create, Read, Update, Delete) functionalities to manage friends, clients, or partners effectively.

 Key Features
 
 Add New Contact: Input detailed information (Full Name, Phone Number, Email, Address, etc.).

 View List: Display contacts in a clear, organized table format (DataGridView).

 Edit Information: Update details for existing contacts easily.

 Delete Contact: Remove obsolete or unwanted contacts from the list.

 Search: Quickly look up contacts by name or phone number.

 Data Persistence: Data is saved securely (Local file or Database support depending on implementation).

 Tech Stack
 
Language: C#

Framework: .NET Framework / .NET Core (Windows Forms App)

IDE: Microsoft Visual Studio

UI: Windows Forms (WinForms) Standard Controls

 Installation & Usage
Follow these steps to get the project running on your local machine:

1. Prerequisites

Windows Operating System.

Visual Studio (2019 or later) with the ".NET desktop development" workload installed.

2. Steps to Run

Clone the repository:

Bash

git clone https://github.com/LucasJr67/contact-list-winforms.git

Open the project:

Launch Visual Studio.

Select File > Open > Project/Solution.

Navigate to the ContactList folder and select the .sln (Solution) file.

Build and Run:

Press F5 or click the green Start button in the toolbar to compile and launch the application.

Folder Structure

Plaintext

contact-list-winforms/
├── ContactList/          # Main source code directory
│   ├── Forms/            # UI Forms (MainForm, AddEditForm...)
│   ├── Models/           # Data Models (Contact.cs...)
│   ├── Data/             # Data access logic (Repositories/Context)
│   ├── Program.cs        # Application entry point
│   └── ...
├── .gitignore
└── README.md

Contributing

Contributions are always welcome! If you'd like to improve this project, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/AmazingFeature).

Commit your changes (git commit -m 'Add some AmazingFeature').

Push to the branch (git push origin feature/AmazingFeature).

Open a Pull Request.

Contact

Author: LucasJr67
