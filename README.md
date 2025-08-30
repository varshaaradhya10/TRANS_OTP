# OTP Password Verification System with Twilio

This script implements a simple password authentication system with an added layer of security through OTP (One-Time Password) verification. Upon entering the correct password, an OTP is generated and sent to the user’s phone using Twilio's messaging API. The user must then enter the OTP to successfully log in.

## Features

- **Password Protection**: The system requires a correct password before proceeding to OTP generation.
- **OTP Generation**: A unique 6-digit OTP is generated upon successful password entry.
- **Twilio Integration**: The OTP is sent to the user’s phone number using Twilio's messaging service.
- **Retry Mechanism**: The user is given a maximum number of attempts (default 5) to enter the correct password and OTP.
- **Error Handling**: Handles common errors like failed OTP sending or incorrect OTP entry.

## Requirements

- Python 3.x
- Twilio Python SDK: Install it using the following command:

