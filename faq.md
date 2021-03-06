---
title: FAQ
date: 2017-11-29 01:31:00 Z
permalink: "/faq/"
questions:
- question: Is there an online version of the user manual?
  answer: "[Here it is!](/manual/)"
- question: How does it work exactly?
  answer: Simply tap Enso twice, firmly, to turn it on. No other setup required. Then
    hold it in your palm. Allow 15 seconds for Enso to find your heartbeat. Enso will
    sense and pulse in sync with your realtime heartrate. Tap Enso twice more to turn
    it off.
- question: How do I save someone's heartbeat?
  answer: 'Give them an Enso to hold. Open the mobile app and tap the "save a heartbeat"
    button. '
- question: What do I need in order to share my heartbeat?
  answer: Heartbeats are shared from one Enso to another via the mobile app. You will
    each need an Enso and the app.
- question: How many heartbeats can I save?
  answer: You can save as many heartbeats as you want.
- question: Why is Enso pulsing when it's on the table?
  answer: 'We recommend that you double tap Enso twice to turn it off when you set
    it down. Otherwise, Enso gets confused. '
- question: How heavy is Enso?
  answer: Your Enso weighs about as much as a small stone. Heavy enough to feel grounding,
    light enough to easily carry with you.
- question: Is it rechargeable?
  answer: Yes, and your Enso comes with everything you need in order to charge it,
    including a Micro-USB charging cord. Plug the cord into the USB port on Enso.
    Enso takes 1.5 hours to fully recharge. The battery lasts for about five hours
    of continuous use.
- question: 'Why won''t my Enso turn on? '
  answer: 'Ensure Enso is charged. If you''ve charged the Enso and it will not turn
    on, try resetting it with the small metal reset pin included in its box. The reset
    hole is on the bottom of Enso. If you''ve tried charging and resetting and it
    still doesn''t work, try using a different micro USB cord to charge it. If all
    of this fails, please contact Support@ShareEnso.com so the team can troubleshoot
    with you. '
- question: Will I feel a heart arrhythmia?
  answer: No, Enso correlates with your heartrate and will not reflect irregular heartbeats.
    Enso is not a medical device.
- question: Where is the Enso office?
  answer: Our office is located in the Mission District of San Francisco, CA.
- question: When will my Enso ship?
  answer: We are currently shipping! It generally takes 2-3 weeks from the order date.
Field name: 
layout: post
---

<section class="">
{% for q in page.questions %}
<div class="mb2 clearfix">
<h3 class="h2 sans medium mb0">{{ q.question }}</h3>
<p class="sans p">{{ q.answer | markdownify }}</p>
</div>
{% endfor %}
</section>
