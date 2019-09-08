# Floatlink
A minimal webring solution.

## What is a Webring?

> A webring (or web ring) is a collection of websites linked together in a circular structure, and usually organized around a specific theme, often educational or social.[1] They were popular in the 1990s and early 2000s, particularly among amateur websites. — Wikipedia

Webring was one of the popular ways of discovering new website on a specific topic (and also a popular way to expose your website to more viewers) back in the Web 1.0 days.

> Webrings are mainly viewed as a relic of the early web of the 1990s.[3] When the primary site that managed web rings, webring.org was acquired by Yahoo, "ring masters" lost access to their webrings[3] and the web ring hubs were replaced by a Yahoo page.[3] By the time Yahoo stopped controlling webring.org in 2001, search engines had become good enough that web rings were no longer as useful.[3] The webring.org site was still active in the mid-2010s.[3] — Wikipedia

## What are the modern usages of Webring?

Besides its original purpose I can only come up with one single idea. Imagine you are writing / have written a series of posts on one single topic ("How to make a blahblahblah"-kind of things, for example), you can use Floatlink to string them together so that it's easier to share, i.e. Floatlink can be served as an index.

## What are the risks of using Floatlink?

The original main idea of Floatlink is to "'exploit' GitHub's free public code hosting service", hence the name "Float" because it's based on the single premise "GitHub is an infrastructure of modern WWW and is accesible for everyone" (which is, of course, not the case) and thus it's not "solid" and "down-to-ground"; the only "solid" solution is to host the server yourself (webrings are normally hosted on a central server).

##How to join a Floatlink webring?

Ask the webring's ringmaster to add your link to the webring link list, and put the Floatlink widget on your linked page. The widget is normally inserted into the page as an iframe; a typical Floatlink widget installation will be like this:

``` html
<iframe
    src="http://my-floatlink-site.com/widget.html"
    style="margin:0;padding:0;border:0px;width:80px;height:16px"
    title="Floatlink Navigation"></iframe>
```

For security reasons it's recommended to host your own widget.html rather than using the iframe directly.

## How do I host a Floatlink webring?

Publish the content of this git repository to any HTTP server. A few tweaks might be needed to make the widget work properly.

## I host a Floatlink webring, how do I customize the apperance of the widget?

It requires basic HTML/CSS/JS knowledge; there are plenty of related turtorials on the Internet.

## Why should Floatlink exist? Or, why should Webrings ever be revived?

The overall motivation of bringing back (pre-)Web 1.0 experience (RSS, newsgroup, Webrings, and even Gopher) is that modern WWW has failed its original purpose. To me, it really doesn't need to have a practical purpose - it itself already served its purpose as a statement against the modern WWW since the 2010s, an attempt to re-define the existence of websites and their readers.

