# Issue Buddy Tools

![David Veld Logo](IssueBuddyDocs/img/image1.png)

[cite_start]**Version 1.0.0 | June 2026** [cite: 42]

[cite_start]**Issue Buddy Tools** is a collection of tools designed to assist Autodesk Revit users during the final stages of information delivery[cite: 43]. 

[cite_start]The add-in includes **five efficient quick-action commands** engineered to streamline final submittal and information delivery processes, saving countless hours[cite: 44, 49]:

* [cite_start]**CreatePrintSet**: Set up custom print sets driven entirely by sheet revisions[cite: 45, 52].
* [cite_start]**PDFSplitter**: Export dynamically named PDFs and DWGs[cite: 46].
* [cite_start]**ModelStripper**: Clean and protect project data before model delivery[cite: 47].
* [cite_start]**RevisionViewer**: Visualize historical sheet revisions across the entire model[cite: 48].
* [cite_start]**Bonus Tool**: Create print sets directly from your Project Browser selection[cite: 49, 76].

![Issue Buddy Ribbon Toolbar](images/ribbon_toolbar.png)

[cite_start]Below is a brief overview of the tools included in this set[cite: 50].

---

## Tool Overview

### 1. CreatePrintSet
[cite_start]Use this tool to generate a Revit print set driven entirely by sheet revisions[cite: 51, 52]. Simply select a single revision or a range of revisions, specify a name, and click OK. [cite_start]It’s that simple[cite: 53]. 

[cite_start]With this tool, you will never accidentally miss a revised sheet in your submittal package[cite: 54].

![Create Print Set Dialog](images/create_print_set.png)

---

### 2. PDFSplitter
[cite_start]Once a print set is generated, print it to a single combined PDF using your preferred PDF driver (ensuring the option *"Combine multiple selected views/sheets into a single file"* is enabled)[cite: 56, 57]. [cite_start]This combined file is used as the base input for the next step[cite: 58].

![Revit Print Setup](images/revit_print.png)

[cite_start]The **PDFSplitter** reads the combined document and splits it into individual files matching the page order of your print set[cite: 56, 59]. [cite_start]One by one, it generates neatly separated PDFs and accompanying DWGs[cite: 60].

* [cite_start]**Full Naming Control**: Customize your output file names dynamically using any available project or sheet parameters[cite: 61].
* [cite_start]**Reusable Templates**: Save your parameter mappings as naming presets to seamlessly match company or client information protocols[cite: 62].

#### How It Works:
* [cite_start]**Step 1**: Select your combined PDF or drag and drop it directly into the target UI box[cite: 63, 64].
  
  ![PDF Splitter Step 1](images/pdf_splitter_step1.png)

* [cite_start]**Step 2**: Select your preferred DWG export settings, choose the matching print set (the one used to print your combined PDF), and select or create a naming template[cite: 65].
  
  ![PDF Splitter Step 2](images/pdf_splitter_step2.png)

* **Step 3**: Click **Split**. [cite_start]The tool will process the document, generating individual PDFs and corresponding DWGs in your target output directory[cite: 66].
  
  ![PDF Splitter Step 3](images/pdf_splitter_step3.png)

#### Output Results Example:
| Exported PDFs | Exported DWGs |
|---|---|
| ![Exported PDFs List](images/exported_pdfs.png) | ![Exported DWGs List](images/exported_dwgs.png) |

---

### 3. ModelStripper
[cite_start]The **ModelStripper** exports and strips a Revit model to a specified location[cite: 67, 68]. [cite_start]Users can select exactly which non-model components to strip away prior to export, including[cite: 69]:
* [cite_start]Views [cite: 69]
* [cite_start]Sheets [cite: 69]
* [cite_start]Legends [cite: 69]
* [cite_start]Schedules [cite: 69]
* View Templates
* [cite_start]Revit Links (automatically unloaded) [cite: 69]
* [cite_start]Model Groups (automatically ungrouped) [cite: 69]

[cite_start]A central file or a cloud-based shared model will automatically become detached from its source[cite: 70]. [cite_start]After processing, the tool automatically prompts the user to purge unused elements, trimming the file down to its most compact and secure version[cite: 71].

![Model Stripper Dialog](images/model_stripper.png)

---

### 4. RevisionViewer
[cite_start]The **RevisionViewer** allows you to inspect both current and historical revisions across all sheets within the active Revit model[cite: 72, 73]. 

[cite_start]It provides a clean matrix table of your revision streams, making it effortless to cross-check sheet statuses, compile issue records, or generate Task Information Delivery Plans (TIDPs)[cite: 74]. [cite_start]The completed matrix table can be exported directly to a CSV file for external documentation and project tracking workflows[cite: 75].

![Revision History Viewer Matrix](images/revision_viewer.png)

---

### 5. Bonus Tool: Print Set from Selection
[cite_start]When Issue Buddy Tools are installed, a custom context-menu command is integrated directly into the Revit Project Browser[cite: 76, 77]. [cite_start]Simply highlight a selection of sheets in your Project Browser, right-click, and choose **IssueBuddy -> Create Print Set from Selection**[cite: 78].

[cite_start]It is fast, intuitive, and eliminates manual list building[cite: 79].

![Project Browser Context Menu](images/context_menu_selection.png)

> [cite_start]📌 **Note:** This specific context-menu feature is supported in Revit 2025 and higher[cite: 80].
