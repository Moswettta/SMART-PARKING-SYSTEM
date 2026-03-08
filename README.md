🚗 Universal Smart Parking Management System (SPMS)
A robust, high-performance Parking Management System designed to automate vehicle registration, payment verification, and secure access control using QR-coded digital permits.

🌟 Key Features
👤 User Module
Flexible Slot Booking: Users can reserve slots by selecting a specific county or zone and entering their vehicle plate number.

Instant Notifications: Real-time feedback via a dedicated notification hub for payment approvals, rejections, or expiry alerts.

Digital QR Tickets: Generates high-fidelity, printable tickets that encode registration data directly into a QR code for offline security verification.

Live Status Tracking: Dynamic "My Bookings" dashboard with auto-expiry logic that flags overstayed reservations.

🛡️ Administrative Module
Unified Verification Hub: Centralized dashboard to cross-reference M-Pesa, bank, or cash transactions with pending bookings.

Atomic Approvals: Uses SQL Transactions to ensure that booking status, payment status, and user notifications are updated simultaneously.

Automated Rejections: One-click rejection capability that notifies users instantly with specific cancellation details.

Slot Management: Real-time tracking of "Available" vs "Occupied" slots across multiple parking zones.

🛠️ Technical Stack
Backend: PHP 8.x (Procedural & OOP hybrid for performance).

Database: MySQL / MariaDB (Relational schema with foreign key constraints).

Frontend: Modern, responsive CSS using Variables for easy white-labeling and brand customization.

Security: Session-based authorization, mysqli prepared-style escaping, and transaction rollbacks for data integrity.

QR Engine: Integrated QR-Server API for text-based data encoding.
