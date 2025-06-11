# 🎓 Learning Azure the First Time – A Student’s Journey Using the Azure Portal ☁️

Hi there! 👋 I’m learning how to use **Microsoft Azure**, and I thought I’d document my process here — not just what I clicked, but what I was *thinking* along the way.

This is a beginner’s reflection on learning the basics of cloud computing using the **Azure Portal** — no scripts, no command line, just me, a browser, and lots of curiosity.

---

## 🧠 What I Knew (and Didn’t Know) at the Start

When I first logged in to the [Azure Portal](https://portal.azure.com), I was overwhelmed. There were soooo many options!

I had heard about:
- 💻 **Virtual Machines** (VMs): kind of like renting a computer in the cloud
- 🗄️ **Storage Accounts**: a place to keep files, backups, and data
- 📁 **File Shares**: like a shared drive you can mount to a VM

But I wasn’t sure how they all fit together, or *why* I needed them.

---

## 🗂️ Step 1: Making a Resource Group (a place to hold everything)

I learned that a **Resource Group** is like a folder. Every VM, storage account, and network thing lives inside it. So I:

1. Went to the Portal
2. Searched for **“Resource groups”**
3. Clicked **+ Create**
4. Gave it a name like `MyLearningGroup` and picked a region

🧠 *What I learned:* You can delete the whole group later, which is great when you’re just testing things out!

---

## 💻 Step 2: Creating a Virtual Machine (my first cloud PC!)

Next up: I wanted to make a VM. I thought it would be hard — turns out, it’s mostly clicking!

1. I searched for **“Virtual machines”**
2. Clicked **+ Create** > **Azure virtual machine**
3. Chose:
   - Ubuntu for my image (I like Linux, but Windows would work too)
   - A small size (to avoid charges!)
   - My `MyLearningGroup` as the resource group
   - SSH login

I clicked through the tabs and hit **“Create”** — then waited a few minutes.

🚀 Suddenly, I had a **cloud-based computer** running!

-------
I also reseached non-retalional databases vs relational databases.
## 📚 Bonus Learning: Relational vs. Non-Relational Data

While exploring Azure, I came across **Azure SQL Database** and **Cosmos DB**. That led me to learn about the two major types of databases used in the cloud:

### 🧮 Relational Databases (SQL)

- Examples: **Azure SQL Database**, **MySQL**, **PostgreSQL**
- Stores data in **tables with rows and columns**
- Follows a **schema** — each table has a defined structure
- Great for **structured data** that doesn't change shape often
- Ideal for apps that need **consistency** and relationships between data (e.g., finance apps, inventory systems)

📌 *Think of it like a super-organized spreadsheet with rules.*

---

### 📦 Non-Relational Databases (NoSQL)

- Example: **Azure Cosmos DB**
- Stores data in **flexible formats** like JSON documents
- No strict schema — each record (or document) can look different
- Best for **unstructured or semi-structured data** (like logs, user profiles, or IoT data)
- Designed for **speed, scalability**, and **global distribution**

📌 *Think of it like a digital filing cabinet where every folder can have different content inside.*

---

### 🔍 Quick Comparison

| Feature               | Relational (SQL)               | Non-Relational (NoSQL)           |
|-----------------------|--------------------------------|----------------------------------|
| Structure             | Fixed schema (tables)          | Flexible schema (documents, etc.)|
| Data Type             | Structured                     | Semi-structured / unstructured  |
| Use Cases             | Finance, HR, Inventory         | IoT, User data, App telemetry   |
| Azure Service         | Azure SQL Database             | Azure Cosmos DB                 |
| Query Language        | SQL                            | Varies (SQL-like, MongoDB, etc.)|
| Relationships         | Strong (foreign keys, joins)   | Weak or none                    |

---

> 💡 **Student takeaway:** Use **SQL** when your data is structured and needs clear relationships.  
> Use **NoSQL** when you want speed, flexibility, and less rigid data storage.

---
I also have done a mock exam regarding Azure.
![Screenshot 2025-05-30 144726](https://github.com/user-attachments/assets/79fbfaea-e8aa-4c0a-bed0-6f6e26b8cc39)

----
