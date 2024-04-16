# CDAC_Academic_Project-ETour-

--> Guidlines To Copy Database Data in Current System : 
        File Name : ETourProjectDB
        Steps to copy Dummy Data : 
              1. Open MySQL Command Line Client panel.
              2. Then create new database with same name provided in application.json file in Spring Boot project file.
                  ( For current project DB name provided in application.json file is "ETourdb").
              3. Then switch to the newly created DB.
              4. Write below command on MySQL Command Line Client panel along with loacation of the "ETourProjectDB" file -
                    --> Command :  source <file location + file name (i.e ETourProjectDB)>
              5. Then hit enter. All required tables with dummy data is created in the newly created database in current machine.
