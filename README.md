// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyD2e9BtERsCm6n6mAlj6Ll6c7GMcWzc0uE",
  authDomain: "nexwallet-312d9.firebaseapp.com",
  projectId: "nexwallet-312d9",
  storageBucket: "nexwallet-312d9.firebasestorage.app",
  messagingSenderId: "1070652152586",
  appId: "1:1070652152586:web:e82236c52d783b06d578f3",
  measurementId: "G-QHRD1ZWJYH"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
