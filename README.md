# 🕵️‍♂️ Digital Forensics & Steganography Project

<p align="center">
<img src="https://img.shields.io/badge/Digital%20Forensics-FTK%20Imager-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/Steganography-SilentEye-success?style=for-the-badge">
<img src="https://img.shields.io/badge/Evidence-E01-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/Platform-Windows%2010-informational?style=for-the-badge">

</p>

---

# 👤 Project Owner

**Gabriel Anigboro**

---

# 🎯 Objective

This project demonstrates a complete digital forensics investigation involving steganographic analysis, forensic imaging, evidence preservation, and cryptographic verification.

A virtual cyber laboratory was used to analyze digital evidence, create forensic images, verify evidence integrity using cryptographic hashes, and recover hidden messages embedded inside image files. Throughout the investigation, industry-standard forensic procedures were followed to ensure evidence remained unchanged while validating the complete lifecycle from hidden message creation through successful forensic recovery.

---

# 🧠 Skills Demonstrated

- Digital Forensics Investigation
- Evidence Preservation
- Steganographic Analysis
- Hidden Payload Extraction
- Forensic Imaging
- Evidence Hash Verification
- MD5 & SHA-1 Validation
- Hexadecimal Analysis
- NTFS File System Investigation
- Expert Witness (E01) Image Analysis
- Unallocated Space Investigation
- Windows File System Navigation
- Chain of Custody Concepts
- Digital Evidence Integrity Verification

---

# 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| Exterro FTK Imager | Forensic imaging and evidence analysis |
| SilentEye | Steganography encoding and decoding |
| Windows File Explorer | Evidence management |
| Hex Viewer | Raw sector analysis |
| Windows 10 Virtual Machine | Investigation environment |

---

# 🏗️ Investigation Workflow

Virtual Cyber Laboratory (LABVM02)
            │
            ▼
Windows Investigation Environment
            │
            ▼
Steganographic Analysis (SilentEye)
            │
            ▼
Evidence Encoding & Hidden Payload Creation
            │
            ▼
Forensic Drive Acquisition (FTK Imager)
            │
            ▼
Hexadecimal Disk Inspection
            │
            ▼
Forensic Image Creation (.E01)
            │
            ▼
MD5 / SHA-1 Verification
            │
            ▼
Forensic Image Mounting
            │
            ▼
Evidence Examination
            │
            ▼
Successful Hidden Message Recovery


---

# 📷 Project Walkthrough

## Ref 1 – Virtual Cyber Lab Environment and Steganographic Analysis

This screenshot shows the investigation environment running inside the **PG_Cyber_Lab** virtual machine. The desktop includes Exterro FTK Imager, Cyber-Tools, and SilentEye. SilentEye is prepared to analyze the target image **Tom_and_Jerry_art_in_MultiVersus.png**, allowing the investigator to perform encoding or decoding operations.

<p align="center">
<img src="Screenshot 2026-06-27 at 01.08.31.png" width="900">
</p>

---

## Ref 2 – Multi-Format Asset Inspection

This stage compares PNG and JPEG versions of the same image inside SilentEye. The comparison demonstrates how different image formats affect steganographic payload capacity while maintaining image usability.

<p align="center">
<img src="Screenshot 2026-06-27 at 01.21.37.png" width="900">
</p>

---

## Ref 3 – Encoded Evidence Generation

After embedding the hidden payload, the newly created evidence file **Tom_and_Jerry_art_in_MultiVersus._coded.jpg** is successfully written to the forensic workspace on **Local Disk (D:)**, providing an auditable output for subsequent forensic analysis.

<p align="center">
<img src="Screenshot 2026-06-27 at 01.23.56.png" width="900">
</p>

---

## Ref 4 – Clean Evidence Workspace Verification

Prior to evidence acquisition, the investigation storage partition is verified as empty. Establishing a clean destination minimizes contamination risks and supports proper forensic evidence handling.

<p align="center">
<img src="Screenshot 2026-06-27 at 01.32.01.png" width="900">
</p>

---

## Ref 5 – Drive Acquisition and Hex Analysis

Using Exterro FTK Imager, the target partition is mounted for non-destructive analysis. The integrated Hex Viewer displays raw disk sectors and confirms the NTFS file system signature, validating the structure of the evidence before imaging.

<p align="center">
<img src="Screenshot 2026-06-27 at 01.35.16.png" width="900">
</p>

---

## Ref 6 – Evidence Integrity Verification

Following forensic acquisition, FTK Imager verifies the integrity of the evidence using both **MD5** and **SHA-1** hashing algorithms. The matching hashes confirm the forensic image remained unchanged throughout acquisition.

<p align="center">
<img src="Screenshot 2026-06-27 at 01.53.14.png" width="900">
</p>

---

## Ref 7 – Forensic Image Examination

The completed forensic image (**Staganograph.E01**) is mounted for examination. FTK Imager displays the evidence tree, NTFS partitions, orphan files, and unallocated space, allowing investigators to inspect deleted or hidden artifacts.

<p align="center">
<img src="Screenshot 2026-06-27 at 01.55.55.png" width="900">
</p>

---

## Ref 8 – Suspect File Analysis

The recovered suspect image (**$R1UM07L.jpg**) is loaded into SilentEye for detailed analysis. This represents the investigative stage where the examiner attempts to recover concealed information from the image.

<p align="center">
<img src="Screenshot 2026-06-27 at 02.04.39.png" width="900">
</p>

---

## Ref 9 – Hidden Payload Successfully Recovered

SilentEye successfully decodes the concealed message using the correct extraction parameters. The hidden message recovered from the image is:

> **"My favorite cartoon"**

This confirms the successful completion of the forensic investigation and validates the entire steganography workflow from payload creation through forensic recovery.

<p align="center">
<img src="Screenshot 2026-06-27 at 02.04.54.png" width="900">
</p>

---

# 🔐 Evidence Validation

| Verification | Status |
|-------------|--------|
| Evidence Acquired | ✅ |
| Forensic Image Created | ✅ |
| MD5 Hash Verified | ✅ |
| SHA-1 Hash Verified | ✅ |
| Image Mounted | ✅ |
| Hidden Payload Located | ✅ |
| Hidden Message Recovered | ✅ |
| Evidence Integrity Preserved | ✅ |

---

# 📚 Key Takeaways

This project demonstrates the practical application of digital forensic methodologies by combining steganographic analysis with forensic imaging and evidence validation techniques. It reinforces the importance of maintaining evidence integrity through cryptographic hashing while showcasing the investigative workflow required to identify, preserve, analyze, and recover hidden information from digital media.

---

## 📄 License

This project is intended for educational and portfolio purposes.



