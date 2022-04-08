# Getting Started with Simple Firebase authentication

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Steps to get started with firebase..

1. Go to firebase.google.com
2. Got to Console
3. Add a Project
4. Give a meaningful name to your project
5. Create Project
6. Go to Docs
7. Go to Build > authentication.
8. Got to web > get started
9. Click on link: install the Firebase JS SDK and initialize Firebase
10. Install SDK using CMD in project, Command:- npm install firebase
11. Learn about firebase config, Click on Link: Firebase project config
12. On home page Click on the web (</>) logo and Register app
13. Copy FirebaseConfig from Project Settings, Pase it into a File firebase.init.js
14. Export app which is initializing firebase Config from firebase.init.js file
15. import initializing app in App.js
16. Create auth variable in App.js outSide App component function, store getAuth, send app as a parameter of getAuth... e.g(const auth = getAuth(app))
17. import {getAuth} from firebase/auth
18. Go to Docs > build > authentication > web > get started  and Then go to Google sign in
19. go to authentication on project home page > authentication > get started > sign in method >  Enable Google authentication in it...
20. Go to Build in docs > authentication  > google....
21. import GoogleAuthProvider from and create provider variable in App.js App function using new GoogleAuthProvider..e.g(const provider = new GoogleAuthProvider)
22. now onClick of a button Call signInWithPopup function and send auth and provider as parameters... e.g(signInWithPopup(auth, provider))... auth was created before using getAuth(app)....
23. then using .then catch result and for now create a variable of user = result.user
24. or using .cath catch error and console log error..


