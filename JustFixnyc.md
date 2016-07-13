---
layout: page
#title: JustFix.nyc
permalink: /justfixnyc
---
<button onclick="goBack()">Go Back</button>

<script>
function goBack() {
    window.history.back();
}
</script>
<body style="font-family:PT Serif;">
<i>
JustFix.nyc is a responsive website designed to provide tenants and caseworkers the ability to document, organize, and take action in securing repairs on your apartment. Me and my team, Adam Wong and Stacey Zhou, were tasked to refine the service, implement and validate client's existing ideas for features and discover new features. The tool is targeted to help low­ income, underrepresented New Yorkers navigate the complex bureaucratic process of resolving issues related to housing ­­including tenant harassment, wrongful eviction, and maintenance repairs.</i>
<p>
<img src="/assets/img/pagebanner/jfnpagebanner.png" alt="JustFix.nyc">
<p>
The ideas JustFix.nyc already had in mind but have yet to validate usefulness are;
<ul style="list-style-type:square">
<li>PDF conversion of tenant's recorded documentation</li>
<li>Audio recording</li>
<li>Ability to share the case with case workers and neighbors</li>
<li>Removing as much text input from user as possible</li>
</ul>
<p>
Initially, we were all confused and had no idea what being a user on that side would feel like so the first thing we did was visit a housing court. We needed to fit the mentality and learn about the bureaucratic process that tenants have to deal with when resolving their housing issues. So the research begins.
<p>
<img src="/assets/img/pageimages/jfnhc.jpg" alt="New York City Housing Court">
<p>
During our visit to the housing court we interacted with just about everything and everyone we can; computers, tenants, employees, and the court room. There were computers running a software designed to help people walkthrough the bureaucratic process but we saw no one interacting with it. We made an attempt to find information pertaining to a walkthrough of the bureaucratic process or accessing a FAQ section, but couldn't. We assesed that the service was extremely outdated, filled with law jargon, and required an extreme amount of specific information in order to get any actual help.
<p>
We talked to a few people on line waiting to be attended and learned they were tenants handling their own housing court issues. The line right next to it was for tenants being represented by a housing court lawyer and of course, that line was empty. The majority of people handle their housing court issues on their own, alone.
<p>
While we were sitting through several housing court cases, we noticed how unorganized and quick everything was going. Cases were in motion at once, defendants approached the bench and left within 5 minutes or so, but the most unexpected thing we saw was a woman presenting photos to the judge straight from her iPad. Everyone there just wants to get things done quick and go home.
<p>
After reviewing our notes taken from the helpful visit to the housing court, going through all the resources our client provided for us(second hand documents about NYC's bureaucratic housing court process) and scouring the internet for even more information, we sent out a screener survey to recruit people to interview. Based on the scheduled interviews we prepared and the scheduled interviews JustFix.nyc has prepared for us, we learned;

<ul style="list-style-type:square">
<li>Tenants have little to no relationship with their neighbors</li>
<li>Tenants are unaware of the proper steps to take when dealing with housing court issues</li>
<li>Tenants are unaware of their rights as a tenant in NYC</li>
<li>When reporting issues, tenants would report mainly via phone calls</li>
<li>Documentation they collect of their housing issues are unorganized</li>
<li>Tenants don't know how to prepare for housing court trial</li>
<li>Tenants have an interest to learn about their rights as a tenant</li>
<li>Tenants are extremely sensitive about their personal information</li>
</ul>
<p>
And at this point we've finished collecting our data, synthesized it into 3 personas, and began the design phase.
<p>
<img src="/assets/img/pageimages/jfnv1.png" alt="Click to view all screens on Behance">
<p>
Justfix.nyc had given us their ideas and the way we incorporated them were;

<ul style="list-style-type:square">
<li>Implemented audio recording by adding a new card. Every task on the service is sent to the user's "To-Do" tab, in the form of cards, which made it pretty clear that this is where it belongs. The optimal placement of the audio recording card was to be decided after user testing.</li>
<li>Removing as much text input as possible is a long-term goal, but definitely do-able. The copywrite of existing issues to select from the "Checklist" tab were condensed to let the pictures and details that the user inputs speak louder.</li>
<li>A community tab was created. Under this new tab users are able to communicate with other members in their building in a Facebook-like feed. By giving them a platform to communicate amongst each other, they are then able to bring up issues and collect even more evidence to their landlord with confidence.</li>
</ul>
<p>
We also implemented ideas born from user interviews;

<ul style="list-style-type:square">
<li>Added an education aspect site-wide. For every page load, a random tenant rights fact is generated in a non-intrusive area(at the bottom of the page before the footer) so users are learning as they utilize the service. This information is pulled from a newly created page, "Tenant Rights". On this page people can read a simplified version of their rights, motivating users to learn rather than being put off by walls of texts filled with jargon</li>
<li>Being able to navigate and utilize the service without signing up was also added. The alpha required users to go through an extraneous sign up process involving their phone number and address. User interviews suggest this kind of information is extremely private and people would not be willing to give this service a chance due to the sign up process. Anyone would be able to navigate and interact with the "Check list" and "To-Do" tabs. People would then be required to sign up if they wish to interact with "Your Case" and "Community". When dealing with sensitive information, it is important to be transparent with your users and let them know why the information is required. "Your Case" tab requires user information such as phone number and address because this section generates an exportable PDF document that can be sent to your superintendent, landlord, caseworker or appear as an organized document to be shown in court. "Community" tab requires information such as address and apartment number to be placed in a community with other members of your building and for the privacy of other members.</li>
<li>"Your Case" tab has been overhauled and given a streamlined user flow where people can export all of their documentation into a PDF that they can then send via e-mail or text to their superintendent, landlord, or caseworker. People can also share specific issues with their neighbors through the newly created community tab.</li>
<li>A new landing page was created. The old landing page's purpose was created to demonstrate the service to potential business partners, not potential users.</li>
</ul>
<p>
<img src="/assets/img/pageimages/jfnvf.png" alt="Click to view all screens on Behance">
<p>
And finally, all of these ideas have been enhanced through user testing. Prototype 1.0, people have commented on a few issues;

<ul style="list-style-type:square">
<li>Tenant Rights page was too concealed</li>
<li>Lots of confusion towards what the community tab actually was</li>
<li>Misunderstanding of several cards in "To-Do" tab</li>
</ul>
<p>
When people found the Tenant Rights page, their interest peeked, were surprisingly really delighted, and questioned why it wasn't apparant. It was very well received so making it more apparant for the next prototype was a must. We made the Tenant Rights page accessible from the landing page.
<p>
The community tab wasn't very well received. People laid eyes on "community" and were turned off. But after they explored the tab they saw the potential it holds. In a service that holds important information, people did not want to engage in any sort of community so the tab was renamed to "My Building".
<p>
Every card in "To-Do" has a title and a detailed explanation of what they meant but users were still confused, a card labelled "Call Hotline" elicited the most confusion. We clarified the meaning of a few cards by renaming them.
<p>
While testing prototype 2.0, not many new issues were brought up. The one new issue that made users feel uncomfortable pertained to privacy issues. People were unsure if hitting the "Share Case" button would automatically share their entire case to their neighbors or if it let them select the cases they want to share. People were hesitant when dealing with sharing sensitive information and we wanted to eliminate as much hesitation as possible so we changed the flow. We made the option to select the cases you'd like to share immediately visible first, and then enabled users to share what they have selected with a button clearly indicating that the selected content is being shared with users.
<p>
<center>
<a href="https://projects.invisionapp.com/share/KT4WXOUJR#/screens/115062107" target="_blank"><img src="/assets/img/pageimages/justfixnycpss.jpg" alt="Click for Interactable Prototype"></a>
</center>
<p>


