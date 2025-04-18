# ETHICAL-HACKING
**Introduction**
This repository contains beginner-friendly yet powerful tools built in Python for information gathering and network scanning — essential stages in cybersecurity and ethical hacking. These tools automate the process of collecting critical data about a target domain or IP address, including server details, geolocation info, and open ports.

Whether you're a cybersecurity enthusiast, student, or aspiring ethical hacker, these scripts will help you get hands-on experience with real-world reconnaissance techniques using libraries like requests, socket, and nmap.

1. Infromation Gthering Tool
   A simple Python script that collects web and network metadata of a given domain. It extracts:
   i. HTTP Response Headers
   ii. IP address of the target domain
   iii. Geolocation info (City, Region, Country, Coordinates) using the ipinfo.io API
   This tool helps users perform lightweight reconnaissance on a web target by combining DNS resolution, HTTP inspection, and external geolocation 
   data.

2.Custom TCP Port Scanner using Nmap
  This script leverages the Python nmap module to scan specified TCP ports on a target host. It reports the state of each port (e.g., open, 
  closed,filtered) to aid in identifying active services and potential vulnerabilities.
  i. Built a basic port scanner using Python and the nmap module
  ii. Takes a host IP or domain and a list of ports as input
  iii. Scans each port and checks if it is open, closed, or filtered
  iv. Displays the scan results in a readable format
  v. Useful for beginners to understand how port scanning works
   

