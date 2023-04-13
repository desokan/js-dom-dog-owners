# Dog Owners

In this exercise we practice using events and forms. This is a combo that you will find all the time when writing front-end applications. Your end result should be similar to below:

![Result](dog_owner.gif)

## Learning Objectives

- Use event listeners to render dynamic content in response to a click event
- Render dynamic content based on the contents of a submitted form

## Instructions Part 1

- Use the provided `index.js` as a starting point.
- You'll find a variable called `data` in the console.log. That's your **list of dogs**
- Render the top list of dogs using the list item template you'll find on the HTML file
- Each list item **should be clickable**. When you click on an item, the selected dog should display on the main card
- The main card should contain all the information from the selected dog. **Follow the template for the main card that you'll find on the HTML file.**
- There should be only **one card at the time** on the screen

## Instructions Part 2

- When the plus button is clicked, it should replace the main card with a form to add a new dog to the list. You'll find a template for the form on the HTML page.
- Once the form is submitted, add the new dog to the beginning of the list, right next to the plus button.

## Extended

- The dog card should have a button that toggles for the selected dog between good dog/ bad dog


<!-- 
  This is a template for the dog list item

  <li class="dogs-list__button">Mr. Bonkers</li> 

-->

<!-- This is a template for the main dog card -->

<!-- <section class="main__dog-section">
        <h2>Mr. Bonkers</h2>
        <img
          src="https://curriculum-content.s3.amazonaws.com/js/woof-woof/dog_1.jpg"
          alt=""
        />
        <div class="main__dog-section__desc">
          <h3>Bio</h3>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Harum,
            minima voluptates libero cumque rerum consequatur optio aliquid sint
            eum maxime illo laborum omnis quo ab rem cupiditate nulla
            perspiciatis ipsum!
          </p>
        </div>
        <p><em>Is naughty?</em> yes!</p>
        <button>Good dog!</button>
  </section>  -->

<!-- 
    This is a template for the add dog form

    <section class="main__dog-section">
      <h2>Add a new Dog</h2>
      <form class="form">

        <label for="name">Dog's name</label>
        <input type="text" id="name" name="name">

        <label for="image">Dog's picture</label>
        <input type="url" id="image" name="image">

        <label for="bio">Dog's bio</label>
        <textarea rows="5" id="bio" name="bio"></textarea>

        <input type="submit" id="submit" name="submit" value="Let's add a dog!" class="form__button">
      </form>
  </section>
   -->
