# Writebook

## Instantly publish your own books on the web for free, no publisher required.

Blogging and posting on social is easy. But why is it so hard to publish a whole book on the web? It’s not anymore. Writebook is remarkably simple software that allows you to publish text and pictures in a simple, browsable online book format.

Here’s [an example](https://classics.37signals.com/8/the-prophet). And [another](https://classics.37signals.com/7/in-our-time). And [one more](https://books.37signals.com/10/the-united-states-constitution).

## What kind of books can I publish?

Whatever you’ve written is ready for Writebook. No publisher, no gatekeeper, no permission necessary. Just write it.

- **Instruction manuals.** Publish a manual to go along with a piece of software, hardware, or a process that needs simple, clear documentation. Like the [Writebook Manual itself](https://books.37signals.com/2/the-writebook-manual).
- **Graphic novels.** Writebooks offer a picture-page type so you can have a book made entirely of pictures. Perfect for graphic novels, or even just photobooks with captions.
- **Employee handbooks.** Document your internal processes, policies, norms, and rules just for your employees (privately) or for everyone to see (publicly). [Here’s ours, for example](https://books.37signals.com/3/the-37signals-employee-handbook).
- **A collection of short stories.** Maybe you’ve written a handful of separate short stories. Maybe it’s time you pull them all together in a little self-contained anthology. Writebook it!
- **A group of blog posts.** Been blogging for years? How about making a collection of your top 25 as a book? Writebook makes it easy to republish them together as a cohesive whole.
- **Internal technical runbooks.** Have procedures you need documented and followed? Need them hosted elsewhere in case of emergency? Make your runbook a private Writebook.
- **Family stories.** Gather up history, stories, and photos from your extended family. Put it all into a Writebook you can proudly share with family and friends.

## System requirements & installation

Since Writebook is software you install and host yourself, you’ll need a few things before you begin:

- **Your own domain name**. You’ll need to point the DNS to the IP address of the machine that’ll be hosting Writebook.
- **A web server** connected to the internet. This could be your own hardware or something hosted in the cloud like AWS, DigitalOcean, etc. All you need is 2GB RAM/1CPU.
- **Some basic technical know-how**. We’ll give you a single command to run from the terminal on your server that’ll be hosting Writebook. It’ll set everything up for you from there, including the SSL certificate.

We put together [a simple Writebook manual](https://books.37signals.com/2/the-writebook-manual) to walk you through the steps. All in, install and set up should take just about 10 minutes or so.

## FAQs

**Is it really free? No catch?**
Yes, Writebook is free for real. It’s our way to give back and encourage people to publish independently on the web. You’ll have to host the software on your own server, but Writebook itself is entirely free. Besides the finished software, you also get all the Rails code so you can see how we built it.

**What do you mean I have to host Writebook?**
Writebook isn’t an app or service someone else runs. It’s a fully independent system that you run and host yourself. That means you install it on a server you own (or rent) and control. It requires some technical knowledge, but all-in-all it’s quite easy. If you can register a domain name, and change the DNS for that domain name, you can almost certainly handle the install and hosting process for Writebook.

**Can we write private books too?**
All books in Writebook start as private just to the users you’ve invited to your account. But once you flip the switch on a book to publish it on the web, anyone in the world can read the book. You can have a mix of public and private books on the same Writebook installation.

**Can I charge for the books I publish using Writebook?**
We don’t offer a way to sell your books through Writebook, but if you want to put a paywall in front of your copy of Writebook, that’s up to you. However, the software license “does not include the rights to publish, distribute, sublicense, and/or sell copies of the Software, source code or products derived from it.” Further, you can not, for example, sell a separate hosted service on top of Writebook using Writebook code.

**Can I write multiple books with a single copy of Writebook?**
Yes, you can write as many books as you’d like with your copy of Writebook. Note that they’ll all be hosted in the same place on the same domain. If you want to host books in different places, on different domains, you’ll need to install separate copies of Writebook.

**How do I get updates to Writebook software?**
Each Writebook installation pings our server once a day to see if there are any updates. If so, it’ll download and automatically install them. You can turn this off if you’d prefer to do it manually.

**Are native iOS and Android apps available?**
No, Writebook is web-based software. Books will automatically be nicely formatted for reading on the web on mobile devices.

**Can we white label or resell Writebook?**
No. Please be sure to review the license agreement for further details.

**Can we reuse any of the code in another product?**
No. While you are free to review the code and make modifications to Writebook for your own use, you can not use or repurpose the code for your own purposes outside Writebook. Please be sure to review the license agreement for further details.

**Can we modify Writebook for our own purposes?**
Yes, you can make whatever changes to the Rails code that you’d like, but once you change the code from the included code, you’re on your own. Any updates might overwrite your changes as well.

**Can we import existing books into Writebook?**
Writebooks are formatted using Markdown. You can copy/paste any Markdown to/from your pages, but there’s no formal import/export feature. You can’t convert PDFs or other formats into Markdown from within Writebook, but you’re free to do that elsewhere and paste the converted Markdown into Writebook.

**How is Writebook packaged up and distributed?**
Writebook is packed as a Docker container image. When installing Writebook via our ONCE command (we’ll give you this when you sign up), we’ll automatically setup a SSL certificate for the domain or subdomain you’re using. But if you’re technically sophisticated, you can also run Writebook directly via Docker on your internal network.

**Can I export Kindle, PDF, ePUB, or other formats from Writebook?**
Not currently, no. Writebook purely publishes web-based books. We may add other export formats down the road.
