
# ESP32WifiWebpage

A simple web-based WiFi configuration portal for ESP32. It allows you to scan and connect to WiFi networks via a mobile-friendly browser interface.

# Features

AP Mode: Creates a setup hotspot (ESP32_Setup).

WiFi Scan: Lists nearby networks with signal strength (RSSI).

Web UI: Modern Dark Mode interface built with HTML/CSS/JS.

JSON API: Uses /scan and /connect endpoints for data handling.

# How to Use

Upload the code to your ESP32.

Connect to WiFi: ESP32_Setup (Password: 12345678).

Open browser to: 192.168.4.1.

Select your network, enter the password, and connect.

# API Endpoints

GET / : Serves the configuration page.

GET /scan : Returns a list of available WiFi networks in JSON.

POST /connect : Receives ssid and pass to establish a connection.

# Requirements

ESP32 Board

Arduino IDE with ESP32 core installed.
