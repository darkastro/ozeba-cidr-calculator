## Ozeba CIDR Calculator for Masscan  

### 🔍 About  
The **Ozeba CIDR Calculator for Masscan** is a simple and efficient web tool designed for **penetration testers, ethical hackers, and cybersecurity professionals**. It helps convert a starting IP address and an approximate number of IPs into a **CIDR block**, which can then be used in **Masscan**, the fastest port scanner for large network ranges.  

### ⚡ Features  
- ✅ **Convert IPs to CIDR blocks** for efficient scanning  
- ✅ **Generate a ready-to-use Masscan command** automatically  
- ✅ **Simple, dark-themed interface** for ease of use  
- ✅ **Works offline** – no internet required once downloaded  

### 🌍 How to Find IP Ranges by City or Country  
To find IP ranges in a specific **city or country**, you can use **IPinfo**:  

1. **Go to [IPinfo.io Countries](https://ipinfo.io/countries)**  
2. **Select a country**, e.g., Mexico (`MX`).  
3. **Find a city** within that country and check for IP allocations.  
4. **Note the IP range and approximate number of IPs** for that location.  
5. **Use those values in this CIDR calculator** to generate a Masscan command.  

### 🚀 How to Use the Tool  
1. **Enter a starting IP** (e.g., `101.44.16.0`).  
2. **Enter the approximate number of IPs** (e.g., `5,900,000`).  
3. Click **"Calculate CIDR"** and it will generate:  
   - A **CIDR block**  
   - A **Masscan command** formatted for easy copy-paste usage  

### 🛠 Example Output  
#### **Input:**  
- **Start IP:** `101.44.16.0`  
- **IP Count:** `5,900,000`  

#### **Output:**  
- **CIDR Block:** `101.44.16.0/12`  
- **Masscan Command:**  
  ```bash
  ./masscan -p22,80,443 101.44.16.0/12 --rate=500
  ```  

### 📥 Installation & Usage  
- **Option 1:** Download the `ozeba_cidr_calculator.html` file and open it in your browser.  
- **Option 2:** Host it for free using [GitHub Pages](https://pages.github.com/) or [Netlify](https://www.netlify.com/).  

### 🎯 Who is this for?  
- **Penetration testers & ethical hackers**  
- **Cybersecurity professionals**  
- **Anyone working with Masscan and large IP ranges**  

🔗 **Live Demo (Optional if hosted)**: [Your GitHub Pages Link]  

Let me know if you need further refinements! 🚀
