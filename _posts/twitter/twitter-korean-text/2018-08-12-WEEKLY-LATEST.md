---
layout: weekly-metrics-v0.1
title: Metrics report for twitter/twitter-korean-text | WEEKLY-2018-08-12
permalink: /twitter/twitter-korean-text/WEEKLY/

owner: twitter
repo: twitter-korean-text
reportID: WEEKLY-2018-08-12
datestampThisWeek: 2018-08-12
datestampLastWeek: 2018-08-03
---

<table style="width: 100%">
    <tr>
        <th>Metric</th>
        <th>This Week</th>
        <th>Last Week</th>
        <th>+/-</th>
    </tr>
    {% for item in site.data["twitter"]["twitter-korean-text"]["WEEKLY-2018-08-12"]["data"] %}
    <tr>
        <th>{{ item[0] }}</th>
        <th>{{ item[1]["latest"] }}</th>
        <th>{{ item[1]["previous"] }}</th>
        <th>{{ item[1]["diff"] }}</th>
    </tr>
    {% endfor %}
</table>