# Mass-Transfer-Lab
Xcos files with documentation.
CHEMICAL ENGINEERING

MASS TRANSFER LAB

LIST OF PRACTICALS:

1. Water Cooling Tower
2. Rotary Dryer
3. Design of Binary Distillation Column
4. ASTM Distillation
5. Column Tray Efficiency
6. Forced Draft Tray Dryer
7. Binary Vapor Liquid Equilibrium
8. Vapor in Air Diffusion
9. Mass Transfer with or without Chemical Reaction
10. Separating and Throttling Calorimeter
11. Flow Through Porous Media – I
12. Flow Through Porous Media – II


PREFACE:

Before going through the practicals, it is necessary that we understand the basic concepts of the software used here. 

First of all, the operating system in which the practical was made is Ubuntu 14.04. Operating system choice is based on user, and thus these practicals can work on any operating system provided the software Scilab is there. 

To download Scilab, 

Xcos is a graphical editor in Scilab used to design hybrid dynamical systems models. Models can be designed, loaded, saved, compiled and simulated. It contains various blocks which execute the function for which they are programmed.

Although it is not necessary to learn about every block in detail, it would be beneficial to understand the ones used in the practical simulation.

A basic block in xcos is either square or rectangular in shape. Some mathematical and electrical blocks are also available in circular or triangular shapes depending upon their use.

We are now going to look at the blocks that have been used in the practicals in brief.
For ease of understanding, 
the INPUT blocks have been coloured reddish pink  
the EXPRESSION or equation blocks have been coloured pale green
the mathematicals blocks or MATH BLOCK have been coloured pale yellow 
while the OUTPUT blocks have coloured turquiose blue.





This block is a constant value generator. All real numbers can be used as constants in this block. Numbers such as 'pi' or 'e' can also be used by adding a % sign infront of them. Ex: “%pi” or “%e”. In short it is an Input block

The Expression block applies the specified Scilab expressions to its input i.e It executes the equation written on it by utilizing values from input.


This block can realize any type of Scicos block. The function of the block is defined interactively using dialogue boxes and in Scilab language. During simulation, these instructions are interpreted by Scilab; the simulation of diagrams that include these types of blocks is slower. For more information see Scicos reference manual. 


This block opens up a new Xcos window for editing a new block diagram. This diagram describes the internal functions of the super block. 
Super block inputs and outputs (regular or event) are designated by special (input or output) blocks. 

This block displays the value of its unique input inside the block (in the diagram) during simulation. The value shown is numerical. In short it is an Output block.

When you start a simulation, Xcos open Scope windows (Graphs). The Scope block displays its input with respect to simulation time. The Scope block can have multiple axes (one per port); all axes have a common time range with independent y-axes. The Scope allows you to adjust the amount of time and the range of input values displayed. 


The unique output of this block generates a regular train of events that are scheduled by parameter Period in seconds. The starting date of events generation can be set in seconds with the Initialisation Time parameter. 


That block can be used to set the final time of the simulation. When that block is truely parametrized then the simulator will jump to the 'final integration time' defined in the Setup item of the simulate Menu from the time defined by the parameter 'Final simulation time' of the dialog box. That parameter can be a numerical value or a symbolic variable defined in the scicos context. 


The block performs addition of its three inputs. This block can add scalar or vector inputs.

 The output of that block is the element-wise product of its two input vectors. 


This block performs addition or subtraction on its scalar or vector inputs. 


This block computes element-wise multiplication or division of its vector inputs. The number of inputs and operation are specified with the Number of inputs or sign vector parameter. 


This block computes the absolute value of the elements of the input vector. Any value passed through it will give a positive output.


This block computes the square root of each element of the input matrix. It support double and complex data types 


This block computes the logarithm of the elements of the input vector. The user can fix the base with the parameter Basis. By default the block computes the natural logarithm (%e). The input and output port sizes are determined by the context. 


This block computes an output vector y with y[i]= u[i]^a where a is the real scalar given by the parameter to the power of and u the input. The input and output port sizes are determined by the compiler according to the connected blocks port sizes. 


The output of this block is a vector y with y[i]=a^u[i], where the parameter a is a positive scalar and u the input vector. The input and output port sizes are determined by the compiler. 


This special block is only used to add text at any point of the diagram window. It has no effect on the simulation. 
You can add this block directly by a mouse double click in a free part of the diagram. 
After addition, double click on the block and write your text. If you want more control on the text (font type, size or colors), a mouse right click shows a pop-up menu. Select the sub-menu item Edit... of the Format menu item. 









PRACTICAL 1: WATER COOLING TOWER

Introduction: 

Aim: To determine the overall heat transfer coefficient in a forced draft counter current cooling tower.
To measure Tower Characteristic parameter KV/L for various liquid and air flow rates (L/G) in a counter-current Forced draft Cooling Tower.

Technology used: Water from condensers and heat exchangers is usually cooled by an air stream in spray ponds or in Cooling Towers using natural draft or forced flow of the air. Mechanical draft towers are of the forced draft type, where the air is blown into the tower by a fan at the bottom. The forced draft materially reduces the effectiveness of the cooling.

Mind Map: 

Procedure: 

Observation:

Final Conclusion:



PRACTICAL 2: ROTARY DRYER

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 3: DESIGN OF BINARY DISTILLATION COLUMN

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 4: ASTM DISTILLATION

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 5: COLUMN TRAY EFFICIENCY

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 6: FORCED DRAFT TRAY DRYER

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 7: BINARY VAPOUR LIQUID EQUILIBRIUM

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 8: VAPOUR IN AIR DIFFUSION

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 9: MASS TRANSFER WITH AND WITHOUT CHEMICAL REACTION

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 10: SEPARATING AND THROTTLING CALORIMETER

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 11: FLOW THROUGH POROUS MEDIA-1

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:



PRACTICAL 12: FLOW THROUGH POROUS MEDIA-2

Introduction: 

Aim: 

Technology used: 

Mind Map: 

Procedure:

Observation:

Final Conclusion:
