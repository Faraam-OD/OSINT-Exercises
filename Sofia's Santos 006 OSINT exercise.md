# Sofia's Santos 006 OSINT exercise

### Task briefing:
On January 19, 2023, a journalist with almost 140k followers on Twitter shared an image of a destroyed vehicle amidst a large cloud of smoke and fire. The tweet said: “BREAKING: TTP carried out a suicide attack on a police post in Khyber city of Pakistan that killed three Pakistani police officers.”

The photo is not of the event described by the journalist.
a) Verify the statement above.

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236013-5b361089-6327-4d06-a62f-9c955d0610ec.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDAzNzAsIm5iZiI6MTc3MDI0MDA3MCwicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDEzLTViMzYxMDg5LTYzMjctNGQwNi1hNjJmLTljOTU1ZDA2MTBlYy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTIxMTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yN2Y1NTdlNDNiZDc3NjVlMDFkN2VlNDUwN2VhYWY2ZWFmMzY2NmYyOGY4OWVkZjFiZWFkNzY1M2JhZGNiNGIwJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.6UKt9doZFe-PbRCRAjVjFKi0yyrhA3ZRv7syEFd0f8c" />
</p>

We therefore need to verify the veracity of this tweet.

Find the original photo, its date of publication and its context.

<p align="center">∗ &nbsp;&nbsp;&nbsp; ∗ &nbsp;&nbsp;&nbsp; ∗</p>

