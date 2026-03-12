# 🧪 HashCalc — File Hash Verification Lab

> **Summary:** Completed a forensic hashing exercise using **HashCalc** to generate and compare cryptographic hash values for multiple files. The lab demonstrated how hashing is used to verify file integrity and identify identical files through hash comparison.

---

## 🎯 Objectives

- Generate cryptographic hash values using **HashCalc**
- Understand how hashing algorithms verify file integrity
- Compare hashes between files to identify **identical matches**
- Demonstrate that **renaming a file does not change its hash**
- Use hashing to detect **duplicate or identical files**

---

## 🛠 Environment

- **Tool Used:** HashCalc
- **Evidence Type:** Image files
- **Algorithms Used:** MD5, SHA1, RIPEMD160, CRC32

---

## 🚀 Workflow

### 1) Launch HashCalc

- Opened **HashCalc** to begin generating cryptographic hashes.


### 2) Generate Hash Values for Initial File
- The first image file was loaded into HashCalc to generate its hash values.
  - HashCalc generated multiple hash values for the file using the default hashing algorithms.

### 3) Rename File and Recalculate Hash
- The file was renamed and analyzed again in HashCalc.
  - ```bash
    Rename Image1.jpg → Statue_of_Liberty.jpg
- The resulting hash values were compared to verify whether renaming affected the file's integrity.

### 4) Analyze Additional Files
- Additional image files were loaded into HashCalc to generate their hash values. The generated hash values were then compared with the original file's hash values.

### 5) Compare Hash Values
- Hash values across the analyzed files were compared to determine whether any files were exact matches. Matching hash values indicate that two files are identical at the binary level.

### 6) Analyze Hash Dataset
- A collection of files within the provided dataset was processed to generate hash values. The resulting hashes were analyzed to identify duplicate or matching files.

---

## 🧠 Key Concept Demonstrated
- Cryptographic hashing produces a unique digital fingerprint of a file.
- If two files generate the same hash value using the same algorithm, they are identical copies of the same data, even if the filenames are different.
- Hashing is widely used in digital forensics to:
  - Verify evidence integrity
  - Confirm exact file matches
  - Detect duplicate or altered files

---

## 🧠 Skills Demonstrated
- Digital Forensics Fundamentals
- File Integrity Verification
- Cryptographic Hash Analysis
- Evidence Comparison Techniques
- Duplicate File Detection


