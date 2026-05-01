# Assignment-4-Computer-Networks

**Submitted By:** Mohit Goel  
**Roll Number:** 2301730109  
**Program:** BTech CSE (AI/ML), Section B  
**Course:** Computer Networks Lab  
**Course Code:** ENCS304  

**GitHub Link:** [Assignment Link](https://github.com/MohitGoel109/ComputerNetwork_Assignment_4)

---

## 🔹 Overview
This assignment demonstrates the configuration of a **DNS Server** using Cisco Packet Tracer and explains how domain names are translated into IP addresses within a local network.

---

## 🔹 Network Design

**Devices Used:**
- 1 DNS Server  
- 2–3 PCs  
- 1 Switch  

**Topology:**  
PCs → Switch → Server  

---

## 🔹 IP Configuration

**Server:**
- IP Address: 192.168.1.2  
- Subnet Mask: 255.255.255.0  

**PCs:**
- IP Address: 192.168.1.3 / 192.168.1.4 / 192.168.1.5  
- Subnet Mask: 255.255.255.0  
- DNS Server: 192.168.1.2  

---

## 🔹 DNS Configuration

The following DNS records were configured:

- www.example.com → 192.168.1.2  
- www.google.com → 192.168.1.2  

---

## 🔹 Testing

### Ping:
```bash
ping www.example.com
ping www.google.com
```

### NSLOOKUP:
```bash
nslookup www.example.com
nslookup www.google.com
```

### Traceroute:
```bash
tracert www.example.com
```

---

## 🔹 Analysis

### Query Time
- Approximately 1–2 ms due to same network environment  

### Response Accuracy
- All domain names were resolved successfully without errors  

### Name Resolution Process
1. User enters a domain name in the system  
2. The request is sent to the configured DNS server  
3. The DNS server searches its records  
4. The corresponding IP address is returned  
5. The system establishes communication using that IP  

---

## 🔹 Key Observations

- DNS converts human-readable domain names into machine-readable IP addresses  
- Proper IP and DNS configuration is essential for successful communication  
- DNS resolution works independently of general network connectivity  
- Cisco Packet Tracer simulates a local environment and does not access the real internet  

---

## 🔹 Conclusion

The DNS server was successfully configured and tested within the simulated environment.  
All domain names were resolved accurately with minimal delay, demonstrating efficient DNS functionality in a local network.

---

## 🔹 Tools Used

- Cisco Packet Tracer  
- Command Prompt  

---
