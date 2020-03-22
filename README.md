# React Firebase Links
> Libraries and tutorials for integrating Firebase with React

I am collecting a list of tutorials, libraries, and issues related to using Firebase with React.

## React Hooks
- [react-firebase-hooks](https://www.npmjs.com/package/react-firebase-hooks)

## Redux
- [react-redux-firebase](https://www.npmjs.com/package/react-redux-firebase)

## RxFire
- [RxFire in ReactJS using Firebase Firestore and Authentication](https://ajonp.com/lessons/rxfire-in-reactjs-using-firebase-firestore-and-authentication/)
- [RxJS tips](https://fireship.io/lessons/rxjs-basic-pro-tips/)

## Next.js
- [Next.js example with Firebase authentication](https://github.com/zeit/next.js/tree/canary/examples/with-firebase-authentication)
- [Next.js example with Firebase authentication and serverless functions](https://github.com/zeit/next.js/tree/canary/examples/with-firebase-authentication-serverless)
- [Next.js and Firebase starter](https://github.com/rwieruch/nextjs-firebase-authentication)

## Rest API
Probably the best option if you want to avoid adding the huge Firebase dependency

- [SWR by Zeit](https://swr.now.sh/)
- [React Query by Tanner Linsley](https://github.com/tannerlinsley/react-query#usemutation)
- [Google Firestore REST API examples](https://www.jeansnyman.com/posts/google-firestore-rest-api-examples/)

## Cloud Functions
Alternatively, you could use `react-firebase-hooks`, `firebase`, and a couple of Firebase Cloud Functions. Here are some links about them.

- [Can Cloud Functions for Firebase execute on user login?](https://stackoverflow.com/questions/46452921/can-cloud-functions-for-firebase-execute-on-user-login)
- [Firebase Authentication triggers](https://firebase.google.com/docs/functions/auth-events)
- [https://stackoverflow.com/questions/47726099/how-to-write-data-to-firestore-through-firebase-functions](https://stackoverflow.com/questions/47726099/how-to-write-data-to-firestore-through-firebase-functions)
- [Cloud Functions for Firebase Sample Library](https://github.com/firebase/functions-samples/)

## Misc.
- [Authentication in React Applications](https://kentcdodds.com/blog/authentication-in-react-applications)
- [Firestore Data Modeling - Five Cool Techniques](https://www.youtube.com/watch?v=35RlydUf6xo)
- [Role Based Authorization With Firestore](https://fireship.io/lessons/role-based-authorization-with-firestore-nosql-and-angular-5/)
- [Model Relational Data in Firestore NoSQL](https://www.youtube.com/watch?v=jm66TSlVtcc)
- [How to Connect Firebase Users to their Data - 3 Methods](https://www.youtube.com/watch?v=2ciHixbc4HE)

## Tips
1. Import Firebase this way:
```js
// This import loads the firebase namespace.
import firebase from 'firebase/app';
 
// These imports load individual services into the firebase namespace.
import 'firebase/auth';
import 'firebase/database';
```

## FAQ
### Is it safe to expose Firebase API key?
Yes.

Source: [Stack Overflow](https://stackoverflow.com/questions/37482366/is-it-safe-to-expose-firebase-apikey-to-the-public)



