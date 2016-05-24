# Awesome Site Reliability Engineering  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome Site Reliability and Production Engineering resources.

#### Contributing

Please take a look at the [contribution guidelines](CONTRIBUTING.md) first.
Contributions are always welcome!

#### Contents
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

#### Culture
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
* [Engineering Reliability into Web Sites: Google SRE](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/32583.pdf)
* [From SysAdmin to Netflix SRE](https://www.socallinuxexpo.org/sites/default/files/presentations/Scale%20x14%20Slides.pdf)
* [SRE: An incomplete guide to cultural Narnia](http://anthonycaiafa.com/2016/04/10/sre-cultural-narnia/)
* [Putting Together Great SRE Teams](https://www.usenix.org/conference/srecon16/program/presentation/krishnan)

#### Education
* [Panel: Educating SRE](https://www.usenix.org/conference/srecon15/program/presentation/sebenik)
* [From Zero to Hero: Recommended Practices for Training your Ever-Evolving SRE Teams](https://www.usenix.org/conference/srecon15/program/presentation/widdowson)
* [New to an SRE team?](http://anthonycaiafa.com/2016/04/27/new-to-a-team/)

#### Books
* [Site Reliability Engineering: How Google Runs Production Systems](https://landing.google.com/sre/book.html)
* [The Practice Of Cloud System Administration: Designing and Operating Large Distributed Systems](http://the-cloud-book.com/)

#### Hiring
* [SRE Hiring](https://www.usenix.org/conference/srecon15/program/presentation/fong)
* [Hiring SREs at LinkedIn](https://engineering.linkedin.com/engineering-culture/hiring-sres-linkedin)

#### Reliability
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

#### Alerting
* [My Philosophy on Alerting by Rob Ewaschuk](https://docs.google.com/document/d/199PqyG3UsyXlwieHaqbGiWVa8eMWi8zzAn0YfcApr8Q/preview#)

#### Monitoring
* [A Working Theory-of-Monitoring](https://www.usenix.org/conference/lisa13/working-theory-monitoring)
* [The Evolution of Monitoring Systems at Google - Tony Rippy](https://vimeo.com/131484321)
* [Monitoring without Infrastructure @ Airbnb](https://www.usenix.org/conference/srecon15/program/presentation/serebryany)

#### On-Call
* [Being an On-Call Engineer: A Google SRE Perspective](http://research.google.com/pubs/pub44813.html)
* [Inside Atlassian: how our site reliability engineers do incident management](http://blogs.atlassian.com/2016/02/inside-atlassian-site-reliability-engineers-incident-management/)
* [Inside Atlassian: how IT & SRE use ChatOps to run incident management](http://blogs.atlassian.com/2016/02/inside-atlassian-sre-use-chatops-run-incident-management/)
* [Incident Response at Heroku](https://blog.heroku.com/archives/2014/5/9/incident-response-at-heroku)

#### Post-Mortem
* [A collection of post-mortems](https://github.com/danluu/post-mortems)

#### Capacity Planning
* [Capacity Planning](https://www.usenix.org/system/files/login/articles/login_feb15_07_hixson.pdf)

#### Service Level Agreement
* [SLA Aware Maintenance for Operators - Joe Smith](https://www.youtube.com/watch?v=tZ0-SISvCis)
* [If It's in the Cloud, Get It on Paper: Cloud Computing Contract Issues](http://er.educause.edu/articles/2010/6/if-its-in-the-cloud-get-it-on-paper-cloud-computing-contract-issues)
* [Service Level Agreements in the Cloud: Who cares?](http://www.wired.com/insights/2011/12/service-level-agreements-in-the-cloud-who-cares/)

#### Performance
* [Performance Checklists for SREs](https://www.usenix.org/conference/srecon16/program/presentation/gregg)

#### Programming
* [Go Language for Ops and Site Reliability Engineering](http://www.oreilly.com/pub/e/2712)
* [Go for SREs using Python](https://www.usenix.org/sites/default/files/conference/protected-files/srecon16_slides_hamilton.pdf)

#### Articles
* [What is SRE (Site Reliability Engineering)?](https://www.oreilly.com/ideas/what-is-sre-site-reliability-engineering)
* [Here’s How Google Makes Sure It (Almost) Never Goes Down](http://www.wired.com/2016/04/google-ensures-services-almost-never-go/)
* [Are site reliability engineers the next data scientists?](http://techcrunch.com/2016/03/02/are-site-reliability-engineers-the-next-data-scientists/)
* [Site Reliability Engineers: "solving the most interesting problems"](http://googleresearch.blogspot.gr/2012/07/site-reliability-engineers-solving-most.html)
* [Site Reliability Engineers: the "world’s most intense pit crew"](http://googleforstudents.blogspot.gr/2012/06/site-reliability-engineers-worlds-most.html)
* [Notes on Site Reliability Engineering](http://danluu.com/google-sre-book/)

#### Blogs
* [Brendan Gregg's Blog](http://www.brendangregg.com/blog/index.html)
* [Everything Sysadmin](http://everythingsysadmin.com/)
* [High Scalability](http://highscalability.com/)
* [rachelbythebay](https://rachelbythebay.com/w/)
* [SRE Weekly](https://sreweekly.com/)

#### Conferences
* [SRECon Conferences](https://www.usenix.org/conferences/byname/925)
* [LISA Conferences](https://www.usenix.org/conferences/byname/5)

#### Twitter
* [Alice Goldfuss](https://twitter.com/alicegoldfuss)
* [Brendan Gregg](https://twitter.com/brendangregg)
* [Caitie McCaffrey](https://twitter.com/caitie)
* [Dave Hahn](https://twitter.com/relix42)
* [Jennifer Petoff](https://twitter.com/jennski)
* [Jesse DB](https://twitter.com/JesseDearing)
* [Jonah horowitz](https://twitter.com/jonahhorowitz)
* [Niall Murphy](https://twitter.com/niallm)
* [Nick Craver](https://twitter.com/Nick_Craver)
* [SREcon](https://twitter.com/SREcon)
* [Thomas A. Limoncelli](https://twitter.com/yesthattom)
* [Todd Underwood](https://twitter.com/tmu)
* [Twitter SRE](https://twitter.com/TwitterSRE)
* [USENIX Association](https://twitter.com/usenix)
