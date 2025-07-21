# Sign-up-Form

Hey there! 👋

It’s been a while since my last project — work, life, and 16 full HTML/CSS lessons got in the way. 

While some of those lessons felt a bit tedious or repetitive at times, they’ve taught me a great deal — from accessibility, user experience, and professional polish, to how to build layouts like a boss. 💻✨

💡 What This Project Is About

This project is the culmination of everything I’ve learned up to now — applying it to HTML forms.

It may seem simple on the surface(and it is), but behind this form is a treasure trove of:

input types and attributes

Accessibility considerations (ARIA, required fields, label associations)

Using pseudo-classes like :valid / :invalid

Font importing & normalization

🎯 My Personal Goal for This Project

This project isn’t just “build a form.”
Instead, I'm documenting every concept that I've used from the previous lessons in Intermediate HTML & CSS — as a checklist and proof of what I’ve actually internalized.

The following list mentions most of the lessons from this part of the course and how I applied them in this project. Not all of them are featured since some don't really have an appliance here(VSG for example):

* **Emmet:** I made use of Emmet, like always, to make the boilerplate but over I use the wrap with abbreviation at moments where I needed to wrap big snippets that were already written. Apart from that I used emmet syntax to create multiple elements that share the same attribute(like label, snap input)
* **Default Styles:** I made use of a normalize style sheet that made not have to worry about adjusting each specific element that I worked with.
* **CSS Units:** I used relative units like viewport(vh, vw) to define the size of body, along with percentage(%) to have better control how much length each item had. 
* **More Text Styles:** Applied 1.5 line height to meet accessibility standards and self-hosted the logo font.
* **More CSS Properties:** Used border-radius to accomplish the button design of the example
* **Advanced Selectors:** Mostly used child combinators and some pseudo-classes. I found the attribute selector quite useful here to target only the password inputs along with the :invalid pseudo-class. Had I only targeted inputs, then, all of them would have shared this rule.
* **Positioning:** Positioning is something that I hesitate to use because a voice in my head says: "You probably could use flexbox for that". But I think I didn't abuse it here.I used it to position the legend of the fieldset, then to align the submit button area.
* **CSS Functions:** I used url() for the font-family, for the background-image, I used rgb() to control the opacity of the background-color without affecting its children and, finally, I used scale() to make a little effect on the button when hovering. 
* **Browser Compatibility:**  Tested on Firefox and it stays consistent except for the positioning of the input controls which went a little more to the left. Also tried it on Safari mobile and it respects the desktop dimensions thanks to the use of min/max width.

🧠 Why This Matters

A big chunk of the Intermediate course (about the first 69%) is quite dense in reading content and practice — but you don’t really get to use most of it in a project until now.

So, I’m treating this project as:

🔁 A review of the key concepts I might’ve missed or skimmed

📚 A resource list I can reuse and revisit

🤝 A bit of help for other TOP students trying to make sense of how everything fits together

🤝 For Fellow Odins
If you're a fellow TOP student — Great to see you! You've already proven what you are capable of by finishing Foundations and, while there's still a long road ahead, I'm confident you are going ace this course! 

I hope this README (and the project) helps you reflect, build, and revisit key ideas.

