# What is Unicode?

What is Unicode and why is the #MorePrideEmojis campaign focusing on them?  The Unicode Consortium is a non-profit group that essentially "owns" emojis.  They keep the official list of emojis and act as the gatekeepers for new emojis.  A lot of people mistakenly think that Apple and Google are responsible for creating emojis, but they all rely on what Unicode says.

This means that if you want a new emoji, you don't ask Google or Apple.  You have to ask Unicode.

To understand why, let's take a short trip back in time...

## The Chaos of the Olden Days

Today, if you visit a website that's in English, it will be displayed in Latin characters.  Arabic sites use Arabic, Russian sites are Cyrillic, Japanese sites are in Kanji, Hiragana, or Katakana, and so on.  On some sites, you can see all these different languages on the same page.  And it all just _works_.

This was not always the case.

Computers work on numbers.  That's all they know.  All these letters you're reading right now are numbers to the computer.  This page tells your browser "Please show character 65" and the browser puts an "A" on the page. This works because my keyboard and your browser both agree that character 65 is the letter "A".  But there's no natural connection between the number 65 and the letter A.  There's no particular reason why my keyboard and my computer couldn't say that the letter A is actually number 193.  As long as it's consistent on my end, where I hit the A key and see an A on the screen, I don't care what that number is.  But _you_ care, because if I say that A is 193 and send you a file like that, your browser is going to show you something like ┴ instead of an A.

That's literally how computers used to be.  Different systems used different numbers to represent letters, like some electronic Tower of Babel.  The end result was that if you tried to share anything between two different systems, it could turn into a corrupted mess.

Eventually, a consistent standard called ASCII won the day.  ASCII was great!  It had all the letters and numbers and some punctuation.  Now, when I typed an A, you'd see an A on your end, if I typed a %, you'd get a %, and when I typed a "竜", you'd see a...  Well, you'd see something like "ç«œ"...  

ASCII was designed with English in mind and was extended to cover most of the characters used by other Western European languages, but it doesn't cover anything outside of that.  Whenever other languages got involved, computers were right back at the electronic Tower of Babel.  You'd have to tell your computer "This is supposed to be Japanese" for it to understand that it needed to display the page as Japanese instead of as a jumble of Latin characters, and it still would only do that if you had the right fonts installed.  And if you didn't know that something was supposed to be Japanese, good luck trying to figure that out from the random characters on your screen.  That's obviously a problem for an increasingly interconnected world of computers.

This is where Unicode comes in.

The goal of Unicode is define a UNIversal enCODing for text on computers.  That means that my A is your A, your 竜 is my 竜.  Unicode does this by standardizing the numbers behind the characters for pretty much every language on the planet.  A is 65.  竜 is 31452.  And 😀 is 128512.

## The Origin of Emoji

😀 wasn't always 128512.  Unicode was originally focused on text and punctuation characters.  Along the way, they added a few pictographs and symbols, like arrows and hourglasses and chess pieces, but they were very limited.  If you wanted more expressive characters, you had to use fonts like Wingdings.  If you didn't have Wingdings installed, or your application couldn't display in different fonts, my "😀" would become a "J" on your side.  And, of course, there were multiple Wingdings-like fonts out there, so you'd have to know if I meant Wingdings or Webdings 2 or Dingbats.

So we're back at the electronic Tower of Babel again!  And like with all the other times, diverging systems demanded standardization to avoid confusion and complication.  Unicode initially resisted taking it on, but eventually faced enough pressure from the industry do something about it.  Emoji were the result.  The first set of emoji were largely based around the pictograms used by Japanese cell phone providers.

Like with letters, emojis are merely numbers to a computer.  Thus, 😀 became 128512.  Other emojis, like 🏳‍🌈, are sets of numbers.  For 🏳‍🌈, it's the combination of 127987 and 127752, which are the numbers for 🏳 and 🌈.  Whether it's a single number or multiple, Unicode is the one that controls which numbers mean what.

## Which Brings Us To Now

Unicode controls the numbers, so they get to decide what becomes an emoji and what doesn't.  In order for a new emoji to be created, it has to go through an approval process.  That process starts with a proposal.  The proposal process is public, so anyone can submit one.  You don't have to be a big corporation or have connections inside Unicode.  Once the proposal is submitted, it will get reviewed by the Emoji Subcommittee.  The review process is rather strict, somewhat arbitrary, and mostly opaque, and most proposals will get rejected.  If a proposal survives the review and is approved, it is added to the official list of Unicode characters.  At that point, Google and Apple and others will add the new emojis to their systems within about a year.

In 2020, proposals were made to add the bi and ace flags as emoji.  Unicode rejected both proposals.  The individuals who submitted these proposals are now both working on the #MorePrideEmojis effort.  We're planning to re-submit our proposals with additional pride flags this year.  If accepted, these new emojis would likely start hitting phones by late 2022.

Currently, it's possible for individual services to add their own unofficial emoji.  We've seen services like Skype and Twitch each add a series of pride flags, and people using Discord or Slack can add their own custom images.  But what works on Skype won't translate to what's on Slack, and none of these will work on Twitter or Facebook or a group text.

Hmmm...  Something that works one place, but doesn't work somewhere else, leading to inconsistency and confusion...?  Where have I heard that before?  _Is that a tower I see on the horizon?_
