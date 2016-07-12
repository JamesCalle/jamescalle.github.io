---
layout: page
#title: Venmo
permalink: /venmo
---
<button onclick="goBack()">Go Back</button>

<script>
function goBack() {
    window.history.back();
}
</script>
<body style="font-family:PT Serif;">
<p>
<i>In this General Assembly group project, we were assigned and tasked to implement a feature to Venmo. Venmo is an application that allows users to quickly and easily make a transaction with other users for free. Leveraging Venmo’s social media aspect we were tasked to introduce a way for users to send money via their app towards causes they care about — whether it would be a nonprofit that combats hunger or a unique Kickstarter campaign.</i>
<p>
<img src="/assets/img/pagebanner/vpagebanner.png" alt="Venmo">
<p>
Me and my group members, Di Lu and Ron Ng, have never heard or used Venmo before so the first step was to download the app to our devices and use all the features. From the basics such as sending money to each other to reading through other random user's transactions and comments in the public feed section. After fully exploring and familiarizing ourselves with Venmo we found out that it is technically possible to make a monetary contribution to a cause or charity, it's just not safe. There is nothing to reassure users that their monetary contribution is going to the right place.
<p>
We tried looking for other services like Venmo, but there isn't one. The peer to peer, social media, transaction space is currently being dominated by Venmo. But we did explore several other payment services and compared the both to see what makes them tick.
<p>
After reading, exploring and learning all there is to Venmo, we now needed to know; who uses Venmo? What are Venmo user's donation habits like? A screener survey was sent out through every outlet available to us to get an idea of Venmo's demographics, if Venmo users even make donations, and more importantly who would like to come in and talk to us about their donation habits. We scheduled 7 user interviews with people to talk to us about their donation habits, whether they were a Venmo user or not. They told us;
<ul style="list-style-type:none">
<i>
<li>“Stuff more relevant, geolocation. Local and things relevant to me, some jazz foundation. That’d be awesome.” — W.</li>
<li>“It’s tough to find a good charity or organization. I’d wanna do my due diligence.” — C.</li>
<li>“I get told things on twitter.” — J.</li>
<li>“I don’t like the newsfeed. People can see whose paying me. I feel it’s kinda private.” — A.</li>
<li>“I don’t like auto-payments. I like the control.” — Al.</li>
<li>“I’ll give like, a dollar at a store if they ask me.” — K.</li>
</i>
</ul>
<p>
Most Venmo and non-Venmo users told us what they found most important in regards to making a monetary contribution via Venmo are:
<ul style="list-style-type:square">
<li>The ability to search for relevant causes</li>
<li>Trust issues are involved when making a contribution to a charity.</li>
<li>Privacy issues. The ability to make your payments private are currently in the app, but several Venmo users and one heavy Venmo user was unaware of that feature.</li>
<li>Social media plays a huge role when they make a contribution. If they see their friends are talking about a cause they support, then they are more inclined to support that cause as well.</li>
<li>One time payment method is preferred. People do wish to make as much monetary contributions as they can but not when it’s out of their control.</li>
</ul>
<p>
There was plenty of information users gave us and to keep every single thing in mind while thinking of how and what to implement to satisfy users needs, we created 3 personas based on our interviewee's responses.
<p>
<img src="/assets/img/pageimages/vds.jpg" alt="Early Sketches">
<p>
We collected as much data as we could and began our design phase with a methodology known as design studio. Individually, we would all rapidly generate many design solutions around specific problems on paper and after a few minutes we would converge and critique each other's ideas and iterate based on those critiques.
<p>
AND FINALLY, the user testing commences! Based on our first prototype, people said;
<ul style="list-style-type:none">
<i>
<li>"Banner is blocking my friend's activities. I rather it has it's own dedicated area instead of blocking my view." - S.</li>
</i>
</ul>
We didn't want to remove the banner completely otherwise people wouldn't seek out a place to donate money. The banner in this iteration was a solid color so to remedy this person's issue we lessened the amount of space the banner takes up.<p>
<ul style="list-style-type:none">
<i>
<li>"I would want to know how much money has been donate to this organization. What is the fundraising goal and how many people have donated." - D.</li>
</i>
</ul>
At first we thought simply adding a fundraising goal bar around the organization's page would be sufficient enough. But not all charities want to stop collecting funds so we couldn't include that. This person wanted to see more statistical information but we lacked the space. We held off on adding more information but we did keep this in mind.<p>
<p>
In addition to those specific problems, people have also questioned why the newly added "Report" button was taking up a huge portion of the profile page. People didn't like seeing the button so we moved the "Report" function behind the already present 3 dot menu. This gave us enough space to implement Venmo certification system. Inspired by Twitter's verification system, Venmo certification shows authenticity on the organization's profile page so users feel safe and secure about where their money is being donated to.
<p>
We also introduced a trending page, where users can see where people are donating their money towards. But people found this page confusing. They didn't know what was trending and under what basis. So we split the entire trending page to tabs labelled "Crisis" and "Hot Topics" for our next iteration.
<p>
Iteration 2 needed some tweaking. The banner displayed when there is an ongoing crisis is not engaging to users. People didn't even know it was a button so no one interacted with it. Visual changes were made to the banner to make it look more like a button.
<p>
Since our first iteration, people continued questioning why the ability to request money from a charity is available. Venmo does allow you to request money from anyone using the service but it's confusing our testing participants, so we added a button on the profile page labelled "Donate". On the "Donate" page, the ability to request money was removed. We didn't want to disturb the current user flow too much so we simply decided to add a Donate button on the profile page for our next iteration.
<p>
One user suggested to change up the format of the trending page. Changing the title of the tabs on the trending page from "Crisis" to "Current" so people can see more news and information about their friend's acitivities and "Hot Topics" to "Ongoing" would display all the current ongoing causes or charities.
<p>
We also noticed that not a single user at this point interacted or even seemed to notice the notification button at the top right of the page. We took this opportunity to replace it with a search button and moved the notification button to the hamburger menu.  
<p>
<img src="/assets/img/pageimages/vvf.png" alt="Click to view all screens on Behance">
<p>
Our final iteration left us with a few things we would've liked to continue further exploring. From the start of this project, we decided to start designing for Android first mainly because 2 out of 3 members of this group were primarily Android users. Throughout all of our iterations a floating action button(FAB) has been present but at iteration 3, it caused a distraction.
<ul style="list-style-type:none">
<i>
<li>"I wanted to click on the [floating action button] but I saw the [banner CTA] first so I clicked on that first" - C.</li>
</i>
</ul>
This person's attention was caught by the FAB because he was not familiar with Android OS. The FAB deviated another user tester from our intended user flow. After pressing on "VGive" she was confused of everything she saw on the screen and was not quite sure what to press on next. She resorted to clicking on the FAB instead of pressing on one of the charities that her friends donated to. We would've like to test our prototype on people familiar with the Android OS landscape to prevent users pressing on things due to unfamiliarity of the OS as opposed to our design decisions.<p>
<ul style="list-style-type:none">
<i>
<li>"I don't know what current and ongoing means, so I'm not gonna really select ongoing" - C.</li>
</i>
</ul>
The copywrite for the 2 tabs still need to be further explored. Several other users were also confused as to what exactly the 2 tabs meant. We also introduced a "Like" system in hopes that it would help users trust a cause or charity based on user feedback. No one has mentioned nor attempted to interact with the "Like" system. Before completely removing it due to no one interacting with it, we would've like to make it more apparent and hear if people actually would find a feature like this useful.
<p>
<center>
<a href="https://popapp.in/w/projects/56156de590d2b5ab5ad8555f/preview/56156e07004a79607e947248" target="_blank"><img src="/assets/img/pageimages/venmopss.png" alt="Click for Interactable Prototype"></a>
</center>

</body>
