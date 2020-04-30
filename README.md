# CS571 Homework 07
## React Navigation
Create a new React Native app with Expo-CLI and use [React Navigation](https://reactnavigation.org/) to support the following app structure:
* Drawer.Navigator
  * `Home` (Tab.Navigator)
    * `About` (Screen)
    * `Contact us` (Screen)
  * `Profile` (Stack.Navigator)
      * `Account` (Screen)
      * `Security` (Screen)
  
### Implement the following screens features:
* Use [Kanye Rest](https://kanye.rest/) API and fetch a random quote to be displayed within the `About` Screen. Create a button `Refresh` that will fetch a new quote when clicked.
* Both `About` and `Contact us` screens should have icons along with the title.
* The `Account` Screen should have a button to go to `Security` Screen and pass a static `user_id` as parameter. 
* Add a button to `Contact us` Screen to navigate to `Security` Screen and pass a static `user_id` parameter.
* The `Security` Screen will receive the `user_id` param and display it.
