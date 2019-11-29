# ODataTracker
Track and test the odata service requests with one time configuration.

# Description
This project tool allows to test the odata service and monitor the service behavior over the time. 
This tools helps for web software development team during development phase were UI and Odata service is tightly integrated and both UI and Odata service development goes in parallel.
If there is any change in odata service schema / request during odata development, this tool helps to recoginse that and throws error in report.

This needs to be configured one time with sample data and other information and can be triggered run periodically to track the issues in service. Configured Informatio is downloadable and can be shared with any to upload to run the tool for checking the service.

1. Screen 1 - Enter your service detail (Just ODATA Service URL), all other schema related information will be read from servcie and displayed to user. User can select what operation required from each entity / function import or any info from service in this screen.

![Alt_text](Page1.png?raw=true)

2. Screen 2 - Configure Sample data if an operation needs to be tested and monitored. Sample Data option is available to fill the fields automatically. Fields in this screen is read and rendered based on the metadata. These configurations can be downloaded to local system and shared with team members.

![Alt_text](page2.png?raw=true)


3. Screen 3 - Time to RUN. Screen to run the configured service requests and see the report in this screen. Running the requests needs to be done manually all the time to fetch the report. This screen also allows to correct the configurations made for an operation and rerun to check the service.

![Alt_text](page3.png?raw=true)



# Technology Used
This tool is done with SAPUI5 technology and configurations are required to be uploaded (if any valid configuration present) each time  (this can be avoided in future enhancement to reterive from backend based on role assignments).
