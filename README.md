Problem Statement: 

3D AR(Agumented Reality) buying experience

Problem Descrption: 

In this project we are planning to create a buying experience for user using unity.
What we plan to do is create a augemented GUI for placing of furniture.
the user will select the typw of furnitue to place and select it from navigation panel and a augmented furniture will be placed at the location.

Introduction:

While buying furniture online customers does not have a way to visualize how the product will look within content of their home. When plan to create a buying experience for
user using Unity which provides users a way to visualize and experience the look and feel of products. Our application will allow user to choose from a variety of products to view in their home/office setting using AR(Augmented Reality) and VR(Virtual Reality) services provided by us in a simple,elegant graphical user interface, all within their mobile phone.

User can select the type, model, design and colour of the furniture from navigation panel and that furniture will be augmented at the location of the choice. Ability to add/remove multiple objects and change colour and design even after placing them will give user a fully customizable AR buying experience. 

Our VR facility will improve and allow user to get an complete immersive experience. User can capture picture of the blueprint of their house and we will create VR environment according to the given location. Then user can use all other features as our AR buying system and can get an actual immersive buying experience in their phone.


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
   
   Server Side:
      We will have a web hosted server(SQL) that will contain various models and the algorithm of Machine Learning developed by using Open CV and trained CNN Models.
      The scripting language C# wich is compatible for the development of Unity based applications will act as an interface .We will use the Networking libraries and the System libraries to accomplish this.




