**Codechef Sample APP**

This is a minimal baisc app which implments codechef oauth and makes an API request. 

To run the app, simply:
1. Clone the project
2. cd codechef-sample-app
3. Add client key and client secret that you get when you create an app on codechef to index.php (around line 71).
4. run simple php server using this: php -S localhost:8000
5. open localhost:8000, you will get permissions page from codechef. On giving permissions, response recieved from making an api request to contest problem will be dumped on screen.

Note: No database, cache, session etc is used while creating this app. This is only a sample app to help you figure out how to implement codechef oauth and make a simple api request using access token, and getting new access token and refesh token using previous refresh token.
