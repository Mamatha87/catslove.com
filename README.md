<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset=""utf-8>
    <title>CatPhotoApp</title>
  </head>
  <body>
    <main>
     <h1> CatPhotoApp</h1>
<section>
     <h2> Cat Photo</h2>
     <!--Add link to cat photos-->
     <p> See more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a> in our gallery</p>
     <img>
     <!--<a href="https://freecatphotoapp.com">link to cat pictures</a>-->
     <a href="https://freecatphotoapp.com">
     <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
     </a>
</section>
<section>
  <h2>Cat Lists</h2>
  <h3> Things Cats Love:</h3>
  <ul>
    <li> cat nip</li>
    <li>laser pointers</li>
      <li>lasagna</li>
  </ul>
  <figure>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg" alt="A slice of lasagna on a plate.">
  <figcaption>
    Cats <em>love</em> lasagna.
  </figcaption>
  </figure>
  <h3>Top 3 things cats hate:</h3>
  <ol><li>flea treatment</li>  <li>thunder</li>    <li> other cats</li></ol>
  <figure>
    <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg" alt="Five cats looking around a field.">
    <figcaption>Cats <strong>hate</strong> other cats.</figcaption>
  </figure>
</section>
<section>
  <h2>Cat Form</h2>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <fieldset>
      <legend>Is your cat an indoor or outdoor cat?</legend>
      <label><input type="radio" checked id="indoor" name="indoor-outdoor" value="indoor">Indoor</label>
      <label><input type="radio" id="outdoor" name="indoor-outdoor" value="outdoor">Outdoor</label>
      </fieldset>
      <fieldset>
        <legend>What's your cat's personality?</legend>
        <input type="checkbox" checked value="loving" id="loving" name="personality"><label for="loving"> Loving</label>
        <input type="checkbox" value="lazy" id="lazy" name="personality"><label for="lazy"> Lazy</label>
        <input id="energetic" value="energetic" type="checkbox" name="personality"> <label for="energetic">Energetic</label>
      </fieldset>
    <input type="text" name="catphotourl" placeholder="cat photo URL" required >
    <button type = "Submit">Submit</button>
  </form>
</section>
     <!--<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">-->
     </main>
     <footer>
      <p>No Copyright - <a href = "https://www.freecodecamp.org"> freeCodeCamp.org</a></p>
     </footer>
  </body>
</html>
