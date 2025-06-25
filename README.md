# 🎓 Campus IT Support Portal (ServiceNow)

A custom ServiceNow application designed to streamline IT service requests for students, faculty, and administrators within a campus environment.

## 📌 Features

- 🔧 **Service Catalog**: Users can submit requests like "Request a Laptop" via user-friendly catalog items.
- ⚙️ **Flow Designer**: Automates ticket creation, routing, and escalation based on form input.
- 🔐 **Role-based Access (ACLs)**: Ensures students, faculty, and admins have appropriate permissions.
- 📊 **Dashboards & Reporting**: Track request types, urgency, resolution times, and more.
- ✏️ **Custom Tables**: Built a dedicated `IT Request` table for managing all incoming issues.

## 🛠 Technologies Used

- ServiceNow Studio
- GlideScript (Server/Client Scripts)
- Flow Designer
- Access Control Lists (ACLs)
- Service Catalog
- GitHub Integration

## 🚀 How It Works

1. A user submits an IT request (e.g., "Request a Laptop") from the Service Catalog.
2. A Flow Designer flow captures the input and creates a record in the `IT Request` table.
3. ACLs control who can view, edit, and manage tickets.
4. Dashboards help admins monitor trends and performance.

## 📁 File Structure

This repository contains:
- Flow definitions
- Catalog item configurations
- Table schema
- ACLs and client scripts
- App manifest files

## 👨‍💻 Author

**Viswanadhapalli Srinivas**  
B.Tech in Computer Science, 2025  
[LinkedIn Profile](#) *(Add link if available)*

---

Feel free to fork or contribute!
