# Leoch Inventory Website

This site displays daily inventory data from SAP.

---

## Daily Update Steps

Follow these steps every day to update inventory:

### 1. Download Data from SAP

* Run inventory report (Plant N010)
* Export file as Excel

---

### 2. Rename the File

Rename the file exactly to:

```
N010.xlsx
```

⚠️ The filename must match exactly
---

### 3. Upload to GitHub

1. Go to this repository on GitHub
2. Find the "Add file" buttom, and choose "Upload file"
3. Drag and drop your new file to replace it
4. Click **"Commit changes"**

---

### 4. Done

* Wait a few minutes to refresh the website and check the "Last Updated" date

---

## ⚠️ Important Rules

* Do NOT change any codes
* Always use the exact filename: `N010.xlsx`
* Always click **Commit changes**
* Do NOT rename the file
* Do NOT upload multiple versions

---

## ❗ Common Issues

### Website not updating?

* Make sure you clicked **Commit changes**
* Refresh the webpage

### Data looks wrong?

* Check that SAP export includes:

  * Material
  * Leoch Part Number
  * Sto.Loction
  * Qty.Avail

---
