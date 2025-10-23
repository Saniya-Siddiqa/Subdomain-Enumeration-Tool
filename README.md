# Subdomain Enumeration Tool

**Project:** Subdomain Enumeration Tool  
**Author:** Saniya Siddiqa  
**Organization:** InLighn Tech  
**Language:** Python 3

## Overview
This project automates the process of discovering valid subdomains for a given domain.  
It reads potential subdomains from a file and checks their availability using HTTP requests.  
Multithreading is used to speed up the process.

## Features
- Detects active subdomains for a target domain.
- Uses multithreading to scan faster.
- Saves discovered subdomains to a text file.

## Files in this Repository
- `subdomain_enum.py` — main Python script  
- `subdomains.txt` — list of subdomains (optional)  
- `FIG1_vscode.png` — screenshot of the program running in VS Code  

## How to Run
1. Install dependencies:  
2. Update the domain in the script (e.g., `domain = 'youtube.com'`).
3. Add subdomains (one per line) in `subdomains.txt`.
4. Run the script:  

## Output
Discovered subdomains are printed in the console and saved to `discovered_subdomains.txt`.

## FIG
Refer to the `FIG1_vscode.png` file to see an example output from VS Code.

## Note
Use this tool only for authorized testing or educational purposes.
