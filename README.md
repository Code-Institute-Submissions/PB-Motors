# Pearson's Bridge Motors

This is my website which will be used to advertise a small local garage.
It should feature the services offered and a price guide, an about page, a gallery and a contact page.
the primary goal is to intice customers to make contact with the garage via the contact page.

To do this I will need to make a comprehensive guide of services are available and use the price guide to give the customer confidence in what they are spending they're money on.
To bolster this confidence, I will include reviews and an about page.
On the gallery page I will include some images of the garage and some helpful tips for self maintenance for the customer.

## UX

_Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things._

_In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:_

### User Stories

- As a new user, I want to find out what work can I get done to my vehicle?
- As a new user, I want to know if there is a breakdown service?
- As a new user, I want to know how much will the work cost me?
- As a new user, I want to know how can I contact you?
- As a new user, I want to know how do I book an appointment?
- As a user, I want to be able to sign up and sign in to avail of member discounts etc.
- As the owner, I want to advertise the services I offer to new customers.
- As the owner, I want to continue to maintain my existing customer base with loyalty rewards.
- As the owner, I want my site to be easily navigable to both new and existing users.

### Strategy

The main goal of the website is to make an easy way for the user to get a general idea of work that can be done to their car and to get an idea of the price structure in place.
I wish to design an intuitive, easily navigable website to create an enjoyable user experience, which wil benefit both users and the owner.
I wish to make it easy for the user to see what services are available to them and to provide details of the team and facilities to give confidence to the user while browsing on any device.

### Scope

I want to use a minimalist design to demonstrate to customers services offered,
and to ensure customer confidence using the about section.
The option to contact the garage needs to be included also.

### Structure

In each section I want to keep a common navbar and a common footer.
In the header there will be a navbar with site links and a company logo.
In the footer section there will be copyright information and social media icons which will act as buttons linking to their respective sites.

### Skeleton

- Home
- About
- Gallery
- Contact

---

_I will need to make these links to wireframes_

---

### Surface

I wish to use a simple grey and white colour scheme which contrasts well together and is easily read.

_This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser._

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### Existing Features

- Feature 1 - allows users X to achieve Y, by having them fill out Z
- Navbar - allows the user to navigate the site using the listed buttons. The company name/logo also acts as a home button.
- What we do - This section on the home page gives a general view of the services offered which includes a button which links to the contact page or, if trying to contact breakdown services, links to a phone number.
- Price Guide - A table which gives a general price range to inform the customer of costs before they choose to make contact.
- Footer - This will include social links which open in an new tab when selected.
- About - This section will give some information on the technicians and their credentials, which should help to inspire confidence in a user.

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Technologies Used

_In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used._

- [JQuery](https://jquery.com)
  - The project uses **JQuery** to simplify DOM manipulation.
- [Balsamiq Wireframes](https://balsamiq.com/wireframes/?gclid=Cj0KCQiAhs79BRD0ARIsAC6XpaVYvwCWIORZNFLa4ZbfPQf8gAchZhdlP10mZeYDFooTFk1sW1Pua4caAgsmEALw_wcB)
  - I used Balsamiq Wireframes for desktop to generate wireframes for my project.
- [Canva](https://www.canva.com/tools/logo-maker-q1/?utm_source=google_sem&utm_medium=cpc&utm_campaign=REV_UK_EN_CanvaPro_Logo_EM&utm_term=REV_UK_EN_CanvaPro_Logo%20Maker_EM&gclsrc=aw.ds&&gclid=Cj0KCQiAhs79BRD0ARIsAC6XpaV4sEhgBW0e4NXHPZWqHuup9scI62Xw9bDRG2VzYZ_2mEsON57tZ44aAp4sEALw_wcB&gclsrc=aw.ds)
  - I used Canva to create a company logo for the website.
- [Font Awesome](https://fontawesome.com/)
  - I used Font Awesome to add to my navigation buttons.
- [Pexels](https://www.pexels.com/)
  - Many of the photos i used came from this website.
- [CSS Lint](http://csslint.net/)
  - Used to test my CSS after initially manual checks.

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
   1. Go to the "Contact Us" page
   2. Try to submit the empty form and verify that an error message about the required fields appears
   3. Try to submit the form with an invalid email address and verify that a relevant error message appears
   4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

1. Change nav buttons:

   - I decided to change the way the nav buttons appear on mobile as they were taking too much of the screen and hiding site content underneath, and could have been confusing for a user to use. I changed the buttons to appear in two blocks of two instead of 4 full screen width buttons.

2. CSS:

   - First I manually examined my CSS structure and removed uneccessary items and arranged them in a more understandable and easy to read manner.
   - I ran my CSS through [CSS Lint](http://csslint.net/) and found 4 errors.
   - I ran my CSS by direct input through [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) which passed.

3. ## HTML:
   1. Home:
   - I ran the index.html through [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input) by direct input. It resulted in two errors, which were <br> elements within <ul> on the address and opening hours.
   - Removed <br> elements and re-ran test receivedno errors.

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

### Content

- The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)
- The css for hovering the social media icons was copied and pasted directly from w3schools.com.
- I copied the css for the backgound image on the home page from the Whiskey Drop project.
- I copied the html snippet for the contact form from [MDBootstrap.com](https://mdbootstrap.com/snippets/jquery/temp/2746217?action=prism_export). I changed one of the icons, made the input fields required, and used my own text decorations.

### Media

- The photos used in this site were obtained from [Pexels](https://www.pexels.com/). In particular the content creators:
  - [Mídia](https://www.pexels.com/@multimediayreaccion)
  - [Pixabay](https://www.pexels.com/@pixabay)
  - [Andrea Piacquadio](https://www.pexels.com/@olly)
  - [Mike](https://www.pexels.com/@mikebirdy)

### Acknowledgements

- I received inspiration for this project from my first job, which was in my family garage. I noticed that many small garages have no way of being contacted or even noticed unless through word of mouth.
- I took inspiration for the navbar styling from the UCD resume project, using the box style for the navigation buttons, symbols from font awseome, and a transition effect also as in the project.
- One of the main automotive websites I took note of was [Quick Fit](https://quickfit.ie/). In particular on the home page, I took from the opening hours and address at the top, and a row of services performed underneath.
  I borrowed the underline styling in the address and opening hours sub headers, and three separate columns with buttons that link to the contact page or to a phone number.
- I also took note of [Pep Boys](https://www.pepboys.com/), [AA](https://www.theaa.ie/aa-membership.aspx?gclid=Cj0KCQiAhZT9BRDmARIsAN2E-J196kNgel1r2a3OZ1FP-m1-zD2rYuhpq-vEXjsWwIMJGivOowi3RFYaAm_ZEALw_wcB) and [JohnMcCarthy Recovery](https://www.johnmccarthyrecovery.com/services).
