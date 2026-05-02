# DVWA HTTP → HTTPS Security Lab

A step-by-step security lab guide demonstrating how sensitive data is 
exposed over plain HTTP and how to mitigate it using SSL/TLS encryption.

## 🎯 Objective

Prove that HTTP transmits sensitive data in clear text, then secure the 
server by implementing a self-signed SSL/TLS certificate.

## 🧪 Lab Environment

- **OS:** Kali Linux
- **Application:** DVWA (Damn Vulnerable Web Application)
- **Tools:** Apache2, MySQL, OpenSSL, Wireshark

## 📋 What's Covered

- Setting up DVWA on Kali Linux
- Capturing HTTP traffic with Wireshark
- Observing plain-text credential and SQL payload exposure
- Generating a self-signed SSL/TLS certificate
- Configuring Apache for HTTPS
- Verifying encrypted traffic with Wireshark

## 🔐 Key Finding

Sensitive inputs like credentials and SQL payloads are fully visible 
over HTTP. After implementing HTTPS with TLSv1.3, all traffic is 
encrypted and unreadable to an attacker.

## 📄 File

- `DVWA_Lab_Guide.html` — Full lab guide with screenshots (self-contained)

## ⚠️ Disclaimer

This lab is for **educational purposes only**. Always practice ethical 
hacking in controlled, authorized environments.
