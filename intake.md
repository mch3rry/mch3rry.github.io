---
layout: page
title: "New Client Intake"
---

<form class="DoulaForms" action="https://formspree.io/xlelpddo" method="POST">
    <hr>
    <h4>Contact Information</h4><br>
    <h4>more hacks... hack hack hack... hacks</h4><br>
    <div class="left">
        <label for="ClientName">Name of pregnant person:</label>
        <input type="text" name="ClientName">
    </div>
    <div class="right">
        <label for="Pronouns">Preferred pronouns:</label>
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
        <label for="PartnerPronouns">Preferred pronouns:</label>
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
    <div class="center">
        <label for="Childcare">If applicable: What is your care plan for your children during labour?</label>
        <input type="text" name="Childcare">
    </div>
    <hr>
    <h4>Current Pregnancy & Medical History</h4><br>
    <div class="center">
        <label for="EDD">Estimated due date:</label><br>
        <input type="date" name="EDD"><br><br>
    </div>
    <div class="center">
        <label for="Birthday">Pregnant person's date of birth:</label><br>
        <input type="date" name="Birthday"><br><br>
    </div>
    <div class="center">
        <label for="CareProviderType">Type of care provider:</label><br>
        <input type="radio" name="CareProviderType" value="Midwife">
        <label for="CareProviderType">Midwife</label>
        <input type="radio" name="CareProviderType" value="Family Doctor">
        <label for="CareProviderType">Family Doctor</label>
        <input type="radio" name="CareProviderType" value="OB/GYN">
        <label for="CareProviderType">OB/GYN</label><br><br>
    </div>
    <div class="left">
        <label for="CareProviderName">Name of care provider:</label>
        <input type="text" name="CareProviderName">
    </div>
    <div class="right">
        <label for="PracticeName">Name of practice:</label>
        <input type="text" name="PracticeName">
    </div>
    <div class="center">
        <label for="CareProviderPhone">Phone number:</label>
        <input type="text" name="CareProviderPhone">
    </div><div class="center">
        <label for="BirthPlace">Place of birth:</label>
        <input type="text" name="BirthPlace" placeholder="Home, or specify hospital">
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
    <div class="left2">
        <label for="nPregnancies">Number of pregnancies:</label>
        <input type="text" name="nPregnancies" size="10">
    </div>
    <div class="right2">
        <label for="Outcomes">Have you experienced any of the following?</label><br>
        <input type="checkbox" name="Outcomes" value="Miscarriage">
        <label for="Outcomes">Miscarriage</label>
        <input type="checkbox" name="Outcomes" value="Abortion">
        <label for="Outcomes">Abortion</label>
        <input type="checkbox" name="Outcomes" value="Stillbirth">
        <label for="Outcomes">Stillbirth</label>
        <input type="checkbox" name="Outcomes" value="C-section">
        <label for="Outcomes">C-section</label>
        <input type="checkbox" name="Outcomes" value="VBAC">
        <label for="Outcomes">VBAC or HBAC</label><br><br>
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
    <input type="text" name="_gotcha" style="display:none">
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
    background-color: #B6468C;
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
    width: 70%;
}

div.left2 {
    float: left;
    width: 28%;
}
</style>
