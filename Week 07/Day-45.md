# 📅 Day 45 - July 23, 2025

## ✅ What I Worked On
- Added restriction on **Email module** for Guest Users
- Ensured Guest Users cannot send or configure email campaigns

## 🧠 What I Learned
- Handling role-based permissions across multiple modules
- How to centralize guest restrictions for easier maintainability

## 🧩 Challenges I Faced
- Needed to block backend API calls as well, not just the UI
- Preventing Guest User from bypassing restrictions with direct requests

## 🔧 How I Solved / Plan to Solve It
- Applied middleware checks for `user_type = guest` in Email routes
- Updated frontend to hide/disable Email features for Guest Users

## 📚 Resources I Used
- Express middleware patterns for RBAC
- Examples of role-based UI rendering in React

## 💬 Notes / Observations
- Guest restrictions are now active on **AutoDialer + Email modules**  
- Plan to extend the same restrictions to SMS and Campaign management next
