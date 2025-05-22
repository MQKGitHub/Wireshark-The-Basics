### 🛡️ Wireshark: The Basics

**Room:** [Wireshark: The Basics — TryHackMe](https://tryhackme.com/room/wiresharkthebasics)  
**Status:** ✅ Completed  
**Date:** *22 May 2025*

### 🎯 Objective  
To learn the basics of Wireshark and understand how to load, view, and analyse network traffic using PCAP files. The goal was to explore how to dissect packets, apply filters, and follow streams using Wireshark’s GUI.

---

### 🗝️ Key Concepts  
- **Wireshark** — A network traffic analyser tool used for inspecting live traffic and PCAP files.  
- **Packet Dissection** — The process of breaking down packets into their protocol layers using the OSI model.  
- **Display Filters** — Queries used to narrow down and view only specific types of packets in a PCAP.  
- **Conversation Filters** — Filters that focus on all related packets within a specific communication session.  
- **Packet Comments and Marking** — Features that let analysts note or highlight specific packets for further review.  
- **Follow Stream** — Reconstructs application-level communication (like HTTP or TCP) from raw packet data.  
- **Expert Info** — Highlights unusual packet behaviour with severity levels to assist in spotting anomalies.  
- **Packet Colouring** — Uses colours to help visually identify different types of traffic or issues.

---

### 🛠️ Tools Used  
- **Wireshark** — Used for packet capture analysis, protocol inspection, and applying filters to locate specific events.

---

### ⚠️ Challenges Faced  
- The large amount of information in each packet pane was a bit overwhelming at first.  
- I had to go slowly to fully understand the link between OSI layers and the data shown.  
- Reading hex and ASCII bytes took some getting used to.

*Solution:* I focused on the GUI layout, used sample captures, and explored each pane step-by-step alongside the tutorial.

---

### 🧠 What I Learned  
- How to load and analyse PCAP files using Wireshark.  
- The purpose of each pane (packet list, details, bytes) and how they connect.  
- How to apply display and conversation filters effectively.  
- How to follow streams to recreate application-level communication.  
- How to use expert info, packet marking, and comments to aid analysis.

---

### 🌐 Real-World Application:  
> Tools like Wireshark are vital for network analysts and SOC teams to inspect suspicious traffic, find protocol misconfigurations, or track down data exfiltration. Following TCP streams or using expert info can reveal hidden attacks or data leaks.

---

### 💭 Reflections:  
- It was fun exploring the GUI and seeing real packet data.  
- I'd like to explore more advanced filters and scripting in Wireshark later.  
