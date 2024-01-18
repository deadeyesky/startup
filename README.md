# Startup application for CS 260 BYU

## Name of the project
STrade 

## Elevator Pitch
I am creating a simple stock analysis app. I will allow users to add API's and visualize them alongside their realtime stock data. It will allow for preferences to be saved on their own user accounts, and view multiple charts.

## Basic overview of the idea
![STrade](https://github.com/deadeyesky/startup/assets/53882236/3d146386-849b-47ec-afab-fce435a20bd2)

The way this app will work is simple. The user will first sign in to their account and they will be greeted by screen **1**. Next, they will be able to click on any of the indicator value bars from screen **1** and enter into a screen format on screen **2** where they can see the realtime graph of the stock price and volume. In order to access and other information on the site, including their account informaiton, the can click the small menu square in the top left of the screen and they will see screen **3**. There, they can be directed to other pages to change settings and other things. 

## How I will use each technology

- **HTML**: For structuring the application menus, navigation, and page structure do isplay the graphics and images of the service.
- **CSS**: To add style and elegance to the app to allow it to be more user friendly and easy to use.
- **JavaScript**: to animate elements on the page, show key indicators, allow for interactive features and scrolling? and more.
- **Call web services**: I will use JavaScript to make HTTPS requests to API's that provide information about the stock price and key indicators.
- **Provide web services**: The app will have a server that processes events with logging, database access, authentication, and user requests.
- **Authentication**: I will allow users to create accounts (more on that in the next item) and allow them to use the JWT library to allow for token-based user authentication. 
- **Storage**: creates and stores records of user's personal preferences for their stock market views and services.
- **WebSockets**: will allow the server to update the client-side data whenever the stock price or indicator changes. 
