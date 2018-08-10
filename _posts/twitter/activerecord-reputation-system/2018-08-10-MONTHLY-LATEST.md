---
layout: monthly-metrics-v0.1
title: TwiterOSS Metrics Report for twitter/activerecord-reputation-system | MONTHLY-2018-08-10 | 2018-08-10
permalink: /twitter/activerecord-reputation-system/MONTHLY/

owner: twitter
repo: activerecord-reputation-system
reportID: MONTHLY-2018-08-10
datestampThisMonth: 2018-08-10
datestampLastMonth: 2018-07-13
---

<table style="width: 100%">
    <tr>
        <th>Metric</th>
        <th>This Month</th>
        <th>Last Month</th>
        <th>+/-</th>
    </tr>
    {% for item in site.data["twitter"]["activerecord-reputation-system"]["MONTHLY-2018-08-10"]["data"] %}
    <tr>
        <th>{{ item[0] }}</th>
        <th>{{ item[1]["this_month"] }}</th>
        <th>{{ item[1]["last_month"] }}</th>
        <th>{{ item[1]["diff"] }}</th>
    </tr>
    {% endfor %}
</table>
