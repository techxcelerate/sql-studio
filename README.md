# SQL Studio

<div align="center">
   <img src="images/logo.png" alt="SQL Studio Logo" width="100" height="100" />
   <h3>SQL Studio</h3>
   <p>A high-performance, local-first database client and interactive schema visualizer.</p>
   <p>
      <a href="https://github.com/techxcelerate/rust-sql-editor/releases/">
         <img src="https://img.shields.io/badge/Download-Latest_Release-blue?style=for-the-badge&logo=github" alt="Download Latest Release" />
      </a>
   </p>
</div>

---

**SQL Studio** is a powerful, cross-platform database management application developed by **[nitiksh](https://nitiksh.ntxm.org)** at **[ntxm](https://ntxm.org)**. Designed to simplify database management for professionals and teams, SQL Studio provides an advanced, visually stunning, and highly intuitive graphical interface to visualize, query, and perform all operations on your databases without writing repetitive SQL code manually.

Built with Tauri, Rust, and React, SQL Studio runs natively on **Windows, macOS, and Linux**, offering incredible performance and a deeply integrated OS experience.

---

## ✨ Features You'll Love

### 1. Multi-Engine Connection Hub
* **Unified Workspace**: Manage PostgreSQL, MySQL, and SQLite databases simultaneously.
* **Smart Connection Testing**: Test configurations with live latency measurements before saving them.
* **Strict Privacy**: Works 100% offline. No telemetry, tracking, or cloud sync. Your database structures and data never leave your computer.

### 2. Interactive Schema Visualizer
* **Entity-Relationship Diagrams**: Automatically generate clean, node-based layouts of your tables and their foreign key relationships.
* **Canvas Controls**: Smoothly pan, zoom, and organize complex databases.
* **Table Grouping**: Group related tables into custom, color-coded sections to organize large schemas.
* **Instant Inspector**: Click any table node to inspect columns, indexes, and constraints in a side panel.

### 3. Monaco-Powered SQL Query Editor
* **Developer-Grade Editing**: Powered by the same editor engine as VS Code, featuring syntax highlighting, auto-completion, bracket matching, and format-on-save.
* **Multi-Tab Layout**: Keep multiple active queries open. Inactive tabs are optimized to prevent background database requests.
* **Query History**: Search and restore previously executed queries from a dedicated session history panel.

### 4. Interactive Data Panel & Exporters
* **Spreadsheet Grid**: Sort, paginate, and filter table records dynamically.
* **Multi-Format Export**: Export query results and tables directly to **CSV**, **JSON**, or clean **Markdown tables**.

---

## 🔒 Security First
* **Military-Grade Encryption**: Database passwords and connection details are encrypted locally using AES-256-GCM.
* **Isolated Encryption Key**: Cryptographic keys are generated randomly on first launch and protected using OS-level permissions (e.g., `0600` on Unix/macOS) to prevent unauthorized access by other users or processes.

---

## Screenshots

### Connection Hub
Easily manage your recent connections, connect to new databases, or open local SQLite files.
![Connection Hub](images/connection_hub.png)

### Main Workspace
A rich, split-pane workspace featuring an explorer, advanced SQL editor, interactive data panel, schema inspector, and query history.
![Main Workspace](images/main_workspace.png)

### Visual Schema
Explore your database architecture with an interactive, auto-layout node-based Entity-Relationship diagram.
![Visual Schema](images/visual_schema.png)

### Advanced Data Export & Filtering
Dynamically filter rows and export precisely the data you need to CSV or JSON with a few clicks.
![Data Export](images/data_export.png)

---

## 📄 License

> **Note**: This software is proprietary and provided under a private license by **[ntxm](https://ntxm.org)**. You may download and use SQL Studio for personal or internal business purposes, but you are not permitted to modify, redistribute, or reverse-engineer the software without explicit written permission from the developers. All rights reserved.
