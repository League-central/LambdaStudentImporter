# LambdaStudentImporter
AWS Lambda function used to import League Student and Attendance data from Pike13.



1) Building the code:
<br>    a) The build requires the MAVEN Plug-in for Eclipse.
<br>    b) Copy the \src\main\resources\league-importer subdirectory to your Maven repository directory.
<br>    c) Select LambdaStudentImport project, right click to select "Run As", then select "Maven Build".
<br>    d) Set goals to 'package' and run the build.
<br>    e) The resulting jar file will be located in the target subdirectory.
<br>    f) For subsequent builds, first set goals=clean and run, then re-build with goals=package.

2) Uploading as AWS Lambda function:
<br>    a) Sign-in to League AWS account.
<br>    b) Under 'services', search for Lambda.
<br>    c) Under 'Functions' you should see 'StudentImport' and 'SalesForceImport'.
<br>    d) For each function, select the Upload button to upload the jar file you just created. Select Save.
