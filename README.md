<h1 align="center">📦 Distributor Sales & Inventory Automation System</h1>

<p align="center">
  <b>A Google Sheets based automation system for managing distributor sales, inventory, and warehouse operations.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Google%20Sheets-green">
  <img src="https://img.shields.io/badge/Automation-Apps%20Script-orange">
  <img src="https://img.shields.io/badge/Category-Inventory%20Management-blue">
  <img src="https://img.shields.io/badge/Status-Active-success">
</p>

<hr>

<h2>🚀 Project Overview</h2>

<p>
The <b>Distributor Sales & Inventory Automation System</b> helps distributors manage their daily
operations efficiently using <b>Google Sheets automation</b>.
</p>

<p>The system allows distributors to:</p>

<ul>
<li>Track daily sales</li>
<li>Monitor warehouse inventory</li>
<li>Record product dispatch</li>
<li>Track retailer supply</li>
<li>Monitor credit retailers</li>
<li>Track operational expenses</li>
</ul>

<p>
The system automatically performs calculations and updates a <b>dashboard with real-time business insights</b>.
</p>

<hr>

<h2>⚙️ System Workflow</h2>

<table align="center">
<tr>
<td align="center">Warehouse Stock</td>
<td align="center">➡</td>
<td align="center">Dispatch Sheet</td>
<td align="center">➡</td>
<td align="center">Sales Sheet</td>
<td align="center">➡</td>
<td align="center">Dashboard Reports</td>
</tr>
</table>

<hr>

<h2>✨ Key Features</h2>

<h3>📊 Daily Sales Automation</h3>

<ul>
<li>Staff enters daily sales data</li>
<li>System calculates total boxes sold</li>
<li>Automatically calculates revenue</li>
<li>Updates dashboard statistics</li>
</ul>

<h3>📦 Box Dispatch Automation</h3>

<ul>
<li>Warehouse staff record dispatched boxes</li>
<li>System calculates stock movement</li>
<li>Automatically updates remaining stock</li>
<li>Generates invoice values</li>
</ul>

<h3>🏬 Inventory Management</h3>

<ul>
<li>Tracks product stock levels</li>
<li>Monitors available cartons</li>
<li>Generates minimum stock alerts</li>
</ul>

<h3>🛒 Retailer Supply Tracking</h3>

<ul>
<li>Records retailer orders</li>
<li>Tracks supply frequency</li>
<li>Maintains order history</li>
</ul>

<h3>💳 Credit Retailer Tracking</h3>

<ul>
<li>Tracks credit purchases</li>
<li>Monitors outstanding balances</li>
<li>Generates payment summaries</li>
</ul>

<h3>💰 Expense Tracking</h3>

<ul>
<li>Delivery vehicle costs</li>
<li>Staff salaries</li>
<li>Warehouse expenses</li>
<li>Marketing expenses</li>
</ul>

<hr>

<h2>⚠️ Stock Loss Detection</h2>

<p>The system verifies stock consistency using the formula:</p>

<pre>
Opening Stock + Received Stock − Sold Stock
</pre>

<p>If there is a mismatch, the system alerts the distributor about possible stock loss.</p>

<hr>

<h2>🗂 System Structure</h2>

<h3>📦 Products Sheet</h3>

<table border="1" cellpadding="8">
<tr>
<th>Field</th>
<th>Description</th>
</tr>
<tr>
<td>Product_ID</td>
<td>Unique product identifier</td>
</tr>
<tr>
<td>Product_Name</td>
<td>Name of the product</td>
</tr>
<tr>
<td>Brand</td>
<td>Product brand</td>
</tr>
<tr>
<td>Carton_Size</td>
<td>Items per carton</td>
</tr>
<tr>
<td>Cost_Price</td>
<td>Distributor purchase price</td>
</tr>
<tr>
<td>Selling_Price</td>
<td>Retail selling price</td>
</tr>
<tr>
<td>Minimum_Stock_Level</td>
<td>Restock alert threshold</td>
</tr>
</table>

<br>

<h3>👤 Users Sheet</h3>

<p>Stores staff or system users who enter operational data.</p>

<h3>📊 Sales Sheet</h3>

<table border="1" cellpadding="8">
<tr>
<th>Field</th>
<th>Description</th>
</tr>
<tr>
<td>Sale_ID</td>
<td>Unique sales record</td>
</tr>
<tr>
<td>Product_ID</td>
<td>Product sold</td>
</tr>
<tr>
<td>Boxes_Sold</td>
<td>Number of boxes sold</td>
</tr>
<tr>
<td>Date</td>
<td>Sale date</td>
</tr>
<tr>
<td>Entered_By</td>
<td>Staff member</td>
</tr>
</table>

<br>

<h3>🚚 Dispatch Sheet</h3>

<p>Tracks warehouse stock movement and retailer supply.</p>

<hr>

<h2>📈 Dashboard</h2>

<p>The dashboard displays:</p>

<ul>
<li>Daily sales reports</li>
<li>Total revenue</li>
<li>Warehouse stock levels</li>
<li>Product performance</li>
</ul>

<p>
This helps distributors quickly analyze business performance.
</p>

<hr>

<h2>⚙️ Setup Instructions</h2>

<ol>
<li>Open the Google Sheets file</li>
<li>Verify sheets: Products, Users, Sales, Dispatch</li>
<li>Add product information</li>
<li>Start entering sales and dispatch records</li>
<li>Dashboard updates automatically</li>
</ol>

<hr>

<h2>🔗 Project Links</h2>

<p>
<b>Google Sheet</b><br>
<a href="https://docs.google.com/spreadsheets/d/1NND28Wc7r2ORu7gQll5x9nlJiB8dgLu4_Trqxw1q9BI/edit?usp=sharing">
Open Spreadsheet
</a>
</p>

<p>
<b>Apps Script</b><br>
<a href="https://script.google.com/macros/s/AKfycbwi8r9jsffqd7agAwKWHREUikccpcR_AnuJvIuBkbxpbZBD3_GcW7bG9OnPnTdpybVNPw/exec">
View Script
</a>
</p>

<hr>

<h2>🛠 Technologies Used</h2>

<ul>
<li>Google Sheets</li>
<li>Spreadsheet Formulas</li>
<li>Google Apps Script</li>
<li>Dashboard Visualization</li>
</ul>
