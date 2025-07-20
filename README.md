# 📊 Attendance Management System (MS Access)

![Access Version](https://img.shields.io/badge/MS_Access-2019+-blue)
![VBA](https://img.shields.io/badge/VBA-Enabled-green)
![License](https://img.shields.io/badge/License-MIT-orange)

A comprehensive employee attendance tracking system with biometric integration and advanced reporting capabilities.

 🌟 Key Features

 👥 Employee Management
   📝 Complete employee profiles (Name, ID, Department, CNIC)
   📸 Photo storage & management
   📅 Joining date tracking

⏱️ Attendance Tracking
  ✅ Present/Absent/Late status recording
  🕒 Automated time capture
  📲 Scan-based attendance (barcode/RFID support)

🔄 Data Operations
  ✏️ Information updates (Personal/Emergency/Institutional)
  💾 One-click backups to desktop
  📤 Excel export for all reports

🔒 Security
  🔑 Role-based access control
  🔄 Password change with confirmation
  📝 Activity logging

🛠️ Technical Overview

```mermaid
graph TD
    A[Main Form] --> B[Employee Module]
    A --> C[Attendance Module]
    A --> D[Reports Module]
    B --> E[Database]
    C --> E
    D --> E
