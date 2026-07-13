# 01 - Network Basics 🌐

A beginner-friendly introduction to **Computer Networking**.

In this chapter, you will learn:

- What is a Network?
- Why do we need Networks?
- Types of Networks
- How Communication Happens
- What is Data?
- Binary Concept
- Important Networking Terms
- Real-Life Examples
- Network Components
- Interview Questions

---

# What is a Network?

A **Network** is a collection of **two or more devices** connected together to communicate, exchange data, and share resources.

In simple words,

> **A Network allows different devices to communicate with each other.**

Examples of communication include:

- Sharing files
- Sending messages
- Accessing websites
- Playing online games
- Video calling
- Printing documents

---

## Examples of Network Devices

Some common devices connected in a network are:

- 💻 Laptop
- 📱 Mobile Phone
- 🖥️ Desktop Computer
- 🖨️ Printer
- 📺 Smart TV
- 🗄️ Server
- 📡 Router
- 🔀 Switch
- 📶 Wi-Fi Access Point

---

## Example

```text
💻 Laptop  <──────────────>  📱 Mobile

        Data Communication
```

Both devices are connected through a network and can exchange information.

---

# Why Do We Need a Network?

Networks make communication and resource sharing possible.

Without a network:

- ❌ Internet cannot be accessed.
- ❌ Files cannot be shared.
- ❌ Online gaming is impossible.
- ❌ Email cannot be sent.
- ❌ Websites cannot be opened.
- ❌ Network printers cannot be used.

With a network:

- ✅ Share files
- ✅ Access the Internet
- ✅ Print documents
- ✅ Communicate with others
- ✅ Use cloud services
- ✅ Watch online videos
- ✅ Attend online meetings

---

# Types of Networks

Networks are classified according to the geographical area they cover.

The five most common types are:

1. PAN (Personal Area Network)
2. LAN (Local Area Network)
3. CAN (Campus Area Network)
4. MAN (Metropolitan Area Network)
5. WAN (Wide Area Network)

---

# 1. PAN (Personal Area Network)

## Full Form

**PAN = Personal Area Network**

A PAN is the smallest type of network.

It connects devices within a short distance (usually up to 10 meters).

### Examples

- 📱 Mobile ↔ 🎧 Bluetooth Earbuds
- 📱 Mobile ↔ ⌚ Smartwatch
- 💻 Laptop ↔ 🖱️ Wireless Mouse
- 💻 Laptop ↔ ⌨️ Wireless Keyboard

### Diagram

```text
        📱 Mobile
          │
     Bluetooth
          │
     ┌────┴────┐
     │         │
 🎧 Earbuds  ⌚ Smartwatch
```

### Features

- Covers a very small area.
- Used by one person.
- Uses Bluetooth, USB or Wi-Fi.
- Low power consumption.

---

# 2. LAN (Local Area Network)

## Full Form

**LAN = Local Area Network**

A LAN connects devices inside a small area like:

- Home
- School
- Office
- Computer Lab

### Diagram

```text
                📡 Router
                    │
        ┌───────────┼───────────┐
        │           │           │
     💻 Laptop   🖥️ Desktop   🖨️ Printer
```

### Features

- Covers a small area.
- High-speed communication.
- Low installation cost.
- Easy to maintain.
- Usually managed by one organization.

### Advantages

- Fast data transfer
- Resource sharing
- Internet sharing
- Easy management

### Real-Life Examples

- Home Wi-Fi
- Office Network
- School Computer Lab
- College Classroom

---

# 3. CAN (Campus Area Network)

## Full Form

**CAN = Campus Area Network**

A CAN connects multiple LANs inside one campus or organization.

Examples:

- 🏫 University Campus
- 🏢 Company Campus
- 🏥 Hospital Campus

### Diagram

```text
        🏢 Building A (LAN)
               │
               │
        Campus Network
               │
               │
        🏢 Building B (LAN)
```

### Features

- Larger than LAN.
- Smaller than MAN.
- High-speed communication.
- Used by universities and large organizations.

---

# 4. MAN (Metropolitan Area Network)

