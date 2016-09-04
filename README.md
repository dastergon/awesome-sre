# Awesome Site Reliability Engineering  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome [Site Reliability](https://www.usenix.org/conference/srecon14/technical-sessions/presentation/keys-sre) and [Production](https://www.usenix.org/conference/srecon15/program/presentation/canahuati) Engineering resources.

#### What is Site Reliability Engineering?
> "Fundamentally, it's what happens when you ask a software engineer to design an operations function." - Ben Treynor Sloss, VP Google Engineering, founder of Google SRE

## Contributing

Please take a look at the [contribution guidelines](CONTRIBUTING.md) first.
Contributions are always welcome!

## Contents
- [Culture](#culture)
- [Education](#education)
- [Books](#books)
- [Hiring](#hiring)
- [Reliability](#reliability)
- [Alerting](#alerting)
- [Monitoring](#monitoring)
- [On-Call](#on-call)
- [Post-Mortem](#post-mortem)
- [Capacity Planning](#capacity-planning)
- [Service Level Agreement](#service-level-agreement)
- [Performance](#performance)
- [Articles](#articles)
- [Blogs](#blogs)
- [Conferences](#conferences)
- [Twitter](#twitter)

## Culture
* [What is Site Reliability Engineering?](https://landing.google.com/sre/interview/ben-treynor.html)
* [Keys To SRE by Ben Treynor](https://www.usenix.org/conference/srecon14/technical-sessions/presentation/keys-sre)
* [Google SRE Resources](https://landing.google.com/sre/resources.html)
* [Notes from Production Engineering by Pedro Canahuati](https://www.usenix.org/conference/srecon15/program/presentation/canahuati)
* [PostOps: Recovery from Operations](https://www.usenix.org/conference/srecon15europe/program/presentation/underwood)
* [Love DevOps? Wait 'till you meet SRE](https://www.atlassian.com/it-service/site-reliability-engineering-sre)
* [How Google Does Planet-Scale Engineering for Planet-Scale Infra](https://www.youtube.com/watch?v=H4vMcD7zKM0)
* [Site Reliability Engineering at Facebook](https://www.facebook.com/notes/facebook-engineering/site-reliability-engineering-at-facebook/291616313919/)
* [A History of Site Reliability Engineering at Uber](https://www.youtube.com/watch?v=qJnS-EfIIIE&nohtml5=False)
* [Case Study: Adopting SRE Principles at StackOverflow](https://www.usenix.org/conference/srecon15/program/presentation/limoncelli)
* [Site Reliability Engineering at Dropbox](https://www.youtube.com/watch?v=ggizCjUCCqE)
* [Site Reliability Engineers — Keeping Google up and running 24/7](https://www.youtube.com/watch?v=yXI7r0_J29M)
* [Site Reliability Engineering at Salesforce](https://www.youtube.com/watch?v=JLkr6UHXN44&nohtml5=False)
* [From Sys Admin to Netflix SRE](https://www.youtube.com/watch?v=lZI51YzIgVE)
* [SRE@Google: Thousands of DevOps Since 2004](https://www.youtube.com/watch?v=iIuTnhdTzK0)
* [Transactional System Administration Is Killing Us and Must be Stopped](https://www.usenix.org/conference/lisa15/conference-program/presentation/limoncelli)
* [Maslow's hierarchy of SRE needs](https://plus.google.com/+lizthegrey/posts/MLAJFVyEb2f)
* [PostOps: A Non-Surgical Tale of Software, Fragility, and Reliability](https://www.usenix.org/conference/lisa13/technical-sessions/plenary/underwood)
* [From SysAdmin to Netflix SRE](https://www.socallinuxexpo.org/sites/default/files/presentations/Scale%20x14%20Slides.pdf)
* [SRE: An incomplete guide to cultural Narnia](http://anthonycaiafa.com/2016/04/10/sre-cultural-narnia/)
* [Putting Together Great SRE Teams](https://www.usenix.org/conference/srecon16/program/presentation/krishnan)
* [Work at Google: Meet our Production Engineers for Site Reliability Hangout on Air](https://www.youtube.com/watch?v=bwt6TZjefGM)
* [Toil: A Word Every Engineer Should Know](https://medium.com/production-ready/toil-a-word-every-engineer-should-know-f0b676e41c86)
* [Engineering Reliability into Web Sites: Google SRE](https://research.google.com/pubs/pub32583.html)
* [DEVOPS & SRE AMA - Building High Performance Organizations](http://pages.catchpoint.com/DEVOPS-SRE-AMA-mkty.html)
* [Site Reliability Engineering with Paul Newson](https://www.gcppodcast.com/post/episode-38-site-reliability-engineering-with-paul-newson/)

## Education
* [Panel: Educating SRE](https://www.usenix.org/conference/srecon15/program/presentation/sebenik)
* [From Zero to Hero: Recommended Practices for Training your Ever-Evolving SRE Teams](https://www.usenix.org/conference/srecon15/program/presentation/widdowson)
* [New to an SRE team?](http://anthonycaiafa.com/2016/04/27/new-to-a-team/)
* [The Systems Engineering Side of Site Reliability Engineering](https://www.usenix.org/publications/login/june15/hixson)

## Books
* [Site Reliability Engineering: How Google Runs Production Systems](https://landing.google.com/sre/book.html)
* [The Practice Of Cloud System Administration: Designing and Operating Large Distributed Systems](http://the-cloud-book.com/)
* [Web Operations - Keeping the Data On Time](http://shop.oreilly.com/product/0636920000136.do)
* [The Checklist Manifesto: How to Get Things Right](http://atulgawande.com/book/the-checklist-manifesto/)

## Hiring
* [SRE Hiring](https://www.usenix.org/conference/srecon15/program/presentation/fong)
* [Hiring SREs at LinkedIn](https://engineering.linkedin.com/engineering-culture/hiring-sres-linkedin)
* [Hiring Site Reliability Engineers](https://www.usenix.org/publications/login/june15/hiring-site-reliability-engineers)

## Reliability
* [The Realities of the Job of Delivering Reliability](https://www.usenix.org/conference/srecon16/program/presentation/kroll)
* [Fail at Scale by Ben Maurer](http://queue.acm.org/detail.cfm?id=2839461)
* [Embracing Failure: Fault-Injection and Service Reliability](https://www.youtube.com/watch?v=wrY7XoOnysg)
* [10 Years of Crashing Google](https://www.usenix.org/conference/lisa15/conference-program/presentation/krishnan)
* [How we break things at Twitter: failure testing](https://blog.twitter.com/2015/how-we-break-things-at-twitter-failure-testing)
* [Reliable Cron across the Planet](http://queue.acm.org/detail.cfm?id=2745840)
* [Push our limits - reliability testing at Twitter](https://blog.twitter.com/2014/push-our-limits-reliability-testing-at-twitter)
* [The Verification of a Distributed System by Caitie McCaffrey](http://queue.acm.org/detail.cfm?ref=rss&id=2889274)
* [Weathering the Unexpected](http://queue.acm.org/detail.cfm?id=2371516)
* [The Remediation Ballet](http://files.sans.org/summit/Threat_Hunting_Incident_Response_Summit_2016/PDFs/The-Remediation-Ballet-Performing-the-Delicate-Dance-of-Clean-Up-Matt-Linton-Google.pdf)
* [SRE Hour: Tech Talks by Box & Yelp](https://www.youtube.com/watch?v=YFDwdRVTg4g)
* [Simplicity: A Prerequisite for Reliability](https://medium.com/production-ready/simplicity-a-prerequisite-for-reliability-8d000f8d18df#.74t9t0em2)
* [The Two Sides to Google Infrastructure for Everyone Else](https://speakerdeck.com/garethr/the-two-sides-to-google-infrastructure-for-everyone-else)
* [How Embracing Continuous Release Reduced Change Complexity](https://www.usenix.org/conference/ures14west/summit-program/presentation/dickson)
* [Making "Push On Green" a Reality](https://www.usenix.org/publications/login/october-2014-vol-39-no-5/making-push-green-reality)
* [BeyondCorp: A New Approach to Enterprise Security](https://www.usenix.org/publications/login/dec14/ward)
* [Brainstorming Failure by Jeff Smith](https://www.youtube.com/watch?v=dKe9S8u44Yk)
* [The Ripple Effect Of Outages And Downtime Cannot Be Underestimated](http://cloudtweaks.com/2016/04/outages-and-downtime/)
* [The infrastructure behind Twitter: efficiency and optimization](https://blog.twitter.com/2016/the-infrastructure-behind-twitter-efficiency-and-optimization)

## Alerting
* [My Philosophy on Alerting by Rob Ewaschuk](https://docs.google.com/document/d/199PqyG3UsyXlwieHaqbGiWVa8eMWi8zzAn0YfcApr8Q/preview#)

## Monitoring
* [A Working Theory-of-Monitoring](https://www.usenix.org/conference/lisa13/working-theory-monitoring)
* [The Evolution of Monitoring Systems at Google - Tony Rippy](https://vimeo.com/131484321)
* [Monitoring without Infrastructure @ Airbnb](https://www.usenix.org/conference/srecon15/program/presentation/serebryany)
* [Monitoring distributed systems](https://www.oreilly.com/ideas/monitoring-distributed-systems)

## On-Call
* [Being an On-Call Engineer: A Google SRE Perspective](http://research.google.com/pubs/pub44813.html)
* [Inside Atlassian: how our site reliability engineers do incident management](http://blogs.atlassian.com/2016/02/inside-atlassian-site-reliability-engineers-incident-management/)
* [Inside Atlassian: how IT & SRE use ChatOps to run incident management](http://blogs.atlassian.com/2016/02/inside-atlassian-sre-use-chatops-run-incident-management/)
* [Incident Response at Heroku](https://blog.heroku.com/archives/2014/5/9/incident-response-at-heroku)

## Post-Mortem
* [A collection of post-mortems](https://github.com/danluu/post-mortems)
* [Blameless PostMortems and a Just Culture](https://codeascraft.com/2012/05/22/blameless-postmortems/)
* [A Tale of Postmortems](https://blog.box.com/blog/a-tale-of-postmortems/)

## Capacity Planning
* [Capacity Planning](https://www.usenix.org/system/files/login/articles/login_feb15_07_hixson.pdf)

## Service Level Agreement
* [SLA Aware Maintenance for Operators - Joe Smith](https://www.youtube.com/watch?v=tZ0-SISvCis)
* [If It's in the Cloud, Get It on Paper: Cloud Computing Contract Issues](http://er.educause.edu/articles/2010/6/if-its-in-the-cloud-get-it-on-paper-cloud-computing-contract-issues)
* [Service Level Agreements in the Cloud: Who cares?](http://www.wired.com/insights/2011/12/service-level-agreements-in-the-cloud-who-cares/)
* [Making a point with SLAs](https://blog.serverdensity.com/making-a-point-with-slas/)

## Performance
* [Performance Checklists for SREs](https://www.usenix.org/conference/srecon16/program/presentation/gregg)

## Programming
* [Go Language for Ops and Site Reliability Engineering](http://www.oreilly.com/pub/e/2712)
* [Go for SREs using Python](https://www.usenix.org/sites/default/files/conference/protected-files/srecon16_slides_hamilton.pdf)

## Articles
* [What is SRE (Site Reliability Engineering)?](https://www.oreilly.com/ideas/what-is-sre-site-reliability-engineering)
* [Here’s How Google Makes Sure It (Almost) Never Goes Down](http://www.wired.com/2016/04/google-ensures-services-almost-never-go/)
* [Are site reliability engineers the next data scientists?](http://techcrunch.com/2016/03/02/are-site-reliability-engineers-the-next-data-scientists/)
* [Site Reliability Engineers: "solving the most interesting problems"](http://googleresearch.blogspot.gr/2012/07/site-reliability-engineers-solving-most.html)
* [Site Reliability Engineers: the "world’s most intense pit crew"](http://googleforstudents.blogspot.gr/2012/06/site-reliability-engineers-worlds-most.html)
* [Site reliability engineering kicks rote tasks out of IT ops](http://searchitoperations.techtarget.com/feature/Site-reliability-engineering-kicks-rote-tasks-out-of-IT-ops)
* [Notes on Site Reliability Engineering](http://danluu.com/google-sre-book/)
* [Adventures in SRE-land: Welcome to Google Mission Control](https://cloudplatform.googleblog.com/2016/07/adventures-in-SRE-land-welcome-to-Google-Mission-Control.html)

## Real-time Messaging
* [#sre channel at Hangops Slack](https://hangops.slack.com/) - Discussion of Site Reliability Engineering generally.
* [#incident_response channel at Hangops Slack](https://hangops.slack.com/) - Discussion about Incident Response.

## Blogs
* [Brendan Gregg's Blog](http://www.brendangregg.com/blog/index.html) - Highly Techincal Blog Posts About Systems Internals, Performance and SRE.
* [Everything Sysadmin](http://everythingsysadmin.com/) - Blog Posts About SysAdmin/DevOps/SRE by Tom Limoncelli.
* [High Scalability](http://highscalability.com/) - Technical Blog Posts About Systems Architecture.
* [rachelbythebay](https://rachelbythebay.com/w/) - Techincal Blog Posts.
* [SRE Weekly](https://sreweekly.com/) - Weekly Site Reliability Newsletter.
* [Production Ready](https://tinyletter.com/production-ready) - A mailing list about building resilient infrastructure and tools.

## Conferences
* [SRECon Conferences](https://www.usenix.org/conferences/byname/925) - The Official SRE Conference.
* [LISA Conferences](https://www.usenix.org/conferences/byname/5) - Prominent Conference About SysAdmin/DevOps/SRE.
* [SRE Tech Talks](https://developers.google.com/events/sre/) - SRE Talks Hosted by Google.

## Twitter
* [Alice Goldfuss](https://twitter.com/alicegoldfuss) - SRE @ New Relic - Tweets About the SRE Culture.
* [Brendan Gregg](https://twitter.com/brendangregg) - SRE @ Netflix - Technical Resources about Systems, Performance and Site Reliability Engineers.
* [Caitie McCaffrey](https://twitter.com/caitie) - Tweets About Reliability and Distributed Systems.
* [Dave Hahn](https://twitter.com/relix42) - SRE @ Netflix.
* [Highscal](https://twitter.com/highscal) - Feed of the High Scalability Blog.
* [Jennifer Petoff](https://twitter.com/jennski) - Program Manager for Google's Site Reliability Engineering team.
* [Jesse DB](https://twitter.com/JesseDearing) - SRE @ New Relic.
* [Jonah horowitz](https://twitter.com/jonahhorowitz) - SRE @ Netflix.
* [Niall Murphy](https://twitter.com/niallm) - SRE @ Google.
* [Nick Craver](https://twitter.com/Nick_Craver) - SRE @ StackOverflow.
* [SREBook](https://twitter.com/SREBook) - The Official Twitter Account of Site Reliability Engineering Book.
* [SREcon](https://twitter.com/SREcon) - SRECon's Official Twitter Account.
* [Thomas A. Limoncelli](https://twitter.com/yesthattom) - Prominent Author About SysAdmin/DevOps/SRE.
* [Todd Underwood](https://twitter.com/tmu) - SRE @ Google.
* [Twitter SRE](https://twitter.com/TwitterSRE) - The Official Twitter Account of Twitter's SRE team.
* [USENIX Association](https://twitter.com/usenix) - The Official USENIX Twitter Account.
