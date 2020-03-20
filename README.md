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



