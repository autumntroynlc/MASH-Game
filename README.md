<!DOCTYPE html>
<html>

  <!-- HEAD SECTION STARTS -->
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=0.5, maximum-scale=0.5, minimal-ui">
    <title>MASH</title>
    <link href="normalize.css" rel="stylesheet">
    <link href="style.css" rel="stylesheet">
  </head>
  <!-- HEAD SECTION ENDS -->

  <!-- BODY SECTION STARTS -->
  <body>
    <h1>MASH</h1>
    <p class="description">Come my child and sit down. Now, don't be shy! Before you I have these blanks - fill them in and see where your future lies.</p>
    <form action="" method="post" id="mash">
      <div id="answers" class="hide">
        <p>Ah! How strange! Well, it's to be expected. You will dwell in <span id="answer_1"></span> with a <span id="answer_3"></span> and you will become a <span id="answer_2"></span> who owns a <span id="home"></span>.
      </div>
      <div class="bucket">
        <div class="choice-bucket">
          <h4 class="highlight">The first question - Where are the places you want to live?</h4>
          <input name="answer_1[]" type="text">
          <input name="answer_1[]" type="text">
          <input name="answer_1[]" type="text">
          <input name="answer_1[]" type="text">
        </div>
        <div class="choice-bucket">
          <h4 class="highlight">Now tell me, who do you think you are meant to be? </h4>
          <input name="answer_2[]" type="text">
          <input name="answer_2[]" type="text">
          <input name="answer_2[]" type="text">
          <input name="answer_2[]" type="text">
        </div>
        <div class="choice-bucket">
          <h4 class="highlight">And lastly, give me four animals.</h4>
          <input name="answer_3[]" type="text">
          <input name="answer_3[]" type="text">
          <input name="answer_3[]" type="text">
          <input name="answer_3[]" type="text">
        </div>
      </div>
      <button type="submit" class="button-submit">Your fate is sealed when you press this button. Click it and it will reveal your future!</button>
    </form>  
    <script src=""></script>
  </body>
  <!-- BODY SECTION ENDS -->

</html>
