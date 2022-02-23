# diamond-shape
n=int(input("enter a value:")) 

for i in range(1,n+1):         
for k in range(n-i,0,-1):                
print(" ",end=" ")        
 for j in range(1,i+1):             
   print(" *",end="   ")        
 print("\n") 
for i in range(n+1):           
for k in range(1,i):                 
print("  ",end=" ")         
  for j in range(n-i+1,0,-1):                
 print(" *",end="   ")          
 print("\n")                
