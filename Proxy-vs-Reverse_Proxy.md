src = https://www.youtube.com/watch?v=4NB0NDtOwIQ&t=40s

---

# Forward proxy

![image](https://github.com/user-attachments/assets/9a3dc1e3-522f-4bf6-b363-359979639379)

- A forward proxy is a server that sits between a group of client machines and the internet.
- when those clients make requests to websites (or web apps), the forward proxy acts as a middleman
- it intercepts those requests and talk to the web servers on behalf of those client machines
- a forward proxy protects the client's online identity:
  - the IP address of the client is hidden from the web servers
  - only the IP address of the proxy is visible to the web servers
- a forward proxy can be used to block access to certain content

---

# Reverse proxy

![image](https://github.com/user-attachments/assets/4062c129-ee5c-451e-b27d-10322b559901)

- a reverse proxy sits between the internet and the web servers
- it intercepts the requests from the clients and talk to the web servers on behalf of the clients
- it can be used to protect a website (or web app):
  - the web servers IP addresses are hidden behind the reverse proxy and are not revealed to the clients
  - this makes it much harder to target a DDoS attack against a website
- a reverse proxy is used for **load balancing**:
  - a popular website handling millions of users every day is unlikely to be able to handle the traffic with a single server
  - a reverse proxy distributes incoming requests to a large pool of web servers, effectively preventing any one of them from becoming overloaded

---
EOF
