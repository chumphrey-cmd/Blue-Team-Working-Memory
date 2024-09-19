# Security Hardening and Logging Overview

## Overview

This document provides a brief overview of the essential procedures for securing various open ports and configuring event logging on a intentionally vulnerable Windows 10 system. It covers the hardening steps for different ports, including SSH, RPC, NetBIOS, SMB, RDP, and HTTP, as well as the critical logging practices to enhance system security.

## Key Areas Covered

- **Port Hardening:** Guidelines for securing commonly exposed ports to mitigate potential vulnerabilities.
- **Event Logging:** Recommendations for configuring event logs to improve security monitoring and detection capabilities.

## Important Concepts

1. **Process Creation Logging:** Essential for tracking and monitoring processes running on a system, with options for using Sysmon or built-in Security logs.
2. **Security Log Configuration:** Proper tuning of the Security log for effective system monitoring.
3. **PowerShell Logging:** Enabling Module and ScriptBlock logging to detect and respond to PowerShell abuse.
4. **Sysmon and Additional Logs:** Utilizing Sysmon events and other critical logs for comprehensive security oversight.
