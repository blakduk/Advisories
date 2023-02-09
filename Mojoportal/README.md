# Mojoportal Multiple Vulnerabilities
############################################################<br />
<br />**[CVE-2023-24322] Reflected Cross-site Scripting (XSS)**
<br />- Description: A reflected Cross-site Scripting (XSS) vulnerability was discovered in the FileDialog.aspx component of mojoPortal v2.7 allows unauthenticated attackers to execute arbitrary web scripts or HTML via a crafted payload injected into the 'ed' and 'tbi' parameters.
<br />- Vulnerability Type: Cross-site Scripting (XSS)
<br />- Vendor of Product: i7MEDIA, LLC
<br />- Affected Product Code Base: Mojoportal - v2.7
<br />- Attack Type: Remote
<br />- Author: Blakduk
<br />- PoC: https://youtu.be/a-Fl5dfnDnc
<br />- Reference:
<br />https://www.mojoportal.com/
<br />https://github.com/i7MEDIA/mojoportal
<br /><br />############################################################<br />
<br />**[CVE-2023-24323] XML External Entity (XXE) injection**
<br />- Description: mojoPortal v2.7 was discovered to contain an authenticated XML external entity (XXE) injection vulnerability
<br />- Attack Vectors: To exploit this vulnerability, authenticated user must in "Content Administrators" or "Administrators" role or user must have "Edit Content and Style Templates" permission
<br />- Vulnerability Type: XML External Entity (XXE)
<br />- Vendor of Product: i7MEDIA, LLC
<br />- Affected Product Code Base: Mojoportal - v2.7
<br />- Attack Type: Remote
<br />- Author: Blakduk
<br />- PoC: https://youtu.be/GhMLACuFjL4
<br />- Reference:
<br />https://www.mojoportal.com/
<br />https://github.com/i7MEDIA/mojoportal
<br /><br />############################################################<br />
<br />**[CVE-2023-24687] Stored Cross-site Scripting (XSS)**
<br />- Description: mojoPortal v2.7 was discovered to contain a Stored Cross-site Scripting (XSS) vulnerability in the Company info Settings component. This vulnerability allows authenticated attackers to execute arbitrary web scripts or HTML via a crafted payload injected into the "txtCompanyName" parameter
<br />- Vulnerability Type: Cross-site Scripting (XSS)
<br />- Vendor of Product: i7MEDIA, LLC
<br />- Affected Product Code Base: Mojoportal - v2.7
<br />- Attack Type: Remote
<br />- Author: Blakduk
<br />- Reference:
<br />https://www.mojoportal.com/
<br />https://github.com/i7MEDIA/mojoportal
<br /><br />############################################################<br />
<br />**[CVE-2023-24688] User Registration Restriction Bypass**
<br />- Description: An issue in mojoPortal v2.7 allows unauthenticated attacker to register a new user even if "Allow User Registrations" feature is disabled
<br />- Vendor of Product: i7MEDIA, LLC
<br />- Affected Product Code Base: Mojoportal - v2.7
<br />- Attack Type: Remote
<br />- Author: Blakduk
<br />- PoC: https://youtu.be/-7UfEQ0XtLY
<br />- Reference:
<br />https://www.mojoportal.com/
<br />https://github.com/i7MEDIA/mojoportal
<br /><br />############################################################<br />
<br />**[CVE-2023-24689] Directory Traversal**
<br />- Description: An issue in mojoPortal v2.7 and below allows an authenticated attacker to list all css files inside the root path of the webserver via manipulation of the 's' paramter in ManageSkin.aspx
<br />- Vulnerability Type: Directory Traversal
<br />- Vendor of Product: i7MEDIA, LLC
<br />- Affected Product Code Base: Mojoportal - v2.7
<br />- Attack Type: Remote
<br />- Author: Blakduk
<br />- Reference:
<br />https://www.mojoportal.com/
<br />https://github.com/i7MEDIA/mojoportal
