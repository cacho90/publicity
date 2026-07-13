// Import the functions you need from the SDKs you need
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";
// TODO: Add SDKs for Firebase products that you want to use
// https://firebase.google.com/docs/web/setup#available-libraries

// Your web app's Firebase configuration
// For Firebase JS SDK v7.20.0 and later, measurementId is optional
const firebaseConfig = {
  apiKey: "AIzaSyCxp4CGtYk5wiHGARJsuajZ_Gc1_7zmZKg",
  authDomain: "publicity-671f5.firebaseapp.com",
  projectId: "publicity-671f5",
  storageBucket: "publicity-671f5.firebasestorage.app",
  messagingSenderId: "71873567886",
  appId: "1:71873567886:web:c253893c363389bf417ddf",
  measurementId: "G-T9458SE4HJ"
};

// Initialize Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);