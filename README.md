# InBoX-app
![splash_logo](https://github.com/josflesan/InBOX-app/assets/34693834/4985dfd1-34cb-44d9-b1b3-e72dca215ac3) 

This repository contains the full-stack Android/iOS companion app for InBoX users built using Flutter. The application consists of three main screens:

- Home Screen displaying InBOX units with installed compartments and Quick Access Functions
- Deliveries Screen displaying active deliveries and associated metadata including proof of delivery images
- Settings Screen to display per-user settings

Some screenshots of the app are displayed in the screenshots section below.

# 1. Use Case

The typical use case from the user's perspective is outlined below:

1. User creates a new delivery in the deliveries screen and fills in associated metadata
2. User assigns delivery to one of the available compartments in their InBOX unit
3. App generates a courier-service URL which the user copies and sends in delivery notes in their marketplace of choice when completing the order
4. Courier will then click on the URL and follow the steps on the website to fulfill the order

# 2. Tech Stack

The InBOX app was built mostly using Flutter and Dart and interacts with our own custom RESTful API (InBOX-REST) for CRUD operations and socket data streaming (such as for live security video feed)

# 3. Screenshots

![image](https://github.com/josflesan/InBOX-app/assets/34693834/86c43f84-6310-4088-b70d-52ae87539ef3)

# 4. Other Resources

Some other resources that might be of interest are listed below

- [Industry Demo Pitch Slide Deck](https://docs.google.com/presentation/d/1NE28d_SRYNQWkQGMZM1fWwCQm3ODPQ9a69ss8PNqeZE/edit#slide=id.g1dfcd81692f_9_3870)
- [Demo Video](https://drive.google.com/file/d/1OrW2YZdVVJr2LTwp0EIaV5xusSFn1ItH/view?resourcekey)


**This repository is part of the InBOX System Design Project (associated with University of Edinburgh)**
