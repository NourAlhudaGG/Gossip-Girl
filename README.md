# Gossip-Girl
Nour-Alhuda Gossip Girl
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>xoxo, Gossip Girl</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #0d0d0d;
      color: #fff;
    }
    header {
      background-color: #000;
      color: gold;
      text-align: center;
      padding: 2rem 1rem 1rem;
      border-bottom: 2px solid gold;
    }
    header h1 {
      margin: 0;
      font-size: 2.8em;
    }
    .container {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .post {
      background-color: #1a1a1a;
      padding: 1rem;
      border-left: 5px solid gold;
      margin-bottom: 1.5rem;
      box-shadow: 0 0 10px rgba(255, 215, 0, 0.2);
    }
    .post h3 {
      margin: 0 0 0.5rem 0;
      color: gold;
      font-weight: normal;
    }
    .post p {
      margin: 0.5rem 0 1rem;
    }
    .reactions span {
      margin-right: 1rem;
      cursor: pointer;
    }
    form {
      background-color: #111;
      padding: 1rem;
      border: 1px solid #444;
    }
    form textarea {
      width: 100%;
      height: 100px;
      padding: 0.5rem;
      background-color: #222;
      color: white;
      border: none;
      resize: none;
    }
    form button {
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background-color: gold;
      color: black;
      border: none;
      cursor: pointer;
    }
    footer {
      text-align: center;
      color: #888;
      padding: 2rem 1rem;
      font-size: 0.9em;
      border-top: 1px solid #333;
    }
  </style>
</head>
<body>
  <header>
    <h1>xoxo, Gossip Girl</h1>
    <p>Where secrets don't stay secret...</p>
  </header>

  <div class="container">
    <!-- Example Gossip Posts -->
    <div class="post">
      <h3>From: anonymous - 2:47 PM</h3>
      <p>Serena spotted sneaking into the boys' dorm. Trouble?</p>
      <div class="reactions">
        <span>👀 21</span><span>🔥 17</span><span>😱 10</span>
      </div>
    </div>
    <div class="post">
      <h3>From: insider - 1:20 PM</h3>
      <p>Chuck and Blair arguing again at lunch. Same old drama?</p>
      <div class="reactions">
        <span>👀 30</span><span>🔥 22</span><span>😱 5</span>
      </div>
    </div>

    <!-- Submit Gossip Form -->
    <form onsubmit="submitGossip(event)">
      <h3>أرسل إشاعة مجهولة</h3>
      <textarea placeholder="اكتب الإشاعة هنا..." required></textarea>
      <br>
      <button type="submit">إرسال</button>
    </form>
  </div>

  <footer>
    أنت لا تعرفني... لكني أعرف كل شيء عنكم 😉<br>
    &copy; Gossip Girl School Edition
  </footer>

  <script>
    function submitGossip(e) {
      e.preventDefault();
      alert("تم إرسال الإشاعة بنجاح! سيتم مراجعتها من قبل Gossip Girl.");
      e.target.reset();
      // ملاحظة: هنا منقدر نربط الإشعار يوصل لإيميلك لاحقًا
    }
  </script>
</body>
</html>
