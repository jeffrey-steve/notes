**Function:**  
- Distributes incoming traffic across multiple servers

**Key Concepts:**  
- Layer 4 (Transport) or Layer 7 (Application)  
- Round-robin, Least connections, IP hash, etc.  
- Health checks on backend servers

**Types:**  
- Hardware (F5, Citrix)  
- Software (HAProxy, NGINX)

**Benefits:**  
- Prevents overload  
- Improves availability and fault tolerance

**Security Risks:**  
- Misrouting of sessions  
- Insecure configuration of session persistence

---