To begin with, the description of the tweet refers to a terrorist attack carried out by the TTP in Pakistan in the city of Khyber, which killed three Pakistani police officers. The presumed date of this event is January 19, 2023 (date of publication of the tweet highlighting the #BREAKING, thus accentuating the immediate effect of the event).

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236010-87501081-ff5e-4063-98b4-6d7f8269eba1.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDAzNzAsIm5iZiI6MTc3MDI0MDA3MCwicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDEwLTg3NTAxMDgxLWZmNWUtNDA2My05OGI0LTZkN2Y4MjY5ZWJhMS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTIxMTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00NjJkNzNlZjA3ZmY0ZDBhYTdkN2FlMmNmZGZkZTc3Njc0ZjU0NzA0OTgyYTNmOGVjNTY2N2U4MmRmODcwZDliJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.uzDrkgUYthF-e547Wj3X9oA4GW47VnaBpOHarStdQfI"/>
</p>

The first thing to do is to perform a reverse image search. To do this, we will use TinEyes. Copy the photo and paste it into the TinEyes search engine.

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236017-12fb577e-164a-421a-b9e4-0a2521ca9d7b.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDAzNzAsIm5iZiI6MTc3MDI0MDA3MCwicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDE3LTEyZmI1NzdlLTE2NGEtNDIxYS1iOWU0LTBhMjUyMWNhOWQ3Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTIxMTBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT00ODcxYmRiMDQxNjg3ODg4NjZmNTQ2NmU2Y2M0ZjhlOGY4ODM1ZGZlOTY1OWIxYWY4OGY2ZmMzZmI3Y2M4MjFkJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.Kw2IxiyNrl1Dt72T1WZ0mnicUTr8yJ_Hx_rkF8_daaI"/>
</p>

You’ll come across hundreds of results. A huge number of sites containing this image. However, you must be careful not to factualize from just any site. We need to identify a few “safe” sites that have a certain public legitimacy.

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236011-01c798a1-bb60-4900-b46f-2fcf7938617b.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDA3MDMsIm5iZiI6MTc3MDI0MDQwMywicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDExLTAxYzc5OGExLWJiNjAtNDkwMC1iNDZmLTJmY2Y3OTM4NjE3Yi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTI2NDNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wN2E4ZGIwMWU1ZTczY2U3MmVjMDc5YTliYWRhY2JmOTI1ZWMxMzk5OWViOGU3MGFjMTJkYjhiNzViYzY5YThiJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.fxg0b-DiOfiw2FUAB_KEYBQSBi-X9sPt-YZVrWk3Hw4"/>
</p>

Already, on the first page, the first two results that host this photo are; alamy.com (which is a media library offering a diverse range of photos, videos and archive content) and a Wikipedia England source.

Now let’s check whether these two seemingly “safe” sources indicate the same date and context.

* For **alamy.com**, the photo was taken on August 27, 2006.

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236018-99d7fb18-4364-40f6-a7e3-04c2cffc4d32.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDA3MDMsIm5iZiI6MTc3MDI0MDQwMywicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDE4LTk5ZDdmYjE4LTQzNjQtNDBmNi1hN2UzLTA0YzJjZmZjNGQzMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTI2NDNaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hMGRkZDE1YTA3ZWEzNGI5ZGJhZGY4NzBmZDM3NzAzNmMxNjhlMDY4MWNhMjZhN2IzYjZlYjUyNWYyYzk0YTI0JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.SqYOpYvTmPpFXBORuvk3ik637dlUBv7JNsL-oVd0OKk"/>
</p>

* For the Wikipedia link, we had to go down to the page entitled ‘Al-Qaeda in Iraq’ and find the photo embedded in the text in the ‘October 2006: AQI creates Islamic State of Iraq’. Click on the small frame just below the picture to enlarge it. The ‘More details’ option will then appear in the bottom right-hand corner. Clicking on it gives access to the photo’s file information and metadata.

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236014-3015d196-3062-42f1-94e2-b5027baf9d88.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDA5NjcsIm5iZiI6MTc3MDI0MDY2NywicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDE0LTMwMTVkMTk2LTMwNjItNDJmMS05NGUyLWI1MDI3YmFmOWQ4OC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTMxMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02NzRlYjc3NWQyMzA3NDQyNDIwOTY4YjEyMTk0ODQ3MTZlMWUwM2RjN2MxNzQ3OTlmOGI5MzVlOTY3NGEyNjA3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9._WhcT-bNLG-f9OkEnOlQC6ZMIui2dQBX5qSwuqj0Xug"/>
</p>

* We can see the description of the photo (its context), and the date it was taken. Which is also August 27, 2006.

<p align="center">
    <img src=https://private-user-images.githubusercontent.com/172454262/545236016-ca47ac66-eacf-441f-a872-11d18f6ab81c.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDA5NjcsIm5iZiI6MTc3MDI0MDY2NywicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDE2LWNhNDdhYzY2LWVhY2YtNDQxZi1hODcyLTExZDE4ZjZhYjgxYy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTMxMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1iOThjZjJkOTNkYzIzOTUxODYwZmZjNzljYzg1NTA3OWFlZTJlZjNhNDQ5OWY5YWJlMWQxZjkwMDY1OWQ3NTA1JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.uQ50xfob_tEClzFlKOZXojFUeYHC2blC5y7s4SsdpKc"/>
</p>

* We can also see the metadata for this photo shown right here:

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236019-5def8a39-2446-4529-aa18-152c725173c3.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDA5NjcsIm5iZiI6MTc3MDI0MDY2NywicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDE5LTVkZWY4YTM5LTI0NDYtNDUyOS1hYTE4LTE1MmM3MjUxNzNjMy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTMxMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zMzBhMjhlMGM4Y2ZiMzc3MjdkYzY3MGIzYmFmM2QzMWEyYmZjYzUwMmZjZDJiOWVkMmQ3NTk5NWYwOGQxZTQ2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.BBgKK4rpSx9WTmJkGGp82Qx41EOLqeJh82ueOCLbhso"/>
</p>

* I then opened the link named ‘exact source’ in ‘File information’. But I came across a page with a 404 error.

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236015-5b89ad6a-d341-4370-9c4a-0dd90b9c2032.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDA5NjcsIm5iZiI6MTc3MDI0MDY2NywicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDE1LTViODlhZDZhLWQzNDEtNDM3MC05YzRhLTBkZDkwYjljMjAzMi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTMxMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1mNWVkNTllY2NhZDZiMjk2ODZhMDAzYWJkMjU1NDRiMTAxNGY1ZGVkMjI0YTJhNmNiN2Y0OTZlYWViOTYwMmE5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.R0qNIo-Qa2cSXbhHS_nt9duZ1H4_V-57NKo5bB33lSo"/>
</p>

* So I copied the URL link and pasted it into the time machine. I got a match on March 04, 2016.

<p align="center">
    <img src="https://private-user-images.githubusercontent.com/172454262/545236012-5eeeb6ea-6c22-42ed-bd05-c1941ee778aa.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzAyNDA5NjcsIm5iZiI6MTc3MDI0MDY2NywicGF0aCI6Ii8xNzI0NTQyNjIvNTQ1MjM2MDEyLTVlZWViNmVhLTZjMjItNDJlZC1iZDA1LWMxOTQxZWU3NzhhYS5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMjA0JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDIwNFQyMTMxMDdaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yNTdkNWRlY2Y5MjJiZTYzOGZmNzA2OGE3NjkxYTc3ZjQzZmY5Njc2YzM2NTk5ZGRkYjkzYWJiZWQzNDIzY2QyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.olKLPR8Tu5YN6JuhTQb2HXerkBlAsoibmUA1Wpe64zQ"/>
</p>

So we’ve just found the original source! So we were dealing with fake news in the original tweet. The event was not taking place in Pakistan in January 2023, and was not initiated by the TTP. The event was photographed in Waziriya, Iraq, on August 27, 2006.

The context behind the photo is distinctly different, and is described as follows: “A Vehicle Born Improvised Explosive Devise (VBIED) after exploding on a street outside of the Al Sabah newspaper office in the Waziryia district of Baghdad, Iraq. The VBIED destroyed more than 20 cars, killing two people and wounding as many as 30. U.S. Navy photo by Mass Communication Specialist 2nd Class Eli J. Medellin”

<p align="center">∗ &nbsp;&nbsp;&nbsp; ∗ &nbsp;&nbsp;&nbsp; ∗</p>

P.S. This is my first OSINT exercise. Thank you again Sofia for providing us with this support to learn and improve in this incredible field of OSINT.

*made on April 4, 2025*