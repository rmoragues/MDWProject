#Data Flow Diagram Dictionary

###External Entities:
  
  ##### Corporate Manager - Individual who will request risk evaluations from the risk database and set policies for those evaluations.
  
  ##### Corporate Developer - Individual(s) who submit into the external source.
  
  ##### National Vulnerability Database - Database containing all risks associated with any external sources.
  

###Databases: 
  
  #####NIST CPE Information - Database containing known CPEs.
  
  #####Risk DB - Database that will contain the risks associated with the company.
  

Processes:
  
  Code Streams - Passes code to be checked and verified, as well as to send CPE information.
  
  Seperate CPE Information - Seperates the information to be sent into the NIST database.
  
  Verify Project Information -
  
  Manage Project Information -
  
  Policies Generator - Allows the Corporate Manager to create and edit policies for projects.
  
  Manage CPE Information -
  
  Verify CPE Available -
  

Data Flows:
  
  File - a container holding code
  
  Package - a container holding multiple files
  
  Package Query - a request for information corresponding to particular package
  
  CPE Information - risk information from the NIST database corresponding to particular code
  
  CPE File - a container holding CPE information
  
  CPE Request - a request for information corresponding to particular CPE
  
  CPE Response - the response to a CPE request, returning CPE information
  
  Project Info Request - 
  
  Project Info Response - 
  
  Package and CPE Information -
  
  Package Information Response - 
  
  Package Information Request - 
  
  
  
