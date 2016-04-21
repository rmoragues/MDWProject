#Data Flow Diagram Dictionary

###External Entities:
  
  *Corporate Manager* - Individual who will request risk evaluations from the risk database and set policies for those evaluations.
  
  *Corporate Developer* - Individual(s) who submit into the external source.
  
  *National Vulnerability Database* - Database containing all risks associated with any external sources.
  

###Databases: 
  
  *NIST CPE Information* - Database containing known CPEs.
  
  *Risk DB* - Database that will contain the risks associated with the company.
  
  *Policy Database* - Holds existing and new policy information.

###Processes:
  
  *Code Streams* - Passes code to be checked and verified, as well as to send CPE information.
  
  *Seperate CPE Information* - Seperates the information to be sent into the NIST database.
  
  *Manage Manifest Information* - Carries data downstream to the other processes.
  
  *Manage Project Information* - Sends out the correct information regarding the current project.
  
  *Policies Generator* - Allows the Corporate Manager to create and edit policies for projects.
  
  *Manage CPE Information* - Sends the CPE files from the National Vulnerability Database into the NIST DB. 
  
  *Verify CPE Available* - Verifies that the same CPE information does not go into the Risk DB.
  

###Data Flows:
  
  *File* - A container holding code.
  
  *File Query* - Files containing seperated CPE information.
  
  *Package* - A container holding multiple files.
  
  *Package Query* - A request for information corresponding to particular package.
  
  *CPE Information* - Risk information from the NIST database corresponding to particular code.
  
  *CPE File* - A container holding CPE information.
  
  *CPE Request* - A request for information corresponding to particular CPE.
  
  *CPE Response* - The response to a CPE request, returning CPE information.
  
  *Project Info Request* - Request of data made by the Corporate Manager.
  
  *Project Info Response* - The Response to the data the Corporate Manager made.
  
  *Package and CPE Information* - Information that will be sent to be verified against existing data.
  
  *Package Information Response* - Response of packages containing risks
  
  *Package Information Request* - Request of packages for known risks
  
  *New Policy Data* - New policies to be implemented into the project.
  
  *Policy Verification* - New policies that need to be verified.
  
  *New Policy Information* - Policy information that will be sent into the database to be recorded.
  
  *Policy Information Request* - Information about policies that the Corporate Manager asks for.
  
  *Policy Information Response* - The return of the available policies in place.
  
  
