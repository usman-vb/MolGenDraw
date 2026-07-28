# MolGenDraw 🧪

**MolGenDraw** is your intuitive 2D molecular editor! Draw, edit, and explore chemical structures with real-time analysis. Featuring ring/structure templates, SMILES support, and PubChem integration, it outshines others with advanced SDF database support—seamlessly merge `.mol` files and edit custom tags. A fast, beautiful, and portable chemistry app designed for researchers, chemists, and students!

🆕 **Current Version**  
Version: 1.152 (First Official Stable Release)  
Build Date: July 27, 2026  
Platform: Windows 64-bit (Standalone Executable)  

---

✨ **Features**

🎨 **Interactive 2D Canvas & Drawing Tools**  
- Intuitive tools to draw, edit, and manipulate chemical structures directly on the canvas.  
- Easily add atoms, cycle through bond orders (single, double, triple), and fuse predefined ring templates (Benzene, Cyclohexane, Cyclopentane, etc.).  

🔄 **Advanced Canvas Manipulation & Selection**  
- Robust selection tool to interact with specific parts of a molecule.  
- Rotate structures freely up to 360 degrees using the mouse, or perform 180-degree vertical and horizontal flips for optimal layout.  

📂 **Advanced SDF File Management** *(Signature Feature)*  
- Seamlessly navigate through multi-molecule Structure-Data Files (`.sdf`).  
- Edit, create, or delete specific SDF tags/properties via a dedicated tag editor.  
- **SDF Generator**: Merge multiple standalone `.mol` files into a single, organized `.sdf` database file (outshining the limited SDF support in tools like ChemDraw, ChemSketch or Ketcher etc).  
- Options to "Save Current Molecule Only" or delete specific records with confirmation dialogs.  

📊 **Real-Time Molecular Analysis**  
- Automatically calculate and display key chemical properties as you draw.  
- Instant updates for Molecular Formula, Molecular Weight, Exact Mass, Elemental % Composition, InChI String, and InChI Key.  

🌐 **PubChem Data Integration**  
- Built-in PubChem Data Retriever connects to the PubChem API.  
- Enter a compound name or SMILES string to instantly retrieve comprehensive chemical data, display it in a formatted popup, and auto-copy to the system clipboard.  

📑 **Advanced Export Options**  
- Generate professional, single-page A4 PDF files containing the molecular structure alongside a detailed analysis report.  
- Export high-quality PNG images with transparent backgrounds.  
- Save the current molecule as a reusable custom template for future drawing sessions.  

🛡️ **Chemical Validation & Offline Generation**  
- Continuous validation for correct valence and structural rules.  
- Dynamic status bar catches and displays RDKit sanitization errors (e.g., explicit valence violations) in real-time red text.  
- Offline generation of SMILES, InChI, and InChI Key directly from the drawn molecule.  

🧪 **Interactive Periodic Table & History**  
- Built-in, fully populated periodic table dialog displaying Atomic Number, Symbol, Name, Atomic Weight, and Exact Mass.  
- Multi-level Undo/Redo system ensuring no drawing progress is ever lost.  

---

🖥 **Screenshots**  

*(Screenshots are stored in the `/Screenshots` folder.)*  

**1. Main Interface**  
![Main Interface](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_Template.png)  
*The clean, intuitive drawing canvas with the top control bar, tool toggles, and real-time formula display.*  

**2. Advanced SDF Database Management**  
![SDF Molecular File](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_SDF_File.png) 
![SDF File Generator](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_SDF_Generator.png)
![SDF Tags Editor](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_SDF_Tags_Editor.png)
 
*Navigating multi-molecule SDF files, editing custom tags, and merging standalone .mol files into a unified database.*  

**3. Real-Time Molecular Analysis & Validation**  
![Analysis Panel](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_New_molecule.png)
![Analysis Panel](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_More_Info.png)
*Live calculation of Molecular Weight, Exact Mass, InChI Key, and dynamic RDKit error tracking in the status bar.*  

**4. Delete Molecular Fragment & Merge**  
![Delete Fragment](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_Delete_Fragment.png)
![Delete Second Fragment](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_Delete_Fragment2.png)
![Merge with Template](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_Merge2.png)
![Press F6 Shortcut Key to Search on PubChem](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_Search_F6.png)
*Delete molecular fragments and then merge with Template to create a new molecule. Press F6 Shortcut Key to search on PubChem online database.*  

**4. Interactive Periodic Table & Drawing Tools**  
![Periodic Table](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_Periodic_Table.png)  
*Selecting elements directly from the built-in periodic table with detailed atomic info, alongside ring fusion tools.*  

**5. Export Options & PDF Reports**  
![Export Options](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_PDF_Report.png)  
*Generating professional A4 PDF analysis reports and transparent PNG images of the drawn structures.*  

**6. PubChem Data Integration**  
![PubChem Retrieval](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_PubChem_Data.png)  
*Fetching comprehensive compound data from the PubChem API and auto-copying it to the clipboard.*  

**7. About the Software & Author**  
![About Dialog](https://github.com/usman-vb/MolGenDraw/blob/main/Screenshots/MolGenDraw_About.png)  
*Version history, build details, and direct links to the developer's website and GitHub repository.*  

---

⚙️ **System Requirements**  

- **Operating System**: Windows 10 or Windows 11 (64-bit)
- **Dependencies**: **None**. The software is fully self-contained. No Python installation or external libraries required!

---

🚀 **How to Download and Run**  

MolGenDraw is distributed as a portable, standalone Windows executable. No installation wizard is needed.

1. Navigate to the **[Releases](https://github.com/usman-vb/MolGenDraw/releases)** section on the right-hand sidebar of this GitHub repository.
2. Download the latest ZIP archive (e.g., `MolGenDraw_v1.152.zip`).
3. Extract the contents of the ZIP file to any folder on your computer (e.g., `C:\MolGenDraw` or your Desktop).
4. Double-click **`MolGenDraw.exe`** to launch the application.
5. *(Optional)* Right-click the `.exe` file, select **Send to > Desktop (create shortcut)** for easy future access.

> **⚠️ Windows SmartScreen Notice:**  
> Because this software is independently compiled and not signed with an expensive enterprise digital certificate, Windows Defender SmartScreen might flag it upon the first run. If this happens, simply click **"More info"** and then **"Run anyway"** to start the program safely.

---

👨‍💻 **Developer**  

**Usman Afzal**  
🌐 Website: [https://www.usmanafzal.pk](https://www.usmanafzal.pk)  
🐙 GitHub: [https://github.com/usman-vb](https://github.com/usman-vb)  

---

🔮 **Planned Enhancements**  

- 3D structure visualization and conformer generation.  
- Advanced reaction drawing and arrow tools.  
- Batch SMILES-to-Structure conversion with progress tracking.  
- Dark mode UI theme.  

---

⚠️ **Disclaimer**  
This software is provided as freeware. It may contain bugs. Use it at your own risk, as its stability and functionality are not guaranteed for critical clinical or industrial applications without independent validation.  

© 2026 MolGenDraw. All Rights Reserved.
