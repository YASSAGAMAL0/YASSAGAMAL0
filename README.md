<!-- "Hero" Header (Dark Mode) -->
<div align="center" style="background:#0d1117; color:#c9d1d9; padding:20px;">
  <img src="https://github.com/BrunnerLivio/brunnerlivio/blob/master/images/welcome.png?raw=true" style="max-width: 100%;" alt="Welcome to my Github Profile" />
  <br /><br />
  <a href="https://github.com/YASSAGAMAL0">
    <img height="50" alt="My Name" src="https://github.com/BrunnerLivio/brunnerlivio/blob/master/images/personal_note.svg" />
  </a>
  <br /><br />
</div>

<!-- Social (Dark Mode) -->
<table width="100%" align="center" style="background:#0d1117; color:#c9d1d9;">
<tr>
<td align="center">
<a href="https://github.com/YASSAGAMAL0" style="color:#58a6ff;">
<strong>My GitHub Profile</strong>
<br /><br /><br />
<p><img alt="GitHub" height="80" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"></p>
</a>
</td>

<td align="center">
<a href="https://www.youtube.com/@YOUR_CHANNEL_HERE" style="color:#ff0000;">
<strong>YouTube Channel</strong>
<br /><br />
<p><img height="100" alt="Music" src="https://github.com/BrunnerLivio/brunnerlivio/blob/master/images/music.gif"></p>
</a>
</td>
</tr>

<tr>
<td align="center">
<a href="https://www.facebook.com/yassa.gamal.273769" style="color:#1877f2;">
<strong>Facebook</strong>
<br /><br />
<p><img height="80" alt="Facebook" src="https://cdn-icons-png.flaticon.com/512/733/733547.png"></p>
</a>
</td>

<td align="center">
<a href="https://www.instagram.com/yassa_gamall" style="color:#e1306c;">
<strong>Instagram</strong>
<br /><br />
<p><img height="80" alt="Instagram" src="https://cdn-icons-png.flaticon.com/512/174/174855.png"></p>
</a>
</td>
</tr>

<tr>
<td align="center" colspan="2">
<a href="https://www.linkedin.com/in/yassa-gamalshawqy0-674b2125a" style="color:#0a66c2;">
<strong>LinkedIn</strong>
<br /><br />
<p><img height="80" alt="LinkedIn" src="https://cdn-icons-png.flaticon.com/512/174/174857.png"></p>
</a>
</td>
</tr>
</table>

<div align="center">
<a href="#guestbook">
<img src="https://github.com/BrunnerLivio/brunnerlivio/blob/master/images/guestbook.svg">
</a> 
</div>

---

<div align="center" style="margin-top:18px;">
# 🔧 Languages & Examples
</div>

<table align="center" style="background:#0d1117; color:#c9d1d9; width:90%; margin-top:10px;">
<tr>
  <td align="center" style="padding:12px;">
    <strong>C</strong>
    <br />
    <small>Classic systems & embedded code</small>
    <br /><br />
    <pre><code>#include &lt;stdio.h&gt;

int main() {
    printf("Hello World\n");
    return 0;
}
</code></pre>
  </td>
  <td align="center" style="padding:12px;">
    <strong>C++</strong>
    <br />
    <small>OOP, STL, competitive programming</small>
    <br /><br />
    <pre><code>#include &lt;iostream&gt;
using namespace std;

int main() {
    cout &lt;&lt; "Hello World" &lt;&lt; endl;
    return 0;
}
</code></pre>
  </td>
</tr>

<tr>
  <td align="center" style="padding:12px;">
    <strong>C#</strong>
    <br />
    <small>Desktop Apps & Unity</small>
    <br /><br />
    <pre><code>using System;

class Program {
    static void Main() {
        Console.WriteLine("Hello World");
    }
}
</code></pre>
  </td>
  <td align="center" style="padding:12px;">
    <strong>Java</strong>
    <br />
    <small>Android, backend</small>
    <br /><br />
    <pre><code>public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
</code></pre>
  </td>
</tr>
</table>

---

<div id="guestbook" align="center" style="margin-top:18px;">
## 📝 Guestbook
<form id="guestForm">
<input type="text" id="name" placeholder="Your Name" required>
<input type="text" id="message" placeholder="Your Message" required>
<button type="submit">Add Entry</button>
</form>

<h2>Entries:</h2>
<ul id="entries"></ul>
</div>

<script>
const form = document.getElementById('guestForm');
const entriesList = document.getElementById('entries');

form.addEventListener('submit', function(e) {
    e.preventDefault();
    const name = document.getElementById('name').value;
    const message = document.getElementById('message').value;
    const li = document.createElement('li');
    li.textContent = name + ': ' + message;
    entriesList.appendChild(li);
    form.reset();
});
</script>

---

<!-- Footer (Dark Mode) -->
<div align="center" style="background:#0d1117; color:#c9d1d9; padding:10px;">
<img height="120" alt="Thanks for visiting me" width="100%" src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/marquee.svg" />
<br />
<img src="https://profile-counter.glitch.me/YASSAGAMAL0/count.svg" />
<img src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/notepad.gif" alt="Site created with Notepad" height="30" />
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>  
<img src="https://raw.githubusercontent.com/BrunnerLivio/brunnerlivio/master/images/ie_logo.gif" alt="Microsoft Internet Explorer" />
<span>&nbsp;&nbsp;&nbsp;&nbsp;</span>  
<img src="https://github.com/BrunnerLivio/brunnerlivio/blob/master/images/noframes.gif" alt="No Frames" />
</div>
