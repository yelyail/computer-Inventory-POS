<p align="center"> <h1 align="center"> Computer Inventory and POS</h1> </p>

<p>
A web-based Inventory and Point of Sale (POS) Management System developed using 
<strong>Laravel</strong>, <strong>Blade</strong>, and <strong>Tailwind CSS</strong>.
The system manages inventory, suppliers, sales transactions, user accounts,
serial tracking, and reporting with role-based access control.
</p>

<hr>

<h2>🚀 System Overview</h2>

<ul>
    <li>Inventory Management (Products, Serial Tracking, Archiving)</li>
    <li>Supplier Management</li>
    <li>Point of Sale (POS) Module</li>
    <li>Sales & Inventory Reports (Printable)</li>
    <li>Approval Workflow for Pending Requests</li>
    <li>Role-Based Access (Admin / Staff)</li>
    <li>Authentication System with Session Alerts</li>
</ul>

<hr>

<h2>🛠️ Tech Stack</h2>

<ul>
    <li>Backend: Laravel</li>
    <li>Frontend: Blade Templates + Tailwind CSS</li>
    <li>Build Tool: Vite</li>
    <li>Database: MySQL</li>
    <li>Server: XAMPP / Apache</li>
</ul>

<hr>

<h2>📂 Project Structure (Core)</h2>

<pre>
app/
 └── Http/
     └── Controllers/
         ├── LoginController.php
         ├── supervisorController.php
         ├── printController.php

resources/
 ├── views/
 │    └── Inventory/
 │         └── Login.blade.php
 ├── css/
 └── js/

routes/
 └── web.php
</pre>

<hr>

<h2>🔐 Authentication Flow</h2>

<ol>
    <li>User accesses root route <code>/</code></li>
    <li>Login form submits via POST</li>
    <li>LoginController validates credentials</li>
    <li>Redirects based on role (Admin / Staff)</li>
    <li>Session flash messages handle success/error alerts</li>
</ol>

<hr>

<h2>📊 Core Modules</h2>

<h3>Admin (Supervisor)</h3>
<ul>
    <li>Dashboard</li>
    <li>Inventory Management</li>
    <li>Supplier Management</li>
    <li>User Management</li>
    <li>POS Transactions</li>
    <li>Pending Approvals</li>
    <li>Sales Report</li>
</ul>

<h3>Staff</h3>
<ul>
    <li>Dashboard</li>
    <li>Inventory View</li>
    <li>POS Transactions</li>
    <li>Submit Pending Requests</li>
</ul>

<hr>

<h2>🖨️ Reporting</h2>

<ul>
    <li>Order Receipt Printing</li>
    <li>Inventory Report Printing</li>
    <li>Sales Report Printing</li>
</ul>
</body>
</html>
