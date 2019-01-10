Problem Descrption: 


In this project we are planning to create a buying experience for user using unity.
What we plan to do is create a augemented GUI for placing of furniture.
the user will select the typw of furnitue to place and select it from navigation panel and a augmented furniture will be placed at the location.


Approach:


1. To create augmented reality we will be using unity engine.

2. A user can place a request for a furniture from the list in the naviation
   The furniture will be selected and will be placed in the virtual environment
   The furtinure will be placed untill it is removed

3. The model for the requested type of furniture will be downloaded from the aws server

4. User can also click a picture of the BluePrint of the house(Rectangular right now)

5. this image will be send to the aws where different machine learning functions will be applied to it

6. Using open cv we will mark the edges of the image
  a) funtion to be used => cv2.Canny()
  b)


7. A CNN  model will be trained to detect edges .

8. Model will be trained to detect four types of edges.

9. All edges will be detected and and a sorted Nx3 dimensional vector will be created.
   where N is the number of edges and 3 dimension are for the x and y coordinate and 3rd coloumn will the type of the edge

10. this vector will be passed to unity.




   This image will be used to create a total virtual reality around user where user can place his furniture




