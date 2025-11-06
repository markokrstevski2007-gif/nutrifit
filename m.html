<!DOCTYPE html>
<html lang="mk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mabeta • Chatbot Demo</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      background: linear-gradient(white, #e6e6e6);
    }

    .brand {
      position: absolute;
      top: 20px;
      left: 50%;
      transform: translateX(-50%);
      font-size: 20px;
      font-weight: 600;
      color: #333;
      letter-spacing: 1px;
    }

    .center-text {
      font-size: 28px;
      color: #333;
      text-align: center;
    }
  </style>
</head>

<body>

  <div class="brand">Mabeta</div>

  <div class="center-text">
    вашата веб страница ќе биде тука
  </div>

  <!-- ✅ Chatbase Widget Script (Mabeta Chatbot) -->
  <script>
  (function(){
    if(!window.chatbase || window.chatbase("getState") !== "initialized"){
      window.chatbase = (...arguments) => {
        if(!window.chatbase.q){ window.chatbase.q = [] }
        window.chatbase.q.push(arguments)
      };
      window.chatbase = new Proxy(window.chatbase, {
        get(target, prop){
          if(prop === "q"){ return target.q }
          return (...args) => target(prop, ...args)
        }
      });
    }
    const onLoad = function(){
      const script = document.createElement("script");
      script.src = "https://www.chatbase.co/embed.min.js";
      script.id = "wR60_6KyWlWE_vlLLSEuI";  /* ✅ Mabeta bot ID */
      script.domain = "www.chatbase.co";
      document.body.appendChild(script);
    };
    if(document.readyState === "complete"){ onLoad() }
    else { window.addEventListener("load", onLoad) }
  })();
  </script>
  <!-- ✅ END Chatbase Script -->


  <!-- ✅ Identify User with Token -->
  <script>
  async function identifyUser() {
    try {
      // Call your backend to get the signed JWT token
      const response = await fetch('/api/chatbase-token');
      const data = await response.json();

      if (data.token) {
        window.chatbase('identify', { token: data.token });
        console.log('✅ Chatbase user identified');
      }
    } catch (err) {
      console.error('❌ Error identifying user with Chatbase:', err);
    }
  }

  // Wait a bit for the Chatbase widget to initialize
  window.addEventListener('load', () => {
    setTimeout(identifyUser, 2000);
  });
  </script>

</body>
</html>
