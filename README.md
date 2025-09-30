# Lab 01a – Manage Subscriptions and RBAC

This lab is part of my AZ-305 tactical sprint, focused on governance foundations in Azure. It covers management group hierarchy, built-in and custom RBAC roles, and access auditing via the Activity Log. All actions were performed using Cloud Express Pass credentials on the XtremeLabs platform.

## 🔧 Lab Summary

- Created a **Management Group** (`az104-mg101`) to organize subscriptions under a centralized governance structure.
- Assigned the **Virtual Machine Contributor** built-in role to the `helpdesk` group using least privilege principles.
- Cloned and customized the **Support Request Contributor** role to exclude unnecessary permissions, creating `Custom Support Request 101`.
- Audited role assignments using the **Activity Log**, confirming changes and validating compliance.

## 📸 Screenshots Included

- Management Group hierarchy view  
- Role assignment blade with VM Contributor  
- Custom role JSON and permission exclusions  
- Activity Log filtered by role assignment events

## 🧠 Key Takeaways

- Management Groups enable scalable governance across subscriptions.  
- Built-in roles simplify access control; custom roles provide precision.  
- RBAC roles are defined using JSON with `Actions`, `NotActions`, and `AssignableScopes`.  
- The Activity Log is essential for tracking and auditing access changes.


