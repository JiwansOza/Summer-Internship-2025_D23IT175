# 📅 Day 44 - July 22, 2025

## ✅ What I Worked On
- Implemented restriction on **AutoDialer module** for Guest Users
- Ensured guest users cannot access or trigger AutoDialer functionality

## 🧠 What I Learned
- Fine-grained permission handling for specific modules
- How to enforce access restrictions at both **UI and backend levels**

## 🧩 Challenges I Faced
- Needed to ensure that guest restrictions don’t affect normal registered users
- Handling conditional rendering of UI components based on role

## 🔧 How I Solved / Plan to Solve It
- Added role-based access control (RBAC) check for `org_name` and `user_type`
- Updated UI to disable/grey out AutoDialer option for Guest Users

## 📚 Resources I Used
- RBAC implementation examples
- Documentation on middleware for access restriction

## 💬 Notes / Observations
- Guest restrictions working as expected for AutoDialer  
- Next step: Apply similar restrictions to other sensitive modules
