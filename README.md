# Task 2: Phishing Email Detection & Awareness System
Cybersecurity Internship . Future Interns . Task 2

Author: Kenza YOUSSI

## Overview
This repository contains a phishing email analysis project completed as part of the Futre Interns  cybersecurity training program. The project focuses on examining suspicious email samples to identify common phishing characteristics and document the analysis process using industry-inspired investigative practices.
The repository includes the email samples used during the investigation and a comprehensive report detailing the methodology, findings, and conclusions.

## Samples Used

| Sample | Pretented to be | Classification |
|--------|-------------|--------|
| sample_1004.eml | founder of P&F Industries | Phishing |
| sample_1017.eml | A nutritionist | Phishing |
| sample_1025.eml | Microsoft Accound | Phishing |

## Tools Used
- cat / sed / grep (read headers, fields, links)
- Google Admin Toolbox — Messageheader (SPF/DKIM/DMARC)
- VirusTotal, urlscan.io (domain/URL reputation)
- base64 decoder (reveal hidden links)
- Ubuntu Linux (isolated VM)

## Analyst Approach
The analysis was conducted using the following workflow:

- Collect the phishing email samples.
- Examine the email headers and metadata.
- Inspect the email content for suspicious elements.
- Identify phishing indicators, such as spoofed addresses, malicious links, and social engineering techniques.
- Compare the findings across all samples.
- Summarize the identified phishing characteristics.

## Ethical Statement
All analysis was passive and conducted on public samples for education only.

