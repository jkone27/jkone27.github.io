<!-- https://docs.google.com/forms/d/e/1FAIpQLScXM1VXgxbZCnwtuE8xdwKzJokwfvjzZXB7LafKqZiiYXWZVw/viewform?usp=pp_url&entry.2005620554=test&entry.1045781291=test@emai.com&entry.839337160=what+if+bla+bla+bl? -->

<script src="assets/js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLScXM1VXgxbZCnwtuE8xdwKzJokwfvjzZXB7LafKqZiiYXWZVw/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  First name:<br>
  <input type="text" name="entry.2005620554" id="entry.2005620554"><br>
  Email:<br>
  <input type="text" name="entry.1045781291" id="entry.1045781291">
  <input type="submit" value="Submit">
</form>

<br>Question</br>
<textarea rows="4" cols="50" name="entry.2005620554" id="entry.2005620554" form="gform">
Enter text here...</textarea>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>