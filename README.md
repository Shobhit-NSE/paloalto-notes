# Palo Alto Firewall Notes

A structured knowledge base covering networking fundamentals, Palo Alto Networks Next-Generation Firewalls (NGFW),
PAN-OS concepts, firewall configuration, and troubleshooting.

This repository is part of my network security learning portfolio, where I document technical concepts, 
practical takeaways, useful commands, and interview preparation notes.

## Objectives
-Document Palo Alto Networks firewall concepts in a clear, organized way.

-Maintain a reference for PAN-OS CLI commands and troubleshooting techniques.

-Prepare for Network Security Engineer and Palo Alto Firewall support interviews.

## Topics Covered
### 1. PAN-OS Fundamentals
 -Firewall architecture and core components
 
 -Interfaces, zones, and virtual routers

 -Management plane and data plane

 -GUI Dashboard 

### 2. Security Policies
-Overview of Security Policy structure and matching

-Policy Logging and traffic verification

### 3. NAT
- NAT and its Types

- NAT rule matching and ordering

- NAT Troubleshooting Fundamentals

### 4. Session
-What is  a session? Session Browser

-Types of session , Flags , 
 
-Session table, End reason

-Life Cycle of a Session 

-How to filter the session and clear the session 

### 5. Life of a Packet
 -Packet Flow 

-Stages of Packet Sequence

-Ingress,Slow Path,Fast Path and Egress stage.

-Flow lookup,Appid- cache,tuneel decryption/encryption,SSL Decryption and encryption

### 6. Packet Captures, Packet Filters and Global Counters
-Packet capture stages - receive, firewall, drop and transmit

-Packet Filters for Different traffic -DNS,ICMP and Web Traffic
GUI and Cli commands.

-Introduction and uses of Global Counters in Troubleshooting. 

-Different Counter analysis with and without Packet filters.

### 7. APP-ID
-Introduction to APP-ID

-Predefined APP vs Custom APP

-How Fw identify the traffic?

-Application Signatures / patterns, App-Id Cache

-App-Shift, Dependent Applications, Explicit vs Implicit application 

-App Override

### 8. URL Filtering
-Introduction to URL FIltering Profile

-URL category vs URL Filtering profile

-Actions - Allow, Alert,Block,Override,Continue
