![CI](https://github.com/devanshukothe/SGGS-Permit-Flow/actions/workflows/client-ci.yml/badge.svg)
![CI](https://github.com/devanshukothe/SGGS-Permit-Flow/actions/workflows/server-ci.yml/badge.svg)

📌 What is SGGS Permit Flow?
SGGS Permit Flow is a centralized web portal designed for students and faculty of SGGS to manage and approve various permission-based processes including:

🎤 Event organization requests

🏫 Facility booking (labs, halls, grounds)

🗓️ Leave applications (students & faculty)

💬 Feedback and approval workflows

📁 PDF upload and digital proof verification

🔐 College-email authentication (@sggs.ac.in)
---
##✨ Features
🔄 Live Status Tracking – Students can track the real-time status of their applications.

📝 Smart Feedback System – Faculty/Secretaries can approve/reject with remarks.

📄 PDF Viewer Integration – Preview uploaded documents before approval.

🧠 Priority-based Escalation – Automatically escalates pending requests.

📬 Email Notifications – Alerts on status change or required action.

📊 Dashboard for Role-Based Access – Secretary, Faculty & Student panels.
 ---
🛠️ Tech Stack
Layer	Technology
Frontend	React.js, Tailwind CSS
Backend	Firebase Firestore & Functions
Auth	Firebase Auth (SGGS email only)
File Storage	Firebase Storage
PDF Viewer	PDF.js or external viewer API
Hosting	Firebase Hosting

🚀 Getting Started
bash
Copy
Edit
# Clone the repository
git clone https://github.com/devanshukothe/sggs-permit-flow.git
cd sggs-permit-flow

# Install dependencies
npm install

# Run the app
npm start
Ensure Firebase project setup is done, and .env is configured with your Firebase keys.

🖼️ Demo Screenshots
Student Panel	Secretary Panel	PDF Viewer

🎯 Use Cases
Event Management: Students submit proposals, upload PDFs, and track approvals.

Facility Booking: Clubs can request slots with real-time availability.

Leave Automation: Student leave requests routed to faculty → HoD → Coordinator.

Digital Governance: General Secretaries manage all requests transparently.

🤝 Contributing
PRs are welcome! For major changes, please open an issue first to discuss what you would like to change.

Fork the repo

Create your feature branch: git checkout -b feature/yourFeature

Commit your changes: git commit -m 'Add some feature'

Push to the branch: git push origin feature/yourFeature

Open a pull request

📄 License
MIT License. See LICENSE for more information.

💬 Connect
Built with ❤️ by SGGS Developers

📧 Email: 2022bcs073@sggs.ac.in

🌐 Website: sggs.ac.in


