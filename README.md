# NashWD-1E
Adding CSS to your Dream Vacation Site

## Style it up!

#### Now let's make your webpage a little fancy
> Below are some suggestions. If you want to come up with more styles on your own, feel free!
1. Add a background color to your page using the `body` selector in your `styles.css`. Here is a easy way to pick a [hex color](https://www.google.com/search?q=hex+color+picker&oq=hex+color+picker&aqs=chrome.0.0l6.3344j0j7&sourceid=chrome&ie=UTF-8). 
1. Add an `id` called `"page-title"` to your header. Now, use the `id` to select this header in the `styles.css` file so you can add styles.
  - Change the color of the text
  - Center the text
  - Underline the text
  - Change the font
1. Look at the paragraph that explains some attraction and/or fun facts about your destination. Add an `id` to your paragraph, call it something like `"description"`. Now use this `id` to select the paragraph tag in your `styles.css` file.
  - Add a gray border around the paragraph
  - Change the background color
  - Add some padding around `50px`. What did that do? Play around with the right amount of `px`
  - Add some margin around `100px`. What did that do? Play around with the right amount of `px`
  - Use `border-radius` to round the corners of your box
1. Add an id to your image. 
  - Center the image
1. Put parent `<div>`s around your `<ul>`  and `<ol>` code. Add a class  It should look something like this...
  ``` HTML
    <div class="list-box">
      <h3>Local Attractions</h3>
      <ul>
        <li>Beach #1</li>
        <li>Beach #2</li>
        <li>Beach #3</li>
      </ul>
    </div>
    <div class="list-box">
      <h3>Best Restaurants</h3>
      <ol>
        <li>Restaurant #1</li>
        <li>Restaurant #2</li>
        <li>Restaurant #3</li>
      </ol>
    </div>
  ```
  - Add the same class to each parent `<div>` and call it something like `"list-box"`.
  - Change the background color of the `"list-box"` class
  - Add padding to the `"list-box"` class
  - Add a dotted border on the `"list-box"` class

#### Advanced Styling Suggestions!
1. Looking at your paragraph description
  - change the background color to be partially transparent using `rgba`
1. Looking at your image
  - Turn your image into a [parallax image](https://www.w3schools.com/howto/howto_css_parallax.asp) (This will involve removing the `<img>` tag from your html)
1. Can you use [`display: inline-block`](http://learnlayout.com/inline-block.html) to get your list-boxes to show up side by side?
1. Looking at all of your text. Can you figure out how to import a google font check out this [link](https://codeburst.io/intro-to-google-fonts-for-web-developers-5559b63807d3)


