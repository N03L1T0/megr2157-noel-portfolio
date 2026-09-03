# A2 – Truss Stress Analysis

## Objective

Successfully create and model a truss within defined parameters in a 3D CAD system, and calculate every variable through the required steps.

Research the likelyhood of different failure modes in the components of a truss.

## Analyze

Throughout this assignment, I was asked to derive, calculate, and model a truss system with specific values and materials given to me. For the truss designing, we were given a pin connection, roller connection, and two required pin joints within certain lengths, provided in this image: 

 ![Truss Parameters](trussparameters.png)

Within these given instructions, I created a simple truss system with 9 individual members, and 6 total connections, one roller, one pin connection, and two pin joints not including C and D. As I created my truss, I was tasked to make it statically determinate with a simple design. For the free body diagram, we were required to have a whole body diagram, as well as a diagram for each and every joint in the truss. Within this next image is the design I finalized and free body diagram for it:

![TRUSS DRAFT & FBD](IMG_6073.jpeg)

After designing the truss, I was tasked with both symbolically and numerically solving for each internal and reactional force on the truss to verify that it was in static equilibrium. Truthfully, I was slightly rusty in my method of sections, so I opted for doing the lengthy process of solving with the method of joints. Within this next image depicts the symbolic and numerical methods of solving for each internal and reactional force at every joint. This process took longer than I am willing to admit:

![truss method of joints](IMG_6074.jpeg)

With all of the statics work for the truss complete, it was time to start the solids portion; stress, cross sectional area, volume, mass and weight. The maximum force I used was 41.67 kilonewtons as calculated from my statics work. The material required was A500 steel, but the CAD system I used, CREO Parametric, did not have it in their system of materials. I opted to use galvanized steel as an alternative, as it was most similar to the yield strength of A500 steel in the system. I firstly listed every known variable and their values, as well as the unknowns that I needed to fully finish this problem. For a quick note, the length of the truss was determined through the addition of every member utilized, which gave me a value of 3.7 meters, as displayed in the image below:

![truss statics knowns and unknowns](IMG_6077.jpeg)

With this information, I was able to solve both symbolically and numerically for the cross-sectional area, and overall weight of the truss. Truthfully, I had trouble determining which equations to use, as I am currently taking solids alongside this course. I utilized my solids textbook to find all of the equations utilized for this part of the assignment. Through my solution, I ended up with a cross sectional area of 464.47 square millimeters. With this value, I calculated a total weight, with the use of the density, of 132.3 newtons. Below is my work shown for these values:

![truss solids solutions](IMG_6078.jpeg)

After the truss was completely accounted for, next was the pins. At this point I am about 4.5 hours into this assignment. This part alone took me around 3 hours to do. As I said before, I am currently taking solids alongside this course, and we had yet to go over shear strength. As of writing this, I have learned about shear strength and now understand it better than I did before. I firstly wrote down the knowns and unknowns of my problem, as well as the pin I chose and the free body diagram of joint A, which also included the maximum force on the truss of 41.67 kilonewtons. This is portrayed in the below image:

![pin shear FBD plus unknowns and knowns](IMG_6075.jpeg)

Alongside the final step of calculations for the pin, I scoured my statics textbook for equations necessary to solve for the cross-sectional area and total weight of the pins. I found the allowable shear strength with the safety factor and yield strength, which gave me a value of 42.5 KSI, which I converted into 293.04 MPa. Through this, I found the cross-sectional area with the max force divided by the allowable shear strength, which gave me a value of 142.2 square millimeters. With this information, I calculated the weight using the cross-sectional area, density, gravity constant, and length, I got a value of 0.2727 newtons per pin. For the length, I could not find a specified value for the length, so I assumed a length of 1 inch, converted to 25.4 millimeters. With this, I found the total weight of all 6 pins to 1.636 newtons. This is portrayed in the below image:

![pin shear calculations](IMG_6076.jpeg)

After all of these calculations were complete, it was time to recreate my truss and pins inside of CREO Parametric. Through tons of trial and error, I ended up with a final truss design that fit nearly exactly to the parameters of my calculated truss. For the length and width of the truss bars, I took the cross-sectional area of the truss and assumed it was square, which meant the width and height were the same, allowing me to come up with a value of 21.55 millimeters. With this value for length and width, I utilized the extrude tool to create the trapezoid outline of the truss, and specific lengths and angles of triangle sketches along the backside of the truss to remove material to fit the exact proportions of the truss. The angle I calculated from my statics work was 36.87 degrees, which was also a staple to help me fit exact lengths to have each truss member be 21.55mm by 21.55mm and have the right length. The truss took me around 1.5 hours to complete. With the galvanized steel material selected, the system calculated the mass of the truss to be 12.32 Kg, which is pretty close to my 13.49 Kg calculations. I left the small disparity up to the system's calculation method and the way the truss was structured with overlapping pieces.  Below is the finished product:
## Decide
_Which geometry did you select, and why? This is your first open design choice in the course — defend it._

## Communicate

