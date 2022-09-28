# User-stories

1. Login functionalities: Naba 

	1.1 User credentials - username and password
	
	1.2 UI Design - SwiftUI/Storyboard
	
	1.3 API - service url, payload, response(POSTMAN tool to validate the API response)
	
	1.4 Business logic to consume API - API Handler
	
	1.4 Create model
	
	1.5 Parse response to Model
	
	1.6 Error handling - Try catch, http response code(200, 404, 204, 401)
	
	1.7 Add validation for username and password 
	
	1.8 Business logic to bind data
  
  	1.9 Navigation handling 
	
	1.10 Maintain user session - storing username and password in keychain
  
  	1.11 Unit testing

2. Forgot password: Naba
  
  2.1 UI Design - SwiftUI/Storyboard
    
    2.1.1 Two fields - enter new password, re-enter new password
  
  2.2 Error handling - New password and re-enter new password fields match, either one of them is not empty when clicking on the save button, verify new    password is not the same as old password
  
  2.3 Update password to new password in the login database
  
  2.4 Update user session - storing new password in keychain
  
  2.5 Unit testing
  
3. Signup 

4. Displying list of issues
