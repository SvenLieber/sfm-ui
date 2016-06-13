---
layout: article
title: "Overview of Social Feed Manager"
permalink: /about/overview
date: 2016-06-10
modified: 2016-06-10
excerpt: ""
share: false
ads: false
---

Social Feed Manager is a web application which allows users to create collections of data from social media platforms, 
including Twitter, Flickr, and Sina Weibo. It is open source software and connects to the platforms' public APIs to harvest data. In addition to harvesting social media data, it can also harvest web resources such as images and web pages that are linked from or embedded in the social media.
 
Researchers, librarians, archivists, and students can use SFM to:

<ul>
<li>Gather datasets tailored to specific research questions</li>
<li> Build collections for future research. This might include:</li>
  <ul>
  <li>collecting "at risk" social media data around a particular event or topic</li>
  <li>filling gaps in special collections</li>
  <li> archiving the social media activity of their institution</li>
  </ul>
</ul>

For both of these cases, SFM documents the steps in collecting in order to support valid, reproducible research and the needs of archives.

Using SFM, an institution can provide social media collecting as a service to members of its community.

Who is Social Feed Manager for?
-------------------------------
SFM is intended for use by researchers, students, librarians, and archivists who need to collect social media. 

SFM is intended to be run by an institution such as a library, although nothing prevents it from being run by an individual. SFM can manage collections created by many users, across multiple social media platforms.

How do I use SFM to collect data?
--------------------
You can use SFM to collect social media data:

<ol>
<li>Define and organize collections.
</br><img src="{{ site.github.url }}/images/overview/collection_set_multi.png" alt="collection set page with list of collections"></li>
<li> Add collections with various harvest types.
<p><img src="{{ site.github.url }}/images/overview/collection_types.png" alt="list of collection harvest types"></p></li>
<li>Add seeds.
</br><img src="{{ site.github.url }}/images/overview/seeds.png" alt="list of seeds"></br></li>
<li>Turn it on.  SFM will harvest the data on an on-going basis or according to the schedule you specify.
<img src="{{ site.github.url }}/images/overview/collection.png" alt="collection turned on"></li>
<li>Monitor harvests.</br>
</br><img src="{{ site.github.url }}/images/overview/harvests.png" alt="list of harvests"></li>
</ol>


How do I make use of social media data collected by SFM?
--------------------------------------------------------
Export a collection to a spreadsheet.

![spreadsheet screenshot]({{ site.github.url }}/images/overview/excel.png)

You can also feed data into your own processing pipeline from the command line or explore data with Elasticsearch/Logstash/Kibana (ELK).


![Kibana]({{ site.github.url }}/images/overview/kibana.png)

What sort of expertise is needed to use SFM?
--------------------------------------------
No specific expertise is needed to use SFM, but it is helpful to read the [SFM documentation](https://sfm.readthedocs.org) and be familiar with social media APIs.

What sort of technical expertise is needed to get SFM running?
--------------------------------------------------------------
SFM requires some level of expertise to run.  [Instructions](https://sfm.readthedocs.io/en/latest/install.html) are provided for running in any environment that supports Docker.  [Instructions](https://sfm.readthedocs.io/en/latest/install.html#amazon-ec2-installation) are also provided for Amazon Web Services (AWS).

What is the state of the software?
----------------------------------
The first version of SFM was released in June 2016.  While it is suitable for production, it should be considered a work in progress.  Development is active and ongoing.


Social Feed Manager is supported by a grant from the National Historical Publications & Records Commission. 