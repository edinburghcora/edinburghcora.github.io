---
title: Page Title
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
  @media (max-width: 700px) { .row { flex-direction: column; align-items: stretch; } }
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

<div class="cta"><a href="https://example.com/cta">Primary call to action</a></div>

<!-- Images can come from this repo (assets/images/...) or from any https:// URL.
     Step 1 below uses an online image; Steps 2 and 3 use files from assets/images/. -->
<div class="row">
  <div markdown="1">

## Step 1 – Heading
Text for step 1. Explain what happens at this stage and what the reader needs to do.

  </div>
  <div><img src="https://picsum.photos/id/1015/800/500" alt="Step 1"></div>
</div>

<!-- Step 2 uses an image stored in this repo: the file is assets/images/step-2.jpg,
     and the src below points at it. To change it, drop a new file into assets/images/
     and update the filename here. -->
<div class="row">
  <div><img src="{{ '/assets/images/step-2.jpg' | relative_url }}" alt="Step 2"></div>
  <div markdown="1">

## Step 2 – Heading
Text for step 2. Keep it to a short paragraph.

  </div>
</div>

<div class="row">
  <div markdown="1">

## Step 3 – Heading
Text for step 3. Close out the sequence with the final action.

  </div>
  <div><img src="{{ '/assets/images/step-3.png' | relative_url }}" alt="Step 3"></div>
</div>

<div class="cta"><a href="https://example.com/cta">Secondary call to action</a></div>

<footer>
  <span>Questions? <a href="mailto:contact@ed.ac.uk">contact@ed.ac.uk</a><br>
  © The University of Edinburgh · <a href="https://www.ed.ac.uk">ed.ac.uk</a></span>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/University_of_Edinburgh_c%C3%ADmer.svg/960px-University_of_Edinburgh_c%C3%ADmer.svg.png" alt="University of Edinburgh">
</footer>
