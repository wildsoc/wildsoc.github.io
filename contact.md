---
layout: contactindex
title: Contact
permalink: /contact/
---
<div class="group">
    <div class="left">
        <p>Get in touch with me!</p>
        <p>I'm always keen to talk to people - if there's anything I can help with, or an opportunity that you think might be of interest to me, don't hesitate to drop me a line.</p>
        <p>You can get in touch with the form, or alternatively you can find me online at the links in the footer!</p>
    </div>
    <div class="right">
        <br>
        <br>
        <form action="//formspree.io/sghillman@gmail.com" method="POST">
            <fieldset>
                <label for="name">Your name</label>
                <br>
                <input type="text" name="name" placeholder="Name" required>
            </fieldset>
            <fieldset>
                <label for="_replyto">Your email</label>
                <br>
                <input type="email" name="_replyto" placeholder="example@domain.com" required>
            </fieldset>
            <fieldset>
                <label for="message">Your message</label>
                <br>
                <textarea name="message" rows="1" placeholder="Message" required></textarea>
            </fieldset>
            <input class="hidden" type="text" name="_gotcha" style="display:none">
            <input class="hidden" type="hidden" name="_subject" value="Message via http://domain.com">
            <input class="button submit" type="submit" value="Send">
        </form>
    </div>
</div>


