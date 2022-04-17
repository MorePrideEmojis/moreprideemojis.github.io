---
title: Our Response To Unicode's Announcement About Flags
description: Unicode is making a wrong move by banning new flags.  Find out why.
---

# Our Response To Unicode's Announcement About Flags

On March 28th, 2022, the Unicode Emoji Subcommittee made a blog post, titled [The Past and Future of Flag Emoji](https://blog.unicode.org/2022/03/the-past-and-future-of-flag-emoji.html).  While that title implies a glorious future for flag emojis, the reality is very different.  Unicode has slammed the door on all future flag emojis, refusing to even consider any future proposals in the entire category.  As a result of this decision, you will never see a bisexual or non-binary or any other pride flag emoji, nor will you see any other flags, like the red, black, and green Pan-African flag.  No matter how widespread, how popular, or how important, Unicode just says no.

Much of the blog post is dedicated to discussing country flags, and using them as the basis for a justification for rejecting all other flags.  Let's break down their points and explain why they are not a valid justification for rejecting all flags going forward.

**There are over 200 flags, and many of them are among the least used emoji.**

This point is true, but largely irrelevant.  Country flags are often a sign of national pride, so countries that have a higher population, or a population that is more on-line, or that have a better sports team for the Olympics or World Cup, will tend to have more flag use, because there are more people who are interested in using that flag.  It's not always a direct correlation (China and India have populations several times the population of the US, but their flags are used less.), but it is a general trend.

Take, for example, Liechtenstein.  The Liechtenstein flag emoji consistently ranks very low on lists of emoji usage frequency.  That's understandable, because the population of Liechtenstein is around 40,000 people, less than the typical in-person attendance of an NFL game.  It is likely that the flag of Liechtenstein sees less use than the Seattle Seahawks "12th Man" flag.   But it's not just people who are physically at the game who might use that flag, it's the entire population of the Seattle sports market, which is roughly five million people.  About half the countries in the world have a population of less than five million people.  So is the "12th Man" flag more popular than half the national flags in the world?

There is a clear structural reason here for why the existing flags as a category see low use, and it is disingenuous to extrapolate that all flags will also see such limited use.  A common estimate of the prevalence of asexual people would indicate that there are at least 79 million aces in the world.  That's more than the population of the UK and France, and just shy of the population of Germany, all of which have country flags that see above median use.  Some estimates claim that the number of bisexual people worldwide rivals the population of the United States, the third most populous country in the world, and holder of the most used flag emoji. (According to the [Ipsos LGBT+ Pride 2021 Global Survey](https://www.ipsos.com/sites/default/files/ct/news/documents/2021-06/LGBT%20Pride%202021%20Global%20Survey%20Report_3.pdf), around 1% of the world population is ace, and 4% is bi.)  Going by these numbers, it is reasonable to conclude that pride flag emojis would out-perform the majority of the existing flag emojis.

Further evidence:  The second most popular emoji flag, after the US flag, is the Rainbow Flag.  The rainbow flag is also one of the few flags to gain usage between 2019 and 2021, according to Unicode's own statistics.  Additionally, Pride Flags will have worldwide appeal and use, they are not limited to one country or region or culture.

**ISO 3166-2 Subdivisions are Unused, So No Other Flags Would Be Used**

This section of the blog post is a bit technical and may be hard to understand.  What they're saying is that countries are on a list called "ISO 3166-1", and that anything on that list automatically is an emoji simply by virtue of being on that list.  That's why you end up with tiny, tiny places like the Pitcairn Islands, population 50, getting an emoji.  Then, in 2016, they said that any region on the "ISO-3316-2" list _could_ be an emoji, if anyone wanted to make it one.  This "-2" list has states, provinces, cantons, that sort of thing.  They explain that the only three regions from this "-2" list which are widely implemented are England, Scotland, and Wales.  Then, the post wonders, "So, with so many 'valid sequences' why hasn’t anyone taken advantage of this sweet sweet rich flag opportunity?"

They are completely glossing over their own role in why that's the case!  The "valid sequences" they mention are part of the Unicode standard, which are a set of guidelines that say "You are _allowed_ to do this, and if you _want_ to do this, here's how to do it."  But what they aren't is a recommendation that you _should_ do it.  Emojis that an implementer _should_ include are called "RGI", or "Recommended for General Interchange".  That is a much smaller set.

Most emoji implementers stick to the RGI set, and hardly ever bother with the rest of the "valid sequences", because of self-sustaining circular apathy.  The whole point of Unicode is to share text between systems, and it relies on everyone involved doing the same thing.  So, Apple implements RGI and doesn't implement the rest of the valid sequences because that's what Google does, and Google does that because that's what Apple's doing, and in the end, that's why no one anywhere has a British Columbian flag emoji on their phones, even though it would technically be allowed.

So, what of England, Scotland, and Wales?  Why are they the only ones out of the that ISO-3316-2 to have widely adopted emojis?  _Because Unicode said so!_  Those three -- and _only_ those three -- ISO-3166-2 codes are on the "You _should_ include these" RGI list.  That means that everyone is going to include them because everyone else is going to include them.  They would not have been implemented otherwise, and if Unicode truly wants to see more of the ISO-3166-2 flags get implemented, all they have to do is say they're now "Recommended For General Interchange", and they will get implemented more broadly.

All of that aside, this whole section is hand-waving misdirection.  If implementers want to include those regional flags in the "-2" list, they can, because Unicode explicitly has said "These flags are legal in our standard and here's how you do it.".  But there is _nothing_ in the standard like that for Pride Flags.  There's no ISO-3166-QUEER list for identities, which means there's no instructions on how to include additional pride flags, even if someone wanted to.  Without that, any emoji provider would be on their own in coming up with how a flag should be represented in computer code, which means that Google and Apple and others might come up with _different_ ways to represent the flags.  That would mean that additional flags would be incompatible across different systems, which was the very problem Unicode was created to prevent.

**Flags Aren't Frequently Used In Social Media Profiles**

They claim that flags don't get a lot of use in social media profiles, and that is a reason for not including more flag emojis.  However, they then list the top five Twitter bio emojis as proof:  ❤️✨💙💜💛

How many of those hearts are being used to represent Pride flags that don't exist as emojis?  Furthermore, the [paper that they cite](https://aclanthology.org/2020.nlpcss-1.22.pdf) shows that the Rainbow Flag is one of the _most_ popular emojis used in Twitter bios, and is even more popular than the US flag for that purpose.

**Pride Flags Change Too Much**

One of the more bizarre statements in the blog post is the following:

> In the past six years since adding a Pride Flag to the Unicode Standard (2019) it’s already been redesigned. Many times.

This is flatly untrue and is revealing of their total ignorance on this subject.  The rainbow flag which was turned into an emoji has been unchanged since 1979.  That makes it older and more stable than many country flags that are included as emojis, in fact, it's older than many of those countries themselves.  It's even older than Unicode itself!

But even if it had changed, that wouldn't matter!  As they mention later on in the post, country flags do change and when that happens:

> Unicode does not specify the appearance of flag emoji. It is the responsibility of font designers to update their fonts as politics change.

So, if a pride flag _does_ change, it's not Unicode's problem!

**You Can Use Stickers, Gifs, and Image Attachments**

No.  No, you cannot.  Again, Unicode is ignoring its role here.  An emoji sequence approved by Unicode is supported everywhere that the standard is implemented.  I can copy a Tweet over to Facebook and it works.  I can take that Facebook post and save it in a text file and it works.  I can import that text file into a database and it works.  And it works because of the Unicode standard that makes sharing that content across diverse services and systems.  Stickers and image attachments are platform specific and non-portable.

**Emojis Are Too Small For Flags**

This statement is not true for the vast majority of Pride Flags, and is therefore not a reason to reject them.  The following graphic proves this, by showing a series of flags at 10 pixels high:

![A series of small pride flags.](/images/10px-flags.png)

Even at such a small size, smaller than the size emojis are generally displayed, the flags are recognizable.

**Flags Make Emoji Fonts Too Large And Too Hard To Implement**

The post argues that flags are a significant burden on implementors that is not justified by their level of use.  We've already gone over how the "level of use" argument doesn't hold water when it comes to Pride Flags, so we won't rehash that here.  Instead, it is worth pointing out that implementors are free to leave out any emojis they do not wish to implement.  The "Recommended For General Interchange" list is, as the name says, just a recommendation.  There is nothing that requires an emoji provider to have a design for any particular emoji.  Emoji providers can balance consumer demand with effort involved and make a decision on what they want to include.

As the blog post points out in an aside, Microsoft has never implemented country flag emojis.  If you view a string of text that contains a country flag emoji on Windows, you will see pairs of letters like "US" or "LI" in place of the flag image.  Microsoft is compliant with the standard, even without these images. 

But do you know what flags Microsoft _has_ decided to implement?  🏳️‍⚧️🏳️‍🌈  They have decided that it is worth supporting the two Pride Flags that are RGI, even though they don't support any country flags.  Yet Unicode's decision to not standardize any other flags prevents Microsoft, and any other emoji provider, from including any additional flags, even if they wanted to.  And there is evidence that Microsoft _would_ want to.  Their Skype messaging service has had a wide variety of Pride Flags available for years, and they have showcased many flags in some XBox games and device skins.

**You Can Use Hearts Instead**

Unicode has offered the suggestion that users simply use colored heart emojis to represent the missing Pride Flags.  This is clearly misguided and inadequate.

On a practical note, there simply aren't enough colored hearts to make every pride flag, even with the three they are adding this year.  The aro flag has two shades of green.  Various Lesbian flags involve multiple shades or orange or pink.  Then, because different flags involve different numbers of colors, anyone using hearts would potentially have to use an unwieldy amount of characters, which could run into character counts and line breaks or other limitations. Additionally, hearts are not specific enough.  If I post 💚🤍🖤, is that message aro, agender, demiromantic, or about the Kingdom of Jordan?

Hearts also have a "love" or "romance" connotation that is inappropriate for a number of contexts.  Aromantic people may not want to use hearts for many reasons.  In a formal context, such as a corporate DEI group or professional association, use of flags to signify one's identity would be acceptable, while a string of colored hearts would seem unprofessional.

# Conclusion

We believe that Unicode's decision to stop accepting additional flag emojis is short-sighted and wrong, and we believe their stated justification for that decision is shallow and easily dismissed.

If Unicode does not want the responsibility of determining which flags should be RGI, they can hand that authority over to another party, as they have done with their decision to delegate responsibility for which country flags are RGI to the ISO-3166-1 list.  If Unicode is concerned about implementation burdens, they should remember that they are not the implementor, just the coordinator, and that any implementor can make their own decisions.  If Unicode is concerned about the prospective usage levels, they should consider including more emojis that people are clamoring for, like Pride Flags, and less that no one really has asked for, like "Shake Face".