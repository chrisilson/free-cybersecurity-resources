# Local Environment Setup Guide

## Introduction

Breaking into the tech industry—and cybersecurity in particular—can feel overwhelming, especially if you don’t already have a job, a mentor, or a clear starting point. I’ve been fortunate to gain experience through hands-on work, but not everyone has access to those kinds of opportunities. This guide exists to level the playing field.

The goal here is simple: provide a practical, structured way to build a local virtual lab environment using free trials of enterprise-grade software, open-source tools, and automation. Instead of endless searching through scattered tutorials or drowning in conflicting advice, this guide stitches together a working, expandable environment that builds real skills from day one.

You won’t just install software—you’ll simulate realistic enterprise IT and cybersecurity scenarios. Whether you're exploring Active Directory, writing scripts, or testing basic red team techniques, the experience will be hands-on, repeatable, and designed to grow with you.

Idea crafted by Chris Ilson and refined using ChatGPT.

---

## Why Use Trial Software?

Enterprise-class operating systems are expensive—but the companies who build them want professionals to try them. Microsoft, for example, offers time-limited evaluation versions of both **Windows 11** and **Windows Server**. These trial versions are perfect for:

- Practicing real-world enterprise scenarios
- Understanding Active Directory, DNS, DHCP, GPOs
- Creating a client-server network in a lab

Combined with tools like **Kali Linux**, you can build an entire virtual network from scratch using just your own hardware.

---

## When the Trial Expires

One of the challenges with using evaluation software is that it will expire—usually within 90 to 180 days. But that’s not a limitation; it's an opportunity.

In a real IT job, environments break. Systems need to be rebuilt. New hardware arrives. Version upgrades roll out. This guide teaches you how to **automate the process** so that rebuilding isn't a burden—it's a routine.

---

## Key Operating Systems in This Lab

| OS / Platform | Purpose |
|---------------|---------|
| **Windows 11 Evaluation** | Enterprise client for testing domain joins, GPOs |
| **Windows Server Evaluation** | Domain Controller, DNS, DHCP, file shares |
| **Kali Linux** | Security testing, reconnaissance, scripting |
| [**Metasploit Vulnerable Targets**](https://docs.rapid7.com/metasploit/setting-up-a-vulnerable-target/) | Simulated vulnerable Linux systems for offensive testing |
| [**Security Onion 2.4**](https://docs.securityonion.net/en/2.4/first-time-users.html) | Network detection, intrusion analysis, and SIEM practice |

All of these are available for free through legitimate sources, such as the [Microsoft Evaluation Center](https://www.microsoft.com/en-us/evalcenter) and [Kali.org](https://www.kali.org/get-kali/).

---

## Automating Setup with Scripts

To support repeatable learning, this guide includes sample setup scripts:

- **Windows setup** via PowerShell: Auto-configure hostname, network, install tools
- **Kali setup** via Bash: Preload tools, set up internal NAT networking
- **Networking automation**: VirtualBox XML for creating NAT/internal networks
- **Configuration backup**: Exporting settings and using templates

You’ll learn how to rebuild your environment in minutes—not hours—and you’ll understand every step of how it works.

---

## Learning to Rebuild Is the Skill

This guide isn’t just about *setting up once* and moving on. It’s about learning how to rebuild environments with confidence.

When your trial ends or something breaks, you won’t panic—you’ll deploy a clean lab using your saved scripts, apply your configs, and get back to learning. That’s the kind of resilience and confidence that employers notice.

---

## Next Step

Guide is a work in progress. Additional content to follow.
