

# 🧪  Laboratory Inventory Management System

[![PHP Version](https://img.shields.io/badge/PHP-%3E%3D%208.1-777BB4.svg)](https://www.php.net/)
[![Framework](https://img.shields.io/badge/Framework-CodeIgniter%204-FC4C02.svg)](https://codeigniter.com)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**LabTrack** is a web-based inventory management solution developed using **CodeIgniter 4**, created to help universities and research laboratories efficiently monitor and manage their lab equipment and consumables. The system is designed to simplify record keeping, minimize data entry errors, and improve accessibility for students, technicians, and administrators.

---

## 🌟 Main Features

- **Multi-User Roles & Permissions** — Administrators, lab technicians, and students have specific access privileges.  
- **University Email Verification** — Login and registration are restricted to verified institutional email addresses.  
- **QR Code Management** — Automatically generate and assign unique QR codes for each item, allowing quick access via scanning.  
- **CSV Upload Support** — Import large datasets at once for faster data population and updates.  
- **Dynamic Search & Filter Tools** — Instantly find equipment or materials using category-based search filters.  
- **Inventory Insights Dashboard** — Visual overview of available stock, recent activity, and usage analytics.  
- **Responsive Design** — Built for accessibility on both desktop and mobile browsers.

---

## 🧰 Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | PHP 8.1+, CodeIgniter 4 |
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Database** | MySQL |
| **QR Code Generation** | chillerlan/php-qrcode |
| **Version Control** | Git |

---

## ⚙️ Installation Guide

Follow these steps to set up the project locally for testing and development.

### 1️⃣ Prerequisites

Ensure the following are installed:
- PHP ≥ 8.1 (with `intl`, `mbstring`, `json`, `libcurl`, `mysqlnd`, `gd` or `imagick`)
- Composer
- Git
- A web server (Apache, Nginx, or use `php spark serve`)
- MySQL or compatible database

### 2️⃣ Clone the Repository

```bash
git clone https://github.com/HashaniKulathunga/labtrack.git
cd labtrack
