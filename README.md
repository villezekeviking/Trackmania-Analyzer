# Trackmania-Analyzer
This is a Power BI project for the racing game Trackmania in which you analyze the replay files.
You will need Power BI Desktop from the Microsoft Store for this. This is a free software from Microsoft.
https://www.microsoft.com/store/productid/9NTXR16HNW1T?ocid=pdpshare


Download the files from this repo.
Open CMD and CD to the GBXToJSON Extractor folder
Run the GBXToJSON.exe like this:
GBXToJSON.exe "C:\Path\Replay.gbx" "C:\Path\Input"

When all you replay files are converted from GBX to JSON, make sure they are named to whatever you want them to be shown as in the report.
Doubble click on the Trackmania Replay Analyzer.pbit file to open it in Power BI Desktop.
The report will ask for a seach path to the Input folder that you used above to store the json-files in. Type it in and do not use a closing \ (just like in the example above).
Sit back and wait for Power BI to generate your report and start analyzing!

If you want to add new runs, convert them and put the JSON file in the same input folder as the rest of the files and click "Refresh" in Power BI to collect the addiotional information.


You can find more information on how the use the report in this blog post:
https://www.villezekeviking.com/trackmania-analyzer-part-1-using-the-report/
