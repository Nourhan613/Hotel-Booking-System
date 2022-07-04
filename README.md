# Hotel-Booking-System
##  DESCRIPTION:  
1. The hotel has EMPLOYEES      
   - Each employee has a name, social security number, address, salary, sex, job, and birthdate.  
2. Many employees serve customers.    
   - Each customer is described by address, name, unique ID, sex, unique social security number, email, birthdate, and multiple phone numbers. We also keep track of the direct supervisor of each employee. 
3. Each customer may have several dependents.    
   - For each dependent, we keep track of their name, sex, birth date, and relationship to the customer for insurance purposes. 
## One customer can book many rooms, but one room can be booked by many customers at different times, and room prices are dependent on the class and type of the room that the customer booked.       
- Each Room is described by a unique number, unique password, status, type, level, price, view, and class type.         
- We keep track of the number of rooms that the customer booked them and the date(start, end)     
- All the payments of the customer will be in one bill and one bill should be paid by one customer.      
- Each bill has a unique ID and may have a discount.  
- We keep track of the total price and pay time.   

## Er diagram of the project 
![image](https://drive.google.com/uc?export=view&amp;id=1kl00zC3d3Q5r1iiZ8tm3IDVsYpz_5bLZ) 

## Schema of the project 
![image](https://drive.google.com/uc?export=view&amp;id=1i6ijN5leX0vQYpfMaa4LpzmlAWHN4NCA) 

## Mapping
There are 3 different types of relations :
- one-to-one.  
- one-to-many.  
- many-to-many.   

![image](https://drive.google.com/uc?export=view&amp;id=1erSoj7krWmFXGKM9tGwTyM12f-CAGq8l)
