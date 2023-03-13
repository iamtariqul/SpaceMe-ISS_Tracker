# SpaceMe: International Space Station (ISS) 3D Tracker
Our project provides an open-source web application to track the ISS. This application makes it easy to track the ISS for any timespan by the 3D depictions of the ISS, the Earth, etc., with functionality for the users to specify which moment they would like to observe. Moreover, we demonstrate the accurate orientation of the ISS, which rotates while orbiting and always faces toward the Sun. Down to the Earth, we display all ground stations and circle an area for link-available stations; up to space, we show all space debris and indicate the nearest one with a vibrant sphere. With this lightweight application, one can explore the mystery of the ISS to their heart’s content.

# Goal
We developed a web application, which includes a 3D ISS model revolving around a 3D Earth surrounded by debris. Two tracks, one indicates the route on which ISS will travel, the other the route that ISS has traveled, a control panel for the users to manipulate the viewpoint, a timeline bar for the users to set time, and text information regarding the ISS, are additional features. We host our application on GitHub Page, which is stable and publicly accessible, and hence all needed calculations and rendering are done on the browser. Although all the endeavors are done by the client, with our lightweight ISS model (less than 1 MB) and attempt to optimize this app, the client can utilize these features all the way smoothly, especially compared to existing, similar websites. The ISS model prototype comes from NASA, but we painted it more beautifully with Blender. The main goal of our project is to provide an efficient yet vivid depiction of the orbiting ISS. With this, anyone is able to learn and even immerse themselves in the beauty of the space!

**Screenshot:**
![ISS](https://user-images.githubusercontent.com/72482679/224536718-dd2ead6b-8641-4eea-ad04-22ef67456700.png)
---

# Feature
1.  Show **ground stations** on the Earth.
2.  Show the **visible range of the ISS** (link-availability).
3.  Visualize the **track** of the ISS (past & future).
4.  **Time-travel to any moment** and see the calculated position.
5.  **Rotate the ISS** according to the position of the Sun.
6.  Visualize the **debris** in the space, and mark the closet one to the ISS.
7.  Double click to **focus** on the ISS.
8.  The ISS moves all the time.

# Tutorial
1.  Press the "Toggle Ground Stations" button (right bottom) to show or hide ISS ground stations. 
2.  Press the "Toggle Debris" button (right bottom) to show or hide debris around earth.
3.  Drag the timeline bar and press the date button to set the time and date of the tracker.
4.  Press the "Set to current time" to set to current time.
5.  Double click anywhere to center the ISS.
6.  Scroll up and down to zoom in and out.
7.  Left click and drag to spin the earth.
8.  Right click and drag to adjust the view angle.
9.  Yello track indicates the track the ISS passed.
10. White track indicates the pridicted track.
11. The cap below the ISS is the visible range of the ISS (link-availability).
12. The white text on the left shows information of the ISS.

# Data
- ISS TLE (https://live.ariss.org/tle/)
