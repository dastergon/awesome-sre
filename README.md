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
- [Monitoring and Alerting](#monitoring-and-alerting)
- [On-Call](#on-call)
- [Post-Mortem](#post-mortem)
- [Capacity Planning](#capacity-planning)
- [Service Level Agreement](#service-level-agreement)
- [Performance](#performance)
- [Misc Articles](#misc-articles)
- [Blogs](#blogs)
- [Conferences & Meetups](#conferences--meetups)
- [Twitter](#twitter)

## Culture
* [What is Site Reliability Engineering?](https://landing.google.com/sre/interview/ben-treynor.html)
* [Keys To SRE by Ben Treynor](https://www.usenix.org/conference/srecon14/technical-sessions/presentation/keys-sre)
* [Google SRE Resources](https://landing.google.com/sre/resources.html)
* [Notes from Production Engineering by Pedro Canahuati](https://www.usenix.org/conference/srecon15/program/presentation/canahuati)
* [PostOps: Recovery from Operations](https://www.usenix.org/conference/srecon15europe/program/presentation/underwood)
* [Love DevOps? Wait 'till you meet SRE](https://www.atlassian.com/it-service/site-reliability-engineering-sre) [[video]](https://youtu.be/fsTpRx8Pt-k)
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
* [SRE: An incomplete guide to cultural Narnia](http://anthonycaiafa.com/2016/04/10/sre-cultural-narnia/) - [[Video]](https://www.youtube.com/watch?v=__wypEhdcrQ&t=0s)
* [Putting Together Great SRE Teams](https://www.usenix.org/conference/srecon16/program/presentation/krishnan)
* [Work at Google: Meet our Production Engineers for Site Reliability Hangout on Air](https://www.youtube.com/watch?v=bwt6TZjefGM)
* [Toil: A Word Every Engineer Should Know](https://medium.com/production-ready/toil-a-word-every-engineer-should-know-f0b676e41c86)
* [Engineering Reliability into Web Sites: Google SRE](https://research.google.com/pubs/pub32583.html)
* [DEVOPS & SRE AMA - Building High Performance Organizations](http://pages.catchpoint.com/DEVOPS-SRE-AMA-mkty.html)
* Site Reliability Engineering with Paul Newson - [Part 1](https://www.gcppodcast.com/post/episode-38-site-reliability-engineering-with-paul-newson/) & [Part 2](https://gcppodcast.com/post/episode-59-sre-ii-with-paul-newson/)
* [How SysAdmins Devalue Themselves](https://queue.acm.org/detail.cfm?id=2891413)
* [The Softer Side of DevOps](https://www.youtube.com/watch?v=ry51Llzil1I)
* [SRE, noun. See also: confidence, trust.](https://medium.com/@kobolog/sre-noun-see-also-confidence-trust-e7e33e19efc1)
* [Site Reliability Engineering with Stephen Weinberg](https://youtu.be/24xb7oZgu-I?t=29m24s)
* [We are the Google Site Reliability team. We make Google’s websites work. Ask us Anything!](https://www.reddit.com/r/IAmA/comments/177267/we_are_the_google_site_reliability_team_we_make)
* [We are the Google Site Reliability Engineering team. Ask us Anything!](https://www.reddit.com/r/IAmA/comments/1w1y5m/we_are_the_google_site_reliability_engineering/)
* [The Ops Identity Crisis](http://www.susanjfowler.com/blog/2016/10/13/the-ops-identity-crisis)
* [The Irreproducibility Of Bugs In Large-Scale Production Systems](http://www.susanjfowler.com/blog/2016/11/2/the-irreproducibility-of-bugs-in-large-scale-production-systems)
* [SE-Radio Episode 276: Björn Rabenstein on Site Reliability Engineering](http://www.se-radio.net/2016/12/se-radio-episode-276-bjorn-rabenstein-on-site-reliability-engineering/)
* [Microservices, DevOps and Production Complexity](https://blog.netsil.com/microservices-devops-and-operational-complexity-be98cb01b660)
* [Introducing Google Customer Reliability Engineering](https://cloudplatform.googleblog.com/2016/10/introducing-a-new-era-of-customer-support-Google-Customer-Reliability-Engineering.html)
* [Evolution or Rebellion? The rise of Site Reliability Engineers (SRE)](http://126kr.com/article/7vkoxnk6s01)
* [The difference between Site Reliability Engineering, System Administration, and DevOps](https://standalone-sysadmin.com/the-difference-between-site-reliability-engineering-system-administration-and-devops-d05031495499)
* [SRE in the Small and in the Large](https://www.usenix.org/conference/lisa16/conference-program/presentation/closing-plenary)
* [SBSRE Meetup: Different SRE roles and challenges(Netflix)](https://www.youtube.com/watch?v=zLXf0cKDOv0)
* [Panel: Who/What Is SRE?](https://www.usenix.org/conference/srecon16/program/presentation/definition-of-sre-panel)
* [Hope Is Not a Strategy](https://medium.com/@jerub/hope-is-not-a-strategy-6a7d0a3b1c08)
* [Tenets of SRE](https://medium.com/@jerub/tenets-of-sre-8af6238ae8a8)
* [Site Reliability Engineering Demystified](https://medium.com/@venkatachalamrangasamy/site-reliability-engineering-demystified-ed676e0a7d56)
* [Is Site Reliability Engineering the True ‘Ops’ in DevOps?](https://devops.com/site-reliability-engineering-sre-true-ops-devops/)
* [SRE vs. DevOps vs. Cloud Native: The Server Cage Match](https://devops.com/sre-devops-cloud-native-server-cage-match/)
* [SRE: What’s The Big Idea?](https://youtu.be/8dfYLRAWn_c)
* [Building the SRE Culture at LinkedIn](https://engineering.linkedin.com/blog/2017/05/building-the-sre-culture-at-linkedin)
* [SRE white paper by RackN](https://rackn.com/sre-white-paper/)
* [Podcast #111 – SRE: Occasionally Maintaining Infrastructure That You Hate](https://stackoverflow.blog/2017/06/12/podcast-111-sre-occasionally-maintaining-infrastructure-hate/)
* [Splicing SRE DNA Sequences in the Biggest Software Company on the Planet](https://www.usenix.org/conference/srecon16europe/program/presentation/splicing-sre-dna-sequences-biggest-software-company)
* [Why should your app get SRE support? - CRE life lessons](https://cloudplatform.googleblog.com/2017/06/why-should-your-app-get-SRE-support-CRE-life-lessons.html)
* [How SREs find the landmines in a service - CRE life lessons](https://cloudplatform.googleblog.com/2017/06/how-SREs-find-the-landmines-in-a-service-CRE-life-lessons.html)
* [Making the most of an SRE service takeover - CRE life lessons](https://cloudplatform.googleblog.com/2017/07/making-the-most-of-an-SRE-service-takeover-CRE-life-lessons.html)
* [The Cloudcast #301: SRE and Infrastructure Operations (Podcast)](https://dzone.com/articles/the-cloudcast-301-sre-and-infrastructure-operation) 
* [The SRE model](https://medium.com/@rakyll/the-sre-model-6e19376ef986)
* [Onboarding New Site Reliability Engineers](https://circleci.com/blog/onboarding-new-site-reliability-engineers/)
* [Building Blocks for Site Reliability At Google](https://www.youtube.com/watch?v=nQv9ySa8MTU)
* [Beyond Google SRE: What is Site Reliability Engineering like at Medium?](https://blog.netsil.com/beyond-google-sre-what-is-site-reliability-engineering-like-at-medium-71c65bd35f4e)
* [Intelligent Site Reliability Engineering – A Machine Learning Perspective](http://blog.adnanmasood.com/2016/05/19/intelligent-site-reliability-engineering-a-machine-learning-perspective/)
* [A crash course in LinkedIn's global site operations](https://engineering.linkedin.com/day-life/crash-course-linkedins-global-site-operations)
* [Google’s Site Reliability Engineering with Todd Underwood](https://softwareengineeringdaily.com/2016/06/14/googles-site-reliability-engineering-todd-underwood/)
* [The Rise of the Site Reliability Engineer](https://blog.newrelic.com/2017/10/30/site-reliability-engineer-sre)

## Education
* [Panel: Educating SRE](https://www.usenix.org/conference/srecon15/program/presentation/sebenik)
* [From Zero to Hero: Recommended Practices for Training your Ever-Evolving SRE Teams](https://www.usenix.org/conference/srecon15/program/presentation/widdowson)
* [New to an SRE team?](http://anthonycaiafa.com/2016/04/27/new-to-a-team/)
* [The Systems Engineering Side of Site Reliability Engineering](https://www.usenix.org/publications/login/june15/hixson)
* [Graduating from Bootcamp and interested in becoming a Site Reliability Engineer?](https://medium.com/@tammybutow/graduating-from-bootcamp-and-interested-in-becoming-a-site-reliability-engineer-b69a38ce858b)
* [So you want to be a Site Reliability Engineer?](https://www.loomsystems.com/single-post/2016/03/23/So-you-want-to-be-a-Site-Reliability-Engineer)
* [Spiraling Ops Debt & the SRE Coding Imperative](https://blog.loomsystems.com/2017/02/06/spiraling-ops-debt-the-sre-coding-imperative/)
* [So you want to be an SRE?](https://hackernoon.com/so-you-want-to-be-an-sre-34e832357a8c)
* [Career Profiles/Site Reliability Engineer](https://www.khanacademy.org/college-careers-more/career-content/career-profile-videos/site-reliability-engineer/v/ruth-grace-site-reliability-engineer-what-i-do-and-how-much-i-make)
* [What is the role of a Site Reliability Engineer?](https://cloudacademy.com/blog/what-is-the-role-of-a-site-reliability-engineer/)

## Books
* [Site Reliability Engineering: How Google Runs Production Systems](https://landing.google.com/sre/book.html)
* [The Practice Of Cloud System Administration: Designing and Operating Large Distributed Systems](http://the-cloud-book.com/)
* [Web Operations - Keeping the Data On Time](http://shop.oreilly.com/product/0636920000136.do)
* [The Checklist Manifesto: How to Get Things Right](http://atulgawande.com/book/the-checklist-manifesto/)
* [Microservices in Production - Standard Principles and Requirements](http://www.oreilly.com/programming/free/microservices-in-production.csp)
* [Production-Ready Microservices - Building Standardized Systems Across an Engineering Organization](http://shop.oreilly.com/product/0636920053675.do)
* [Systems Performance: Enterprise and the Cloud](https://www.amazon.com/Systems-Performance-Enterprise-Brendan-Gregg/dp/0133390098/)
* [Monitoring Distributed Systems: Case Studies from Google's SRE Teams](http://www.oreilly.com/webops-perf/free/monitoring-distributed-systems.csp)
* [The Human Side of Postmortems: Managing Stress and Cognitive Biases](http://www.oreilly.com/webops-perf/free/the-human-side-of-postmortems.csp)
* [Chaos Engineering: Building Confidence in System Behavior through Experiment](http://www.oreilly.com/webops-perf/free/chaos-engineering.csp)
* [Post-Incident Reviews: Learning from Failure for Improved Incident Responses](https://victorops.com/oreilly-post-incident-review/)
* [Antifragile Systems and Teams](http://www.oreilly.com/webops-perf/free/antifragile-systems-and-teams.csp)

## Hiring
* [SRE Hiring](https://www.usenix.org/conference/srecon15/program/presentation/fong)
* [Hiring SREs at LinkedIn](https://engineering.linkedin.com/engineering-culture/hiring-sres-linkedin)
* [Hiring Site Reliability Engineers](https://www.usenix.org/publications/login/june15/hiring-site-reliability-engineers)
* [Hiring your first SRE](https://sreally.com/hiring-your-first-sre-bdda38ee175d#.2m3sqyuw9)
* [Growing the Site Reliability Team at LinkedIn: Hiring is Hard](https://www.youtube.com/watch?v=ZemNg9GYvOA)

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
* [Dickerson's Hierarchy of Reliability](https://docs.google.com/drawings/d/1kshrK2RLkW-XV8enmWZxeRFRgADj6d4Ru_w5txz_k9I/edit)
* [The Morning Paper on Operability](https://blog.acolyer.org/2016/09/21/the-morning-paper-on-operability/)
* [Production is all that matters](http://naildrivin5.com/blog/2013/06/16/production-is-all-that-matters.html)
* [Using load shedding to survive a success disaster - CRE life lessons](https://cloudplatform.googleblog.com/2016/12/using-load-shedding-to-survive-a-success-disaster-CRE-life-lessons.html)
* [How to avoid a self-inflicted DDoS Attack - CRE life lessons](https://cloudplatform.googleblog.com/2016/11/how-to-avoid-a-self-inflicted-DDoS-Attack-CRE-life-lessons.html)
* [Don't gamble when it comes to reliability](https://www.oreilly.com/ideas/dont-gamble-when-it-comes-to-reliability)
* [Resilience Engineering: Learning to Embrace Failure](https://queue.acm.org/detail.cfm?id=2371297)
* [The Infrastructure Behind Twitter: Scale](https://blog.twitter.com/2017/the-infrastructure-behind-twitter-scale)
* [Scaling Reliability at Twitter: So You Want to Add a 9](https://www.youtube.com/watch?v=hYu13kBenjE)
* [Principles Of Chaos Engineering](http://principlesofchaos.org/)
* [Chaos Engineering](https://www.infoq.com/articles/chaos-engineering)
* [Available...or not? That is the question - CRE life lessons](https://cloudplatform.googleblog.com/2017/01/available-or-not-that-is-the-question-CRE-life-lessons.html)
* [How Google Backs Up The Internet Along With Exabytes Of Other Data](http://highscalability.com/blog/2014/2/3/how-google-backs-up-the-internet-along-with-exabytes-of-othe.html)
* [Performance, Scalability, And High Availability: 3 Key Infrastructure Adaptability Requirements](http://highscalability.com/blog/2017/2/2/performance-scalability-and-high-availability-3-key-infrastr.html)
* The Production Environment at Google - [Part 1](https://medium.com/@jerub/the-production-environment-at-google-8a1aaece3767) & [Part 2](https://medium.com/@jerub/the-production-environment-at-google-part-2-610884268aaa)
* [Reliable releases and rollbacks - CRE life lessons](https://cloudplatform.googleblog.com/2017/03/reliable-releases-and-rollbacks-CRE-life-lessons.html)
* [How release canaries can save your bacon - CRE life lessons](https://cloudplatform.googleblog.com/2017/03/how-release-canaries-can-save-your-bacon-CRE-life-lessons.html)
* [Things I Learned Managing Site Reliability for Some of the World’s Busiest Gambling Sites](https://zwischenzugs.wordpress.com/2017/04/04/things-i-learned-managing-site-reliability-for-some-of-the-worlds-busiest-gambling-sites/)
* [Every Day Is Monday in Operations](https://www.linkedin.com/pulse/introduction-every-day-monday-operations-benjamin-purgason)
* [Under the Hood: Ensuring Site Reliability](https://engineering.squarespace.com/blog/2017/under-the-hood-ensuring-site-reliability)
* [Designing reliable systems with cloud infrastructure (Google Cloud Next '17)](https://www.youtube.com/watch?v=7Hy_6SMn8pY)
* [A Google SRE explores GitHub reliability with BigQuery](https://cloud.google.com/blog/big-data/2016/10/a-google-sre-explores-github-reliability-with-bigquery)
* [How release canaries can save your bacon - CRE life lessons](https://cloudplatform.googleblog.com/2017/03/how-release-canaries-can-save-your-bacon-CRE-life-lessons.html)
* [Know thy enemy: how to prioritize and communicate risks - CRE life lessons](https://cloudplatform.googleblog.com/2017/05/know-thy-enemy-how-to-prioritize-and-communicate-risks-CRE-life-lessons.html)
* [Chaos Engineering resources](https://github.com/dastergon/awesome-chaos-engineering)
* [CRE life lessons: What is a dark launch, and what does it do for me?](https://cloudplatform.googleblog.com/2017/08/CRE-life-lessons-what-is-a-dark-launch-and-what-does-it-do-for-me.html)

## Monitoring and Alerting
* [A Working Theory-of-Monitoring](https://www.usenix.org/conference/lisa13/working-theory-monitoring)
* [The Evolution of Monitoring Systems at Google - Tony Rippy](https://vimeo.com/131484321)
* [Monitoring without Infrastructure @ Airbnb](https://www.usenix.org/conference/srecon15/program/presentation/serebryany)
* [Monitoring distributed systems](https://www.oreilly.com/ideas/monitoring-distributed-systems)
* [Observability at Uber Engineering: Past, Present, Future](https://www.youtube.com/watch?v=2JAnmzVwgP8)
* [The 4 Golden Signals of API Health and Performance in Cloud-Native Applications](https://blog.netsil.com/the-4-golden-signals-of-api-health-and-performance-in-cloud-native-applications-a6e87526e74)
* [My Philosophy on Alerting by Rob Ewaschuk](https://docs.google.com/document/d/199PqyG3UsyXlwieHaqbGiWVa8eMWi8zzAn0YfcApr8Q/preview#)
* [Time To Detect - Netflix](https://www.youtube.com/watch?v=wsgpV67MLFo)
* [Why Percentiles Don’t Work the Way you Think](https://www.vividcortex.com/blog/why-percentiles-dont-work-the-way-you-think)
* [Building Twitter’s Next-Gen Alerting System](https://www.youtube.com/watch?v=jQggG0qIjTM)
* [Instrumentation: Worst case performance matters](https://honeycomb.io/blog/2017/01/instrumentation-worst-case-performance-matters/)
* [Instrumentation: What does 'uptime' mean?](https://honeycomb.io/blog/2017/01/instrumentation-what-does-uptime-mean/)
* [Incidents + Outages at CircleCI: Our Playbook and What We’ve Learned](https://circleci.com/blog/incidents-outages-at-circleci-our-playbook-and-what-we-ve-learned/)
* [An introduction to monitoring and alerting with timeseries at scale, with Prometheus](https://www.youtube.com/watch?v=gNmWzkGViAY)
* [Detecting outliers and anomalies in realtime at Datadog](https://www.youtube.com/watch?v=mG4ZpEhRKHA)

## On-Call
* [Being an On-Call Engineer: A Google SRE Perspective](http://research.google.com/pubs/pub44813.html)
* [Inside Atlassian: how our site reliability engineers do incident management](http://blogs.atlassian.com/2016/02/inside-atlassian-site-reliability-engineers-incident-management/)
* [Inside Atlassian: how IT & SRE use ChatOps to run incident management](http://blogs.atlassian.com/2016/02/inside-atlassian-sre-use-chatops-run-incident-management/)
* [Incident Response at Heroku](https://blog.heroku.com/archives/2014/5/9/incident-response-at-heroku)
* [Who's On Call?](http://www.susanjfowler.com/blog/2016/9/6/whos-on-call)
* [SysAdvent - Day 6 - No More On-Call Martyrs](https://sysadvent.blogspot.com/2016/12/day-6-no-more-on-call-martyrs.html)
* [On Being On Call](http://naildrivin5.com/blog/2016/12/07/on-call.html)
* [PagerDuty Incident Response](https://response.pagerduty.com/)
* [The On-Call Handbook](https://github.com/alicegoldfuss/oncall-handbook)
* [Incident management at Google — adventures in SRE-land](https://cloudplatform.googleblog.com/2017/02/Incident-management-at-Google-adventures-in-SRE-land.html)
* [How Spotify and GOV.UK handle on call, and more](https://blog.serverdensity.com/spotify-gov-uk-handle-on-call/)
* [Run Book / Operations Manual template](https://github.com/SkeltonThatcher/run-book-template)

## Post-Mortem
* [A collection of post-mortems](https://github.com/danluu/post-mortems)
* [Blameless PostMortems and a Just Culture](https://codeascraft.com/2012/05/22/blameless-postmortems/)
* [A Tale of Postmortems](https://blog.box.com/blog/a-tale-of-postmortems/)
* [Building a Blameless Post-Mortem Culture with Jason Hand](http://runasradio.com/Shows/Show/486)
* [The infinite hows](https://www.oreilly.com/ideas/the-infinite-hows)
* [Failure is Always An Option: How a Blameless Culture Leads to Better Results](https://victorops.com/blog/blameless-culture/)
* [How to write an Incident Report / Postmortem](https://sysadmincasts.com/episodes/20-how-to-write-an-incident-report-postmortem)
* [SysAdvent - Day 1 - Why You Need a Postmortem Process](https://sysadvent.blogspot.com/2016/12/day-1-why-you-need-postmortem-process.html)
* [Etsy’s Debriefing Facilitation Guide for Blameless Postmortems](https://codeascraft.com/2016/11/17/debriefing-facilitation-guide/)
* [Writing Your First Postmortem](https://medium.com/production-ready/writing-your-first-postmortem-8053c678b90f)
* [How to Write Great Outage Post-Mortems](https://artsy.github.io/blog/2014/11/19/how-to-write-great-outage-post-mortems/)
* [A collection of postmortem templates](https://github.com/dastergon/postmortem-templates)
* [Embracing Feedback](https://blog.heptio.com/embracing-feedback-2fd703da714f)
* [Postmortem Action Items: Plan the Work and Work the Plan](https://www.usenix.org/conference/srecon17americas/program/presentation/lueder)

## Capacity Planning
* [Capacity Planning](https://www.usenix.org/system/files/login/articles/login_feb15_07_hixson.pdf)
* [SouthBay SRE: Cloud Capacity Planning](https://www.youtube.com/watch?v=MDQ0uEUmLOo)

## Service Level Agreement
* [SLA Aware Maintenance for Operators - Joe Smith](https://www.youtube.com/watch?v=tZ0-SISvCis)
* [If It's in the Cloud, Get It on Paper: Cloud Computing Contract Issues](http://er.educause.edu/articles/2010/6/if-its-in-the-cloud-get-it-on-paper-cloud-computing-contract-issues)
* [Service Level Agreements in the Cloud: Who cares?](http://www.wired.com/insights/2011/12/service-level-agreements-in-the-cloud-who-cares/)
* [Making a point with SLAs](https://blog.serverdensity.com/making-a-point-with-slas/)
* [SysAdvent- Day 20 - How to set and monitor SLAs](https://sysadvent.blogspot.com/2016/12/day-20-how-to-set-and-monitor-slas.html)
* [SLOs, SLIs, SLAs, oh my - CRE life lessons](https://cloudplatform.googleblog.com/2017/01/availability-part-deux--CRE-life-lessons.html)
* [Service Levels and Error Budgets](https://www.usenix.org/conference/srecon16/program/presentation/jones)
* [(Un)Reliability Budgets - Finding Balance between Innovation and Reliability](https://www.usenix.org/system/files/login/articles/login_aug15_06_roth.pdf)
* [The Calculus of Service Availability](https://queue.acm.org/detail.cfm?id=3096459&__s=dnkxuaws9pogqdnxmx8i)
* [Availability Calculator: Calculate how much downtime should be permitted in your SLA](https://dastergon.github.io/availability-calculator/)
* [Standardize cloud SLA availability with numerical performance data](https://www.ibm.com/developerworks/cloud/library/cl-SLAloadbalance-numanalysis/)
* [Best practices to develop SLAs for cloud computing](https://www.ibm.com/developerworks/cloud/library/cl-slastandards/)
* [A Practical Guide to SLAs](http://blog.catchpoint.com/2016/08/04/sla-practical-guide/)
* [Building good SLOs - CRE life lessons](https://cloudplatform.googleblog.com/2017/10/building-good-SLOs-CRE-life-lessons.html)
* [No Grumpy Humans and Other Site Reliability Engineering Lessons from Google](https://thenewstack.io/sre-lessons-google-no-grumpy-humans/)

## Performance
* [Performance Checklists for SREs](https://www.usenix.org/conference/srecon16/program/presentation/gregg)
* [South Bay SRE Meetup - Netflix Cloud Performance Team](https://youtu.be/uQ0flQOtQEA)

## Programming
* [Go Language for Ops and Site Reliability Engineering](http://www.oreilly.com/pub/e/2712)
* [Go for SREs using Python](https://www.usenix.org/sites/default/files/conference/protected-files/srecon16_slides_hamilton.pdf)
* [Operability in Go](https://speakerdeck.com/ianschenck/operability-in-go)
* [Go Reliability and Durability at Dropbox](https://www.youtube.com/watch?v=5doOcaMXx08)

## Misc Articles
* [What is SRE (Site Reliability Engineering)?](https://www.oreilly.com/ideas/what-is-sre-site-reliability-engineering)
* [Here’s How Google Makes Sure It (Almost) Never Goes Down](http://www.wired.com/2016/04/google-ensures-services-almost-never-go/)
* [Are site reliability engineers the next data scientists?](http://techcrunch.com/2016/03/02/are-site-reliability-engineers-the-next-data-scientists/)
* [Site Reliability Engineers: "solving the most interesting problems"](http://googleresearch.blogspot.gr/2012/07/site-reliability-engineers-solving-most.html)
* [Site Reliability Engineers: the "world’s most intense pit crew"](http://googleforstudents.blogspot.gr/2012/06/site-reliability-engineers-worlds-most.html)
* [Site reliability engineering kicks rote tasks out of IT ops](http://searchitoperations.techtarget.com/feature/Site-reliability-engineering-kicks-rote-tasks-out-of-IT-ops)
* [Notes on Site Reliability Engineering](http://danluu.com/google-sre-book/)
* [Adventures in SRE-land: Welcome to Google Mission Control](https://cloudplatform.googleblog.com/2016/07/adventures-in-SRE-land-welcome-to-Google-Mission-Control.html)
* [LinkedIn Preps Site Reliability Engineers (SREs) For Exciting Careers](http://devops.com/2015/09/10/linkedin-preps-site-reliability-engineers-sres-exciting-careers/)
* [Book Review: Site Reliability Engineering - How Google Runs Production Systems](https://www.infoq.com/articles/site-reliability-engineering)
* [Site Reliability Engineers: “We solve cooler problems”](https://www.google.com/about/careers/stories/site-reliability-engineering-profile-google/)
* [SREcon17: Brave new world of site reliability engineering](http://www.networkworld.com/article/3182827/cloud-computing/srecon17-brave-new-world-of-site-reliability-engineering.html)
* [Open AWS guide](https://github.com/open-guides/og-aws)

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
* [Susan J. Fowler](http://www.susanjfowler.com/blog/) - Various blog posts about SRE, Software Engineering and Microservices.
* [SREally?!](https://sreally.com/)
* [SysAdvent](https://sysadvent.blogspot.com) - One article for each day of December, ending on the 25th article.
* [Operations for Developers](http://some.ops4devs.info/) - A collection of resources for developers to strengthen their Ops skills.
* [ProdOps: From Product to Production](http://prodops.guide/)
* [Stephen Thorne's Blog](https://medium.com/@jerub) - Blog Posts About SRE
* [Increment](https://increment.com/) - A digital magazine about how teams build and operate software systems at scale.
* [O’Reilly Systems Engineering and Operations Newsletter](http://www.oreilly.com/webops-perf/newsletter.html) - Weekly systems engineering and operations news and insights from industry insiders.
* [GopherSRE](http://www.gophersre.com/) - Blog Posts about Go and SRE.

## Conferences & Meetups
* [SRECon Conferences](https://www.usenix.org/conferences/byname/925) - The Official SRE Conference.
* [LISA Conferences](https://www.usenix.org/conferences/byname/5) - Prominent Conference About SysAdmin/DevOps/SRE.
* [SRE Tech Talks](https://developers.google.com/events/sre/) - SRE Talks Hosted by Google.
* [South Bay Site Reliability Engineering (Sunnyvale, CA) Meetup](https://www.meetup.com/South-Bay-Site-Reliability-Engineering/) - A Group For Individuals Who Tackle Reliability Challenges For Web-Scale Systems.
* [San Francisco Reliability Engineering](https://www.meetup.com/San-Francisco-Reliability-Engineering/) - A Group Of People Who Are Passionate About Reliable, Performant Software Systems.
* [Front Range Site Reliability Engineering](https://www.meetup.com/site-reliability/) - SRE Meetup in Boulder/Denver/Golden/DTC/FoCo area.

## Twitter
* [Alice Goldfuss](https://twitter.com/alicegoldfuss)
* [Brendan Gregg](https://twitter.com/brendangregg)
* [Caitie McCaffrey](https://twitter.com/caitie)
* [Charity Majors](https://twitter.com/mipsytipsy)
* [Dave Hahn](https://twitter.com/relix42)
* [Highscal](https://twitter.com/highscal)
* [Jennifer Petoff](https://twitter.com/jennski)
* [Jesse Dearing](https://twitter.com/JesseDearing)
* [Jonah Horowitz](https://twitter.com/jonahhorowitz)
* [Julia Evans](https://twitter.com/b0rk)
* [Krishelle Hardson-Hurley](https://twitter.com/khardsonhurley)
* [Niall Murphy](https://twitter.com/niallm)
* [Nick Craver](https://twitter.com/Nick_Craver)
* [SREBook](https://twitter.com/SREBook) - The Official Twitter Account of Site Reliability Engineering Book.
* [SREcon](https://twitter.com/SREcon) - SRECon's Official Twitter Account.
* [Tammy Bütow](https://twitter.com/tammybutow)
* [Thomas A. Limoncelli](https://twitter.com/yesthattom)
* [Todd Underwood](https://twitter.com/tmu)
* [Twitter SRE](https://twitter.com/TwitterSRE) - The Official Twitter Account of Twitter's SRE team.
* [USENIX Association](https://twitter.com/usenix) - The Official USENIX Twitter Account.
