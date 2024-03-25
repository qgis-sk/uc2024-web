---
layout: post
title: Sponsors
permalink: /sponsors/
isStaticPost: true
image: sponsors.jpg
---


<div class="container">
    {% for partner in site.data.partners %}
    {% if partner.group != "Organizers" %}
    <h3>{{ partner.group }}</h3>
    <ul class="list-inline">
        {% for element in partner.elements %}
        <li>
            <a href="{{ element.link }}" target="_blank">
                <img src="{{ site.baseurl }}/img/partners/{{ element.imageUrl }}" title="{{ element.description }}" alt="{{ element.name }}" height="{{ partner.height }}">
            </a>
        </li>
        {% endfor %}
    </ul>
    {% endif %}
    {% endfor %}
</div>


<div class="row">
    <div class="col-lg-9">

<h3>Become a sponsor</h3>

<p>

We are honoured to invite you to take this opportunity to be a financial partner for the QGIS User Conference in Bratislava in 2024. By sponsoring the conference, you are extending your support to the whole QGIS community, a contribution that is essential in keeping this valuable community vibrant. In return this offers you the possibility to network and showcase your work and solutions to future customers or partners.

</p>

</div></div>



### Why become our partner?

<div class="row"><div class="col-lg-9">

<p>
QGIS User Conference partners are exposed to a highly engaged international audience of policy makers, business representatives, and industry professionals.
</p>

</div></div>

<p>
Partnership in the QGIS User Conference gives you:
</p>

* Opportunity to engage with the geospatial technology industry
* Marketing and brand exposure
* Networking opportunities
* Opportunity to make valuable contacts and increase sales


### Sponsorship Packages

<p>
If you are interested in becoming a sponsor, please contact us at: <b>uc2024@qgis.sk</b>

</p>
<p>

To learn more about the sponsorship packages and opportunities, please have a look at the linked PDF:

<div align="">
    <a href="{% link download/QGIS UC 2024 Sponsorship.pdf %}" class="btn btn-primary waves-effect waves-button waves-light waves-float">Sponsorship Packages</a>
</div>

</p>

