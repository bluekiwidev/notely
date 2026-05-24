<script lang="ts">
  import logo from "$lib/assets/logo.svg";
</script>



<ul>
  <li><img src={logo} alt="Notely logo" class="logo"></li>
  <li><a href="default.asp">Home</a></li>
  <li><a href="news.asp">News</a></li>
  <li><a href="contact.asp">Contact</a></li>
  <li><a href="about.asp">About</a></li>
  <li><a href="/signin">Sign In</a></li>
  <li><a href="/signup">Sign Up</a></li>
</ul>

<form method="get" action="/signup">
  <label for="name">Name:</label><br>
  <input type="text" id="name" name="name" required><br>
  <label for="email">Email:</label><br>
  <input type="email" id="email" name="email" required><br>
  <label for="password">Password:</label><br>
  <input type="password" id="password" name="password" required><br><br>
  <input type="submit" value="Sign Up">
</form>
