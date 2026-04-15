<script type="module">
  import { initializeApp } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-app.js";
  import { getAnalytics } from "https://www.gstatic.com/firebasejs/10.7.1/firebase-analytics.js";

  const firebaseConfig = {
    apiKey: "TU_API_KEY",
    authDomain: "nexwallet-312d9.firebaseapp.com",
    projectId: "nexwallet-312d9",
    storageBucket: "nexwallet-312d9.appspot.com",
    messagingSenderId: "1070652152586",
    appId: "1:1070652152586:web:e82236c52d783b06d578f3",
    measurementId: "G-QHRD1ZWJYH"
  };

  const app = initializeApp(firebaseConfig);
  const analytics = getAnalytics(app);
</script>
