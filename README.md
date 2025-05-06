# 💻 Network Project – Grupo Bonice (Apache Demo)

## 🚀 Overview
This HTML file was developed as a **test of an internal Apache web server on Ubuntu**. It’s a single‐page demo that combines a Matrix-style canvas effect, an animated terminal simulation, and a grid of network nodes with fictitious IP addresses :contentReference[oaicite:0]{index=0}:contentReference[oaicite:1]{index=1}.

## ✨ Features
- 🎇 Matrix effect rendered via the Canvas API  
- 🖥️ Animated terminal simulation with sequential command lines  
- 🔲 Grid of “node” cards displaying a name and IP address  
- 🔗 **Access Document** button linking to an external resource  
- 💀 Dark theme with monospace typography  
- ⚡ Glitch title effect and CSS/JS animations  

## 🛠️ Technologies Used
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)  
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)  
![Apache HTTP Server](https://img.shields.io/badge/Apache_HTTP_Server-D22128?style=for-the-badge&logo=apache&logoColor=white)  
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)

## 📂 Structure
```
index.html  – Single‐page demo with embedded styles and scripts&#x20;

````

## 🚀 Deployment on Apache (Ubuntu)
1. Update package index and install Apache:  
   ```bash
   sudo apt update
   sudo apt install apache2
````

2. Enable and start the Apache service:
   ```bash
   sudo systemctl enable apache2
   sudo systemctl start apache2
   ```

3. Copy `index.html` into the web root:
   ```bash
   sudo cp index.html /var/www/html/
   ```

4. Restart Apache:
   ```bash
   sudo systemctl restart apache2
   ```

5. Open in your browser:
   ```
   http://<SERVER_IP>/index.html
   ```

## ⚙️ Customization

* **Styles**: edit the `<style>` block inside `<head>`.
* **Nodes**: update each `<div class="node-container">` to change names or IPs.
* **Terminal**: modify the `terminalLines` array in the `<script>` to adjust displayed commands.

## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
