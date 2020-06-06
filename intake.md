---
layout: page
title: "New Client Intake"
---

<form class="wj-contact" action="https://formspree.io/xlelpddo" method="POST">
    <label for="ClientName">Name of pregnant person:</label>
    <input type="text" name="ClientName">
    <label for="Pronouns">Preferred pronouns:</label>
    <input type="text" name="Pronouns">
    <label for="Birthday">Date of birth:</label><br>
    <input type="date" name="Birthday"><br>
    <label for="ClientPhone">Phone number:</label>
    <input type="text" name="ClientPhone">
    <label for="Email">Email:</label>
    <input type="email" name="_replyto">
    <label for="Address">Address:</label>
    <input type="text" name="AddressLine1" placeholder="Line 1">
    <input type="text" name="AddressLine2" placeholder="Line 2">
    <input type="text" name="AddressCity" placeholder="City">
    <input type="text" name="AddressPostalCode" placeholder="Postal Code">
    <input type="text" name="AddressInstructions" placeholder="Special instructions for accessing your home">
    <input type="hidden" name="_subject" value="New Client Intake">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>

<style>
form.wj-contact input[type="text"], form.wj-contact input[type="email"], form.wj-contact textarea[type="text"] {
    width: 100%;
    vertical-align: middle;
    margin-top: 0.25em;
    margin-bottom: 0.5em;
    padding: 0.75em;
    font-family: "Josefin Sans", sans-serif;
    font-weight: lighter;
    border-style: solid;
    border-color: #444;
    outline-color: #B6468C;
    border-width: 1px;
    border-radius: 3px;
    transition: box-shadow .2s ease;
}

form.wj-contact input[type="submit"] {
    outline: none;
    color: white;
    background-color: #B6468C;
    border-radius: 20px;
    padding: 0.75em;
    margin: 0.25em 0 0 0;
    border: 1px solid transparent;
    height: auto;
}

label {
 font-family: Verdana, Arial, Helvetica, sans-serif;
 font-size: xx-small;
}
</style>
