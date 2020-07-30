![Banner](https://raw.githubusercontent.com/Wise-Badges/documentation/master/data/banner.png)

# **Bridges - WiseBadges**

## At open summer of code
 6 — 30 July 2020

# INTRODUCTION

WiseBadges is the result of great teamwork during osoc20, fits perfectly within the vision of Bridges and made possible by the funding of the Erasmus + programme. It makes giving and receiving recognition for women in STEM careers and education easier and less time-intensive.

The team created an attractive website which immediately invites people to select WiseBadges, select the receiver, add a unique and personal message and the badge is ready to be received. The process of sending WiseBadges takes less than a minute but means a ton for the receiver. It is an appreciation of what the receiver has done, achieved, and or meant for the sender.

The message behind WiseBadges is clear; it is all about empowering and supporting women in STEM. However targeting women, everyone is more than welcome to send and receive WiseBadges.

Let&#39;s spread the word.

# CONTEXT

## Target group

The audience we focus our communication towards and trigger to send WiseBadges:

 (Female) STEM students
 (Female) STEM professionals
 (Female) STEM communities

## Personas - Customer journeys


View our [Miro board](https://miro.com/app/board/o9J_kp9ukoo=/) for the personas and customer journeys

Women in STEM are a minority, and people who are part of a minority group have to overcome particular struggles, whether it is about finding a way to feel confident, finding belonging, finding needed value.

The same is true for women in STEM, and this is not just a feeling, facts show that women are underrepresented in both STEM education and careers. Even in 2020, the inequality in the work floor is still a reality. Women have fewer chances to get hired even when showing the same skills, get paid less, published less, and the list of facts is quite endless.

Our team found it essential to have an insight into the thoughts of women participating in osoc. After all, these women are an integral part of our target audience. To make this happen, we created a poll.

_A link to the poll and the results:_ [https://docs.google.com/forms/d/1QVPziZN73KKFYWAq2XIReXI6bY5-K0VoTdaeWzhA90Q/edit]

The poll showed that not many women participating in osoc know about the existence of female STEM communities, however the interest in becoming part of one seemed to be high. This is an important takeaway in terms of being visible. If the aim of WiseBadges is to create a community of like minded females, then visibility (multiple touchpoints) will be crucial.

Other than the input of female osoc participants and our own experiences we received valuable input from Emma Stoks and Manon Brulard. These meetings resulted in new insights in the needs, thoughts of females working in STEM. It was helpful in choosing which WiseBadges bring the most value, how to communicate this and general do&#39;s and don&#39;ts.

 List of female STEM communities (focusing on Belgium and Europe) can be found on [this Google Document](https://docs.google.com/document/d/151usQDwBnKIqrVUS0_Ms2T3NS9QSTSDwGovlKC3zLEw/edit)

# THE PRODUCT OR SERVICE

All useful links:

- Website: [https://wisebadges.osoc.be](https://wisebadges.osoc.be/)
- [Github](https://github.com/Wise-Badges)
- [Communication plan](https://docs.google.com/document/d/1l0AZbJk9eFqchswjuKWBTVkor2f8gfKpS0xxMIEyNrg/edit#)
- [Pitch](https://drive.google.com/file/d/1EJ3awE-MxgjyTaoHXam97X_OfMe60VTl/view?usp=sharing)
- Social media:
  - [Twitter](https://twitter.com/wisebadges)
  - [LinkedIn](https://www.linkedin.com/in/wisebadges)
  - [Instagram](https://www.instagram.com/wisebadges/)

###

# CREATING THE PRODUCT

## LOGO ![](RackMultipart20200729-4-1u3wc3z_html_4bded4ed59dc1bf9.png)

The logo of WiseBadges resembles a woman&#39;s figure. However WiseBadges is for everyone the main audience are women, we find it crucial to show this not only in the logo but in the overall look and feel of the website, the WiseBadges, and the tone of voice. ![](RackMultipart20200729-4-1u3wc3z_html_d53c5c38551e0d6c.png)

## PROCESS

Link to the steps of the creation process in [Figma](https://www.figma.com/file/Z0CXSEDbYkIGrhknq4Iion/Bridges-Final?node-id=138%3A161) (wireframes &amp; screen designs).

## FRONT-END

The front-end of the app allows the user to send special badges to others on Twitter and is built with Vue.js. The recipient can choose to accept or deny the badges they have received. To build a sense of community, there is an overview of people who have received badges on the website.

[https://wisebadges.osoc.be/](https://wisebadges.osoc.be/)

[Github &amp; documentation](https://github.com/Wise-Badges/frontend)

## TWITTER BOT

Twitter Bot is built to communicate with the users of WiseBadges through Twitter. From the front-end, the user is sent to Twitter to issue a badge just by posting a tweet. The Twitter Bot will see this tweet, and notify the recipient of the badge with another tweet which has a link to the front-end page of the badge (where all options will be shown: how to accept, delete, .. an assertion/badge). The deleting and accepting of a badge also happens through Twitter. Liking the post will accept the badge and commenting &quot;delete&quot; or &quot;invoke&quot; in any way will delete the badge, as well as a specially constructed delete tweet. Accepting the badge can only be done by the recipient, deleting/invoking the badge can only be done by either recipient or sender.

[Link of the bot](https://twitter.com/WiseBadges)

[Github &amp; documentation](https://github.com/Wise-Badges/twitter-bot)

## API

The Badge API is built with express, node and typescript. It allows clients to make, accept and delete assertions in the context of Open Badges. It also allows the client to get data from badgeclasses, assertions and the issuer (in this API, the issuer is WiseBadges), as well as get all assertions from a certain badge class. The API also makes it possible to get a download link for a verifiable Open Badge from an assertion.

[Link of the API](https://api.wisebadges.osoc.be/)

[Github &amp; documentation](https://github.com/Wise-Badges/badge-api)


# THE FUTURE

## Added value for the open source / open data community

Who can work with the code you made? What happens to the data? Who else can benefit, or build later?
 Through the created Slack channel the communication can continue after osoc20. The current team members are part of this channel and anyone (technical/ non-technical) who is interested in WiseBadges can become a part.
 In terms of developing, the Github page is open for anyone who feels like contributing.

[https://wisebadges.slack.com/home](https://wisebadges.slack.com/home)
[https://github.com/Wise-Badges](https://github.com/Wise-Badges)

## Fixes &amp; Bugs

Not any bugs at the moment, if so, these will be mentioned in the Github page.

## Future features and ideas

1. Let users make their own badge classes:

- Make the API accept POST requests for making new badge classes
- Add a page to the front-end to allow people to make their own badge class. This could be on the same website or could be a whole other website/project. (There could be the ability to design the images for the badge classes.)

1. The community page could be expanded: either by geographical maps, graphs, …
2. Now there is only a twitter bot, the ideal would be that people can issue badges through many platforms. If not already done by the open source community, there could be a facebook bot, linkedin bot, .. added.
3. Make a (twitter/facebook/..) button available that developers can just add to their page and it gives a pop-up of issuing a badge (so kind of like the website, but in pop-up version).
4. Possibility to save badges to _badgr_ backpack, or any other way of saving them.
5. When there will be lots of badges / assertions: it would be handy if users could search for badges / assertions or an easy way to navigate through them.
6. Front-end now only shows last 50 assertions (per badge it shows 50, and when selecting "all" it also shows 50), this should make use of the pagination of the API. So there are "next" and "previous" buttons needed to go through the assertions. This can also be integrated with (5.), a search functionality and multiple pages.
7. Right now we're struggling with Twitter: the account giving out the badges sometimes loses its rights to give notifications to recipients. Probably because we're sending out to many tweets. Trying to look for a solution for this problem is also very important.


# TEAM MEMBERS


**Anastasia Krouglova**
Student

[https://linkedin.com/in/anastasia-krouglova-3a67b91a4/](https://linkedin.com/in/anastasia-krouglova-3a67b91a4/)

[https://github.com/anastasiakrouglova](https://github.com/anastasiakrouglova)

[https://www.behance.net/anastasiak039f](https://www.behance.net/anastasiak039f)


**Asja Dabaut**
Student

@asjaontheroad

[https://www.linkedin.com/in/asja-dabaut-b72b27179/](https://www.linkedin.com/in/asja-dabaut-b72b27179/)


**Freya Van Speybroeck**
Student

@fvspeybr

[https://www.linkedin.com/in/freya-van-speybroeck-17ab001a7/](https://www.linkedin.com/in/freya-van-speybroeck-17ab001a7/)

[https://github.com/freyavs](https://github.com/freyavs)

**Sarah Van Den Berghe**
Student 

[https://www.linkedin.com/in/sarahvandenberghe/](https://www.linkedin.com/in/sarahvandenberghe/)

[https://github.com/SarahVanDenBerghe](https://github.com/SarahVanDenBerghe)

[https://www.behance.net/sarahvandenberghe](https://www.behance.net/sarahvandenberghe)

**Ward Beyens**
Student 

[@WardBeyens](https://twitter.com/WardBeyens)

[https://www.linkedin.com/in/wardbeyens/](https://www.linkedin.com/in/wardbeyens/)

[https://github.com/wardbeyens](https://github.com/wardbeyens) ![](RackMultipart20200729-4-1u3wc3z_html_1ce0a79703f0a835.png)

**Michiel Leyman**
Coach

[@MichielLeyman](https://twitter.com/michielleyman?lang=en)

[https://www.linkedin.com/in/michiel-leyman/](https://www.linkedin.com/in/michiel-leyman/)

 **Bert Jehoul** Coach
 
[@jeborsel](https://twitter.com/jeborsel)

[https://www.linkedin.com/in/bertjehoul/](https://www.linkedin.com/in/bertjehoul/)


# THANKS

WiseBadges would not have been possible without Bridges, Erasmus+ and Open Recognition. We would also like to thank Serge Ravet, Emma Stoks, Manon Brulard, Tim Baccaert and Alexander Vandoren for their valuable insights and continuous support.
