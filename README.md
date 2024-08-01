# Adds-the-X-Content-Type-Options-HTTP-header-with-the-value
PowerShell: Adds the X-Content-Type-Options HTTP header with the value

How the script works:
Define Header: Sets the header name and value.
Import Module: Loads the WebAdministration module required to manage IIS settings.
Get Existing Headers: Retrieves current HTTP response headers from the IIS configuration.
Check for Existing Header: Checks if the X-Content-Type-Options header already exists.
Add Header: If the header does not exist, it adds the X-Content-Type-Options: nosniff header.
Verify Header: Confirms that the header was successfully added by retrieving and checking the updated list of headers.

To run this script:

Save it to a .ps1 file, for example, Add-XContentTypeOptionsHeader.ps1.
Open a PowerShell window with administrative privileges.
Execute the script by running .\Add-XContentTypeOptionsHeader.ps1.
This script assumes that you have administrative privileges and that the WebAdministration module is available on your system.
