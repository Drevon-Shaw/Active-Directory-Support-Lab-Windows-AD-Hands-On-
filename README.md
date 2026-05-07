# 🛠️ Active Directory Support Lab – Part 1

This lab simulates a small enterprise environment using **Windows Server 2022** and **Windows 10** to practice real‑world IT support and Active Directory administration. It walks through domain setup, user and group management, Group Policy, account security, and common help desk scenarios.

---

## 🎯 Lab objectives

By completing this lab, I:

- Install and configure a **Domain Controller** for a new Active Directory domain.  
- Create and manage **users, security groups, and Organizational Units (OUs)** aligned to departments.  
- Apply **Group Policy Objects (GPOs)** to control desktop settings and security policies.  
- Configure **file share permissions** and test group‑based access.  
- Implement **account lockout policies** and **password recovery** workflows.  
- Practice day‑to‑day **Active Directory support tasks** in a lab environment.

---

## 🗂️ Lab structure

Each part of the lab is documented in its own walkthrough so it’s easy to follow and revisit specific tasks:

- **Lab Preparation**  
  _Environment overview, prerequisites, and base configuration before promoting the domain controller._  
  👉 [Lab Preparation](Labprep.md)

- **Active Directory Installation**  
  _Rename the server, install AD DS, promote to Domain Controller, and configure certificate services._  
  👉 [Active Directory Installation](02_ADInstall.md)

- **Users and Organizational Units (OUs)**  
  _Design the OU structure, create users, and configure security groups for department‑based access._  
  👉 [Users and Organizational Units (OUs)](03_UsersAndOUs.md)

- **Group Policy Objects (GPOs)**  
  _Create and link GPOs for wallpapers, security baselines, lockout policies, and other user/computer settings._  
  👉 [Group Policy Objects (GPOs)](04_GPOs.md)

- **Account Lockout & Password Reset**  
  _Simulate account lockouts, perform password resets, and safely unlock user accounts the way a help desk would._  
  👉 [Account Lockout & Password Reset](05_AccountLockout.md)

- **Lab Summary & Key Takeaways**  
  _Summary of what was implemented, issues encountered, how they were resolved, and next steps._  
  👉 [Lab Summary & Key Takeaways](06_LabSummary.md)

---

## 🧩 Skills and tools demonstrated

- Active Directory Domain Services (**AD DS**) installation and configuration  
- OU and group design for a small business environment  
- Group Policy creation, targeting, and troubleshooting  
- User lifecycle operations (create, modify, disable, lock/unlock, password reset)  
- Basic **IT support workflows** for Windows clients joined to a domain  

---

## ⚡ How to use this lab

- Follow the sections **in order** the first time to avoid configuration issues.  
- Use the Table of Contents links to jump back to specific tasks when needed.  
- Treat each section as a mini “ticket”: read the scenario, then apply the documented steps to resolve it.

---

🎉 By completing this lab, I gained practical Active Directory administration experience, stronger foundational security skills, and a better understanding of day‑to‑day enterprise support workflows.
