# Ex. No. 7 - SIMULATION OF PRE PROCESSING IN ADDITIVE MANUFACTURING
### DATE: 
## AIM:
### To simulate the Pre Processing for 3D printing.

## REQUIREMENTS:
### System - Windows 7 or higher, 1 GB RAM.

## PROCEDURE:
### Pre-processing encompasses the steps between design and printing. Process of 3D printing starts with designing in CAD. Then printer software slices 3D CAD file into layers. For each slice, the software converts the data into machine code that determines tool paths for the machine to follow. The various steps in pre-processing from design to printing are as follows:

### 1)	CAD File
### 2)	Conversion to STL a. Orientation b. Support Structure c. Slicing d. Path Planning

### 1. CAD File
### Every manufacturing process starts with the process of designing and as in any type of manufacturing, there are certain limitations to the materials and manufacturing processes that dictate how the product should be designed, 3D printing is no different. In 3d printing, characteristics of hardware, software, temperature, filament and many other factors play an important role in how a digital model translates into a printed object. Some of them are designed with a strong base, grain direction, overhung, wall thickness, round corners and tolerances.

### 2. Conversion to STL
### In order to check the interface of the object and make it reliable to 3d printers, conversion to STL file is required. It also facilitates other features like quick error check, bridging the gap between CAD platforms, exhibition purposes and 3D digitizer extension.

### a. Orientation:
### Orientation plays a vital role in the final product of 3d printing as it affects the part accuracy, manufacturing time, strength and surface finish. There are various orientations by which we can print the object such as vertically upward, vertically downward and in horizontal plane.

### b. Support Structure:
### Support structures are required where the objects are unable to get printed directly. Support structures help to guarantee the printability of a section during the 3D printing measure and also it can assist with forestalling part twisting, secure a section to the printing bed and guarantee that parts are joined to the fundamental body of the printed part.

### c. Slicing:
### The motive behind slicing a 3D model is to transform the model into guidelines for the 3D printer. To play out this errand, the slicing software isolates the item into numerous layers. It's classified "slicing" since it "slices" the 3D model to make numerous layers. After the layers have been made, the slicing software applies different qualities to every one of them.

### d. Path Planning:
### Path planning helps to improve the printed surface quality, shape accuracy and infill distribution quality. There are various ways for path planning which can be used to print the objects which may affect the following factors in objects like raster path, grid path, spiral path and zigzag path.

![image](https://github.com/Sellakumar1987/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/113594316/baef8515-67d7-4c96-accc-4ee88035c9e7)

### ●	All the processes related to pre-processing will be shown on the screen.
### ●	Select CAD file preparation from the visible list.
### ●	When the first process is selected then it will open in the blank space in the left side of the screen.
### ●	Select the options of process of pre-processing in the sequence in which they are shown.
### ●	If the user follows an incorrect sequence then a pop-up will appear on the screen showing the name of the process to be selected.

## OUTPUT:
### Step1:
### CAD File Preparation:

![241969009-40134164-60c2-42c5-a24b-1cbf317e9ac0](https://github.com/S-ARVIND01/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118707337/8a1ac439-84cc-40a2-8789-e37b630a9562)

### Explanation:
CAD file preparation is the process of converting a 3D CAD model into a format that can be used by an additive manufacturing (AM) printer. This process involves a number of steps, including:

i.) Checking the model for errors:
The first step is to check the model for any errors, such as missing or duplicate faces. These errors can cause problems during printing, so it is important to fix them before proceeding.

ii.) Generating support structures:
In some cases, support structures may be needed to support overhangs or other features of the model. Support structures are typically made of a different material than the model itself, and they are removed after printing.

iii.) Slicing the model:
The next step is to slice the model into a series of thin layers. This is done so that the printer can print the model one layer at a time.

iv.) Generating G-code:
Finally, G-code is generated for the printer. G-code is a programming language that tells the printer how to move and deposit material. Once these steps have been completed, the 3D model is ready to be printed.

### Step2:
### Conversion to STL:

![241975854-7f76b478-05f4-4b33-a1be-6f01becca869](https://github.com/S-ARVIND01/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118707337/516915f5-cc4d-491a-bc9e-2040196702d6)

### Explanation:
Conversion to STL is an important step in the additive manufacturing pre-processing workflow. It is used to ensure that the 3D model is in a format that can be understood by the printer. It also allows for the detection of errors in the model, such as missing or duplicate faces.Once the STL file has been created, it can be sent to the printer for production.

### Step3:
### Orientation:

![241976986-2026d6bb-f120-469a-9cee-a9cc83664112](https://github.com/S-ARVIND01/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118707337/eb2b94ea-23d1-4653-9855-5c1916149c71)

### Explanation:
Orientation in additive pre-processing is the process of determining the best orientation for a 3D model to be printed. The orientation of the model can have a significant impact on the quality, time, and cost of printing.

There are a number of factors to consider when determining the orientation of a model for printing, including:

Overhangs: Overhangs are areas of the model that extend away from the build platform. Overhangs can be difficult to print and may require support structures.
i.) Surface finish:
The orientation of the model can affect the surface finish of the printed object. Models that are oriented with their smooth surfaces facing up will have a better surface finish than models that are oriented with their rough surfaces facing up.

ii.) Strength:
The orientation of the model can affect the strength of the printed object. Models that are oriented with their load-bearing surfaces facing up will be stronger than models that are oriented with their load-bearing surfaces facing down.

iii.) Print time:
The orientation of the model can affect the print time. Models that are oriented in a way that minimizes the amount of support structures required will print faster than models that require a lot of support structures.

iv.) Material usage:
The orientation of the model can affect the amount of material used. Models that are oriented in a way that minimizes the amount of material required will print with less material waste than models that require a lot of material.

### Step4:
### Support structure:

![241977383-a478de8d-0a40-4459-a114-7846d8d02a3a](https://github.com/S-ARVIND01/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118707337/9d7ce9c4-4807-41ff-b79d-f81e48630c4c)

### Explanation:
Support structures are temporary structures that are used to support overhangs and other features of a 3D model during additive manufacturing (AM). Support structures are typically made of a different material than the model itself, and they are removed after printing.

There are a number of different types of support structures, including:

i.) Overhang supports:
Overhang supports are used to support overhangs, which are areas of the model that extend away from the build platform.

ii.) Bridging supports:
Bridging supports are used to support bridges, which are areas of the model that are printed between two unconnected supports.

iii.) Sacrificial supports:
Sacrificial supports are used to support features of the model that are difficult to print, such as thin walls or small features.

iv.) Snap-off supports:
Snap-off supports are designed to be easily removed from the model after printing.

The type of support structure that is used will depend on the specific features of the model and the AM process that is being used.

### Step5:
### Slicing:

![241979082-ab9e4c35-e706-4aad-b076-29a02f95afdb](https://github.com/S-ARVIND01/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118707337/5ce39f74-0c4f-44a9-8a3e-43f4b316363a)

### Explanation:
Slicing is a pre-processing step in additive manufacturing (AM) that converts a 3D model into a set of instructions that can be used to create a physical object. The slicing software divides the model into thin layers, and then generates a path for the printer to follow for each layer. The path includes information about the speed, temperature, and material flow that should be used for each layer.

There are a number of different slicing software programs available, each with its own strengths and weaknesses. Some of the most popular slicing programs include Cura, Slic3r, and Simplify3D. These programs are all free to download and use, and they offer a wide range of features and options.

### Step6:
### Path planning :

![243106589-5d551a4e-8232-48de-ac6b-08d2e13e8325](https://github.com/S-ARVIND01/Ex.-No.-7---SIMULATION-OF-PRE--PROCESSING-IN-ADDITIVE-MANUFACTURING/assets/118707337/edee7f0e-d82d-49b4-951f-82f64529c1dd)

### Explanation:
Path planning is a pre-processing step in additive manufacturing (AM) that determines the optimal path for the print head to follow when creating a 3D object. The path planner takes into account the geometry of the object, the properties of the material being used, and the capabilities of the printer.

The goal of path planning is to minimize the time and material required to create the object, while also ensuring that the object is printed with the desired accuracy and quality. Path planning can be a complex problem, and there is no single algorithm that can be used to solve it for all cases. However, there are a number of different methods that can be used, and the best method for a particular application will depend on the specific factors involved.

### Name: S ARVIND
### Register Number: 212222240012

## Result: 
### Thus the simulation on the Preprocessing in additive manufacturing is completed.
