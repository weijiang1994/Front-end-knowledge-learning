#### 1. Basic  HTML and HTML5

##### 1.1 Say Hello to HTML Elements

Welcome to freeCodeCamp's HTML coding challenges. These will walk you through web development step-by-step.

First, you'll start by building a simple web page using HTML. You can edit code in your code editor, which is embedded into this web page.

Do you see the code in your code editor that says `<h1>Hello</h1>`? That's an HTML element.

Most HTML elements have an opening tag and a closing tag.

Opening tags look like this:

```html
<h1>
```

Closing tags look like this:

```html
</h1>
```

The only difference between opening and closing tags is the forward slash after the opening bracket of a closing tag.

Each challenge has tests you can run at any time by clicking the "Run tests" button. When you pass all tests, you'll be prompted to submit your solution and go to the next coding challenge.

> Challenge
>
> To pass the test on this challenge, change your `h1` element's text to say "Hello World".

```html
<h1>
    Hello World!
</h1>
```

---

##### 1.2 Headline with the h2 Element

Over the next few lessons, we'll build an HTML5 cat photo web app piece-by-piece.

The `h2` element you will be adding in this step will add a level two heading to the web page.

This element tells the browser about the structure of your website. `h1` elements are often used for main headings, while `h2` elements are generally used for subheadings. There are also `h3`, `h4`, `h5` and `h6` elements to indicate different levels of subheadings.

> Challenge
>
> Add an `h2` tag that says "CatPhotoApp" to create a second HTML element below your "Hello World" `h1` element.

```html
<h1>
    Hello World!
</h1>
<h2>
    CatPhotoApp
</h2>
```

---

##### 1.3 Inform with the Paragraph Element

`p` elements are the preferred element for paragraph text on websites. `p` is short for "paragraph".

You can create a paragraph element like this:

`<p>I'm a p tag!</p>`

> Challenge
>
> Create a `p` element below your `h2` element, and give it the text "Hello Paragraph".
>
> **Note:** As a convention, all HTML tags are written in lowercase, for example `<p></p>` and not `<P></P>`.

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Hello Paragraph</p>
```

---

##### 1.4 Fill in the Blank with Placeholder Text

Web developers traditionally use lorem ipsum text as placeholder text. The lorem ipsum text is randomly scraped from a famous passage by Cicero of Ancient Rome.

Lorem ipsum text has been used as placeholder text by typesetters since the 16th century, and this tradition continues on the web.

Well, 5 centuries is long enough. Since we're building a CatPhotoApp, let's use something called "kitty ipsum text".

> Challenge
>
> Replace the text inside your `p` element with the first few words of this kitty ipsum text: `Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.`

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

---

##### 1.5 UnComment HTML and Comment HTML

Commenting is a way that you can leave comments for other developers within your code without affecting the resulting output that is displayed to the end user.

Commenting is also a convenient way to make code inactive without having to delete it entirely.

Comments in HTML start with `<!--` and end with a `-->`

---

##### 1.6  Introduction to HTML5 Elements

HTML5 introduces more descriptive HTML tags. These include `main`, `header`, `footer`, `nav`, `video`, `article`, `section` and others.

These tags give a descriptive structure to your HTML, make your HTML easier to read, and help with Search Engine Optimization (SEO) and accessibility. The `main` HTML5 tag helps search engines and other developers find the main content of your page.

Example usage, a `main` element with two child elements nested inside it:

```html
<main> 
  <h1>Hello World</h1>
  <p>Hello Paragraph</p>
</main>
```

**Note:** Many of the new HTML5 tags and their benefits are covered in the Applied Accessibility section.

> Challenge
>
> Create a second `p` element after the existing `p` element with the following kitty ipsum text: `Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.`
>
> Then, create a `main` element and nest the two `p` elements inside the `main` element.

```html
<h2>CatPhotoApp</h2>
<main>
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>

<p>
  Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.
</p>
</main>
```

---

##### 1.7 Add Image to Your Website

You can add images to your website by using the `img` element, and point to a specific image's URL using the `src` attribute.

An example of this would be:

<img src="https://www.your-image-source.com/your-image.jpg">

Note that `img` elements are self-closing.

All `img` elements **must** have an `alt` attribute. The text inside an `alt` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.

**Note:** If the image is purely decorative, using an empty `alt` attribute is a best practice.

Ideally the `alt` attribute should not contain special characters unless needed.

Let's add an `alt` attribute to our `img` example above:

<img src="https://www.your-image-source.com/your-image.jpg" alt="Author standing on a beach with two thumbs up.">

> Challenge
>
> Let's try to add an image to our website:
>
> Within the existing `main` element, insert an `img` element before the existing `p` elements.
>
> Now set the `src` attribute so that it points to this url:
>
> ```
> https://bit.ly/fcc-relaxing-cat
> ```
>
> Finally, don't forget to give your `img` element an `alt` attribute with applicable text.

```html
<h2>CatPhotoApp</h2>
<main>
  <img src="https://bit.ly/fcc-relaxing-cat" alt="the cat is so cute."></img>

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

---

##### 1.8 Link to External Pages with Anchor Elements

You can use `a` (*anchor*) elements to link to content outside of your web page.

`a` elements need a destination web address called an `href` attribute. They also need anchor text. Here's an example:

```html
<a href="https://freecodecamp.org">this links to freecodecamp.org</a>
```

Then your browser will display the text **"this links to freecodecamp.org"** as a link you can click. And that link will take you to the web address **https://www.freecodecamp.org**.

> Challenge
>
> Create an `a` element that links to `http://freecatphotoapp.com` and has "cat photos" as its anchor text.

```html
<h2>CatPhotoApp</h2>
<main>

  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <a href="http://freecatphotoapp.com">cat photos</a>
</main>
```

---

##### 1.9 Link to Internal Sections of a Page with Anchor Elements

`a` (*anchor*) elements can also be used to create internal links to jump to different sections within a webpage.

To create an internal link, you assign a link's `href` attribute to a hash symbol `#` plus the value of the `id` attribute for the element that you want to internally link to, usually further down the page. You then need to add the same `id` attribute to the element you are linking to. An `id` is an attribute that uniquely describes an element.

Below is an example of an internal anchor link and its target element:

> Challenge
>
> Change your external link to an internal link by changing the `href` attribute to "#footer" and the text from "cat photos" to "Jump to Bottom".
>
> Remove the `target="_blank"` attribute from the anchor tag since this causes the linked document to open in a new window tab.
>
> Then add an `id` attribute with a value of "footer" to the `<footer>` element at the bottom of the page.

```html
<h2>CatPhotoApp</h2>
<main>

  <a href="#footer">Jump to Bottom</a>

  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.</p>
  <p>Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.</p>

</main>

<footer id="footer">Copyright Cat Photo App</footer>
```

---

##### 1.10 Nest an Anchor Element within a Paragraph

You can nest links within other text elements.

```html
<p>
  Here's a <a target="_blank" href="http://freecodecamp.org"> link to freecodecamp.org</a> for you to follow.
</p>
```

Let's break down the example: Normal text is wrapped in the `p` element:
`<p> Here's a ... for you to follow. </p>` Next is the *anchor* element `<a>` (which requires a closing tag `</a>`):
`<a> ... </a>` `target` is an anchor tag attribute that specifies where to open the link and the value `"_blank"` specifies to open the link in a new tab `href` is an anchor tag attribute that contains the URL address of the link:
`<a href="http://freecodecamp.org"> ... </a>` The text, **"link to freecodecamp.org"**, within the `a` element called `anchor text`, will display a link to click:
`<a href=" ... ">link to freecodecamp.org</a>` The final output of the example will look like this:

Here's a [link to freecodecamp.org](http://freecodecamp.org/) for you to follow.

> Challenge
>
> Now nest the existing `a` element within a new `p` element (just after the existing `main` element). The new paragraph should have text that says "View more cat photos", where "cat photos" is a link, and the rest of the text is plain text.

```html
<h2>CatPhotoApp</h2>
<main>
<p>View more <a href="http://freecatphotoapp.com" target="_blank">cat photos</a></p>  
  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

---

##### 1.11 Make Dead Links Using the Hash Symbol

Sometimes you want to add `a` elements to your website before you know where they will link.

This is also handy when you're changing the behavior of a link using `JavaScript`, which we'll learn about later.

> Challenge
>
> The current value of the `href` attribute is a link that points to "http://freecatphotoapp.com". Replace the `href` attribute value with a `#`, also known as a hash symbol, to create a dead link.
>
> For example: `href="#"`

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#" target="_blank">cat photos</a>.</p>

  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

---

##### 1.12  Turn an Image into a Link

You can make elements into links by nesting them within an `a`element.

Nest your image within an `a` element. Here's  an example:

```html
<a href="#"><img src="https://bit.ly/fcc-running-cats" alt="Three kittens running towards the camera."></a>
```

Remember to use `#` as your `a` element's `href` property in order to turn it into a dead link.

> Challenge
>
> Place the existing image element within an `a` (*anchor*) element.
>
> Once you've done this, hover over your image with your cursor. Your cursor's normal pointer should become the link clicking pointer. The photo is now a link.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```

---

##### 1.13 Create a Bulleted Unordered List

HTML has a special element for creating unordered lists, or bullet point style lists.

Unordered lists start with an opening `<ul>` element, followed by any number of `<li>` elements. Finally, unordered lists close with a `</ul>`

For example:

```html
<ul>
    <li>milk</li>
    <li>cheese</li>
</ul>
```

would create a bullet point style list of "milk" and "cheese".

> Challenge
>
> Remove the last two `p` elements and create an unordered list of three things that cats love at the bottom of the page.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

<ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
</ul>
</main>
```

---

##### 1.14 Create an Ordered List

HTML has another special element for creating ordered lists, or numbered lists.

Ordered lists start with an opening `<ol>` element, followed by any number of `<li>` elements. Finally, ordered lists are closed with the `</ol>` tag.

For example:

```html
<ol>
  <li>Garfield</li>
  <li>Sylvester</li>
</ol>
```

would create a numbered list of "Garfield" and "Sylvester".

> Challenge
>
> Create an ordered list of the top 3 things cats hate the most.