## Full Form

**MAN = Metropolitan Area Network**

A MAN connects multiple LANs across a city.

Examples:

- City Government Network
- Cable TV Network
- ISP City Network

### Diagram

```text
      🏢 Office A
           │
           │
      City Network
           │
           │
      🏢 Office B
```

### Features

- Covers an entire city.
- Faster than WAN.
- Connects many LANs.

---

# 5. WAN (Wide Area Network)

## Full Form

**WAN = Wide Area Network**

A WAN connects networks over very large geographical areas.

It can connect:

- Cities
- States
- Countries
- Continents

The **Internet** is the largest WAN in the world.

### Diagram

```text
🏢 Delhi Office
       │
       │
   🌍 Internet
       │
       │
🏢 Mumbai Office
```

### Features

- Covers a very large area.
- Connects multiple LANs and MANs.
- Uses fiber optics, satellites and leased lines.
- Higher installation cost.
- Used by banks, MNCs and government organizations.

---

# Comparison of Network Types

| Network | Full Form | Coverage Area | Example |
|----------|-----------|---------------|---------|
| PAN | Personal Area Network | Few meters | Bluetooth |
| LAN | Local Area Network | Home / Office | Wi-Fi |
| CAN | Campus Area Network | Campus | University |
| MAN | Metropolitan Area Network | City | City ISP |
| WAN | Wide Area Network | Country / World | Internet |

---

# Quick Revision (Part 1)

✅ PAN → Personal devices

✅ LAN → Home, School, Office

✅ CAN → Campus

✅ MAN → City

✅ WAN → Country / World

✅ Internet = Largest WAN

---

# How Does Network Communication Happen?

Whenever we access a website, send a message, watch a video, or download a file, data travels through a network.

For example, when you open **google.com**, your request passes through different networking devices before reaching Google's server.

---

## Communication Flow

```text
💻 Your Laptop
      │
      ▼
📡 Router
      │
      ▼
🌍 Internet
      │
      ▼
🖥️ Google Server
```

---

## Step-by-Step Process

### Step 1

You enter **google.com** in your browser.

### Step 2

Your laptop creates a request.

### Step 3

The request is sent to the Router.

### Step 4

The Router forwards the request to the Internet.

### Step 5

The Internet finds Google's Server.

### Step 6

Google's Server processes your request.

### Step 7

The Server sends the response back through the same path.

### Step 8

Finally, the webpage is displayed on your screen.

---

# What is Data?

**Data** is any information that is transmitted or received over a network.

Everything that travels through a network is considered data.

## Examples of Data

- 📝 Text
- 🖼️ Images
- 🎥 Videos
- 🎵 Audio
- 📄 PDF Files
- 📧 Emails
- 💬 WhatsApp Messages
- 📂 Documents

---

## Real-Life Example

When you send a photo on WhatsApp,

- The photo is converted into data.
- The data travels through the Internet.
- The receiver downloads the same data.
- The photo appears on the receiver's mobile.

---

# What is Binary?

Computers understand only one language called **Binary Language**.

Binary has only **two digits**.

```text
0
1
```

Every operation inside a computer is performed using these two numbers.

---

## Example

```text
A = 01000001
```

---

## Everything is Converted into Binary

The following are stored and transmitted in Binary format:

- Images
- Videos
- Songs
- Documents
- Websites
- Games
- Applications

Even the webpage you are reading is internally stored as Binary.

---

# Important Networking Terms

## 1. Device

A **Device** is any hardware connected to a network.

### Examples

- 💻 Laptop
- 📱 Mobile
- 🖥️ Desktop
- 🖨️ Printer
- 🗄️ Server
- 📡 Router

---

## 2. Communication

Communication means exchanging data between two or more devices.

### Example

```text
📱 Mobile  <──────────>  💻 Laptop
```

Both devices exchange information through a network.

---

## 3. Internet

The **Internet** is the world's largest network.

It connects millions of computers and devices across the globe.

Using the Internet we can:

- Browse Websites
- Watch YouTube
- Use WhatsApp
- Send Emails
- Play Online Games
- Attend Online Meetings
- Access Cloud Services

---

## 4. Server

A **Server** is a powerful computer that provides services or data to other computers.

Examples:

- Google Server
- YouTube Server
- Amazon Server
- Netflix Server

Whenever you open a website, your request goes to a server.

---

## 5. Client

A **Client** is the device that requests data from a server.

Examples:

- Laptop
- Mobile
- Desktop

Example:

```text
Client (Laptop)
        │
        ▼
Server (Google)
```

---

# Real-Life Network Example

Suppose you send a WhatsApp message.

The communication happens like this:

```text
👤 You
   │
   ▼
📱 Your Mobile
   │
   ▼
📡 Router / Mobile Tower
   │
   ▼
🌍 Internet
   │
   ▼
🗄️ WhatsApp Server
   │
   ▼
📱 Friend's Mobile
```

Your message first reaches WhatsApp's server and then it is delivered to your friend's mobile.

This complete process is called **Network Communication**.

---

# Network Components

Every computer network consists of different components.

---

## 1. End Devices

These devices send or receive data.

Examples:

- 💻 Laptop
- 📱 Mobile
- 🖥️ Desktop
- 🗄️ Server

---

## 2. Networking Devices

These devices help data travel across the network.

Examples:

- 📡 Router
- 🔀 Switch
- 📶 Access Point
- 🌐 Modem

---

## 3. Transmission Media

Transmission Media is the path through which data travels.

Examples:

- Ethernet Cable
- Fiber Optic Cable
- Wi-Fi
- Radio Signals

---

# Summary

- A Network connects two or more devices.
- Networks help in communication and resource sharing.
- Data can be text, images, videos, audio or files.
- Computers understand only Binary (0 and 1).
- PAN is used for personal devices.
- LAN is used inside homes, schools and offices.
- CAN connects multiple LANs inside a campus.
- MAN covers an entire city.
- WAN connects countries and continents.
- The Internet is the largest WAN.
- Routers and Switches help devices communicate.
- Servers provide services to clients.

---

# Important Full Forms

| Short Form | Full Form |
|------------|-----------|
| PAN | Personal Area Network |
| LAN | Local Area Network |
| CAN | Campus Area Network |
| MAN | Metropolitan Area Network |
| WAN | Wide Area Network |
| ISP | Internet Service Provider |
| IP | Internet Protocol |
| TCP | Transmission Control Protocol |
| HTTP | HyperText Transfer Protocol |
| HTTPS | HyperText Transfer Protocol Secure |

---

# Interview Questions

## 1. What is a Network?

A Network is a collection of two or more connected devices that communicate and share data.

---

## 2. Why do we need a Network?

To communicate, share files, access the Internet, use printers, and share resources.

---

## 3. What are the different types of Networks?

- PAN
- LAN
- CAN
- MAN
- WAN

---

## 4. What is the difference between LAN and WAN?

LAN covers a small area like a home or office, whereas WAN covers large geographical areas such as countries and the entire world.

---

## 5. What is Data?

Data is any information transmitted over a network.

---

## 6. What is Binary?

Binary is the language understood by computers and consists of only two digits: **0** and **1**.

---

## 7. What is the Internet?

The Internet is the world's largest WAN that connects millions of devices globally.

---

## 8. What is a Server?

A Server is a computer that provides data or services to other computers over a network.

---

## 9. What is a Client?

A Client is a device that requests services or data from a server.

---

# Quick Revision

✅ Network = Two or more connected devices

✅ PAN = Personal Area Network

✅ LAN = Local Area Network

✅ CAN = Campus Area Network

✅ MAN = Metropolitan Area Network

✅ WAN = Wide Area Network

✅ Internet = World's Largest WAN

✅ Data = Information transmitted through a network

✅ Binary = 0 and 1

✅ Client requests data

✅ Server provides data

✅ Router connects different networks

✅ Switch connects devices inside a LAN

---

# What's Next?

➡️ **02 - OSI Model (Open Systems Interconnection Model)**
