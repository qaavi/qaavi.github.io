---
layout: post
title: GDPR Compliance for Developers
date: 2018-03-22T07:32:21+00:00
author: aqavi
comments: true
guid: http://blog.wecognize.com/?p=1
permalink: /blog/2018/03/22/gdpr-compliance-for-developers/
dsq_thread_id:
  - "6442587030"
onesignal_meta_box_present:
  - "1"
onesignal_send_notification:
  - ""
vcv-be-editor:
  - classic
image: https://blog.wecognize.com/wp-content/uploads/2018/03/europe-3225257_1920-150x113.jpg
categories:
  - General
tags:
  - europe
  - for developers
  - gdpr
  - gdpr compliance checklist
  - GDPR compliant
  - general data protection regulation
  - how to prepare for gdpr

# tags: gdpr gdpr-compliance gdpr-for-developers gdpr regulation
description: The General Data Protection Regulation (GDPR) will come into force on May 25th 2018. To prevent the penalty of the higher of 4% of annual worldwide turnover and EUR20 million, you've to be GDPR-compliant 
---

There are many documents related to GDPR regulation, but they're not easy to understand for developers. In part-1 of GDPR compliance for developers, we'll look into basic concepts in GDPR and how we can get started implementing it.

## What is GDPR?

<ul class="ul1">
  <li class="li1">
    The General Data Protection Regulation (GDPR) will replace the Data Protection Directive 95/46/EC (Directive). It applies to all EU and foreign organisations offering goods/services to individuals in the EU and handling personal data of EU residents.
  </li>
  <li class="li1">
    It even applies to companies that are not registered in Europe but have European customers.
  </li>
  <li class="li1">
    <strong>Approved</strong><b> </b><strong>by</strong> the EU Parliament on <b>14 April 2016</b>.
  </li>
  <li class="li1">
    <strong>Enforcement date:      25 May 2018</strong>
  </li>
</ul>

## Basic Definitions:

<li class="li1">
  <strong>Controller</strong><b>: </b>The legal person or agency that determines the purpose of processing personal data.
</li>
<li class="li1">
  <strong>Processor</strong><b>:</b> The organization that processes that data on behalf of controller.
</li>
<li class="li1">
  <strong>3rd party</strong><b>: </b>Any product/service provided by an organization that you&#8217;re using in your system &#8211; through their API, like Google APIs and others.
</li>
<li class="li1">
  <strong>Data subject:</strong><b> </b>User &#8211; The person who is using your product/service.
</li>
<li class="li1">
  <strong>Personal data: </strong>Basically, it&#8217;s every piece of data that can be used to uniquely identify a person. Data that the user has explicitly provided, but also data that you have collected about them from either third parties or based on user activities on the site.
</li>
<li class="li1">
  <strong>Supervisory authority: </strong> An independent public authority which is established by EU Member State.
</li>

For more details, visit <a href="https://gdpr-info.eu/art-4-gdpr/" target="_blank" rel="noopener">EU Official document</a>

## Who does the GDPR apply to?

<li class="p1">
  The GDPR applies to ‘<strong>controllers</strong>’ and the ‘<strong>processors</strong>’.
</li>

## What is penalty if an organisation isn&#8217;t GDPR compliant?

The GDPR establishes a tiered approach to penalties for breach

<ul class="ul1">
  <li class="li1">
    Fines for some infringements of up to the higher of <strong>4% of annual worldwide turnover and EUR20 million</strong> (eg breach of requirements relating to international transfers or the basic principles for processing, such as conditions for consent).
  </li>
  <li class="li1">
    Other specified infringements would attract a fine of up to the higher of <strong>2% of annual worldwide turnover and EUR10m</strong>.
  </li>
</ul>

## GDPR &#8211; In a nutshell

<a href="https://www.eugdpr.org/key-changes.html" target="_blank" rel="noopener">GDPR Key changes</a> you need to comply with right now.

There is an <a href="http://data.consilium.europa.eu/doc/document/ST-5419-2016-INIT/en/pdf" target="_blank" rel="noopener">Official document</a> prepared by <a href="https://gdpr-info.eu/" target="_blank" rel="noopener">EU GDPR</a> that each company needs to comply with.

<p class="p1">
  There are total of 99 articles, divided into 11 chapters. The summary of each chapter is given below:
</p>

