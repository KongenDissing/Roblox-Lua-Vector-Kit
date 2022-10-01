# Roblox-Lua-Vector-Kit
This is a simple vector kit, which can help you with easy vector calculations within roblox. This will help you focus on the more important things, and not focus on all the math. 


For using my vector kid, I'll go over how to set it up, and a few functions.


You will start by making the VectorKit script into a ModuleScript. 
After you make another moduleScript, which should be a child of the VectorKit script. This script shoud contain the content from the class script


The first thing you should do, is to require the "VectorKit" module. This can be done the following way:

local VectorKid = require(path)

I put in "Path", because you might have your module stored somewhere else than others, note that the name of the variable doesn't have to be VectorKid.

Now we will make the varible, this can be done, the following way:

local newVector = VectorKid(x,y,z)

If you are working with a 2d vector, just leave the z parameter empty.

Now that we basicly have everything sat up, let's go over the function



newVector:create2Vectors(x,y,z) -- Function

This is used to create a second vector. It takes in three parameters, x, y and z. Again, leave the z parameter blank if working with 2d vectors.
You can access it the following way: 


Note that your varible might not be named "newVector"

newVector:GetMagnitude()
This will return the magnite of the vector you sat as the value of newVector

newVector:G:Get2Magnitude()
This will This will return the magnite of the vector you sat as the value of the second vector.

newVector:ScalarMultiplier(x,y,z)
This will multiply your vector with a scaler. Note that this won't change the vector itself, but just return what the new vector would look like.

newVector:Scalar2Multiplier(x,y,z)
This will multiply your second vector with a scaler. Note that this won't change the vector itself, but just return what the new vector would look like.

newVector:vectorSum(x,y,z)
This will return the sum of the your vector, and the values you typed in.

newVector:vector2Sum(x,y,z)
This will return the sum of the your second vector, and the values you typed in.
