
Save New Duplicate & Edit Just Text Twitter
# O2 Phishing Page Documentation

**DISCLAIMER: This documentation is not for educational purposes.**

## Overview

This is a comprehensive documentation of an O2-themed phishing page designed to capture user credentials and payment information. The page mimics the O2 telecom provider's login and verification flow.

## Pages

### Login Page
- Email/password login form with O2 branding
- Toggle between email and phone number login options
- Password visibility toggle
- Error handling for invalid credentials
- Session tracking and management
- Telegram notification system for new visitors

### Phone Verification
- Phone number input with auto-formatting
- Czech Republic prefix (+420) with dynamic display
- Input validation for proper phone number format
- Loading animation during submission
- Error handling for invalid phone numbers

### Email OTP Verification
- 6-digit verification code input
- Individual digit input fields with auto-focus
- Paste functionality for verification codes
- Resend functionality with cooldown timer
- Error handling for invalid codes
- Loading animation during verification

### SMS OTP Verification
- 6-digit verification code input
- Individual digit input fields with auto-focus
- Paste functionality for verification codes
- Resend functionality with cooldown timer
- Error handling for invalid codes
- Loading animation during verification

### Credit Card Information
- Professional payment gateway interface mimicking ČSOB Bank
- Credit card number input with auto-formatting
- Expiry date selection
- CVV input
- Transaction details display
- Merchant information display
- Auto credit card validation features:
  - BIN validation
  - Card type detection
  - Expiry date validation
  - CVV length validation based on card type

## Special Features

### SMS/Email Verification
- Direct paste functionality for verification codes
- Individual digit input with automatic focus advancement
- Backspace functionality that moves focus to previous input
- Resend functionality with 30-second cooldown timer
- Visual error indication for incorrect codes

### Admin Panel
- Secure admin login system
- Real-time session monitoring
- Control panel to manage active sessions
- Ability to trigger different verification steps
- Session status management
- Error logging system
- Responsive design for mobile administration

### Telegram Integration
- Real-time notifications for new visitors
- Detailed visitor information including:
  - IP address
  - Location (city, country)
  - Browser and OS information
  - Timestamp
- Notification for successful logs,resets and data submissions

### User Flow Management
- Seamless transition between verification steps
- Status checking system to determine next steps
- Error handling at each stage
- Session persistence across pages
- Automatic redirection based on verification status

### Mobile-Optimized Design
- Responsive layout for all device sizes
- Native-like mobile interface
- Touch-friendly input elements
- Visual feedback for user actions
- Loading animations during processing

## Usage Notes

The phishing flow follows these steps:
1. User enters email/password on the login page
2. User is prompted to enter their phone number
3. User receives and enters an SMS verification code
4. User receives and enters an email verification code
5. User is prompted to enter credit card information
6. After successful completion, user is redirected to the legitimate O2 app or website

The admin panel allows control over each step of the verification process, with the ability to trigger success or error states at each stage.
