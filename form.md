---
permalink: /form/
---

# ?

<!-- https://github.com/toperkin/staticFormEmails didnt work :( 
  
  https://docs.google.com/forms/d/e/1FAIpQLScXM1VXgxbZCnwtuE8xdwKzJokwfvjzZXB7LafKqZiiYXWZVw/viewform?usp=pp_url&entry.2005620554=John&entry.1045781291=JohnBuck@Bucks.com&entry.839337160=Why+dont+you+mind+your+business?
  -->

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/1FAIpQLScXM1VXgxbZCnwtuE8xdwKzJokwfvjzZXB7LafKqZiiYXWZVw/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  Name:<br>
  <input type="text" name="entry.2005620554" id="entry.2005620554"><br>
  Email:<br>
  <input type="text" name="entry.1045781291" id="entry.1045781291">
  <input type="submit" value="Register">
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script
  src="https://code.jquery.com/jquery-3.4.1.min.js"
  integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous">
</script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>