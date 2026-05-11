# Sofia's Santos \#006 OSINT exercise

`made on April 4, 2025`

### Task briefing:
On January 19, 2023, a journalist with almost 140k followers on Twitter shared an image of a destroyed vehicle amidst a large cloud of smoke and fire. The tweet said: **"BREAKING: TTP carried out a suicide attack on a police post in Khyber city of Pakistan that killed three Pakistani police officers."**

The photo is not of the event described by the journalist.  
**a) Verify the statement above.**

<p align="center">
    <img src="assets/Step 0 - image source.png" width="600" />
</p>

We therefore need to verify the veracity of this tweet.

Find the original photo, its date of publication and its context.

<br>
<p align="center">∗ &nbsp;&nbsp;&nbsp; ∗ &nbsp;&nbsp;&nbsp; ∗</p>
<br>

To begin with, the description of the tweet refers to a terrorist attack carried out by the TTP in Pakistan in the city of Khyber, which killed three Pakistani police officers. The presumed date of this event is January 19, 2023 (date of publication of the tweet highlighting the #BREAKING, thus accentuating the immediate effect of the event).

<p align="center">
    <img src="assets/Step 1 - Date of the tweet.png" width="400" />
</p>

The first thing to do is to perform a reverse image search. To do this, we will use TinEyes. Copy the photo and paste it into the TinEyes search engine.

<p align="center">
    <img src="assets/Step 2 - TinEyes image searching engine.png" width="600" />
</p>

You’ll come across hundreds of results. A huge number of sites containing this image. However, you must be careful not to factualize from just any site. We need to identify a few "safe" sites that have a certain public legitimacy.

<p align="center">
    <img src="assets/Step 3 - Image searching result.png" width="600" />
</p>

Already, on the first page, the first two results that host this photo are; **alamy.com** (which is a media library offering a diverse range of photos, videos and archive content) and a **Wikipedia** England source.

Now let's check whether these two seemingly "safe" sources indicate the same date and context.

* For **alamy.com**, the photo was taken on **August 27, 2006**.

<p align="center">
    <img src="assets/Step 4 - First source.png" width="600" />
</p>

* For the **Wikipedia** link, we had to go down to the page entitled '**Al-Qaeda in Iraq**' and find the photo embedded in the text in the '**October 2006: AQI creates Islamic State of Iraq**'. Click on the small frame just below the picture to enlarge it. The '**More details**' option will then appear in the bottom right-hand corner. Clicking on it gives access to the photo’s file information and metadata.

<p align="center">
    <img src="assets/Step 4 - Second source.png" width="600" />
</p>

* We can see the description of the photo (its context), and the date it was taken. Which is also **August 27, 2006**.

<p align="center">
    <img src="assets/Step 5 - Confirmation source.png" width="600" />
</p>

* We can also see the metadata for this photo shown right here:

<p align="center">
    <img src="assets/Step 5 - Photo metadata.png" width="600" />
</p>

* I then opened the link named '***exact source***' in '**File information**'. But I came across a page with a 404 error.

<p align="center">
    <img src="assets/Step 7 - Error 404 on the website source.png" width="600" />
</p>

* So I copied the URL link and pasted it into the time machine. I got a match on **March 04, 2016**.

<p align="center">
    <img src="assets/Step 8 - Recover via the Wayback Machine.png" width="600" />
</p>

So we've just found the original source! So we were dealing with fake news in the original tweet. The event was not taking place in Pakistan in January 2023, and was not initiated by the TTP. The event was photographed in Waziriya, Iraq, on August 27, 2006.

The context behind the photo is distinctly different, and is described as follows: "A Vehicle Born Improvised Explosive Devise (VBIED) after exploding on a street outside of the Al Sabah newspaper office in the Waziryia district of Baghdad, Iraq. The VBIED destroyed more than 20 cars, killing two people and wounding as many as 30. U.S. Navy photo by Mass Communication Specialist 2nd Class Eli J. Medellin".

<p align="center">∗ &nbsp;&nbsp;&nbsp; ∗ &nbsp;&nbsp;&nbsp; ∗</p>