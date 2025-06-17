# MT5 License Management System

A comprehensive license management system for MetaTrader 5 Expert Advisors (EAs) with separate user and admin interfaces.

## Features

### User Dashboard
- Account Management: Add and manage MT5 account numbers for different EAs
- License Status Tracking: View real-time status (Active, Pending, Denied)
- Multi-EA Support: Manage licenses for multiple Expert Advisors
- Account Limits: Respect configured account limits per EA

### Admin Panel
- License Approval System: Review and approve/deny user requests
- User Management: View all users, block/unblock accounts
- EA Configuration: Set maximum account limits for each EA
- Real-time Monitoring: Track all activities and user status

### Supported Expert Advisors
- EA-Scalper
- EA-Trend
- EA-Grid
- EA-Martingale

## Tech Stack
- React 18 with Hooks
- Tailwind CSS
- Lucide React Icons
- Modern UI/UX Design

## Demo
- **User Login**: Access user dashboard to manage MT5 accounts
- **Admin Login**: Access admin panel for license management

## Installation

```bash
git clone https://github.com/yourusername/mt5-license-system.git
cd mt5-license-system
npm install
npm run dev
