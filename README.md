# Mini-project-Vaccine-scheduling-and-hospital-record-management-
Assumption : 30 min per person for vaccination
             5 hospitals availabel
             Considered duration of project =1 day
Data Structure used: Array and linked list             
Project is divided into two parts:
1.Admin
2.User
#Admin privilages:
  Admin can update count of availabel vaccine in a particular hospital
  know number of patients in a hospital
  can see patient detail from every hospital and individual patient details as well
#User privilages:
  User can register for vaccination
  View its time slot
  Cancel registration
  
  Structure of project:
   Each index of array points to a list of patients stored in linked list.
   
   
   Array of objects:
  ------------------------------------------------------------------------------------------------------------------------------------------------------------
  |                              |                              |                              |                              |                              |
  |                              |                              |                              |                              |                              |    
  |                              |                              |                              |                              |                              |
  |         HOPITAL-1            |          HOPITAL-2           |         HOPITAL-3            |        HOPITAL-4             |            HOPITAL-5         | 
  |                              |                              |                              |                              |                              |
  |                              |                              |                              |                              |                              | 
  ------------------------------------------------------------------------------------------------------------------------------------------------------------
                |                                |                              |                               |                            |
                |                                |                              |                               |                            |
                |                                |                              |                               |                            |
                |                                |                              |                               |                            |
                V                                V                              V                               V                            V
                V  Node                          V Node                         V Node                          V Node                       V Node 
        --------------------            --------------------           --------------------           --------------------         --------------------                                                                                                                 
        |                  |            |                  |           |                  |           |                  |         |                  |                                                                                  
        |                  |            |                  |           |                  |           |                  |         |                  |                                                                                 
        |                  |            |                  |           |                  |           |                  |         |                  |                                                                                  
        |                  |            |                  |           |                  |           |                  |         |                  |                                                                                  
        |                  |            |                  |           |                  |           |                  |         |                  |                                                                                      
        --------------------            --------------------           --------------------           --------------------         --------------------                                                                                                   
        |                  |            |                  |           |                  |           |                  |         |                  |                                                                                          
        |       NULL       |            |       NULL       |           |       NULL       |           |       NULL       |         |        NULL      |                                                                                            
        |                  |            |                  |           |                  |           |                  |         |                  |                                                                                    
        --------------------            --------------------           --------------------           --------------------         --------------------                                                                                                       
