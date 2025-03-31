## WAF Detector

The **WAF Detector** is a PowerShell tool designed to detect and identify Web Application Firewalls (WAFs) protecting web applications. It combines techniques from **Wappalyzer** and **wafw00f** to deliver accurate results.

### Usage

To use the WAF Detector, execute the following command in PowerShell:

```powershell

powershell -ExecutionPolicy Bypass -File ./WAF-Detector.ps1

```

### Examples

**Detect WAF on a website:**

```powershell

./WAF-Detector.ps1 -Url https://example.com

```

**Detect WAF and save results to a file:**

```powershell

./WAF-Detector.ps1 -Url https://example.com -OutputFile results.json

```

