# EX.No.-2.2 CREATE A 3D SOLID MODEL FROM ISOMETRIC DRAWING
## AIM: 

To create a 3Dmodel from the given isometric drawing using fusion 360 tool. 

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE: 
1. Open Autodesk Fusion and create a new design. Select Create Sketch from the Sketch section and choose the top plane as the sketching plane.
2. After entering the sketch environment, select the Line tool from the Sketch toolbar. Draw the initial horizontal and vertical reference lines according to the given drawing and apply the required dimensions using the Sketch Dimension tool.
3. Using the slot constraing in create, draw a slot of 56mm x 36mm dimensions using center to center slot.

<img width="471" height="540" alt="slot" src="https://github.com/user-attachments/assets/98c6c155-fe5a-452b-be6b-f70354ea231f" />

4. Now, select one of the centers and draw a circle of Ø16mm using the circle constraint.

<img width="536" height="443" alt="circlr" src="https://github.com/user-attachments/assets/df3b6611-6aeb-4b2c-95df-c1fe3db90d65" />

5. After drawing the circle, use the mirror constraint to mirror the circle onto the other side on the slot.

<img width="270" height="432" alt="mirror" src="https://github.com/user-attachments/assets/643d086f-2b42-4903-b528-f9b80e6bd1bf" />
<img width="311" height="160" alt="mirror2" src="https://github.com/user-attachments/assets/6a93faa9-4df6-4e45-a2e4-106e8c391fae" />

6. Now, give finish sketch and exit the sketching environment. After exiting now go to extrude constraint and select everything except the two circle. Now extrude the selected sketch to 8mm.

<img width="653" height="773" alt="extrude" src="https://github.com/user-attachments/assets/850a1489-02f9-466d-81fb-cfe67303191b" />

7. Now, enter the sketching environment again and choose the top view. Using mid-point line constraint draw a line of 40mm on the edge on the slot we created previously. Draw two parallel 10mm line on each of the 40mm line and connect them on the other side.

<img width="697" height="540" alt="midpoint line" src="https://github.com/user-attachments/assets/bcaa2c08-066c-4ffb-b01c-8e2dae0839f4" />

8. Now, click finish sketch and exit the sketching environment. Go to extrude constraint and select the rectangle we just drew and extrude it by 32mm.
9. Enter the sketching environment again and draw a 12mm line on the other edge of the base, using the mid-point line constraint. Draw two perpendicular lines on each ends of the 12mm line, connecting the 12mm line and 40mm line on the other side.
10. Exit the sketching environment again and select the rectangle we just drew and extrude it by 32mm.
11. Now use the chamfer constraint on the rectangle with 12mm edge and drag it down until both edges of the base and the rectangle of 40mmx10mm meet. Select chamfer type into two distance.

<img width="667" height="693" alt="chamfer1" src="https://github.com/user-attachments/assets/7a66c8df-23af-426f-8894-17d2590d3c8c" />
<img width="502" height="435" alt="two distance chamfer" src="https://github.com/user-attachments/assets/fcffa4e2-739e-4362-a9ca-a94b5c499a7e" />

12. Again enter the sketching environment, draw two concentric circles of each Ø30mm and Ø20mm. The circles should be 32mm away from 40mm edge. 
13. Now, use the line constraint and draw a line connecting the ends of the 40mm line to the circle. Use the tangent constraint to connect the circle and the line.

<img width="242" height="381" alt="tangent" src="https://github.com/user-attachments/assets/487b3968-0d36-482d-a9dc-8c6467c72adf" />

14. Now, trim the extra length of the line.

<img width="208" height="261" alt="trim" src="https://github.com/user-attachments/assets/6febfd9b-ad1c-4cfb-a437-176de9c2801e" />

15. fter trimming, mirror that line to the other side of the circle. Click finish sketch and exit the sketching environment.
16. Select the entire sketch and extrude it to 10mm. Now select only the ring formed by the concentric circles and extrude by another 10mm.
17. Now, save the design and go to file and click new, then drawing and select manual.
18. Once you go the drawing file, select front view for base view and place it on the blank page. Repeat this step for top view, side view and isometric view.
19. After these views are place enter the required measurements on the drawing. And save the file once this step is done.
## OUTPUT:

<img width="975" height="687" alt="2 2 drawing" src="https://github.com/user-attachments/assets/6f082995-97d1-47e0-8816-5c19ed702e86" />
<img width="572" height="611" alt="exp2 2" src="https://github.com/user-attachments/assets/647307f4-3878-466b-a540-6a994653bdf1" />


## RESULT: 
Thus, the 3D model is created from given isometric drawing.