<ul class="ul1">
  <li class="p1">
    <a href="https://gdpr-info.eu/chapter-1/" target="_blank" rel="noopener">General Provisions (Article 1 &#8211; 4)</a> &#8211; This chapter discusses basic definitions and scope.
  </li>
  <li class="li1">
    The <strong>following 2 chapters</strong> have significant changes that need to be considered and implemented: <ul>
      <li class="li1">
        <a href="https://gdpr-info.eu/chapter-2/" target="_blank" rel="noopener">Principles (Article 5 &#8211; 11)</a> &#8211; This chapter discusses things related to User consent and user’s data processing. “Privacy policy” and “term and conditions” related changes, such as user should explicitly give their consent and can withdraw consent at any time, age check, etc.
      </li>
      <li>
        <a href="https://gdpr-info.eu/chapter-3/" target="_blank" rel="noopener">Rights of the data subject (Article 12 &#8211; 23)</a> &#8211; The end user has full right on their data. The data should be accessed with user’s permission and should be erased on user’s request. This chapter discusses all the rights of end user.
      </li>
    </ul>
  </li>
  
  <li>
    <a href="https://gdpr-info.eu/chapter-4/" target="_blank" rel="noopener">Controller and Processor (Articles 24 &#8211; 43)</a> &#8211;<span class="Apple-converted-space">  </span>The responsibilities of controller and processor are discussed. Besides, this chapter discusses various roles such as duties and responsibilities of DPO &#8211; Data Protection Officer, etc.
  </li>
  <li>
    <a href="https://gdpr-info.eu/chapter-5/" target="_blank" rel="noopener">Transfer of personal data to 3rd countries or international org (Articles 44 &#8211; 50)</a> &#8211; This chapter discussed legal matters related to international transfer of EU citizen’s data.
  </li>
  <li>
    <a href="https://gdpr-info.eu/chapter-6/" target="_blank" rel="noopener">Independent Supervisory Authorities (Articles 51 &#8211; 59)</a> &#8211;<span class="Apple-converted-space">  </span>This chapter discusses the responsibilities of each EU member state to monitor the application of GDPR regulation.
  </li>
  <li>
    <a href="https://gdpr-info.eu/chapter-7/" target="_blank" rel="noopener">Cooperation and Consistency (Articles 60 &#8211; 76)</a> &#8211; This discusses cooperation b/w supervisory authorities, responsibilities of the board and other entities to make sure the consistent application of GDPR regulation.
  </li>
  <li>
    <a href="https://gdpr-info.eu/chapter-8/" target="_blank" rel="noopener">Remedies, Liability and Penalties (Articles 77 &#8211; 84)</a> &#8211; This chapter discusses how end-user can lodge a complaint with “supervisory authority” against any controller, and penalties are discussed.
  </li>
  <li>
    <a href="https://gdpr-info.eu/chapter-9/" target="_blank" rel="noopener">Provisions related to specific Processing situations (Articles 85 &#8211; 91)</a> &#8211;
  </li>
  <li>
    <a href="https://gdpr-info.eu/chapter-10/" target="_blank" rel="noopener">Delegated acts and Implementing Acts (Articles 92 -93)</a> &#8211;
  </li>
  <li>
    <a href="https://gdpr-info.eu/chapter-11/" target="_blank" rel="noopener">Final Provisions (Articles 94 &#8211; 99)</a> &#8211;
  </li>
</ul>

## What should we do to get our system GDPR compliant?

# Principles (Articles 5 &#8211; 11)

<ul class="ul1">
  <li class="li1">
    <strong>Consent checkboxes</strong> &#8211;<a href="https://gdpr-info.eu/art-7-gdpr/" target="_blank" rel="noopener"><b> Article 7</b></a>
  </li>
</ul>

This seems to be the biggest change that the regulation brings. &#8220;I accept the terms and conditions&#8221; would no longer be sufficient to claim that the user has given their consent for processing their data. So, for each particular processing activity, there should be a separate checkbox on the registration (or user profile) screen. You should keep these consent checkboxes in separate columns in the database, and let the users withdraw their consent.

<ul class="ul1">
  <li class="li2">
    <span class="s2"><strong>Age check</strong> &#8211;<a href="https://gdpr-info.eu/art-8-gdpr/" target="_blank" rel="noopener"><b> Article 8</b></a></span>
  </li>
</ul>

You should ask for the user&#8217;s age, and if the user is a child (below 16), you should ask for parent permission.

#   Rights of data subject/User (Articles 12 &#8211; 23)

<ul class="ul1">
  <li class="li2">
    <span class="s2"><strong>Export data</strong> &#8211; <a href="https://gdpr-info.eu/art-20-gdpr/" target="_blank" rel="noopener"><b>Article 20</b></a></span>
  </li>
</ul>

There should be another button, &#8220;export data&#8221;. When clicked, the user should receive all the data that you hold about them.

<ul class="ul1">
  <li class="li1">
    <strong>See all my data</strong> &#8211; <a href="https://gdpr-info.eu/art-15-gdpr/" target="_blank" rel="noopener"><b>Article 15</b></a>
  </li>
</ul>

This is very similar to the &#8220;Export&#8221; button, except data should be displayed in the regular UI of the application rather than an XML/JSON format.

<ul class="ul1">
  <li class="li1">
    <strong>Allow users to edit profile</strong> &#8211;<a href="https://gdpr-info.eu/art-16-gdpr/" target="_blank" rel="noopener"><b> Article 16</b></a>
  </li>
</ul>

This seems an obvious rule, but it isn&#8217;t always followed. Users must be able to fix all data about them, including data that you have collected from other sources (e.g. using a &#8220;login with Facebook&#8221; you may have fetched their name and address).

<ul class="ul1">
  <li class="li2">
    <span class="s2"><strong>Forget me</strong> &#8211; <a href="https://gdpr-info.eu/art-17-gdpr/" target="_blank" rel="noopener"><b>Article 17</b></a></span>
  </li>
</ul>

Make sure you provide &#8220;Forget me&#8221; option in your app/website, where user can click to delete all their data from your system.

<ul class="ul1">
  <li class="li1">
    <strong>Restrict processing</strong> &#8211;<a href="https://gdpr-info.eu/art-18-gdpr/" target="_blank" rel="noopener"> <b>Article 18</b></a>
  </li>
</ul>

In your admin panel where there&#8217;s a list of users, there should be a button labeled &#8220;restrict processing.&#8221; The user settings page should also have that button. When clicked (after reading the appropriate information), it should mark the profile as restricted. That means it should no longer be visible to the back office staff, or publicly.

<ul class="ul1">
  <li class="li1">
    <strong>Notify 3rd party for erasure</strong> &#8211; <a href="https://gdpr-info.eu/art-19-gdpr/" target="_blank" rel="noopener"><b>Article 19</b></a>
  </li>
</ul>

If you are providing user data to 3rd party, make sure you ask 3rd party to delete all the data when user asks your system to &#8220;forget me&#8221;. Calling the third party APIs to remove data is not the full story, though. You also have to make sure the information does not appear in search results. Now, that&#8217;s tricky, as Google doesn&#8217;t have an API for removal, only a <a href="https://support.google.com/websearch/answer/6349986?hl=en" target="_blank" rel="noopener">manual process.</a> Most other organisations also don&#8217;t have regular API to remove data from their system.

## Other Considerations

# Data Encryption:

  1. **Secure communication over TLS (Https):**  All the communication should be over secure channel such as TLS, communication between client and server, and server-to-server.
  2. **Databases encrypted**:  Databases and backups should all be encrypted.
  3. **Pseudonymisation**: When using Production data on test/staging server for testing purpose, make sure you hide actual users data, such that no person is identified.

# Logging data:

  1. **Loggin personal data:  **If you&#8217;re logging data to your server, make sure no personal data is logged.
  2. **Analytics:  **If you&#8217;re using analytics in your system, make sure no personal data is used for analytics purpose.

# 3rd party:

  1. If you&#8217;re sending data to 3rd party for processing, such as data backup, or for analytical processing of data, it&#8217;s your responsibility to make sure 3rd party is GDPR compliant.

**Make sure you&#8217;re not using any data of users who haven&#8217;t agreed with specific terms and conditions on your system.**

&nbsp;

(In progress&#8230;)

Bookmark the [permalink](http://blog.wecognize.com/blog/2018/03/22/gdpr-compliance-for-developers/)


<p class="p1">
  <strong>Disclaimer</strong>:<span class="Apple-converted-space">  </span>I’ve prepared this document to the best of my knowledge and studies related to GDPR regulation. Professionally I’m not a lawyer or DPO, I’m a professional Software developer, so I may have missed some important legal matters. For more detailed explanation &#8211; check <a href="https://www.eugdpr.org/" target="_blank" rel="noopener">EUGDPR</a><span class="Apple-converted-space">  or</span> consult <a href="https://gdpr-info.eu/art-39-gdpr/" target="_blank" rel="noopener"><strong>DPO (Data Protection Officer)</strong></a> who has “expert knowledge of data protection laws and practices”.<span class="Apple-converted-space"> </span>Responsibilities and appointment of DPO are discussed <a href="https://edps.europa.eu/data-protection/data-protection/reference-library/data-protection-officer-dpo_en" target="_blank" rel="noopener">here</a>. This document is work-in-progress, so any changes or rectifications are highly welcomed.
</p>

Inspired from <a href="https://logsentinel.com/gdpr-practical-guide-developers/#more-192" target="_blank" rel="noopener">GDPR-practical-guide</a>