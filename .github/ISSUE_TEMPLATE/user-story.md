**As a** client  
**I need** to retrieve my account details  
**So that** I can see my personal information stored in the system  

### Details and Assumptions
  * The client must be authenticated to view their account details.
  
### Acceptance Criteria     
  ```gherkin
  Given the client is logged in
  When they request their account details
  Then they should see their name, address, and other relevant information
