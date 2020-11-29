# Database Testing: tSQLt unit testing and Azure DevOps

Please [view and download ](https://github.com/Gwayaboy/DatabaseTesting/blob/main/0%20-%20Content/DatabateTestingWorkshop.pdf) Slide deck

## Agenda

1. **SQL Server Testing**
    - Core Concepts
    - SSMS, tSQLt & additional tooling
2. **Azure Pipeline Integration**
    - Understanding CI/CD Flow for SQL Automated SQL Server tests
    - Azure Pipeline Demo


## Module 1: SQL Server Testing with tSQLT

  ### Pre-requisites
    
1. Local or remote (on Azure VM or on-premises) access to a SQL Server instance with administrator rights  
2. [SQL Server Management Studio (SSMS)](https://aka.ms/ssmsfullsetup)    
3. [Git Bash](https://git-scm.com/download/win) and (optionally) [  Redgate's sql tool belt 28 day trial version ](https://www.red-gate.com/products/sql-development/sql-test/trial/) for SSMS (choose SQL Test & SQL Source control)

  #### Exercise 1: Implementing your first tSQLt unit test

  1. Clone this repository to get you started using gitbash or redgate's SQL Source Control at https://github.com/Gwayaboy/DatabaseTesting.git to your local dev folder (for example ```C:\dev```)
      - Click on the "Clone or download" button
      - Clone the repository direclty with SSMS and  SQL Source Control       
        or
      - (If you have git bash) navigate to your local dev folder (```cd /c/dev/```), copy and execute execute the following command :
        ```bash        
        git clone https://github.com/Gwayaboy/DatabaseTesting.git
        ```        
      - Alternatively [download as a zip file](https://github.com/Gwayaboy/DatabaseTesting/archive/main.zip) to your local drive 

  2. Set up customer management database
        - Execute [Database Setup.sql](https://github.com/Gwayaboy/DatabaseTesting/blob/main/1%20-%20tSQlt_UnitTests/01%20-%20Setup%20DB/Database%20Setup.sql)
        - Execute [Populate Data.sql](https://github.com/Gwayaboy/DatabaseTesting/blob/main/1%20-%20tSQlt_UnitTests/01%20-%20Setup%20DB/Populate%20Data.sql)
    
  2. Install tSQLt on customer management database
        - Download and unzip [latest tSQLt release (tSQLt_V1.0.7597.5637)](http://tsqlt.org/download/tsqlt/)
        - Open and run tSQLt.class against the CustomerManagement Database 
        





