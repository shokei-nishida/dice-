# dice-
１or2 を3個。　繰り返し処理されたし。

from vpython import* 

import random

a=random.randint(1,2)

b=random.randint(1,2 )

c=random.randint(1,2 )



if a==1:

    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    
    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.red)
    

elif a==2: 

    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),color=color.black) 
    
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),color=color.black)
    
    
#bに対応するサイコロ 

if b==1:

    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)
    
    cylinder(pos=vector(0-11,0,0),axis=vector(0,0,1),radius=1,color=color.red)
    
elif b==2:

    box(pos=vector(0-11,0,0),length=10,width=1,height=10,color=color.white)
    
    cylinder(pos=vector(2.5-11,2.5,0),axis=vector(0,0,1),color=color.black)
    
    cylinder(pos=vector(-2.5-11,-2.5,0),axis=vector(0,0,1),color=color.black)
  
    

if c==1:

    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)
    
    cylinder(pos=vector(0+11,0,0),axis=vector(0,0,1),radius=1,color=color.red)
    
elif c==2:

    box(pos=vector(0+11,0,0),length=10,width=1,height=10,color=color.white)
    
    cylinder(pos=vector(2.5+11,2.5,0),axis=vector(0,0,1),color=color.black)
    
    cylinder(pos=vector(-2.5+11,-2.5,0),axis=vector(0,0,1),color=color.black)
    
    
