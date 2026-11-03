---
title: CORA Research Group
layout: default
---

<style>
  .row { display: flex; align-items: center; gap: 2rem; margin: 2.5rem 0; }
  .row > div { flex: 1 1 50%; }
  .row img { width: 100%; height: auto; border-radius: 8px; }
  .header { display: flex; justify-content: space-between; align-items: center; }
  .header img { height: 60px; max-width: 40%; object-fit: contain; }
  .cta { text-align: center; margin: 2.5rem 0; }
  .cta a { display: inline-block; padding: 0.8rem 1.6rem; background: #041e42;
           color: #fff; text-decoration: none; border-radius: 6px; font-weight: 600; }
  footer { border-top: 1px solid #ddd; margin-top: 3rem; padding-top: 1rem; font-size: 0.9em;
           color: #555; display: flex; justify-content: space-between; align-items: center; gap: 1rem; }
  footer img { height: 40px; }
  /* ---- Mobile layout (screens narrower than 700px) ----
     On desktop each row is text | image or image | text, alternating.
     On mobile the row stacks vertically, and the rules below decide
     where the image lands in that stack, regardless of HTML order.
     Every flex item defaults to order: 0, so:
       order: 2   -> image sorts AFTER the text
       order: -1  -> image sorts BEFORE the text
     Change the one number below to flip all rows at once. */
  @media (max-width: 700px) {
    .row { flex-direction: column; align-items: stretch; }
    .row .pic { order: 2; }
    /* Per-row exception: add class="pic first" to one image cell
       to put just that image before its text on mobile. */
    .row .pic.first { order: -1; }
  }
</style>

<!-- The crest below is loaded from Wikimedia Commons. Swap the src for a file in assets/images/ to use the official wordmark. -->
<div class="header">
  <h1>CORA Research Group</h1>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/University_of_Edinburgh_c%C3%ADmer.svg/960px-University_of_Edinburgh_c%C3%ADmer.svg.png" alt="University of Edinburgh">
</div>
<h2>Want to experience a social psychology experiment?</h2>
The Contact, Outgroup Relations and Attitudes (CORA) research group at The University of Edinburgh now have a rare opportunity for you to join an in-person, social experiment.

We are studying meaningful interactions with strangers, and how this shapes our perceptions of others and the world around us. The study involves coming to the Psychology department in Edinburgh where you will be paired with a stranger, and asked to play a co-operative game while asking set questions designed to get to know each other on a meaningful level. 

Ready to join? Check your eligibility by clicking through to the survey below. 

<!-- Both buttons currently open an email to the study contact. When the survey or
     sign-up form is live, replace the mailto link in href with its https:// address. -->
<div class="cta"><a href="mailto:ppls.cora@ed.ac.uk?subject=Joining%20the%20CORA%20study">Join our research</a></div>

<!-- Images can come from this repo (assets/images/...) or from any https:// URL.
     Step 1 below uses an online image; Steps 2 and 3 use files from assets/images/. -->
<div class="row">
  <div markdown="1">

## Step 1 – Entrance Survey
Use the button above to check your eligibility for the study, and complete a psychology survey. This takes 10-15 minutes, and is easiest on a laptop. 

  </div>
  <div class="pic"><img src="{{ '/assets/images/survey.png' | relative_url }}" alt="Step 1"></div>
</div>

<!-- Step 2 uses an image stored in this repo: the file is assets/images/step-2.jpg,
     and the src below points at it. To change it, drop a new file into assets/images/
     and update the filename here. -->
<div class="row">
  <div class="pic"><img src="{{ '/assets/images/intervention.png' | relative_url }}" alt="Step 2"></div>
  <div markdown="1">

## Step 2 – Attend your Session
You will be invited to our offices near Bristo Square for your experimental session. A researcher will demonstrate the game and procedure to you and the participant you are paired with. The questions will ask you to share life experiences, important memories, discuss differences in your values and also find common ground. 
Don't worry - you can skip questions that are too difficult! 

  </div>
</div>

<div class="row">
  <div markdown="1">

## Step 3 – Exit Survey
Before you leave, you will be asked to complete the exit survey. This will take another 10-15 minutes. You will then receive your confirmation and compensation. 

  </div>
  <div class="pic"><img src="{{ '/assets/images/completion.png' | relative_url }}" alt="Step 3"></div>
</div>

<div class="cta"><a href="mailto:ppls.cora@ed.ac.uk?subject=Joining%20the%20CORA%20study">Sign up</a></div>

### Compensation

You will receive £5 for completing the entire study, and entered into a prize draw for £150 cash. You receive one entry into the prize draw for completing the entrance survey. You receive an additional ten entries into the prize draw for attending your in-person session and finishing the entire study. 

### Eligibility

You must be 18+ to participate in any part of this study. 
We may not be able to invite all entrance survey completers to an in-person session. However, you will still be entered into the prize draw as detailed above. We will contact you directly if selected for the in-person session. 

### Who Are We?

CORA research group is a team of social psychologists at the University of Edinburgh, composed largely of PhD researchers and undergraduate research assistants. We study attitudes between people in a social world, and are particularly interested in how interacting with other people can change how we view others. 

<footer>
  <span>Questions? <a href="mailto:ppls.cora@ed.ac.uk">ppls.cora@ed.ac.uk</a><br>
  © The University of Edinburgh, 2026 · <a href="https://www.ed.ac.uk">ed.ac.uk</a></span>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/University_of_Edinburgh_c%C3%ADmer.svg/960px-University_of_Edinburgh_c%C3%ADmer.svg.png" alt="University of Edinburgh">
</footer>
