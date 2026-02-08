# KWIC Search Notebook

An easy-to-use Google Colab notebook for searching "keywords in context" (KWIC) in your `.txt`, `.csv`, or `.json` files. Perfect for researchers, students, and anyone who needs to analyze text patterns in their documents.

## What This Tool Does

The KWIC notebook helps you:
- Search for keywords or phrases in your text files
- See results in context (words before and after your search term)
- Export results as CSV files for further analysis
- Work with multiple file formats (`.txt`, `.csv`, `.json`)
- Use an interactive user interface - no coding required

## Project Structure

```
KWIC-notebook/
├── KWIC-with-User-Interface.ipynb  # Main Colab notebook
├── 01-three-men-in-a-boat.txt      # Sample text file
├── 02-quotes-shorter.csv            # Sample CSV file
├── 03-kjv_bible.json                # Sample JSON file
├── results/                         # Output folder (auto-created)
├── LICENSE                          # MIT License
├── .gitignore                       # Git configuration
└── README.md                        # This file
```

---

## How to Run the KWIC Notebook in Google Colab

This project is hosted on GitHub, so you can run it in Colab in two common ways:
- **Option 1 (recommended): Open the notebook from GitHub in Colab** (no manual folder upload required)
- **Option 2: Upload the project folder to Google Drive** (useful if you want everything stored and persisted in Drive)

Choose the option that fits your workflow.

---

## Option 1 (Recommended): Open from GitHub in Google Colab

### 1. Open the notebook from GitHub
- Open this repository on GitHub
- Click the notebook file: `KWIC-with-User-Interface.ipynb`
- Open it in Google Colab (for example via an “Open in Colab” link/badge if provided, or by opening the notebook from Colab’s **GitHub** tab)

### 2. Run the notebook
- In Colab, click **Runtime → Run all** (or press play on the cells)
- When prompted, confirm permissions / execution prompts (this is normal for Colab)

### Notes for this option (important)
- Your Colab runtime is temporary. If the notebook saves outputs to a local runtime folder, they may disappear when the runtime resets.
- If you want outputs to persist (saved files you can keep), use **Option 2 (Google Drive)** or configure the notebook to save to Drive.

---

## Option 2: Upload to Google Drive (keeps files & outputs together)

This guide explains how to set up and run the KWIC Search notebook in Google Colab (for first-time users).

### A. Before You Start: Upload to Google Drive

#### 1. Upload the project folder to Google Drive

- If you received the project as a zipped folder via email → download and unzip it on your computer
- Open Google Drive in your browser
- Click **New → Folder upload**
- Upload the entire project folder to **My Drive** (recommended location)
- **Do not rename or move files** inside the project folder. The notebook expects a consistent structure.

#### 2. Open the notebook in Colab

- In Google Drive, open your project folder
- Right-click the `KWIC-with-User-Interface.ipynb` file → **Open with → Google Colab**

**Tip:** Colab runs Python in the cloud, so you don't need to install Python locally.

### B. If You Haven't Used Google Colab Before: Install/Enable It

Sometimes "Google Colab" is not available under "Open with".

**Option 1 (recommended):**
- Go to the Chrome Web Store
- Search for "Google Colaboratory"
- Click **Add to Chrome**
- Then return to Google Drive → right-click notebook → **Open with → Google Colab**

**Option 2 (works without installing anything):**
- Go to [colab.research.google.com](https://colab.research.google.com)
- Click **File → Open notebook**
- Choose the **Google Drive** tab and select the notebook

(Which option is available can depend on your browser and organization settings.)

### C. First-Time Setup: Google Drive Permissions

When you run the Colab notebook the first time, Google will ask you to confirm permissions. This is normal.

#### Step 1: Connect to Google Drive
- Look for the "Connect to Google Drive" button or link
- Click it to start the authentication process

#### Step 2: Google Account Selection
- Choose your Google account from the list
- If you don't see your account, click "Use another account"

#### Step 3: Permission Requests
- Google will ask for several permissions
- Click **Allow** for each permission request
- These permissions are needed for:
  - Accessing your Google Drive files
  - Running Python code in the cloud
  - Installing packages automatically

#### Step 4: Authorization Complete
1. You'll see a success message
2. The notebook will now have access to your Google Drive files

### D. Folder Structure Requirements (Important)

To avoid "file not found" problems:
- Keep your input files in the project folder (or in the folder you set inside the notebook UI)
- Do not rename the project folder or move files around after uploading
- The notebook will save outputs into: `results/` (inside the project folder / chosen Drive folder)

---

## Troubleshooting

### "File not found"
- Check the Drive folder path in the UI
- Confirm your files are inside that folder
- Confirm the notebook has Drive permissions

### Permission errors
- Rerun the code cell and reconnect Drive
- Make sure you clicked **Allow** for all prompts

### Colab not available in "Open with"
- Use the [colab.research.google.com](https://colab.research.google.com) method (Option 2 above), or install the Colab extension

---

## Sample Files Included

The project includes three sample files to test the notebook:
- `01-three-men-in-a-boat.txt` - Classic novel text
- `02-quotes-shorter.csv` - Collection of quotes
- `03-kjv_bible.json` - Bible text in JSON format

## Requirements

- A Google account
- Google Drive access (required for Option 2; optional for Option 1)
- Internet connection (to run the notebook in Colab)

## License

This project is open source and available for educational and research purposes. See the LICENSE file for details.
