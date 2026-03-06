# Sofia's Santos \#024 OSINT exercise

`made on February 20, 2026`

### Task briefing

There are countless armed insurgent groups spread throughout the globe. The three images below depict individuals associated with internationally recognised terrorist organisations.

***Your task is to identify to which group they have pledged their allegiance.***

a) Photo 1  
b) Photo 2  
c) Photo 3

<p align="center">Photo 1</p>  
<p align="center">
    <img src="https://github.com/user-attachments/assets/abc88043-acce-478b-b115-5dc2e08e5114" width="600" />
</p>

<p align="center">Photo 2</p>  
<p align="center">
    <img src="https://github.com/user-attachments/assets/782c5ed6-314e-49a4-8c00-06b1e5784418" width="600" />
</p>

<p align="center">Photo 3</p>  
<p align="center">
    <img src="https://github.com/user-attachments/assets/201975d6-69d0-43fb-87ce-e93bddfc2927" width="600" />
</p>

<br>
<p align="center">∗ &nbsp;&nbsp;&nbsp; ∗ &nbsp;&nbsp;&nbsp; ∗</p>
<br>

To begin with, the first thing that comes to mind are the patterns that are visible at first glance. We will go through the images one by one, but first let's take a look at the first photo.

## Photo 1

<p align="center">
    <img src="https://github.com/user-attachments/assets/d388763a-59eb-45ff-ab1f-6d903a05a1f0" width="600" />
</p>

In this first photo, the identifying features are as follows: 
1. The red and black scarves that these soldiers wear to hide the lower part of their faces,
2. The barely visible emblem on the right shoulder of the soldier in the foreground. It is very difficult to make out what it is, but it reveals a white circle around the edge of the emblem and a horizontal line on the lower part of the logo that spans its entire diameter
3. A kind of emblem epaulette made of fabric, on which the initials of their group are probably inscribed. In any case, we can see an N, which must be the last letter of their group's initials. Most likely the same scarf worn over their faces here is hanging from the left arm of the soldier on the right. We can see the inscription.
4. Given the vegetation in the background, the image must have been taken in a region of the globe with a humid climate and therefore likely to include jungles or other dense forests.

So, the first places I'm leaning towards are either **South America** (Colombia, Venezuela, Brazil) or **Southeast Asia** (Cambodia, Vietnam, Indonesia). What we are going to do now is perform a **reverse image search**. We will see if Google recognizes certain patterns and if it can lead us to more information. To do this, I'll just go to Google Images and upload the photo.

<p align="center">
    <img src="https://github.com/user-attachments/assets/cd2b4158-c70d-47df-aa98-7d4a8edff638" />
</p>

**Now let's see the results.**

<p align="center">
    <img src="https://github.com/user-attachments/assets/dd98076e-e32e-421e-a035-f970d38f20ee" />
</p>
<p align="center">
    <img src="https://github.com/user-attachments/assets/d9a89ef5-a802-4eae-9bf7-fc05b64f31bd" />
</p>

Okay, that's some interesting information we have there.

First of all, the article titles confirm my initial intuition that the photo was taken in **South America**, because, as indicated, it was taken in **Colombia**. We also have the group's initials, **ELN**. We can also see the badge on the right shoulder of some soldiers and, of course, the red and black scarf bearing the ELN logo.

We will collect information for our survey from trow different sources. These will be as follows:
- The Guardian [(Source)](https://www.theguardian.com/world/2025/dec/12/colombia-eln-guerrilla-rebels-trump)
- Radio France International (RFI) [(Source)](https://www.rfi.fr/en/international-news/20231116-in-the-colombian-jungle-with-eln-rebels)

### From The Guardian – December 12, 2025

<p align="center">
    <img src="https://github.com/user-attachments/assets/f6993ba3-70a4-4f48-a004-3872c1c82bfd" width="600" />
</p>

The ELN (Ejército de Liberación Nacional) is the **oldest guerrilla group still active in the Americas**, with around **5,800 fighters** and a presence in more than a **fifth of Colombia's municipalities**. Claiming to espouse a **left-wing nationalist ideology**, it is nevertheless deeply involved in **drug trafficking** and the control of **coca plantations**. Despite five attempts at peace negotiations with successive governments—all of which have failed—the group continues to intensify its armed operations, including in response to threats of US intervention made by Trump in early 2025.

The Guardian points out that the ELN has been able to adapt to military and political pressure by modulating its actions, sometimes violent, sometimes negotiated, allowing it to **maintain its influence despite decades of conflict**.

So, to summarize here with our first source the key points to remember regarding the exercise: ***"Your task is to identify to which group they have pledged their allegiance"***, we can confirm for the moment that the people in the first photo have pledged allegiance to the **ELN**, a **Colombian criminal rebel group**.

### From RFI/AFP – November 16, 2023

<p align="center">
    <img src="https://github.com/user-attachments/assets/8126e09b-9497-4bb8-af65-22d5f2f45216" width="600" />
</p>

The ELN is a **decentralized organization**, composed mainly of **Afro-Colombian** and **indigenous members**, whose stated goal is to establish a “**democratic government for the people**” — with nationalization of industries and redistribution of land. Founded in **1964**, the group is now the last of its generation still active after the demobilization of the **FARC** (Revolutionary Armed Forces of Colombia) in 2016. Despite a ceasefire agreement with the Petro government, violations of the truce have been documented, and financing through kidnappings remains a reality that the organization struggles to completely deny.

