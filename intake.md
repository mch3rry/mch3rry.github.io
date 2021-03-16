---
layout: page
---
<h2>New Client Intake</h2>
<p>Thank you for taking the time to complete this intake form.</p>
<form class="DoulaForms" action="https://formspree.io/xlelpddo" method="POST">
    <hr>
    <b>Contact Information</b><br>
    <div class="left">
        <label for="ClientName">Name of pregnant person:</label>
        <input type="text" name="ClientName">
    </div>
    <div class="right">
        <label for="Pronouns">Pronouns:</label>
        <input type="text" name="Pronouns">
    </div>
    <div class="center">
        <label for="ClientPhone">Phone number:</label>
        <input type="text" name="ClientPhone">
    </div>
    <div class="center">
        <label for="Email">Email:</label>
        <input type="email" name="_replyto">
    </div>
    <div class="center">
        <label for="Address">Address:</label>
        <input type="text" name="AddressLine1" placeholder="Street">
    </div>
    <div class="left">
        <input type="text" name="AddressCity" placeholder="City">
    </div>
    <div class="right">
        <input type="text" name="AddressPostalCode" placeholder="Postal Code">
    </div>
    <div class="center">
        <input type="text" name="AddressInstructions" placeholder="Special instructions for accessing your home">
    </div>
    <div class="left">
        <label for="PartnerName">Name of partner/support person:</label>
        <input type="text" name="PartnerName">
    </div>
    <div class="right">
        <label for="PartnerPronouns">Pronouns:</label>
        <input type="text" name="PartnerPronouns">
    </div>
    <div class="center">
        <label for="PartnerPhone">Phone number:</label>
        <input type="text" name="PartnerPhone">
    </div>
    <div class="center">
        <label for="Children">Names and ages of any children:</label>
        <input type="text" name="Children">
    </div>
    <hr>
    <b>Current Pregnancy & Medical History</b><br>
    <div class="center">
        <label for="EDD">Estimated due date:</label><br>
        <input type="date" name="EDD"><br><br>
    </div>
    <div class="center">
        <label for="CareProviderName">Name of care provider/practice:</label>
        <input type="text" name="CareProviderName">
    </div>
    <div class="center">
        <label for="BirthPlace">Planned place of birth:</label>
        <input type="text" name="BirthPlace">
    </div>
    <div class="center">
        <label for="MedConcerns">Do you have any risk factors or medical concerns for this pregnancy?</label>
        <textarea type="text" name="MedConcerns" rows="3"></textarea>
    </div>
    <div class="center">
        <label for="Meds">Do you take any medication, vitamins, supplements, etc?</label>
        <textarea type="text" name="Meds" rows="3"></textarea>  
    </div>
    <div class="center">
        <label for="Allergies">Do you have any allergies or intolerances?</label>
        <input type="text" name="Allergies">
    </div>
    <div class="center">
        <label for="BirthExperiences">Describe any previous birth experiences.</label>
        <textarea type="text" name="BirthExperiences" rows="6"></textarea>
    </div>
    <div class="center">
        <label for="ChildbirthClass">Have you taken, or do you plan to take, a childbirth education class? If so, who is the instructor?</label>
        <input type="text" name="ChildbirthClass">
    </div>
    <div class="center">
        <label for="PPPlan">Do you have a postpartum plan? If so, please describe.</label>
        <textarea type="text" name="PPPlan" rows="6"></textarea>
    </div>
    <input type="hidden" name="_subject" value="New Client Intake">
    <input type="submit" value="Submit">
</form>

<style>
form.DoulaForms input[type="text"], form.DoulaForms input[type="email"], form.DoulaForms textarea[type="text"] {
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

form.DoulaForms input[type="submit"] {
    outline: none;
    color: white;
    background-color: #5EA788;
    border-radius: 20px;
    padding: 0.75em;
    margin: 0.25em 0 0 0;
    border: 1px solid transparent;
    height: auto;
}

label {
    font-family: "Josefin Sans", sans-serif;
    font-weight: lighter;
}

div.center {
    clear: both;
}

div.right {
    float: right;
    width: 38%;
}

div.left {
    float: left;
    width: 60%;
}

div.right2 {
    float: right;
    width: 73%;
}

div.left2 {
    float: left;
    width: 25%;
}
</style>
