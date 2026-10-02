# QLDA_NHOM10_GODDY
Phần Mềm Quản Lý Hóa Đơn / Công Nợ Tích Hợp Dashboard Dữ Liệu Tuyển Dụng
# ============================================
# 1. CLONE PROJECT
# ============================================

git clone https://github.com/nguyenhuuphuc22012005-rgb/QLDA_NHOM10_GODDY.git

cd QLDA_NHOM10_GODDY


# ============================================
# 2. KIỂM TRA NHÁNH MAIN
# ============================================

git checkout main
git pull origin main


# ============================================
# 3. TẠO NHÁNH DEVELOP
# ============================================

git checkout -b develop
git push -u origin develop


# ============================================
# 4. FEATURE - DATABASE / ERD
# Huỳnh Nguyễn Vĩnh Phúc - DB/QA
# ============================================

git checkout develop
git checkout -b feature/WBS-2.1-TASK-025-erd-csdl
git push -u origin feature/WBS-2.1-TASK-025-erd-csdl


# ============================================
# 5. FEATURE - AUTH JWT
# Phạm Văn Sơn - Backend
# ============================================

git checkout develop
git checkout -b feature/WBS-2.2-TASK-044-auth-jwt
git push -u origin feature/WBS-2.2-TASK-044-auth-jwt


# ============================================
# 6. FEATURE - CLIENT UI
# Nguyễn Hoàng Phước - Frontend
# ============================================

git checkout develop
git checkout -b feature/WBS-2.3-TASK-052-client-ui
git push -u origin feature/WBS-2.3-TASK-052-client-ui


# ============================================
# 7. FEATURE - INVOICE API
# Phạm Văn Sơn - Backend
# ============================================

git checkout develop
git checkout -b feature/WBS-3.1-TASK-075-invoice-api
git push -u origin feature/WBS-3.1-TASK-075-invoice-api


# ============================================
# 8. FEATURE - DEBT AGING UI
# Nguyễn Hoàng Phước - Frontend
# ============================================

git checkout develop
git checkout -b feature/WBS-3.3-TASK-114-debt-aging-ui
git push -u origin feature/WBS-3.3-TASK-114-debt-aging-ui


# ============================================
# 9. FEATURE - DASHBOARD API
# Phạm Văn Sơn - Backend
# ============================================

git checkout develop
git checkout -b feature/WBS-4.1-TASK-121-dashboard-api
git push -u origin feature/WBS-4.1-TASK-121-dashboard-api


# ============================================
# 10. RELEASE V0.1
# Tạo từ develop
# ============================================

git checkout develop
git pull origin develop

git checkout -b release/v0.1
git push -u origin release/v0.1


# ============================================
# 11. HOTFIX
# Tạo từ MAIN
# ============================================

git checkout main
git pull origin main

git checkout -b hotfix/fix-tax-calc
git push -u origin hotfix/fix-tax-calc


# ============================================
# 12. QUAY LẠI DEVELOP
# ============================================

git checkout develop
