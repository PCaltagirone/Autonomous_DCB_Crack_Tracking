# Autonomous DCB Crack Tracking

The purpose of the software is to streamline the process to obtain fracture toughness from double cantilever beam (DCB) tests. The program analyzes a series of images, looking for the crack tip. Once the crack length has been determined throughout the test, the program then generates compliance plots and calculates the fracture toughness using the modified beam theory as described in ASTM D5528. The fracture toughness is calculated using the three methods found in the standard: the MBT method, the compliance calibration (CC) method, and the modified compliance calibration (MCC) method. The fracture toughness and flexural modulus are exported to the excel file where the force and displacement data are obtained.

## Required Inputs
An excel file with the axial force and axial displacement as shown in Figure 1 must be placed in the same folder as the images. The force data should start in A4 and the displacement data should start in B4. The data must be synced between the force data and the image data for accurate results (the number of images should match the number of force/displacement data points). Image recording should stop once the crack is at its maximum length. 
 
Figure 1 - Excel data example
The other required inputs of the program are the initial crack length in mm, the specimen width in mm, the specimen thickness in mm, the sensitivity of the test (recommend 70-95), and whether an export of the crack length video is desired. These inputs are shown in Figure 2 below.
 
Figure 2 - Program input requirements
The images for one side of the sample should be in order in a single folder along with the data excel file.

## Image Examples
The images should be as clear as possible and the sides of the samples should contain no bubbles or unintended markings. A single black line should indicate where the start of the crack is (the end of the insert). The camera should be setup so that the full sample is shown within the frame, without the hinges in the picture. If desired, a small black marking can be made on the edge of the sample to indicate where to stop the test. An example of a good image frame setup is shown below in Figure 3.
 
Figure 3 - Sample frame example
4.	Program Exports
As stated above, the program exports the fracture toughness data, along with the crack length, to the excel file where the force and displacement data is pulled. The program exports to columns F-L as shown in Figure 4 below (columns C-E are unused data). 

 
Figure 4 - Export data
Additionally, the compliance plots and crack length are also exported as PNG files to the root image folder.