```html
<h2>CatPhotoApp</h2>
<main>
  
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>Cats hate most</li>
    <li>Cats hate most</li>
    <li>Cats hate most</li>
  </ol>
</main>
```

---

##### 1.15 Create a Text Field

Now let's create a web form.

`input` elements are a convenient way to get input from your user.

You can create a text input like this:

```html
<input type="text">
```

Note that `input` elements are self-closing.

> Challenge
>
> Create an `input` element of type `text` below your lists.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text">

</main>
```

---

##### 1.16 Add Placeholder Text to a Text Field

Placeholder text is what is displayed in your `input` element before your user has inputted anything.

You can create placeholder text like so:

```html
<input type="text" placeholder="this is placeholder text">
```

**Note:** Remember that `input` elements are self-closing.

> Challenge
>
> Set the `placaholder` value of your text `input` to "cat photo URL".

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text" placeholder="cat photo URL">
</main>
```

---

##### 1.17 Create a Form Element

You can build web forms that actually submit data to a server using nothing more than pure HTML. You can do this by specifying an action on your `form` element.

For example:

```html
<form action="/url-where-you-want-to-submit-form-data"></form>
```

> Challenge
>
> Nest your text field inside a `form` element, and add the `action="/submit-cat-photo"` attribute to the form element.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  
  <form action="/submit-cat-photo">
  <input type="text" placeholder="cat photo URL">
  </form>
</main>
```

---

##### 1.18 Add Submit Button to a Form

Let's add a `submit` button to your form. Clicking this button will send the data from your form to the URL you specified with your form's `action` attribute.

Here's an example submit button:

```html
<button type="submit">this button submits the form</button>
```

> Challenge
>
> Add a Button as the last element of your `form` element with a type of `submit` ,and 'Submit' as its text.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL">
    <button type="submit">Submit</button>
  </form>
</main>
```

---

##### 1.19 Use HTML5 to Require a Field

You can require specific form fields so that your user will not be able to submit your form until he or she has filled them out.

For example, if you wanted to make a text input field required, you can just add the attribute `required` within your `input` element, like this: `<input type="text" required>`

> Challenge
>
> Make your text `input` a `required` field, so that your user can't submit the form without completing this field.
>
> Then try to submit the form without inputting any text. See how your HTML5 form notifies you that the field is required?

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
```

---

##### 1.20 Create a Set of Radio Buttons

You can use radio buttons for questions where you want the user to only give you one answer out of multiple options.

Radio buttons are a type of `input`.

Each of your radio buttons can be nested within its own `label` element. By wrapping an `input` element inside of a `label` element it will automatically associate the radio button input with the label element surrounding it.

All related radio buttons should have the same `name` attribute to create a radio button group. By creating a radio group, selecting any single radio button will automatically deselect the other buttons within the same group ensuring only one answer is provided by the user.

Here's an example of a radio button:

```html
<label> 
  <input type="radio" name="indoor-outdoor">Indoor 
</label>
```

It is considered best practice to set a `for` attribute on the `label` element, with a value that matches the value of the `id` attribute of the `input` element. This allows assistive technologies to create a linked relationship between the label and the child `input` element. For example:

```html
<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>
```

> Challenge
>
> Add a pair of radio buttons to your form, each nested in its own `label` element. One should have the option of `indoor` and the other should have the option of `outdoor`. Both should share the `name` attribute of `indoor-outdoor` to create a radio group.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
    <label for="indoor">
      <input id="indoor" type="radio" name="indoor-outdoor">indoor</input>
    </label>
    
    <label for="outdoor">
      <input id="outdoor" type="radio" name="indoor-outdoor">outdoor</input>
    </label>
  </form>
</main>
```

---

##### 1.21 Create a Set of Checkboxes

Forms commonly use checkboxes for questions that may have more than one answer.

Checkboxes are a type of `input`.

Each of your checkboxes can be nested within its own `label` element. By wrapping an `input` element inside of a `label` element it will automatically associate the checkbox input with the label element surrounding it.

All related checkbox inputs should have the same `name` attribute.

It is considered best practice to explicitly define the relationship between a checkbox `input` and its corresponding `label` by setting the `for` attribute on the `label` element to match the `id` attribute of the associated `input` element.

Here's an example of a checkbox:

```html
<label for="loving"><input id="loving" type="checkbox" name="personality"> Loving</label>
```

> Challenge
>
> Add to your form a set of three checkboxes. Each checkbox should be nested within its own `label` element. All three should share the `name` attribute of `personality`.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="/submit-cat-photo">
    <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor"> Indoor</label>
    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label for="cb1"><input type="checkbox" id="cb1" name="personality">cb1</label>
    
    <label for="cb2"><input type="checkbox" id="cb2" name="personality">cb1</label>
    
    <label for="cb3"><input type="checkbox" id="cb3" name="personality">cb1</label>
    <br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
```

---

##### 1.22 Use the value attribute with Radio Buttons and Checkboxes

When a form gets submitted, the data is sent to the server and includes entries for the options selected. Inputs of type `radio` and `checkbox` report their values from the `value` attribute.

For example: