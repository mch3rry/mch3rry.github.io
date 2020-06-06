---
layout: page
title: "New Client Intake"
---

<form class="wj-contact" action="https://formspree.io/xlelpddo" method="POST">
    Name of pregnant person: <input type="text" name="Name" placeholder="First Last">
    Preferred pronouns: <input type="text" name="Preferred pronouns">
    Date of birth: 
    <input type="date" name="Birthday"><br>
    Phone number: <input type="text" name="ClientPhone">
    Email: <input type="email" name="_replyto">
    <textarea type="text" name="content" rows="6" placeholder="Tell me about you and your family!"></textarea>
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
</style>
