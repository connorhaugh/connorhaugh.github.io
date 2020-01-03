## This can be your internal website page / project page

**SafeRide:** SafeRide is an ongoing project to make a one-page React app for an existing ridesharing service on Amherst's campus. Due to network security concerns entirely unrelated to SafeRide, the Amherst IT department requires that SafeRide cannot be open-source if it is ever to be put in use. This, however, will attempt to demonstrate the app.

### 1. The Problem: A SafeRide Home, without the hassle
 
SafeRide is an existing service which operates at Amherst every evening, which allows for a safe ride between any two amherst buildings after dark. In the previous system, community members had to call the police dispatcher to request a saferide. That raised questions about how effective the service might possibly be, as the transparency of the service, where students drive the vehicles was in jeapordy. This problem birthed saferide.


### 2. The project began with the design of a lean, single-page app.

I had just finished a CodeCademy course on react, and was excited to try to develop a prototype. Expo was the logical enviroment to develop such an app, as it allows for the development of IOS and Android compatable apps with React.

```<h1>SAFERIDE</h1>
```
<img src="images/reactapp.jpeg?raw=true"/>

### 3. It then required a back-end

I used a flask app server to handle requests for rides and used that to update to a firebase noSQL database (as I wanted to be able to change the kinds of data I recieved as I develop//tweaked and loved the api). In turn the server sent out a notifaction to a driver app which told the driver the pickup/dropoff location.

### 4. What did I learn? What's on the books for saferide?

First and foremost, I leanred that is best to accomplish a larger project in smaller steps and worked out a lot about the interaction between front end and back end. I want to work to create saferide into a more "uber-esque" experince, rather than a simple exercise in making a silly app. I hope that my mobile app developemnt course next semester will do that.
