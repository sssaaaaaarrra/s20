---
desc: Mentor instructions for lab05
github_org: ucsb-cs48-w20
layout: lab
mentor_due: 2020-03-09 17:00
num: lab05_mentors
ready: true
ta_due: 2020-03-10 12:00

---

<div style="display:none">
https://ucsb-cs48.github.io/w19/lab/lab03_mentors/
</div>

{% capture lab %}{{ page.num | replace: '_mentors','' }}{% endcapture %}
{% capture lab_url_raw %}/lab/{{lab}}/{% endcapture %}
{% capture lab_url %}{{lab_url_raw | relative_url }}{% endcapture %}


# These instructions are for mentors/TAs only

Students, you are welcome to read them; there are no secrets here.   But there are probably better uses of your time. :-)

# Setting up templates for {{lab}}

Due {{page.mentor_due}}

The evaluation of [{{lab}}]({{lab_url}}) is only at the team level:

| Part | Template to Use | Where to Put It |
|------|-----------------|-----------------|
| Team | [<tt>{{lab}}</tt>](https://github.com/{{page.github_org}}/FEEDBACK_TEMPLATES/blob/master/{{lab}}.md) | team `_FEEDBACK` repos |


You can copy the contents of the templates file into the feedback repo and then fill it out.

# TA Review/Grading of {{lab}}

Due {{page.ta_due}}
