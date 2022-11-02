# React Assignment - Hard

> This assignment is aimed to help us assess your React and JavaScript skills.

There are several projects, please choose one to complete.

- [React Assignment - Hard](#react-assignment---hard)
  - [No.1 build a very simple Twitter-like web application.](#no1-build-a-very-simple-twitter-like-web-application)
  - [No.2 TODO:](#no2-todo)

## No.1 build a very simple Twitter-like web application.

<details>

This is a Reactjs exercise that requires you to build a very simple Twitter-like web application. For simplicity, there is no backend involved in the application and the data should be stored on Redux. So, it doesn't matter if all the data is lost on closing/reloading of the webpage.

Task Details On homepage, the user has the option to either login or register. The registration form consists of the following fields:

Username (Should be unique to all users) First Name Password The login form consists of the following two fields:

Username Password Store the password as plaintext ignoring the security concerns.

After either successful registration or login, user is taken to his timeline page with URL path (/{username}). In the timeline page, user can post tweets (only text), and can see all the tweets along with their posting timestamp and the first name of their creators in descending order of their creation timestamp (newer tweets shown before older) posted by all users of the platform.

All tweets are publicly readable but they can be edited or deleted only by their owners (who posted them).

Each tweet has a unique integer ID (similar to primary key) which is incremental. For example the first posted tweet has id 1, second has id 2 and third has id 3. ID of a tweet is never changed.

On clicking on the tweets shown in the timeline page, user is taken to the corresponding tweet's dedicated page which is at URL path /tweet/{tweet ID}. User can see all the information related to the tweet here e.g. tweet id, tweet text, tweet posted time and first name of the poster.

In the timeline page, there is a Logout button so that the user can logout and be taken to the homepage again, where he can register another account. But registering a new account (with a new Username) doesn't delete the tweets created by previous users if the session has not been destroyed.

Bonus Point: Use bootstrap framework for designing the UI. Use only latest stable versions of all the libraries you use. Assessment You can create a github repo and push the code there and then share the repo url. Document how to run your code on our local machine. Clean readable code is preferred over a feature rich app.

</details>

## No.2 TODO: