# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="762" height="428" alt="Screenshot 2025-09-04 111645" src="https://github.com/user-attachments/assets/f7f0d618-fa64-4f9a-bbd1-f334330d0e71" />
<img width="758" height="433" alt="Screenshot 2025-09-04 111653" src="https://github.com/user-attachments/assets/699fa2e5-5915-4b39-bcf4-e7d4bcd25ab2" />
<img width="764" height="427" alt="Screenshot 2025-09-04 111703" src="https://github.com/user-attachments/assets/a6f211d9-44ce-4afa-9890-f3347b7c8ebe" />
<img width="766" height="426" alt="Screenshot 2025-09-04 111716" src="https://github.com/user-attachments/assets/becb7c9b-1d99-4606-aaa9-23d221ea10ac" />
<img width="760" height="431" alt="Screenshot 2025-09-04 111730" src="https://github.com/user-attachments/assets/d48b463b-e76f-4e33-8bfd-5a4fca2122fe" />
<img width="768" height="430" alt="Screenshot 2025-09-04 111754" src="https://github.com/user-attachments/assets/4a185dad-943f-42da-87f4-5f8df9a9d3af" />
<img width="766" height="430" alt="Screenshot 2025-09-04 111804" src="https://github.com/user-attachments/assets/9112df85-5dd8-4545-bbad-1e673996761b" />
<img width="762" height="434" alt="Screenshot 2025-09-04 111821" src="https://github.com/user-attachments/assets/10529822-1135-4a74-8625-174436283356" />
<img width="768" height="434" alt="Screenshot 2025-09-04 111829" src="https://github.com/user-attachments/assets/434ec47f-4913-4583-bf50-5bfbd5908d3b" />









## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
