# 🔔 SharePoint File Alert Flow

This is a real-world automation scenario using Microsoft Power Automate and SharePoint Online.
It demonstrates how to send an automated email notification when a file is added to a document library.

## 📌 Use Case
A company wants to be notified when a user uploads a new file into a sensitive SharePoint document library to detect any unusual activity.

## ⚙️ Technologies Used
- SharePoint Online
- Microsoft Power Automate
- Outlook 365

## 📸 Screenshots
All steps are documented in the `/screenshots` folder.

## 📥 Flow Logic
1. **Trigger**: When a new file is added to library `RH-01`
2. **Action**: Get file properties
3. **Action**: Send email to the admin (via Outlook)

## 📄 Files
- Exported Flow (`flow_export/flow.json`)
- Visual documentation (`screenshots/`)

## 🧠 What I Learned
- How to automate notifications from SharePoint
- How to use dynamic content and triggers in Power Automate
- How to build secure flows for internal file monitoring

## ✅ This lab is part of my Canadian IT Lab Series 2025
