# 02 - OSI Model (Open Systems Interconnection Model)

A beginner-friendly guide to the **OSI Model**.

In this chapter, you will learn:

- What is the OSI Model?
- Why do we need the OSI Model?
- Advantages of the OSI Model
- 7 Layers of the OSI Model
- Functions of each Layer
- Real-Life Example
- Data Flow
- Devices used in each Layer
- Protocols
- Interview Questions

---

# What is the OSI Model?

**OSI** stands for **Open Systems Interconnection**.

The OSI Model is a **reference model** that explains **how data travels from one computer to another over a network**.

It divides network communication into **7 different layers**.

Each layer performs a specific task and communicates with the layer above and below it.

---

# Full Form

**OSI = Open Systems Interconnection**

---

# Why Do We Need the OSI Model?

Without the OSI Model:

- Different devices may not communicate properly.
- Troubleshooting becomes difficult.
- Network design becomes complicated.
- Different manufacturers may not follow the same communication rules.

With the OSI Model:

- ✅ Easy to understand networking.
- ✅ Easy troubleshooting.
- ✅ Standard communication method.
- ✅ Better compatibility between different devices.
- ✅ Easy development of networking technologies.

---

# Advantages of the OSI Model

- Standard networking model.
- Easy to learn.
- Easy troubleshooting.
- Modular design.
- Supports different hardware and software.
- Improves communication between vendors.

---

# Seven Layers of the OSI Model

The OSI Model has **7 layers**.

They are:

| Layer No. | Layer Name |
|------------|-------------------------|
| 7 | Application Layer |
| 6 | Presentation Layer |
| 5 | Session Layer |
| 4 | Transport Layer |
| 3 | Network Layer |
| 2 | Data Link Layer |
| 1 | Physical Layer |

---

# Easy Memory Trick

From Top to Bottom

```text
All
People
Seem
To
Need
Data
Processing
```

Application

Presentation

Session

Transport

Network

Data Link

Physical

---

From Bottom to Top

```text
Please
Do
Not
Throw
Sausage
Pizza
Away
```

Physical

Data Link

Network

Transport

Session

Presentation

Application

---

# OSI Layer Diagram

```text
+-------------------------+
| 7. Application Layer    |
+-------------------------+
| 6. Presentation Layer   |
+-------------------------+
| 5. Session Layer        |
+-------------------------+
| 4. Transport Layer      |
+-------------------------+
| 3. Network Layer        |
+-------------------------+
| 2. Data Link Layer      |
+-------------------------+
| 1. Physical Layer       |
+-------------------------+
```

---

# How Data Travels Through the OSI Model

When you send data:

```text
Sender

Application
      ↓
Presentation
      ↓
Session
      ↓
Transport
      ↓
Network
      ↓
Data Link
      ↓
Physical

----------------------------

Transmission Media

----------------------------

Physical
      ↑
Data Link
      ↑
Network
      ↑
Transport
      ↑
Session
      ↑
Presentation
      ↑
Application

Receiver
```

The sender sends data from **Layer 7 to Layer 1**.

The receiver receives data from **Layer 1 to Layer 7**.

---

# Real-Life Example

Suppose you send a WhatsApp message.

The message passes through all seven layers before reaching your friend's mobile.

```text
📱 Your Mobile

↓

Application

↓

Presentation

↓

Session

↓

Transport

↓

Network

↓

Data Link

↓

Physical

↓

🌍 Internet

↓

Friend's Mobile
```

Each layer performs its own work before passing data to the next layer.

---

# Layer 7 - Application Layer

The **Application Layer** is the top layer of the OSI Model.

It is the layer closest to the user.

Users directly interact with this layer.

This layer provides network services to applications.

---

## Functions

- Provides network services.
- Allows users to access websites.
- Sends and receives emails.
- Supports file transfer.
- Supports remote login.

---

## Examples

- Web Browser
- Gmail
- WhatsApp
- YouTube
- Google Chrome
- Firefox

---

## Common Protocols

- HTTP
- HTTPS
- FTP
- SMTP
- POP3
- IMAP
- DNS

---

## Real-Life Example

When you open **www.google.com**, the browser communicates with the Application Layer.

The Application Layer prepares your request and sends it to the next layer.

---

# Summary (Part 1)

- OSI stands for Open Systems Interconnection.
- It is a reference model.
- It contains seven layers.
- Each layer has a specific function.
- Communication starts from Layer 7 and ends at Layer 1.
- The receiver receives data from Layer 1 to Layer 7.
- The Application Layer is the closest layer to the user.

---

# Continue...

➡️ **Part 2 covers:**
- Layer 6 (Presentation)
- Layer 5 (Session)
- Layer 4 (Transport)
- Protocols
- Examples
- Devices

- # Layer 6 - Presentation Layer

