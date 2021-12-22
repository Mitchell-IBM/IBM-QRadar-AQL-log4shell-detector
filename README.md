# IBM-QRadar-AQL-log4shell-detector
IBM QRadar AQL function based on https://github.com/Neo23x0/log4shell-detector and uses the MIT License.

Please find further details on implementing this custom function here: https://community.ibm.com/community/user/security/blogs/adam-frank/2021/12/13/detection-of-log4shell-using-qradar

**Note: QRadar will log the JavaScript into the SIEM. This may produce false positives at the initial point of uploading the AQL function on the strings in the code that are being monitored for. Please ignore these messages when they occur - you will likely see them as the QRadar IP being the source and destination addresses. **

# Building An AQL Function
In order to build your own AQL function, there are some useful resources to review to get you started on your journey of increasing your Advanced Search capabilities.

Official Documentation
- Custom AQL Functions Overview (Including Examples) [https://www.ibm.com/docs/en/qradar-common?topic=1-custom-aql-functions]
- AQL Function XML Required Fields [https://www.ibm.com/docs/en/qradar-common?topic=functions-custom-aql-function-fields]
- JavaScript Utilities Already Available [https://www.ibm.com/docs/en/qradar-common?topic=functions-custom-aql-function-utilities]

Jose Bravo's AQL Function Video:
- AQL Custom Functions (2021) & Log4J Example [SOON]
- AQL Custom Functions (2016) [https://www.youtube.com/watch?v=6z8zjXw-xE4]

