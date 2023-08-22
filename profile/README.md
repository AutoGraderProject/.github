```import wce.tyIt.teamTheBest.*;

public class AutoGrader{

    public AutoGrader(){
    
    	 Frontend=Html Css Bootstrap;
    	 ServerProgramming= NodeJS and express;
    	 DataBase=MongoDB;
    	 Authentication=undefined;
    	 HostingPlatform=undefined;
   
    	 }
    	 
    Modules-1 (Admin){
    
        UIScreens(){
        
            0. Pre-requisite
                - Color Theme
                - Logo
                - Header & Footer
                - NavBar
                - common landing page with student and admin option

            1. LoginScreen
                - Form with Username password and submit button
                - Link to forget Password

            2. DashBoard
                - Number of Stuents Registered
                - Total Number of visitors
                - Total number of Entries
                - Optional - Graph for Analysis

            3. Records
                - Form with PRN field to search Student.
                - After search
                    > Details Visible are:
                        1. Name
                        2. Department
                        3. Current Year of Study
                        4. Total Number of Assesment taken
                        5. Link to List of Proofs Submitted.
                        6. Techno-Socio Activity Index.
                        7. Current Status : Approve/Not Approved(Default)/Invalid

            4. Open Requests
                - List of Open Request 
                - After clicking each Request 
                    > Details Visible: 
                        1. Name
                        2. Department
                        3. Current Year of Study
                        4. Link to List of Proofs Submitted.
                        5. Action: Approve/Invalid
                            if(Approve){
                                update Index;
                            } 
            
            5. Modify Questions{
                - View Categories as radio Button.(show relevent questions when selected).
                - option to edit questions with options and option Weight.
            }
            
            6. Logout option
        }
    }
    
    Module -2 (Student){
    
    	UIScreen(){
    	
    	0. Pre requisite
    		- Same header and footer as admin module
    		- same color theme
    		- common landing page with student and admin option
    		
    	1. Login Screen/Register Screen
    		- Registration details- Name,PRN,Branch, DOB, Email, Password, Graduation Year.
		- Form with Username password and submit button
                - Link to forget Password
        
        2. DashBoard
        	- Total Number of test taken
        	- Student Score index
        	- (more suggestions required)
        	
        3. Assesment tab
        	- show categories to select test
        	- Continue option
        
		3A. Show Test Guidelines
			- start Test button.
		
		3B. Test Scrren
			- Question Number
			- Question 
			- Question Options
			- Next and Previous Options
			- End of test Upload certificate/Proof option.
			- Everything is mandatory.
			
		3C. Confirm screen
			- CheckBox to confirm question and submit (Request to approve sent to admin).
	
	4. Uploads
		- List of Uploaded Certificates.
	
	5. Logout option.
        
    }
}
```
