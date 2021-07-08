---
layout: page
title: Contact Me
description: Let's make friends~
background: "/img/et.jpg"
form: true
---

有任何想法歡迎吿訴我哦～

<form action="https://formspree.io/f/mbjqknyv" method="POST">
    <div class="control-group">
        <div class="form-group floating-label-form-group controls">
            <label>Name</label>
            <input
                type="text"
                class="form-control"
                placeholder="Name"
                id="name"
                name="Name"
                required
                data-validation-required-message="Please enter your name."
            />
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="control-group">
        <div class="form-group floating-label-form-group controls">
            <label>Email Address</label>
            <input
                type="email"
                class="form-control"
                placeholder="Email Address"
                id="email"
                name="Email"
                required
                data-validation-required-message="Please enter your email address."
            />
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>Phone Number</label>
            <input
                type="tel"
                class="form-control"
                placeholder="Phone Number"
                id="phone"
                name="Phone"
                required
                data-validation-required-message="Please enter your phone number."
            />
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="control-group">
        <div class="form-group floating-label-form-group controls">
            <label>Message</label>
            <textarea
                rows="5"
                class="form-control"
                placeholder="Message"
                id="message"
                name="Message"
                required
                data-validation-required-message="Please enter a message."
            ></textarea>
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <br />
    <div id="success"></div>
    <div class="form-group">
        <button type="submit" class="btn btn-primary" id="sendMessageButton">
            Send
        </button>
    </div>
</form>
