# dice-
if a==1:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.red)
elif a==2:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
elif a==3:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
elif a==4:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
elif a==5:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(0,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
else:
    box(pos=vector(0,0,0),length=10,width=1,height=10,color=color.white)
    cylinder(pos=vector(2.5,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,0,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,-2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
    cylinder(pos=vector(-2.5,2.5,0),axis=vector(0,0,1),radius=1,color=color.black)
