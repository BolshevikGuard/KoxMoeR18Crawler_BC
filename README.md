# KoxMoeR18Crawler_BC  

A crawler to get all R18/R15 manga titles and ratings from [kox.moe](https://kox.moe).  
This README is basically generated by ChatGPT  

## ✨ Features  
- 📜 **Scrape all manga URLs** from kox.moe _(Country: Japan / Language: Chinese)_  
- 📊 **Extract title, type(R18 / R15), rating, and URL**  
- 📁 **Export results in TXT, JSON, and XLSX formats**  

## 📦 Installation  

### 1. Clone the repository  
```bash
git clone https://github.com/BolshevikGuard/KoxMoeR18Crawle_BC.git
cd KoxMoeR18Crawler_BC
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

## 🚀 Usage

### **1. Scrape manga URLs**
```bash
python listpage.py
```
Collect all manga URLs from kox.moe and save them to a txt.

### **2. Extract manga details**
```bash
python titleNrating.py
```
Analyze each URL, extract and save title, type, rating, and url to a txt.

### **3. Post-process results**
```bash
python after.py
```
Format the extracted data into TXT, JSON, and XLSX files for easy access.

## 📂 Output Files
* **url_list_yh2.txt** - Raw URLs of manga (2025.03.14)
* **output.txt** - extracted data in form of "type title rating url"
* **output.json** - json version of output.txt
* **output.xlsx** - xlsx version of output.txt

## 📜 License
This project is licensed under the **MIT** License.
