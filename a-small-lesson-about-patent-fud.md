% A (small) lesson about patent FUD.  
% Hugo Roy
% 2013-04-16


Steve Jobs, the MPEG LA and HTML5's \<video\>.
==============================================

On March 7, Google
[announced](http://blog.webmproject.org/2013/03/vp8-and-mpeg-la.html
"on the webM project blog") they reached an Agreement with
[MPEG-LA](https://pinboard.in/u:hugoroy/t:MPEG-LA/ "articles about
MPEG-LA in my pinboard") around patents that *“may”* cover the [open
video codec VP8](https://en.wikipedia.org/wiki/VP8 "Wikipedia
article on VP8").  

Thanks to this agreement, the most serious concerns that people
had about using VP8 and webM for their videos on the web are gone.
(Well, almost, because Nokia(/Microsoft) [claims to have patents
infringed by VP8 still](https://lwn.net/Articles/545562/ "LWN's
excellent article on the patents war around VP8")).

Monty from [Xiph.Org](http://www.xiph.org "the Xiph.Org
Foundation"), developer of free software and open video codecs
like [Theora](https://en.wikipedia.org/wiki/Theora "Wikipedia
article on Theora") is [very
happy](http://xiphmont.livejournal.com/59893.html) about this
announcement. Indeed, it shows that MPEG-LA has lost. They did not
have anything serious to bring VP8 down. 

 > Oh. Oh my. After a decade of the MPEG LA saying they were
 > coming to destroy the FOSS codec movement, with none other than
 > the late Steve Jobs himself chiming in, today the Licensing
 > Authority announced what we already knew. 
 >
 > They got nothing.

But what should remain from this? I think there are some lessons
to learn here for Free Software. Sure, MPEG-LA has lost. But who
won? Not us, and surely not the Web. 

The question is: how's that possible that a group of patent
holders who had nothing serious to stop adoption of webM and other
open codecs like Theora managed to impose on us their
patent-restricted codec?

Let's go back a little. The whole saga starts from the HTML5
group. (Bear in mind that this effort started outside of the W3C,
comprising mainly of browser-vendors including Apple and
Microsoft.) I don't have enough knowledge of the inside politics of
this group. But what remains out of it is that one of the most
discussed features of HTML5, the \<video\> element, is a failure.

## Why HTML5 \<video\> has been a failure

Why's that a failure? Because today, it seems that most of the
time HTML5 videos are encoded solely using the
[restricted-by-patents](http://www.mpegla.com/main/programs/AVC/Pages/Agreement.aspx
"MPEG-LA's patent licensing agreement excludes Free Software")
[AVC/H.264](https://en.wikipedia.org/wiki/H.264/AVC "Wikipedia
article on H.264/AVC") format. That means that publication on the
Web is now restricted by rules determined by a cartel of patent
holders (The MPEG-LA has been under investigation by the US
Department of Justice for anti-trust concerns [since
2011](http://gigaom.com/2011/03/04/doj-investigates-mpeg-la%E2%80%99s-webm-patent-pool/).)

This is certainly not how the web was envisioned. The web was
envisioned with freedom at its core. Just like Tim Berners-Lee
didn't have to ask anybody's permission to [make the Web work 22
years ago](http://blogs.fsfe.org/hugo/2010/12/the-web-is-20/
"The Web turned 20 in 2010")[¹](#fn), nobody should have to ask
anyone's permission to publish something on the web. 

## Why HTML5 \<video\> is still a failure

Now the second attack against HTML5 \<video\> [has
come](http://blogs.fsfe.org/hugo/2012/02/%E2%80%9Cunethical%E2%80%9D-html5-content-restriction-proposal-aka-drm/
"An unethical proposal"). We saw it coming, about a year ago. But
nothing was done. It is only now that I see a reaction (BTW if you
haven't done yet, please sign now to stop Digital Restrictions
Management (DRM) on the Web:
[http://www.defectivebydesign.org/no-drm-in-html5](defectivebydesign.org/no-drm-in-html5)).

Make no mistake. These are concordant, and very important attacks.
They will deeply change the Web if they succeed. Microsoft, Apple,
Netflix and others want to control who can publish videos (though
patents) and who can watch videos (through DRM). 

The first part (patents) seems lost. We have to fight for the
second part.

## What we need: to weigh in the political process of shaping HTML5 and to fight FUD

Here I want to focus a little bit on how they achieved to control
videos through patents and how this is related to what we're
witnessing with the proposal to include DRM in HTML.

These are some of the steps:

1. Make a technical proposal to the HTML5 group.

    Oppose inclusion in the standard of Free Software and claim
    the reason is concerns around patents.

    In case opposition come from Free Software folks, claim there
    is no problem because your proposal can be [included in
    hardware](http://blogs.fsfe.org/hugo/2012/02/%E2%80%9Cunethical%E2%80%9D-html5-content-restriction-proposal-aka-drm)


2. Spread FUD everywhere that Free Software implementations and
technological alternatives are violating patents. 

    (Of course, hope that nobody sees how hypocrite you are,
    because the patent risks come from your own patents and from
    organisations like MPEG-LA of which you are a part of)

3. Make vague threats of lawsuits and show your muscles. 

    (I now regret having participated in this by publishing Steve
    Jobs' answer to my [open
    letter](http://blogs.fsfe.org/hugo/2010/04/open-letter-to-steve-jobs/
    "An open letter to Steve Jobs - and a reply"). I should have
    handled this more carefully and contacted other organsations
    like Xiph.Org… This could have been a nice opportunity to
    debunk FUD more efficiently.)

4. Buy yourself time, [continue spreading
FUD](http://www.osnews.com/story/23058/Theora_More_of_a_Patent_Threat_than_H264_Wait_What_)


I think it's time to realise that building web technologies is a
process with political implications. They're trying to change the
web from a place where you're free to express yourself without
having to ask anybody's permission or having to agree to a
restricted-patent-license, into something where you cannot express
freely without paying for patents and where DRM prevent you from
doing legitimate things (like saving a private archive of online
content).

Of course, people who are aware enough of these issues will still
be able to publish using Free Software with webM and Theora, and
the next open codecs. Surely, there will be ways to crack DRM.

But what about everyone else? Do we want to accept the Web as a
fragmented place? No, we want to keep the Web as it is,
universal.

IMHO, the only reason why things aren't so bad is thanks to
Mozilla. By building Firefox, maintaining an independent browser
engine when everybody's going WebKit, and getting involved in the
whole HTML5 spec process, they've managed to hold back these
attacks. But they haven't succeeded entirely. How long before
Mozilla suffers from these attacks and cannot be as competitive as
other web browsers? 

We all need each other here. And I think it's time to bring some
political weight to the HTML5 process to counterbalance this.

* * *

<a id="fn"> </a>

1.  Actually, TBL did have to ask someone's permission: his
    employer, CERN. But it's totally unrelated ;-)
    [↩](#ref-cern-pd)

* * *

[Edit](https://pad.fsfe.org/p/nRrXNbLuOb)
[Source](https://github.com/hugoroy/blog/blob/master/a-small-lesson-about-patent-fud.md)
[Link](http://blogs.fsfe.org/hugo/?p=523)
