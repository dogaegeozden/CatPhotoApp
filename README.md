# CatPhotoApp

Welcome to CatPhotoApp! This HTML app is designed to showcase adorable cat photos, share interesting cat facts, and even allow you to submit your own cat photos. Whether you're a cat lover or just looking for some feline-themed fun, CatPhotoApp has something for everyone.

## Cat Photos

Explore our collection of captivating cat photos. From cute kittens to majestic cats, our gallery has it all. [See more cat photos](https://freecatphotoapp.com)

![A cute orange cat lying on its back.](https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg)

## Cat Lists

### Things cats love:
- Cat nip
- Laser pointers
- Lasagna

Cats *love* lasagna.
![A slice of lasagna on a plate.](https://cdn.freecodecamp.org/curriculum/cat-photo-app/lasagna.jpg)

### Top 3 things cats hate:
1. Flea treatment
2. Thunder
3. Other cats

Cats **hate** other cats.
![Five cats looking around a field.](https://cdn.freecodecamp.org/curriculum/cat-photo-app/cats.jpg)

## Cat Form

Want to share your own cat photo? Use our simple submission form!

<form action="https://freecatphotoapp.com/submit-cat-photo">
  <fieldset>
    <legend>Is your cat an indoor or outdoor cat?</legend>
    <label><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
    <label><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label>
  </fieldset>
  <fieldset>
    <legend>What's your cat's personality?</legend>
    <input id="loving" type="checkbox" name="personality" value="loving" checked> <label for="loving">Loving</label>
    <input id="lazy" type="checkbox" name="personality" value="lazy"> <label for="lazy">Lazy</label>
    <input id="energetic" type="checkbox" name="personality" value="energetic"> <label for="energetic">Energetic</label>
  </fieldset>
  <input type="text" name="catphotourl" placeholder="Cat photo URL" required>
  <button type="submit">Submit</button>
</form>

## Copyright

No Copyright - [freeCodeCamp.org](https://www.freecodecamp.org)