The **Presentation Layer** is the **6th layer** of the OSI Model.

It is also known as the **Translation Layer** because it translates data into a format that both sender and receiver can understand.

This layer is responsible for:

- Data Translation
- Data Encryption
- Data Decryption
- Data Compression
- Data Decompression

---

## Functions

- Converts data into a standard format.
- Encrypts data before transmission.
- Decrypts received data.
- Compresses data to reduce size.
- Decompresses received data.

---

## Real-Life Example

When you use **HTTPS**, your data is encrypted before it travels over the Internet.

When the server receives it, the data is decrypted.

Example:

```text
Original Data
      │
      ▼
Encryption
      │
      ▼
Internet
      │
      ▼
Decryption
      │
      ▼
Original Data
```

---

## Common Formats

- JPEG
- PNG
- GIF
- MP3
- MP4
- ASCII
- Unicode

---

# Layer 5 - Session Layer

The **Session Layer** is the **5th layer** of the OSI Model.

It creates, manages and terminates communication sessions between two devices.

A session is simply a connection between two computers.

---

## Functions

- Establishes a session.
- Maintains the session.
- Synchronizes communication.
- Terminates the session.

---

## Real-Life Example

During a **Zoom Meeting** or **Google Meet**, the Session Layer keeps the meeting connected until it ends.

```text
Start Session
      │
Communication
      │
End Session
```

---

# Layer 4 - Transport Layer

The **Transport Layer** is the **4th layer** of the OSI Model.

It provides **end-to-end communication** between sender and receiver.

It ensures that data reaches the destination correctly.

---

## Functions

- End-to-End Communication
- Error Detection
- Error Recovery
- Flow Control
- Segmentation
- Reassembly
- Reliable Data Transfer

---

## Protocols

### TCP (Transmission Control Protocol)

Features:

- Reliable
- Connection-Oriented
- Error Checking
- Ordered Delivery

Examples:

- HTTP
- HTTPS
- FTP
- Email

---

### UDP (User Datagram Protocol)

Features:

- Fast
- Connectionless
- No Error Recovery
- Less Reliable

Examples:

- Online Games
- Live Streaming
- Voice Calls
- Video Calls

---

## TCP vs UDP

| TCP | UDP |
|------|------|
| Reliable | Fast |
| Connection-Oriented | Connectionless |
| Error Checking | No Error Recovery |
| Ordered Delivery | No Order Guarantee |

---

## Real-Life Example

Imagine sending a parcel.

TCP checks whether every parcel reaches safely.

UDP simply sends the parcel without waiting for confirmation.

---

# Data Unit (PDU)

Each OSI layer uses a different name for data.

| Layer | PDU |
|--------|------|
| Application | Data |
| Presentation | Data |
| Session | Data |
| Transport | Segment |
| Network | Packet |
| Data Link | Frame |
| Physical | Bits |

---

# Devices Used

| Layer | Device |
|--------|---------|
| Application | Gateway |
| Presentation | Gateway |
| Session | Gateway |
| Transport | Gateway |
| Network | Router |
| Data Link | Switch, Bridge |
| Physical | Hub, Repeater, Cable |

---

# Summary (Part 2)

- Presentation Layer translates and encrypts data.
- Session Layer manages communication sessions.
- Transport Layer provides reliable communication.
- TCP is reliable.
- UDP is faster.
- Each layer has its own PDU.
- Different networking devices work at different layers.

---

# Continue...

➡️ **Part 3 covers:**
- Network Layer
- Data Link Layer
- Physical Layer
- Encapsulation & Decapsulation
- Interview Questions
- Quick Revision
- Important Full Forms

- # Layer 3 - Network Layer

The **Network Layer** is the **3rd layer** of the OSI Model.

It is responsible for delivering data from the source network to the destination network.

The main job of this layer is to find the **best path (Route)** for data.

---

## Functions

- Logical Addressing (IP Address)
- Routing
- Path Selection
- Packet Forwarding
- Internetwork Communication

---

## Protocols

- IPv4
- IPv6
- ICMP
- IPsec

---

## Device

- 📡 Router

---

## PDU

**Packet**

---

## Real-Life Example

When you send data from Satna to Delhi, the Router decides the best path for your data.

```text
💻 Laptop
     │
     ▼
📡 Router
     │
     ▼
🌍 Internet
     │
     ▼
🖥️ Destination
```

---

# Layer 2 - Data Link Layer

The **Data Link Layer** is the **2nd layer** of the OSI Model.

It provides communication between two devices on the same network.

It uses the **MAC Address** for communication.

---

## Functions

- Physical Addressing (MAC Address)
- Framing
- Error Detection
- Flow Control
- Media Access Control

---

## Device

- 🔀 Switch
- Bridge

---

## PDU

**Frame**

