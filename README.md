# Sentinel-API-For-VT
program written in Python that makes an API call to VirusTotal and pushes the results to Microsoft Sentinel
This program uses the requests library to make a POST request to the VirusTotal API for scanning the file and to Microsoft Sentinel for pushing the results.

You will need to replace your_api_key_here with your actual VirusTotal API key, path/to/file.ext with the path of the file you want to scan, your_workspace_id_here with your actual Microsoft Sentinel workspace id and your_workspace_key_here with your actual Microsoft Sentinel key.

Please note that this is just a basic example, you might want to handle errors, parse the json response, etc.

You can find more information about the VirusTotal API and how to use it in their documentation: https://developers.virustotal.com/v3.0/reference and Microsoft Sentinel documentation https://docs.microsoft.com/en-us/azure/sentinel/quickstart-send-data-portal
