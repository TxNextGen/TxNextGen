<div class="TxNextGen">
  <div class="auto-type-container">
    <span id="auto-typing"></span>
  </div>

  <p class="flicker-tag">🛠️ Co-founder of <strong>Flicker AI</strong> – AI web app</p>

  <pre><code>
.TxNextGen {
  languages: html css js;
  tools: vscode git;
  current-project: Flicker-AI;
  status: grinding-code;
}

.TxNextGen .contact {
  discord: @txnextgen;
}
  </code></pre>
</div>

<style>
.auto-type-container {
  font-family: 'Courier New', monospace;
  font-size: 2rem;
  white-space: nowrap;
  overflow: hidden;
  border-right: 2px solid #00fff7;
  width: fit-content;
  animation: blink-caret 0.7s step-end infinite;
  margin-bottom: 10px;
}

#auto-typing {
  background: linear-gradient(90deg, #00fff7, #00b7ff, #ff4dff);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.flicker-tag {
  font-family: 'Segoe UI', sans-serif;
  font-size: 1rem;
  margin-bottom: 10px;
  color: #ccc;
}

pre {
  background: #111;
  padding: 1rem;
  border-radius: 8px;
  color: #0ff;
  font-family: monospace;
  font-size: 0.95rem;
}
@keyframes blink-caret {
  50% {
    border-color: transparent;
  }
}
</style>

<script>
  const text = "Hi I'm TxNextGen";
  const typingSpeed = 100;
  let i = 0;

  function typeEffect() {
    if (i < text.length) {
      document.getElementById("auto-typing").innerHTML += text.charAt(i);
      i++;
      setTimeout(typeEffect, typingSpeed);
    }
  }

  window.onload = typeEffect;
</script>
