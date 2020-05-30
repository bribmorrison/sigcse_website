---
title: CompEd Conference
layout: page

conferences:
- title: CompEd 2021
  year: 2021
  location: "Hyderabad, India"

- title: CompEd 2019
  year: 2019
  date: "May, 2019"
  url: https://www.acmcomped.org/
  proceeding: "CompEd '19: Proceedings of the ACM Conference on Global Computing Education"
  location: "Chengdu, Sichuan China"
  doi: https://dl.acm.org/doi/proceedings/10.1145/3300115
  companion: "CompEd-WGR '19: Proceedings of the Working Group Reports on Global Computing Education"
  companion-doi: https://dl.acm.org/doi/proceedings/10.1145/3372262
  companion-title: "Working Group Reports"

---

*Note: "SIGCSE Global" was a temporary name for this conference. The conference has now been named ACM Global Computing Education Conference, with a short name of CompEd.*

The ACM Global Computing Education Conference (CompEd) is SIGCSE's new and fourth conference. There will be three conferences, being held every other year before a review. The first CompEd was held in Chengdu, China on May 17-19 2019. In general, the conference should run in countries where we do not regularly hold SIGCSE conferences, so not in North America or Europe.

<!-- The 2019 website is [here.](http://www.acmcomped.org/)
 -->
More information on the structure of the conference is here: [Information about ACM Global Computing Education Conference](https://docs.google.com/document/d/1kbI3dl3pcQxnlgFMHGmpbE0PN173WhaCZICmNw2EKME/edit?usp=sharing)

<!-- We are considering a site in India for the second CompEd in 2021. There is some flexibility on holding the conference at different times of the year, as long as it is not too close to one of our other conferences. The language of the conference will be English.
 -->
**Call for volunteers for Program Chair and other committee positions**

Fill out the form below if you are interested in volunteering as a Program Co-Chair or other position for CompEd 2021 (possibly to be held in India) or a future CompEd: [Program Chair and other committee positions volunteer form.](https://forms.gle/JHJoaSsSUPEK9Lfj9)

Please respond by March 2, 2020, though we will continue to look at responses after that date if required.


**Past, present and future CompEd conferences**\
Follow the links to conference web sites and proceedings.

{% assign items = page.conferences | sort: 'year' | reverse %}
{% for c in items %}
- {% if c.url %}[{{c.title}}]({{c.url}}){%else%}{{c.title}}{%endif%}: {{c.location}}{% if c.doi %}, [Proceedings]({{c.doi}}){%endif%}{% if c.companion-doi %}, [{{c.companion-title}}]({{c.companion-doi}}){%endif%}{% endfor %}



**Proposing an ACM Global Computing Education Conference Location**

CompEd will be hosted by universities whose computing faculty are committed to the improvement of computing education. SIGCSE seeks proposals from universities interested in hosting CompEd. The conference takes place any time during the year, but at least 6 weeks away from one of SIGCSE's other conference. [More information](https://www.acmcomped.org/host/).

