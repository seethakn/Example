## Seetha's Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Responsive Web Design</title>
</head>
<body>
<h1>Responsive Web Design Resolves</h1>
<p>
Responsive web design is the key to future.Some of the problems RWD addresses are as follows:
1. SEO errors
RWD reduces most of SEO errors and makes it easy for search engines to reach your site.
2. Aids speedy responsive website on mobile devices
Helps load up pages faster than on mobile screens than the desktop version for the mobile device.
3. Adapts to any screen size
No matter what the screen size is, the website will be displayed properly to fit on the screen.
4. No need of maintaining multiple versions of the same site
5. Makes online shopping more accessible
6. a very good user experience - easy navigation and minimal scrolling.
</p>
<form>
  <label>Your name:*
    <input type="text" name="name" size="40" autofocus required>
  </label>
  <br>
  <br>
  <label>Phone number:
    <input type="tel" name="phonenumber" size="15">
  </label>
  <br>
  <br>
  <label>Email id:*
    <input type="email" name="email" size="40" pattern="[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,3}$" title="characters@characters.domain" required>
  </label>
  <br>
  <br>
  <label>Web page you are looking to redesign:*
    <input type="url" name="webpage" size="40" required>
  </label>
  <br>
  <br>
  <label>
    How many unique visitors does your website recieve daily?:
    <input type="number" name="NoofVisitors" min="1" max="10000" size="6" required>
  </label>
  <br>
  <br>
  <fieldset>
    <legend>Why are you interested in making your website responsive?</legend>
    <label>
      <input type="checkbox" name="WhyRWD" value="OneURL">
      One URL
    </label>
    <br>
    <label>
      <input type="checkbox" name="WhyRWD" value="Flex">
      Flexible User Interface
    </label>
    <br>
    <label>
      <input type="checkbox" name="WhyRWD" value="Fast">
      Faster loading
    </label>
  </fieldset>
 <br>
  <fieldset>
    <legend>What is your biggest concern with your current website?</legend>
    <label>
      <input type="radio" name="concern" value="Scalability" required>
      Lack of scalability
    </label>
    <label>
      <input type="radio" name="concern" value="SEO" required>
      Lack of better Search Engine rankings
    </label>
    <label>
      <input type="radio" name="concern" value="UI" required>
      Lack of image flexibility on user devices
    </label>
  </fieldset>
  <br>
  <label>Do you have any other comments?
    <textarea name="comments"></textarea>
  </label>
<br>
  <input type="submit" name="submit" width="48" height="48" value="Send">
</form>
</body>
</html>