---

## Real-Life Example

A Switch sends data to the correct computer inside a Local Area Network (LAN) using the MAC Address.

```text
      🔀 Switch
     ┌────┼────┐
     │    │    │
   💻   🖥️   🖨️
```

---

# Layer 1 - Physical Layer

The **Physical Layer** is the **1st and lowest layer** of the OSI Model.

It is responsible for transmitting raw bits through cables or wireless signals.

---

## Functions

- Data Transmission
- Electrical Signals
- Optical Signals
- Wireless Signals
- Bit Transmission

---

## Devices

- Hub
- Repeater
- Ethernet Cable
- Fiber Optic Cable

---

## PDU

**Bits**

Example:

```text
01010110
10101011
00110101
```

---

# Encapsulation

**Encapsulation** is the process of adding information (Headers) to data while it moves from **Layer 7 to Layer 1**.

```text
Application
      ↓
Presentation
      ↓
Session
      ↓
Transport
      ↓
Network
      ↓
Data Link
      ↓
Physical
```

Each layer adds its own header before sending the data.

---

# Decapsulation

**Decapsulation** is the process of removing headers while data moves from **Layer 1 to Layer 7** at the receiver.

```text
Physical
      ↑
Data Link
      ↑
Network
      ↑
Transport
      ↑
Session
      ↑
Presentation
      ↑
Application
```

Each layer removes its own header and passes the data to the next layer.

---

# Complete Data Flow

```text
Sender

Application
      │
Presentation
      │
Session
      │
Transport
      │
Network
      │
Data Link
      │
Physical
      │
──────── Transmission Media ────────
      │
Physical
      │
Data Link
      │
Network
      │
Transport
      │
Session
      │
Presentation
      │
Application

Receiver
```

---

# OSI Layers Summary

| Layer | Name | Main Function | Device | PDU |
|------|----------------|------------------------|--------------|---------|
| 7 | Application | User Services | Gateway | Data |
| 6 | Presentation | Translation, Encryption | Gateway | Data |
| 5 | Session | Session Management | Gateway | Data |
| 4 | Transport | Reliable Communication | Gateway | Segment |
| 3 | Network | Routing, IP Address | Router | Packet |
| 2 | Data Link | MAC Address, Framing | Switch, Bridge | Frame |
| 1 | Physical | Signal Transmission | Hub, Repeater | Bits |

---

# Important Full Forms

| Short Form | Full Form |
|------------|-------------------------------------------|
| OSI | Open Systems Interconnection |
| TCP | Transmission Control Protocol |
| UDP | User Datagram Protocol |
| IP | Internet Protocol |
| ICMP | Internet Control Message Protocol |
| MAC | Media Access Control |
| PDU | Protocol Data Unit |

---

# Real-Life Example

Suppose you send a photo on WhatsApp.

- Application Layer → WhatsApp creates the request.
- Presentation Layer → Encrypts the photo.
- Session Layer → Maintains the connection.
- Transport Layer → Divides the data into segments.
- Network Layer → Finds the best route using the IP Address.
- Data Link Layer → Uses the MAC Address inside the local network.
- Physical Layer → Sends the bits through Wi-Fi or Mobile Network.

At the receiver side, the same process happens in reverse order.

---

# Interview Questions

### 1. What is the OSI Model?

### 2. What is the full form of OSI?

### 3. Why do we use the OSI Model?

### 4. Name all seven layers of the OSI Model.

### 5. Which layer is responsible for Routing?

### 6. Which layer uses the IP Address?

### 7. Which layer uses the MAC Address?

### 8. Which layer is responsible for Encryption?

### 9. Which layer is responsible for Session Management?

### 10. Difference between TCP and UDP?

### 11. What is Encapsulation?

### 12. What is Decapsulation?

### 13. What is the PDU of each OSI layer?

### 14. Which device works at the Network Layer?

### 15. Which device works at the Data Link Layer?

---

# Quick Revision

✅ OSI = Open Systems Interconnection

✅ Total Layers = 7

✅ Layer 7 = Application

✅ Layer 6 = Presentation

✅ Layer 5 = Session

✅ Layer 4 = Transport

✅ Layer 3 = Network

✅ Layer 2 = Data Link

✅ Layer 1 = Physical

✅ Router works at Layer 3

✅ Switch works at Layer 2

✅ Hub works at Layer 1

✅ Network Layer uses IP Address

✅ Data Link Layer uses MAC Address

✅ Transport Layer uses TCP & UDP

✅ Physical Layer sends Bits

✅ Data Link Layer sends Frames

✅ Network Layer sends Packets

✅ Transport Layer sends Segments

✅ Encapsulation = Sender Side

✅ Decapsulation = Receiver Side

---

# What's Next?

➡️ **03 - TCP/IP Model**
