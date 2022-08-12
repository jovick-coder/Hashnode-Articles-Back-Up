## Static website forms

**Good day pals, if you are looking for a very easy way to integrate a serverless from on your frontend website, you are at the right article. **

A functional website must have form submission and integration. A functioning **Form** can be found on almost all hosted websites, including portfolios, landing pages for businesses, e-commerce sites, etc. It is impossible to deny the value of forms on a website. For a front-end developer who has little to no experience with the backend, it is challenging to construct a functional form on either our unpaid or paid projects. **This is the reason I'm giving you a short fix for that issue. ** [Fabform](https://fabform.io)

# Get started with FabForm
To make use of the service FabForm is providing you have to have an account with them.

This is has simple as anything, it will take less than 2 minutes to set up an account.

- Visit [Fabform](https://fabform.io)
- Click on the **Get started** button
- fill the registration form <br/>
all you need is a working email and a password.
- verify your email by clicking on the link sent to your email address.

*At this point you have successfully created a working account with febform.*

# Create an endpoint
All you need for submitting your form to FabForm is an endpoint.

Creating an endpoint will take few steps, let create one.

- login your account [Login](https://app.fabform.io/login)
- Click one **create endpoint**
- Give your endpoint a name
- Click on **save endpoint**
- Click on name to get your unique endpoint

# Submit form
FabForm gives you totally control of the structure and style of your form, it doesn't give you custom attribute or a set of rules while creating your form, they make use of the already existing and we'll know attributes of the form element which are **action** and **name** attributes 

## Action attribute
Action attribute is used to specify the URL of the document where the data to be sent after the submission of the form [read more](https://www.google.com/amp/s/www.geeksforgeeks.org/html-action-attribute/amp/)

This is where you pass the endpoint you created from your FabForm dashboard
``` 
https://fabform.io/f/unique-endpoint
```

## Name attribute
The name attribute specifies a name for an HTML element [read more](https://www.w3schools.com/tags/att_name.asp#:~:text=The%20name%20attribute%20specifies%20a,to%20target%20a%20form%20submission.).

The input elements should have a descriptive name because it would be use to identify the element.

# Form sample
```html
<form action="https://fabform.io/f/Zwr174X" method="post">
  <label for="firstName">First Name</label>
  <input name="firstName" type="text" required>
  <label for="lastName">Last Name</label>
  <input name="lastName" type="text" required>
  <label for="email">Email</label>
  <input name="email" type="email" required>
  <button class="button is-link" type="submit">Test Form</button>
</form>
```
Note: replace "Zwr174X" to your endpoint.

# Access submitted form
At this point we have reviewed all it needs to create a form and submit it to FabForm.

**How can we access the submitted values**

- login your account
- Click on the form you created
- All response received through the endpoint will be displayed.


# More settings
They are forms of setting that can be made on an endpoint.

- Setting email notification
- Email template
- Form submit message
- Google Sheet 
- Redirect URL

# Congratulations
Congratulations, It has been a long learning process, and I hope you understand the above-mentioned subject.

# Give feedback
If you enjoyed and learned something new from this article, follow me for More web simplified topics, and do well to give me feedback by using the reaction emojis. Let me know how you feel about the explanation in the comment section. Give feedback, corrections, and recommendations. Much 🥰

# Let us connect
I would like to connect with any and every reader. 
<br/>
**Let us connect ** <br/>
[victorjosiah19@Twitter](https://twitter.com/victorjosiah19)<br/>
[josiah-victor@LinkedIn](https://www.linkedin.com/in/josiah-victor/)

