## How to Download These Projects

**Important:** These projects have a few special requirements. Please follow these steps exactly.

---

### 1. How to Download

The `.pbip` project files in this repository may not download correctly if you click them individually (you will get an empty file).

To get all the complete, working projects at once, you **must** download the entire repository as a ZIP:

1.  Click the green `<> Code` button at the top of this page.
2.  Select `Download ZIP` from the dropdown menu.

This will download a single file (`dashboards-powerbi-main.zip`) containing all the project folders.

---

### 2. How to Unzip (To Fix "Path Too Long" Error)

After downloading, you **must** unzip the file to a location with a very short path.

If you try to unzip it in your `Downloads` or `Documents` folder, you will likely get a **"path too long" error**. This happens because `.pbip` projects contain many nested folders.

**Simple Solution:**

1.  Find the downloaded `dashboards-powerbi-main.zip` file.
2.  Move it directly to your **`C:\`** drive.
3.  **Right-click** the file and "Extract All..." from there.

This will create a short, working path like `C:\dashboards-powerbi-main\`.

---

## What is a .pbip Project?

A **`.pbip` (Power BI Project)** file is not like a normal `.pbix` file. Instead of being one single file, it's a **folder structure** that separates the report, the data model, and other settings into individual text-based files.

This format is used for version control (like Git) because it allows developers to track specific changes to measures or visuals.

---

## How to Open the Projects

Once you have unzipped the main `dashboards-powerbi-main` folder:

1.  Open the folder (e.g., `C:\dashboards-powerbi-main\`).
2.  You will see the folders for the different projects (like `case_study_databel` or `ThreadsLtd_dashboard`). Open the one you want to view.
3.  Inside, you will see several items, including a `.Report` folder, a `.SemanticModel` folder, and a file ending in **`.pbip`**.
4.  To open the project, **double-click the `.pbip` file**. This file tells Power BI Desktop how to load all the other parts of the project.
