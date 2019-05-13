# Personal Site

[Live Site](https://www.jjyang.me)

This is a live site for my personal website. I designed it using a template from Colorlib and added some of my own tweeks to it.

## Table of contents
* [Technologies](#technologies)
* [Message Form](#coin-chart-creation)
* [Future Plans](#future-plans)

## Technologies

* HTML5
* CSS3
* Bootstrap
* JavaScript
* formspree.io/

## Message Form

Using formspree.io, created a message form that allows the user to send me an email straight from the personal site.

```javascript
  <div class="col-md-7 col-md-push-1">
    <div class="row">
      <div class="col-md-10 col-md-offset-1 col-md-pull-1 animate-box" data-animate-effect="fadeInRight">
        <form id="messageForm" method="POST" action="https://formspree.io/rongyang610@gmail.com" target="_blank" onsubmit="this.submit(); this.reset(); return false;">
          <div class="form-group">
            <input type="text" name="Name" class="form-control" placeholder="* Name" required>
          </div>
          <div class="form-group">
            <input type="email" name="Email" class="form-control" placeholder="* Email" required>
          </div>
          <div class="form-group">
            <input type="text" name="Subject" class="form-control" placeholder="Subject">
          </div>
          <div class="form-group">
            <textarea name="Message" id="message" cols="30" rows="7" class="form-control" placeholder="* Message" required></textarea>
          </div>
          <div class="form-group">
            <input id="submitForm" type="submit" class="btn btn-primary btn-send-message" value="Send Message">
          </div>
        </form>
      </div>
    </div>
  </div>
```

![Display](/images/personal.png)