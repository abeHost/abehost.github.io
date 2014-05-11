---
layout: default
title: Support
slug: support
items:
-
    title: Control Panel
    alias: control-panel
    desc: "Our custom-made control panel is designed with you in mind. But if you are having any difficulty with logging in, or using the customer area, then read on."
-
    title: Domains
    alias: domains
    desc: "Registering a domain name with us couldn't be simpler. But what happens after you own it? Do you need to delegate it to different nameservers? Don't know what zone records are? This resource is for you."
-
    title: Cloud Hosting
    alias: cloud-hosting
    desc: "Just bought Cloud web hosting? Use this resources to help set up your email, upload your website with FTP, and install databases."
-
    title: cPanel
    alias: cpanel
    desc: "Never used cPanel before? Don't worry, we've covered the basics here. cPanel also has a complete user guide, available from within your cPanel interface."
---
# Support

We pride ourselves on our knowledge and support. For the most frequently asked support questions, please check the resources below. If you cannot find what you are looking for here, please contact us and we will assist you.

<ul class="box-list equal">
  {% for item in page.items %}
  <li><a class="box" href="{{ item.alias }}">
    <h3 class="media-heading">{{ item.title }}</h3>
    <span class="text-muted">{{ item.desc }}</span>
    </a>
  {% endfor %}
</ul>
