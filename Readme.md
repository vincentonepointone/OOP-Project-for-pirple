1.  Object Oriented Programming
    OOP is representing real world thing and their data in Object
    These Objects have methods and proporties we can call

2.  An OOP Patern would be better for tasks that need structured 
    data and methods that have to be reused multiple times
    Changin a color of a dom element does not need to have it own
    function an object to work well. But when we handle data and 
    functions in a repetative manner that can be structured OOP 
    works bettern create one contructor and multipe Real world 
    object or Data can be manipulated with one object 


3.  The Project I have chosen is an application "Catch of the Day
    Score Board" that would rank fishermans' Fish in wheight, type 
    of fish, time it was coucht and where the specific fishermen 
    ranks on a score board.

    From the users perspective: 
    1. A user Signs up
       - 1.1 Information that is entered are:
           - a. Name
           - b. Last Name
           - c. Gender
           - d. Type of fishermen
               - d.1. Fly fisherman
               - d.2. Bass fisherman
               - d.3. Carp fisherman
               - d.4. Specimen fisherman
        1.2 What methods will be available to call on data?
          - a. Create a User => createUser();

    2. A user Enters a Catch
       - 2.1 Information that is entered are:
           - a. Name of user
           - b. Type of Fisherman
           - c. Type of fish
           - d. Wheight of fish
       - 2.2 What method will be available to call on data?
           - a. Create new user based on type of fisherman and add name wheight of fish 
             - to that class of fishermans score board => addToScoreBoard();

---

### reAdder object inherit properties from fisherman object
                                                                                                                   
                   >Fisherman Object                                       reAdder Object                        
                  +--------------------------------------+              +-----------------------------------------+
                  |  Value added to new Fisherman Obj    |              |  Value added to scoreAdder Obj          |
                  |--------------------------------------|              |---------------------------------------- |
                  |  this.name = name;                   |              |  this.name = name;                      |
                  |  this.lastName = lastName;           |              |  this.fishType = fishType;              |
                  |  this.gender = gender;               |              |  this.fisherType = fisherType;          |
                  |  this.type  = type;                  |              |  this.whieght = wheightOfFish;          |
                  |                                      |              |  this.time = getTime();                 |
                  |--------------------------------------|              |-----------------------------------------|
                  |  Metdods to be called                |              |  Methods to be called                   |
                  |--------------------------------------|              |-----------------------------------------|
                  |  newUser = () => {                   |              |   let score = new scoreAdder(name, type,|
                  |    {this.name} = this.name this.age.......          |   fishtype, wheight, time)              |
                  |  }                                   |              |                                         |
                  |                                      |              |// add score to document //              |
                  |                                      |              |                                         |
                  |                                      |              |                                         |
                  |                                      |              |                                         |
                  |                                      |              |                                         |
                  +--------------------------------------+              +-----------------------------------------+


                      -\                                                                             
                    -/  -\                                                                           
                -------------                                                                    
                    | - |                     -+-                                                    
                    +---+                   -/   -\                                                  
                    |-/|                  -/       --\                                               
                    |--|-\              -/            -\                                             
                    |--|  ---\         /                --\                                          
                    | |||---\  ---\   -/                    --\                                       
                    | ||||   ---\  --/                         -\                                     
                    /\ |||       --/                             --\                                  
                     |\| |/          /                             --\                               
                    \ -\||                                             -\                             
                    |||/|                                                --\                          
                    |||||                                                   --\                       
                    \||||                                                      -\                     
                    ||||                                                        --\                  
                    ||||                                                           --\               
                    ||||                                                              -\             
                    ||||                                                                --\          
                    |-||                                                                   --\       
                    +-----+                                                                   -\     
                    +-----+                                                                     --\  
                                                                                                    --
                                                                                                    
                                                                                                                               
                                                                                                                               