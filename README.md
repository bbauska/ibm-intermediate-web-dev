---
title: "IBM's Intermediate Web & Front-end Development"
author: "bbauska"
date last editted: "10/15/2023 1+pm"
output: 
  markdown:
    with_style
---
<!-- [IBM's Intermediate Web and Front-End Development by Coursera](https://www.coursera.org/learn/intermediate-web-and-front-end-development/lecture/k0fxN/course-introduction) -->

<!-- https://www.coursera.org/learn/intermediate-web-and-front-end-development/lecture/k0fxN/course-introduction -->

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ readme.md of ibm-web-dev.bauska.org ~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image001.webp" 
  alt="Intermediate Web &amp; Front-end Development." 
  style="border: 2px solid #000000;" 
  width="500" />
</p>

[![A mushroom-head robot](/assets/images/image001.webp 'Intermediate Web &amp; Front-end Development.')](https://ibm-web-dev.bauska.org)

[![readme](https://github.com/bbauska/ibm-intermediate-web-dev/tree/main/assets/images/image001.webp 'image 001')](https://github.com/bbauska/ibm-intermediate-web-dev)

<h2><a href="#table-of-contents">Table of Contents</a></h2>

## [**Week 1: Content Management Systems (CMS)**](#ch1)
>### 1.01 [**Introduction to Intermediate Web &amp; Front-end Development**](#ch1-01)
>### 1.02 [**Introduction to Content Management Systems (CMS)**](#ch1-02)
>### 1.03 [**Features of Web CMS**](#ch1-03)
>### 1.04 [**Popular CMS Platforms/Tools**](#ch1-04)
>### 1.05a [**Web Development with CMS part 1**](#ch1-05a)
>### 1.05b [**Web Development with CMS part 2**](#ch1-05b)
>### 1.06a [**Getting Started with WordPress part 1**](#ch1-06a)
>### 1.06b [**Getting Started with WordPress part 2**](#ch1-06b)
>### 1.07 [**Adding E-Commerce to your Website**](#ch1-07)

## [**Week 2: Search Engine Optimization (SEO)**](#ch2)
>### 2.08 [**Introduction to Search Engine Optimization (SEO)**](#ch2-08)
>### 2.09 [**Popular SEO Tools**](#ch2-09)
>### 2.10 [**SEO Strategies**](#ch2-10)
>### 2.11 [**Mobile Friendly SEO**](#ch2-11)
>### 2.12 [**Page Optimization for SEO**](#ch2-12)
>### 2.13 [**Running Campaigns and Tracking Results**](#ch2-13)
>### 2.14 [**Do's and Don'ts of Search Engine Optimization**](#ch2-14)

## [**Week 3: WebPack**](#ch3)
>### 3.15 [**Introduction to Web Build and Automated Tools**](#ch3-15)
>### 3.16 [**Introduction to Webpack 5**](#ch3-16)
>### 3.17 [**Essential Concepts of Webpack**](#ch3-17)
>### 3.18 [**Working with Webpack**](#ch3-18)
>### 3.19 [**Setting up Production with Webpack**](#ch3-19)
>### 3.20 [**Using Webpack Tools**](#ch3-20)
>### 3.21 [**Using Webpack with Frontend Frameworks**](#ch3-21)
>### 3.22 [**Webpack Best Practices**](#ch3-22)
>### 3.23 [**HTTPS &amp; SSL Certificates**](#ch3-23)

## [**Week 4: Optimization &amp; Testing**](#ch4)
>### 4.24 [**JavaScript Optimization**](#ch4-24)
>### 4.25 [**Popular Optimization Tools**](#ch4-25)
>### 4.26 [**Testing Frameworks**](#ch4-26)
>### 4.27 [**Testing Tools – Mocha and Jasmine**](#ch4-27)
>### 4.28 [**Using Jasmine**](#ch4-28)
>### 4.29 [**Front-end Testing Best Practices**](#ch4-29)

## [**Week 5: Debugging &amp; Troubleshooting**](#ch5)
>### 5.30 [**JavaScript Debugging**](#ch5-30)
>### 5.31 [**Basic Debugging Concepts**](#ch5-31)
>### 5.32 [**Introduction to Debugging Tools**](#ch5-32)
>### 5.33 [**Troubleshooting with Chrome DevTools**](#ch5-33)
>### 5.34 [**Monitoring your Website**](#ch5-34)
>### 5.35 [**Popular Monitoring Tools**](#ch5-35)

## [**Week 6: Interest Rate Calculator**](#ch6)
>### 6.36 [**Interest Rate Calculator**](#ch6-36)

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<h1 name="ch1" style="margin:15px;">WEEK 1 - Content Management Systems (CMS's)</h1>

<h2>01. Course Introduction</h2>

https://www.coursera.org/learn/intermediate-web-and-front-end-development/lecture/k0fxN/course-introduction

<h2 name="ch1-01" style="margin:15px">01. Introduction to Intermediate Web &amp; Front-End Development</h2>

Hello and welcome to this course on Intermediate Web and Front-end
Development. Are you interested in learning how to optimize your website
for search engines? Or do you want to learn how to increase the
visibility of your website? You will need to be familiar with the
various tools and technologies available on the market for this. You
will also need to learn about testing and the tools needed to conduct
tests while staying within your budget. There are numerous options
available to you in this field, but you need to have a solid foundation
in web development fundamentals.

Search engines are constantly changing their algorithms and implementing
modifications for website ranking. You can evaluate and interpret user
experiences using web optimization based on website runtime and load
time.

Learning about automated build tools and bundlers can help you build
your website successfully.

Tools like these broaden your opportunities to focus on better
development. Coding errors may cause your website to crash or lag. To
understand why debugging is such a crucial part of the software
development process, you'll require testing frameworks with automated
testing.

These improve testing speed and efficiency, test accuracy, and reduce
test maintenance costs and risks. Learning the fundamentals presented
here is the first step towards a long and rewarding career as a web
developer.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image002.webp"
  alt="To complete this course, you should be familiar with the following knowledge."
  width="500" />
</p>
<!-- height="2.8327996500437447in"} -->

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

To successfully complete this course, you should be familiar with the
following:

-   Basic knowledge of computer terminology,

-   Basic knowledge of website development,

-   Have a familiarity with the web development tools, and

-   Have a familiarity with the search engine elements.

This course is part of a series of IBM courses designed to help you
improve your skills as a front-end developer and understand the
technical aspect of web and front-end application development.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~ 03. when you complete this course, you will be able to (xx) ~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image003.webp"
  alt="When you complete this course, you will be able to:"
  width="500px;" />
</p>
<!-- {width="5.0in" height="2.8327996500437447in"} -->

When you complete this course, you will be able to:

-   Identify how to work with content management systems (CMSs)

-   Identify how to improve a website&apos;s search engine ranking,

-   Discuss the importance of bundling code with a module bundler to
    deploy code faster,

-   Describe how automated testing frameworks assist in developing test
    cases that enhance a website&apos;s effectiveness and performance
    (efficacy), and

-   Demonstrate best practices for using debugging tools to find bugs in
    code by increasing visibility, analysis, and testing.

This course is designed specifically for beginners, with guided
instructional videos that walk you through key concepts and essential
need-to-know facts.

It includes interactive activities to reinforce what you&apos;ve learned in
videos and virtual hands-on labs to help you apply what you&apos;ve learned
as you go.

The forums connect you with others so you can introduce yourself,
provide feedback, and get support. And the practice assessments help you
assess your knowledge, while the graded assessments prove what you&apos;ve
learned, leading to a shareable badge and certificate that you can show
prospective employers. We're here to support your success and are
excited you're here. Let's get started!
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 name="ch1-02">02. Introduction to Content Management System (CMS)</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image004.webp"
    alt="Introduction to Content Management System (CMS)."
    width="500" />
</p>
<!-- {width="5.0in" height="2.557691382327209in"} -->

<!-- <https://www.coursera.org/learn/intermediate-web-and-front-end-development/lecture/zjLwk/introduction-to-content-management-system-cms> -->

Welcome to "Introduction to Content Management System (CMS)"

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~ 05. define cms, list cms platforms and recognize benefits of cms (xx) ~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image005.webp"
    alt="After reading, you will be able to: Define CMS, List several CMS platforms and Recognize the benefits of using CMS."
    width="500" />
</p>
<!-- {width="5.0in" height="2.5576924759405073in"} -->

After reading this module (02), you will be able to:

-   Define Content Management Systems (CMSs),

-   List several CMS software/platforms, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Recognize the benefits of using a CMS.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~ 06. what is content management system? (xx) ~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image006.webp"
    alt="What is Content Management System?"
    style="width:500px;"/>
</p>
<!-- {width="5.0in" height="2.7841885389326335in"} -->

What is a Content Management System (or CMS)? A CMS is a tool that helps
developers build websites. It is software that allows developers to
create, manage, and modify content on a website without requiring users
to have specialized technical knowledge. CMS is a general term for the
processes involved in developing a large-scale website. Well-managed
content makes a website more useful to visitors and valuable to the
person or organization who owns the website.

A CMS has two core parts: The Content Management Application (CMA) is a
software tool that enables developers to add and manage content on a
website. And the Content Delivery Application (CDA) is the back-end
process that takes the content you put into the CMA, stores it properly,
and makes it visible to website visitors.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~ 07. 3 common types of cms; web, digital and enterprise (xx) ~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image007.webp"
    alt="There are 3 common typoe of CMS;  Web CMS, Digital CMS, and Enterprise CMS."
    style="width:500px;"/>
</p>
<!-- {width="5.0in" height="2.7841885389326335in"} -->

There are three common types of content management systems:

  - A Web Content Management System (WCMS) controls the content on many digital
    channels. It also manages and handles HTML documents and associated
    images. A WCMS enables developers to maintain an extensive collection of
    web documents and materials.
  - A Digital Asset Management System (DAMS) focuses on the customer experience
    (CX). It enables the correct delivery of content to the users and centralizes
    assets, content, workflows, and operations. And,
  - Enterprise Content Management System (ECMS) collects, stores, delivers, and
    manages unstructured data, enables delivery of the correct content to targeted
    audiences, and archives files after a set time.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~ 08/09. examples of proprietary and open-source cms sfwr (xx) ~~~~~~~~~~~~~~~~-->
<p align="center">
<img src="./assets/images/image008.webp"
  style="width:400px;"
  alt="Examples of proprietary and open-source CMS software." />
<img src="./assets/images/image009.webp"
  style="width:400px;"
  alt="More examples of proprietary and open-source CMS software." />

<!-- {width="3.0in" height="1.6705129046369205in"}! -->

There is both proprietary and open-source CMS software. Some examples
are WordPress, Drupal, Joomla, Magento, Squarespace, Wix, and HubSpot.
Some of these are software you can install on your website host, for
example, Wordpress.org, Drupal, and Joomla. Others are available as
hosted services like WordPress.com, HubSpot, and Wix. Many kinds of CMS
software are available, depending on how developers want to use them.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~ 10. benefits of cms software (xx) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image010.webp"
  alt="Benefits of CMS Software." 
  style="width:500px;"/>
</p>
<!-- {width="5.0in" height="2.7927351268591427in"} -->

So why use a CMS? Instead of creating a new web page or designing a new
website, many solutions exist that can function how designers want.

A CMS makes a recognizable and comfortable website and is quick and easy
for developers and organizations to manage. Some people use content
management systems to create content for many reasons, like creating and
managing. Static websites, membership sites, blogs, forums, social
networking sites, e-commerce stores, online courses, and portfolios.

One of the biggest benefits is that users can create websites quickly
and easily because they need little to no programming language
background. Another benefit is scheduled updates. Updates to content and
the website are easy to make. Some CMS software also prepares for
publishing and updates. Affordability is a huge benefit of using CMS
software. Instead of using a large web development team, websites can be
managed by a smaller group or by a person, reducing the website&apos;s cost.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~ 11. add'l benefits of cms software (xx) ~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image011.webp"
  alt="Additional Benefits of CMS Software." 
  style="width:500px;"/>
</p>

CMS software also provides tools to allow users to customize their
website, regardless of the company size or the user's needs. Many CMSs
include drag-and-drop interfaces and visual editors for building
websites rather than coding them.

CMSs have templates and third-party extensions that make it easy to
customize the website and extend its capabilities.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 12. choosing a cms (xx) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image012.webp"
  alt="Choosing a CMS." 
  style="width:500px;"/>
</p>

So how do you choose a CMS? In the planning stage of the software
development cycle, you&apos;ll consider what you need to help you create and
manage a website. You&apos;ll ask:

-   How big does your website need to be to meet your organization&apos;s
    needs?

-   Who will be using your website?

-   What functionality do you and your users need to have?

-   What skills do you need to have to develop the website? And,

-   Does your CMS need other technologies or software to work with it?

Once you&apos;ve answered these questions, you're ready to choose the best
CMS for you and your website!

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ 13. module 02 summary (xx) ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image013.webp"
  alt="Module Summary (02)." 
  style="width:500px;"/>
</p>

In this module (02), you learned that:

-   A Content Management System (or CMS) is a tool that helps developers
    build websites,

-   A Content Management Application (or CMA) allows developers to add
    and manage content on a website,

-   A Content Delivery Application (or CDA) manages the back-end
    process, including content in the CMA, storage, and visibility,

-   Three types of content management systems are;

  1.  Web content management systems,

  2.  Digital asset management systems, and

  3.  Enterprise content management systems.

-   CMS benefits include more accessible website publishing, scheduling,
    affordability, and customization,

-   Some popular CMS platforms are WordPress, Drupal, Joomla, Magento,
    Squarespace, and Wix.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<h2 name="ch1-03">03. Features of Web CMS</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!-- <https://www.coursera.org/learn/intermediate-web-and-front-end-development/lecture/BWeid/features-of-web-cms> -->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~14. features of web cms ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image014.webp"
  alt="Features of Web CMS." 
  style="width:500px;"/>
</p>

Welcome to "Features of Web CMS."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image015.webp"
  alt="What you will learn in Module 03 - Features of Web CMS."
  style="width:500px;"/>
</p>

After reading this module (03), you will be able to:

-   Describe a Web Content Management System (WCMS) and its types,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify the characteristics of the Web Content Management System,
    and

-   Explain Enterprise Content Management System (ECMS).

In today's digital world, an organization must manage and update its
official website regularly. An organization needs to enable technical
and non-technical end users to create and manage the content on its
website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image016.webp"
  alt="What is WCMS - Web Content Management System?" 
  style="width:500px;"/>
</p>

This is made possible by Web Content Management System (WCMS). It is a
program that helps users create, manage, modify, and publish content on
a web page. A user interacts with a Web Content Management System
through a standard web browser. Users store the content in a database
using programming languages like XML and .Net.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image017.webp"
  alt="Types of WCMSs: No-code and Code." 
  style="width:500px;"/>
</p>

Let's discuss the two kinds of WCMSs: no-code and code. You can choose
between the two based on your requirements, technical skills, and the
time needed to create a web page. Technical and non-technical users
adopt the no-code approach to develop a web page using a graphical user
interface. Note that users do not have to write code for the
development.

The no-code approach allows the user to review the page before it is
published. No-code is easier, quicker, cheaper, and ideal for beginners
and small businesses.

The other type of development, code, enables a user to create a fully
customizable web page with unique features. In this case, the user needs
basic knowledge of programming languages, such as HTML, CSS, and PHP, to
create, customize, and host web pages. We will now talk about the
essential characteristics of WCMS.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image018.webp"
    alt="A WCMS enables a user to accomplish the following tasks." 
	style="width:400px;"/>
  <img src="./assets/images/image019.webp"
    alt="More tasks accomplised with WCMS software."
	style="width:400px;"/>
</p>

A WCMS enables a user to accomplish specific tasks. Some of these
include:

-   Creating web pages quickly with pre-set page layouts and content
    blocks,

-   Reviewing and approving the content before it is published,

-   Automating the publishing process,

-   Editing and formatting the content using simple drag-and-drop tools,

-   Collaborating with different users to create and modify the content,
    and

-   Scaling and implementing change to multiple domains easily and
    quickly.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image020.webp"
    alt="WCMS enables a user to accomplish the following additional tasks." 
	style="width:400px;"/>
  <img src="./assets/images/image021.webp"
    alt="WCMS enables a user to accomplish the following additional tasks." 
	style="width:400px;"/>
</p>

Here are the additional tasks that a WCMS enables a user to accomplish:

-   Managing the life cycle of a document, including creation,
    revisions, publication, archive, and removal,

-   Translating and publishing content in different languages easily,

-   Saving and retrieving different versions of a web page,

-   Updating a web page as per the latest web standards quickly,

-   Adding plugins to enhance the functionality of a web page, and

-   Managing user access to a particular page on a website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image022.webp"
  alt="Enterprise CMS: Manage content throughout the lifecycle intelligently." 
  style="width:500px;"/>
</p>

Enterprise Content Management System (ECM) allows businesses to manage
content throughout their lifecycle intelligently. A Web Content
Management System is a subset of an Enterprise Content Management
System. It primarily focuses on web content. An Enterprise Content
Management System integrates software tools with an organization's
strategy and aligns with its routine business operations.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image023.webp"
  alt="Module 3 Summary: WCMS." 
  style="width:500px;"/>
</p>

In this module (03), you learned that:

-   A WCMS enables users to create, manage, and modify content on a web
    page,

-   There are two kinds of WCMSs:

    -   No code enables both technical and non-technical users to
        develop a website, and

    -   Code enables a user to create customizable web pages.

-   A WCMS has several features that an end user can use to create and
    manage the content on their website.

<h2 name="ch1-04">04. Popular CMS Platforms/Tools</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image024.webp"
  alt="Welcome to Popular CMS Platofrms/Tools (04)." 
  style="width:500px;"/>
</p>

Welcome to "Popular CMS platforms/tools."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image025.webp"
  alt="Summary Module 04: Explain Headless CMS and Identify popular CMS Platforms and Tools."
  style="width:500px;"/>
</p>

After reading this module (04), you will be able to:

-   Explain Headless Content Management System (CMS), and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify popular CMS platforms and tools.


<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image026.webp"
  alt="Headless CMSs: True Integration." 
  style="width:500px;"/>
</p>

Headless content management systems (CMSs) have gained popularity
recently and are set to replace traditional CMSs. A conventional CMS
needs more flexibility for content reuse or formatting. Once published,
a content asset is in its final state and can be neither reused nor
formatted. If a user wants to customize a traditional CMS, the best they
can do is add a plugin, which is more like a Band-Aid. On the other
hand, a "headless" CMS offers true integration as new functionalities or
features can be added to a website easily and comprehensively. Today, we
live in a world that is Omni channel. Unlike in the past, users now
consume data on different channels. Hence, from an organizational
perspective, the content developed for the organization's website must
also be uploaded on other channels such as apps or newsletters. Any
change made at a centralized location is implemented everywhere where it
matters. This is the power that a headless CMS has.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image027.webp"
  alt="Headless CMS: to deliever content to the different channels." 
  style="width:500px;"/>
</p>

The headless approach enables organizations to deliver content to
different channels, such as mobile applications or JavaScript
applications running on a browser, email blasts, and social media
campaigns. In this type of architecture, the backend, the CMS, or the
body, is separated from the front end, the presentation layer, or the
head. Therefore, it is called a headless CMS. A headless CMS platform
ensures that, regardless of the device a customer uses to interact with
a brand, their experience is consistent. A headless CMS architecture is
less susceptible to cyber security threats as the back end is separated
from the front end.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image028.webp"
  alt="WordPress and Joomla CMS Platforms."
  style="width:500px;"/>
</p>

WordPress is one of the most popular CMS platforms. It accounts for more
than 60% of the CMS market. It offers the flexibility and freedom to
build and run any type of website without a developer. It has a hugely
supportive community and offers more extensibility through different
plugins and apps. It supports SEO, and you can control how to earn
online from the website you own.

Another popular CMS is Joomla, which comes with many different templates
and extensions. Joomla is ideal for developers and experienced website
creators. It has a large pool of extensions that gives plenty of design
options and constant feature updates.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image029.webp"
  alt="Squarespace &amp; WIX CMS Platforms." 
  style="width:500px;"/>
</p>

The next popular CMS that we are going to discuss is Squarespace. It's
an integrated platform where you can build your website and blog, host
content, and sell your products and services. You need to sign up for
the subscription, and Squarespace will make it easy for you to build a
website from scratch, which is handy if you don't have web development
experience or need to get a website up and running in a short time.

We will now explore another functional CMS, which is Wix. It is a
cloud-based web development platform that lets you create HTML5 and
mobile-optimized websites easily. The platform offers a drag-and-drop
system and you can add more functionalities by adding plugins. One can
use Wix for various purposes, such as email marketing, e-commerce,
contact forms, and community forums. You can choose from different plans
based on your requirement.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image030.webp"
  alt="Shopify CMS Platform."
  style="width:500px;"/>
</p>

Shopify is a popular CMS platform for developing e-commerce websites.
It's an all-in-one website builder and content management system with
built-in payment processing for selling online. The software offers
tools to build a brand, sell on social media platforms and online
marketplaces, and process in-person sales with Shopify POS. Shopify
makes it easy for you to manage every aspect of product sales. You can
set variants, allow inventory tracking, adjust pricing, add weights,
change the order of your products, and do more. You can create, edit,
and manage blogs, landing pages, and other navigation elements besides
managing products.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image031.webp"
  alt="Drupal and Adobe Commerce CMS Platforms."
  style="width:500px;"/>
</p>

Drupal is a free and open-source CMS. It's not as popular as WordPress
and Joomla in terms of market share but is impressive in delivering
higher performance. It offers the flexibility to create and manage
custom post types. You'll also benefit from the high level of control
that it offers users and permissions. Drupal also can deliver
multilingual websites right out of the box, enabling your business to
reach a wider audience.

Adobe Commerce, earlier known as Magento, targets companies that want to
take their customers' online shopping experience to the next level. This
software is not meant for beginners. It's mostly used mainly by
mid-market and enterprise businesses and B2B organizations that need
complete customization at a scale. Another highlight of this software is
its ability to create a progressive web app (PWA) for your online store.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image032.webp"
  alt="Module 04: What you Laerned."
  style="width:500px;"/>
</p>

In this module (04), you learned that:

-   Headless CMSs have become increasingly popular and are set to
    replace traditional CMSs,

-   WordPress offers the flexibility to build and run any type website,
    and

-   Joomla, Squarespace, Wix, Shopify, Drupal, and Adobe Commerce are
    all popular CMS platforms.

<h2 name="ch1-05a">05a. Web Development with CMS - Part 1</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image033.webp"
  alt="Welcome to Web development with CMS - Part 1"
  style="width:500px;"/>
</p>

Welcome to "Web development with CMS - Part 1."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image034.webp"
  alt="Explain important elements of a web development plan and define best practices for a sucessful business website."
  style="width:500px;"/>
</p>

After reading this module (05a), you will be able to:

-   Explain important elements of a web development plan, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Define best practices for a successful business website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image035.webp"
  alt="Web development plan and it's elements."
  style="width:500px;"/>
</p>

In today's competitive world, a website is essential for a business
owner to acquire new and loyal customers. However, before the website
launch, planning is necessary. A lot is done before the actual coding
for the website starts. A web development plan needs to be in place.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image036.webp"
  alt="Web development plan and it's 5 elements."
  style="width:500px;"/>
</p>

Let's discuss the five important elements of this plan.

These include:

-   Developing a web strategy,

-   Adopting a global approach,

-   Creating page templates,

-   Focusing on personalization,

-   Leveraging user and group roles.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image037.webp"
  alt="Elements of a Web development plan: Developing a web strategy."
  style="width:500px;"/>
</p>

Let's discuss each of them in detail.

An important element of a web development plan is developing a web
strategy. A web strategy lays the foundation for a website's build and
design. It's a comprehensive plan that takes into account various
aspects.

Some of these include:

-   Aims and objectives of the business,

-   Geographic reach,

-   Marketing goals,

-   Brand identity tone and essence, and

-   Financial targets.

Having a web strategy ensures that:

Your web design is in line with your web goals, and yhe website that the
designers and developers create functions as per your business goals.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image038.webp"
  alt="Elements of a Web development plan: Adopting a global approach."
  style="width:500px;"/>
</p>

Adopting a global approach is the next important element of a web
development plan. In the 21st century, the growth of the internet has
created a mindset of "going global." Businesses, regardless of their
size, are aiming to capture new markets. As a result, developers have to
ensure their websites are valuable and accessible to a wide and diverse
range of international customers. They need to adopt a global
modular approach. Measures need to be put in place at the outset so that
adaptation later is as easy as possible. You will not have to edit every
page if your website needs an update.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image039.webp"
  alt="Elements of a Web development plan: Creating page templates."
  style="width:500px;"/>
</p>

The other important element of a web development plan is the creation of
page templates. A website template is a pre-defined layout that enables
a developer to arrange a website's content to make it appealing to
users. If you plan to develop a website using a template, you don't need
coding experience. You need to select a template based on the nature and
purpose of your website. You can customize the template according to
your business's goals. This will help you save time, money, and effort.
A website developed using a template can be updated easily and
regularly.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image040.webp"
  alt="Elements of a Web development plan: focusing on Personalization."
  style="width:500px;"/>
</p>

Today, every visitor to a website expects a customized user experience.
This is why focusing on personalization is an important element of a web
development plan. With customization, you can target your audience and
give them a tailored experience across all platforms. Additionally, you
can manage all web-based projects online, regardless of where you deploy
them, and give autonomy to marketing. As an API works seamlessly across
all channels, personalized information appears for each visitor,
regardless of how they access the website or what device they use. By
providing content tailored to each visitor's taste, content
recommendations personalize every visitor's digital experience.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image041.webp"
  alt="Elements of a Web Development Plan: Leveraging user and group roles."
  style="width:500px;"/>
</p>

The last element of a web development plan that we are going to be
discussing is leveraging user and group roles. Member roles are
systematic assignments of privileges to members. These include general
rights for groups, system preferences, content, analysis tools, and
sharing. A group with more rights than the general group is given
administrative privileges. Administrators can leverage pre-existing
roles and build new ones to suit their user base.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image042.webp"
  alt="Best practices for creating a successful business website."
  style="width:500px;"/>
</p>

Now, we will explore some best practices for creating a successful
business website. Ensure that your website makes the best use of search
engine crawlers. Ensure Google and other popular search engines can
easily find your website. Use a CMS to manage your website&apos;s content.
Use an optimizer tool or an image optimization service to optimize
images for SEO. Use an insights tool or an online speed testing service
to optimize text for SEO. Use fonts optimized for website readability
rather than typefaces that might be too small or too big for some
devices or browsers. Use JavaScript to enhance your website's
functionality. Use CSS to style the graphics and text on your website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image043.webp"
  alt="05a Web Development with CMS - Part 1."
  style="width:500px;"/>
</p>

In this module (05a), you learned about:

-   The important elements of a web development plan, and

-   Best practices to create a successful website.

<h2 name="ch1-05b">05b. Web Development with CMS - Part 2</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image044.webp"
  alt="Welcome to 05b Web Development with CMS - Part 2."
  style="width:500px;"/>
</p>

Welcome to "Web development with CMS -- Part 2 (05b)."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image045.webp"
  alt="Module 05b Summary: Identify types of website pages and features of a CMS."
  style="width:500px;"/>
</p>

After reading this module (05b), you will be able to:

-   Identify the types of pages of a website, and

-   Explain the features of a CMS.
<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image046.webp"
  alt="Summary of Different Page types of a web site."
  style="width:500px;"/>
</p>

<p>Each page of a website plays a vital role in its functioning. For users
to easily navigate and access content, it is crucial that each page
functions effectively and meets the user's needs. In this module (05b), we will
explore different types of pages of a website developed using a CMS.</p>
<p>These include:</p>

-   Front page,

-   Post page,

-   List or category page,

-   Search page,

-   User or author profile, and

-   User home or dashboard.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image047.webp"
  alt="Website Page Types: Front Page and Post Page."
  style="width:500px;"/>
</p>

Let's discuss each page in detail. The first type of page that we are
going to talk about is the front page. This page is the formal entry
point and is like a homepage. It helps highlight what is crucial,
especially when there is a vast amount of content to access. It
typically shows concise versions of posts.

The next type of page is the posting page. A "post" is the central
component of a CMS-driven application. The posting page displays all of
the public information about a post. The purpose of this type of page is
to display timely and regularly updated content. It could be an
informational page about a person, group, event, product, and so on.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image048.webp"
  alt="Website Page Types: List or Category Page and Search Page."
  style="width:500px;"/>
</p>

Now, we will talk about the list or category page. Well-organized
website content improves user experience. A developer, therefore, needs
to use lists and categories effectively. A category helps classify your
content, create a logical structure for your website, and enhance the
users&apos; reading experience. Users can browse through posts on a list or
category page and filter them according to categories, attributes, or
other criteria. A "sort" option is often available on this page when
there is a significant volume of content to scroll through. A category
page benefits a user in getting what they're looking for instantly and
enables the website owner to keep their website structured.

Another type of page of a website is the search page. A dedicated search
page is unnecessary for smaller applications but can be beneficial. It
can be integrated or merged with the list or category page.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image049.webp"
  alt="Types of pages of a website: User/author profile and user's home or dashboard."
  style="width:500px;"/>
</p>

The next type of page is the user or author profile. Any author or user
that creates one or multiple posts has a dedicated page. Blogs with a
single author and small news sites occasionally skip this page. However,
this page is essential for content-driven social networks, sizeable
multi-author news websites, and other user-generated apps. Listing all
the user's posts on this page is a customary and practical practice.

The last type of page we will explore in this session is the user's home
or dashboard. This page displays content tailored to the needs or
preferences of the user currently logged in, such as status updates,
personal newsfeeds, recent activities, and recommended content. A
dashboard is essential for social networks and gated applications but
optional or irrelevant for others.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image050.webp"
  alt="Features of a CMS."
  style="width:500px;"/>
</p>

Now, we are going to discuss the features of a CMS. Despite slight
variations in design, every CMS has the same fundamental features. You
can create the content of your website using different CMS features.
Some of these include: Page design, Blog content, and Content storage.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image051.webp"
  alt="Features of a CMS: Page design and Blog content."
  style="width:500px;"/>
</p>

The most important feature of a CMS is designing a page. A developer can
start designing a page using a template or a blank canvas. The selection
depends on the type of CMS you use. Using a template, you can start
adding content to a page immediately. If you do not use a template, you
must arrange the page elements and place them where you want. This
feature lets you view the content in the What-You-See-Is-What-You-Get
(WYSIWYG) editor. This editor displays your content as if you were
looking at a word processor. As a result, you can see what the end user
will view on your page. You can even switch to an HTML view to edit the
code.

Another valuable feature of a CMS is developing blog content. CMSs also
allow you to create blogs in the system directly. To create a blog,
first, you must create a container page and link the blog page to other
blogs. Even though it might appear complicated, this feature enables you
to reuse the same content on various websites. Businesses that rely
significantly on digital marketing can save time as they can produce
content and use it across different parts of a website and advertising
channels.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image052.webp"
  alt="Features of a CMS: Content storage."
  style="width:500px;"/>
</p>

The last feature of a CMS that we will discuss in this session is
content storage. This feature of a CMS allows you to store all your
content in a centralized place and make it accessible anywhere. Almost
all CMSs will have some content repository. You can upload an image or
file to your CMS. Or, pull it from your content library when you want to
place it on a specific site. CMSs also allow you to review and approve
the content before publication.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image053.webp"
  alt="Summary Module 05b: CMS page types and features of a CMS."
  style="width:500px;"/>
</p>

In this module (05b), you learned that:

-   A CMS helps in developing several types of pages on a website. The
    types of pages include the:

    -   Front Page,

    -   Post Page,

    -   List or Category Page,

    -   Search Page,

    -   User or Author Profile, and

    -   User Home or Dashboard, among others.

-   Some of the features of a CMS include page design, blog content, and
    content storage.

<h2 name="ch1-06a">06a. Getting Started with WordPress - Part 1</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image054.webp"
  alt="Getting Started with WordPress, Part 1."
  style="width:500px;"/>
</p>

Welcome to "Getting started with WordPress - Part 1."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image055.webp"
  alt="06a. Define WordPress as CMS and describe key concepts related to WordPress."
  style="width:500px;"/>
</p>

After reading this module (06a), you will be able to:

-   Define WordPress as a Content Management System (CMS) and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Describe key concepts related to WordPress.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image056.webp"
  alt="WordPress: Website creation and mgmt, installation of plugins, greater flexibility and constant updates."
  style="width:500px;"/>
</p>

WordPress is a CMS that helps you build and manage your website. It
serves as a foundation for your content and allows you to install
plugins that enhance your website&apos;s functionality and design. WordPress
CMS gives you greater flexibility and control over your website and
content than What-You-See-Is-What-You-Get (WYSIWYG) website builders.
You may want to use WYSIWYG website builders for their ease of use.
However, they are frequently feature-limited and require you to host
with a specific company. WordPress allows you to constantly update your
website&apos;s design, content, and functionality.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image057.webp"
  alt="WordPress: Ease of customization, excellect performance and highly robust features."
  style="width:500px;"/>
</p>

WordPress is a good fit for your projects and websites due to several
factors. These include the ease of customization, excellent performance,
and highly robust features that allow a CMS to run a wide range of
websites, including blogs, business, and e-commerce sites.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image058.webp"
  alt="WordPress.org and WordPress.com - summary."
  style="width:500px;"/>
</p>

There are two common platforms: WordPress.org and WordPress.com.

WordPress.org is a platform where you can download CMS, themes, and
plugins. Wordpress.org does not provide web hosting packages, so it
encourages you to self-host a WebPress installation by directing you to
third-party hosts. Some of these services also offer dedicated WordPress
hosting plans. A2, Bluehost, and WP Engine are some options to consider.

A self-hosted WordPress installation allows you to install any theme or
plugin.

Wordpress.com is a blogging platform owned by Automattic, co-founded by
WordPress developer Matt Mullenweg.

Wordpress.com differs from Wordpress.org as it offers free and paid
hosting options. It, however, does have a few limitations. For example,
none of WordPress. com&apos;s offerings allow you to access your server via
Secure Shell (SSH) or edit code via File Transfer Protocol (FTP).
However, you can do so with Wordpress.org, as you must use it with a
third-party host. You can install third-party plugins with
WordPress.com&apos;s top-tier business plan.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image059.webp"
  alt="WordPress concepts: database, core, plugins, hooks, customization updates and rest API."
  style="width:500px;"/>
</p>

Users, developers, or both should know certain concepts and
terminologies related to WordPress. These include the following terms:
Database, WordPress Core, plugins, themes, hooks, customization options,
and Rest API.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image060.webp"
  alt="WordPress concepts: Database supports MySQL and MariaDB.  WordPress Core explained."
  style="width:500px;"/>
</p>

Let's discuss each of these in detail now.

A database contains all your website&apos;s content, settings, and dynamic
information. WordPress officially supports the database engines MySQL
and MariaDB.

WordPress includes every essential file needed for a WordPress website
to function. This is available for download from Wordpress.org or as
part of your hosting package.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image061.webp"
  alt="WordPress concepts: Plugins and Themes."
  style="width:500px;"/>
</p>

Plugins are pieces of code you can write yourself or download from
places like the WordPress Plugin repository. Plugins can add new
features and behaviors to your website.

Themes enable you to personalize and control the visual aspects of your
website. They determine the look and feel of the public-facing website.
Themes, like plugins, are created from scratch or pre-made. There are
two types of Themes. Classic themes allow users to make minor
adjustments, such as adding custom logos or colors. It is an older style
of theming. Block themes are more modular. They provide users with more
customization options and require less coding. The Block Theme system is
the future of WordPress theming.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image062.webp"
  alt="WordPress concepts: Hooks and Customization options."
  style="width:500px;"/>
</p>

Hooks are the foundation of the WordPress core, themes, and plugins.
There are two types of hooks: actions and filters. Action hooks allow
you to add more functionalities to the website. Filter hooks allow you
to modify the function's existing code. They intercept the data being
processed, let you change it, and then pass it back.

Customization options offer different approaches depending on the type
of customization and functionality you want to add to your website.
There are two types: visual changes facilitated by themes and functional
changes implemented by plugins.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image063.webp"
  alt="WordPress concepts: Rest API."
  style="width:500px;"/>
</p>

The Rest API is new and allows you to build true WordPress applications.
These include iPhone, Android, and TV apps if you are familiar with
other programming languages.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image064.webp"
  alt="Module 06a Getting Started with WordPress."
  style="width:500px;"/>
</p>

In this module (06a), you learned:

-   WordPress is a CMS that helps you build and manage your website,

-   Wordpress.org is a platform where you can download CMS, themes, and
    plugins,

-   Wordpress.com is a blogging platform that offers free and paid
    hosting options,

-   Plugins are pieces of code you can write yourself or download from
    places like the WordPress Plugin repository,

-   Themes enable you to personalize and control the visual aspects of
    your website,

-   Hooks are the foundation of how the WordPress core, themes, and
    plugins work, and lastly,

-   Customization options offer different approaches depending on the
    type of customization and functionality you want to add to your
    website.

<h2 name="ch1-06b">06b. Getting Started with WordPress - Part 2</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image065.webp"
  alt="Welcome to Getting Started with WordPress - Part 2."
  style="width:500px;"/>
</p>

Welcome to "Getting started with WordPress -- Part 2."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image066.webp"
  alt="Module 06b summary - WordPress - Part 2."
  style="width:500px;"/>
</p>

After reading this module (06b), you will be able to:

-   Describe the popular website builder, WordPress,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify the steps to create a website using WordPress, and

-   Identify the skills required to enhance WordPress.

WordPress is a user-friendly platform that enables you to develop a
professional website without coding knowledge. This module will teach
you how to create a website using WordPress.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image067.webp"
  alt="Steps to create a website using WordPress."
  style="width:500px;"/>
</p>

The steps to create a website using WordPress include the following:

-   Selecting a domain name,

-   Setting up web hosting Installing WordPress,

-   Selecting a theme for your website,

-   Designing the homepage and creating additional web pages,

-   Installing plugins,

-   Creating navigation menus, and finally,

-   Integrating your social media with the website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image068.webp"
  alt="First Step: select domain name."
  style="width:500px;"/>
</p>

Let's discuss each of these steps in detail.

The first step of creating a website using WordPress is selecting a
domain name. Your domain name is the permanent Internet address for your
WordPress website and plays a crucial role in branding, so give it some
thought. After you&apos;ve found the perfect domain name, get that
registered with a domain name registrar. Some popular registrars include
GoDaddy and Google Domains.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image069.webp"
  alt="Next step: setting up web hosting."
  style="width:500px;"/>
</p>

The next step in creating a website using WordPress is setting up web
hosting. Web hosting is the \"engine\" that powers your WordPress
website and allows visitors from all over the world to access it. Web
hosting means renting computer space to power your website. Hosting is
available at all price points, ranging from a few dollars to hundreds
per month.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image070.webp"
  alt="Next: install wordpress software."
  style="width:500px;"/>
</p>

Next, you need to install the WordPress software. Most WordPress hosting
companies provide simple tools to install free WordPress software. The
hosting package you select will typically include instructions on
installing the software, which will require downloading and uploading
the software or using a quick installation method. Using a managed
WordPress hosting account, you&apos;ll be able to install and use the
software immediately.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image071.webp"
  alt="Next: select a theme."
  style="width:500px;"/>
</p>

After you've installed the WordPress software, you need to select a
theme for your website. Your WordPress theme determines how your website
appears.

WordPress allows you to customize your website without any specialized
knowledge. Using a high-quality theme gives your website a professional
appearance while adhering to the latest web standards and conventions. A
free theme will suffice if you want to post a simple blog. Premium
themes typically have advanced functionalities and no branding from the
creator. Look for frequently updated themes to ensure that your website
stays current.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image072.webp"
  alt="Next: design the homepage and additional pages of your website."
  style="width:500px;"/>
</p>

After selecting the theme of your website, you need to design the
homepage and the additional pages of your website. To create an
excellent first impression, you must identify the essential things you
want your users to access when visiting your website. You can use either
a blank webpage or a pre-designed page layout provided by WordPress to
develop that impressive homepage quickly. Next, you need to create
additional web pages for your website. These may include the About Us
page, the Contact page, the Privacy Policy page, the custom landing
page, and so on.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image073.webp"
  alt="Installing plugins."
  style="width:500px;"/>
</p>

Now, to boost the functionality of your website, you can install
plugins. Note that this step is optional. While themes are concerned
with appearance, plugins are concerned with adding new functionality to
your website.

WordPress offers tools to improve search engine optimization (SEO),
create user forums, and manage comments. One important consideration is
that coding errors from a plugin developer may leave your website
vulnerable to cyberattacks. Hence, research before you install one.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image074.webp"
  alt="Creating navigation menus."
  style="width:500px;"/>
</p>

The next step is creating navigation menus. Users can browse different
pages or sections of your website using navigation menus. Menus are
links at the top of a web page that users can click to navigate your
website. WordPress includes a robust navigation menu system, which your
WordPress theme uses to display menus.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image075.webp"
  alt="Social media and the website."
  style="width:500px;"/>
</p>

The last and optional step is integrating your social media with your
website. This helps you to enhance brand reach and awareness, encourage
engagement, and enable you to reach a wider audience, boosting traffic
to your website. WordPress allows you to add various icons related to
social media platforms. These include Facebook, Twitter, Instagram,
YouTube, and others. It also allows you to post online or redirect users
to your social media profiles. You must be familiar with specific tools
to begin working with WordPress development and website design.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image076.webp"
  alt="Skills required for enhancing WordPress; HTML, CSS, PHP, JS, and MySQL."
  style="width:500px;"/>
</p>

Let us understand the skills required for enhancing WordPress. The
following skills are:

-   Hypertext Markup Language (HTML),

-   Cascading Style Sheets (CSS),

-   Hypertext Preprocessor (PHP),

-   JavaScript (JS), and

-   My structured Query Language (MySQL).

HTML and CSS are the first two languages you should learn. No matter
what code you write or the language you use, it all comes down to HTML
and CSS.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image077.webp"
  alt="."
  style="width:500px;"/>
</p>

HTML is responsible for giving a website its structure. This implies
deciding what text should be a heading, what should be a list, what goes
in the sidebar, and what goes in the header and footer.

CSS is used for adding styles to the HTML structure. You can define the
color of text, image alignment, paragraph spacing, border colors, border
thickness, float properties, and other elements.

WordPress development requires a solid understanding of PHP as WordPress
and other content management systems are developed using the PHP
programming language.

JavaScript is commonly used on websites for asynchronous loading and
adding dynamic functionality to web pages.

MySQL is a database-access and data-management language. WordPress
relies on it to retrieve all its data.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image078.webp"
  alt="Summary module 06b; Wordpress, part 2."
  style="width:500px;"/>
</p>

In this module (06), you learned that:

-   WordPress is a user-friendly platform that enables you to develop a
    professional website without the knowledge of coding, and

-   The steps to create a website using WordPress include:

    -   Selecting a domain name,

    -   Setting up web hosting,

    -   Installing WordPress,

    -   Selecting a theme for your website,

    -   Designing the homepage and

    -   Creating additional webpages,

    -   Installing plugins,

    -   Creating navigation menus, and

    -   Integrating your social media with the website.

<h2 name="ch1-07">07. Adding E-commerce to Your Website</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image079.webp"
  alt="07. Welcome to Adding E-commerce to your Website."
  style="width:500px;"/>
</p>

Welcome to "Adding E-commerce to Your Website."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image080.webp"
  alt="Summary of Adding E-commerce to your Website."
  style="width:500px;"/>
</p>

After reading this module (07), you will be able to:

-   Explain the benefits of adding e-commerce functionality to your
    website, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Describe how to add e-commerce functionality to your website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image081.webp"
  alt="Why add e-commerce functionality?"
  style="width:500px;"/>
</p>

Businesses must adapt to the new online world to remain relevant and
profitable. Those who depend on customers visiting a storefront must
shift to an entirely new business model to survive. Suppose you run a
business that sells physical products. In that case, it is possible to
transition to an e-commerce business to keep things afloat in the coming
months. 
And, for most businesses, adding an e-commerce store to its
existing website is surprisingly easy. How you achieve this depends on
how you build your website. However, like most businesses, if you&apos;re
either using WordPress website or a website builder to create your
website, adding e-commerce functionality is simple.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image082.webp"
  alt="Why add e-commerce functionality?"
  style="width:500px;"/>
</p>

The global consultancy firm AT Kearney stated, \"e-commerce is the next
frontier in global expansion. Global e-commerce has grown by thirteen
percent over the last five years. 
As online sales skyrocket in developing markets, an online presence is a 
low-risk way to test new markets and complement existing store footprints." 
E-commerce is easy and affordable. It allows you to sell locally and globally every 
hour of every day.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image083.webp"
  alt="Strategies to add e-commerce functionality"
  style="width:500px;"/>
</p>

Adding e-commerce features to a website requires a certain degree of
technical knowledge. Here are some ways to add e-commerce to your
website, depending on your platform's complexity level, business needs,
and the available budget. Start selling products online. For new
sellers, marketplaces are accessible, affordable options. Add a "Sell"
button to your website. You can create buttons online or quickly add a
shopping basket to your website. Using drag-and-drop website builder
software will help you easily create high-converting landing pages, web
pages, and blog posts.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image084.webp"
  alt="Adding e-commerce features to CMS."
  style="width:500px;"/>
</p>

The first option is to add a store to your website. This option is great
if you have full permission to edit your website. You can add payment
gateways and shopping carts to make your website e-commerce capable. To
add e-commerce functionalities, you can use numerous third-party tools
or plugins. These plugins are software that add various functionalities
to a website, including web form builders, analytics, SEO meta tags,
payment gateways, and shopping carts.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image085.webp"
  alt="Adding e-commerce features to CMS."
  style="width:500px;"/>
</p>

If you're a lucky owner of WordPress, Joomla, or Drupal websites,
installing a plugin will be the most viable way to add e-commerce
features to your website. The process of adding a plugin to your
e-commerce platform is easy. Go to Plugins in the admin dashboard,
select the one compatible with your website version, and click
"Install." Installing the following plugins will add e-commerce features
to your CMS: WordPress and WooCommerce, Joomla and Hikashop, Drupal and
Drupal Commerce, and Wix and Wix Stores.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image086.webp"
  alt="Selling on online marketplaces."
  style="width:500px;"/>
</p>

Online marketplaces are beneficial to all. The buyer finds e-commerce
platforms convenient and secure places to purchase goods immediately.
The seller is attracted to marketplaces by potential customers.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image087.webp"
  alt="Adding marketplaces to your website."
  style="width:500px;"/>
</p>

Let's discuss some easy ways to include marketplaces on your website.

WooCommerce, WP e-commerce, and BigCommerce are service providers that
allow you to create an online store. If you have WordPress installed,
enter the "marketplace" query on the official WordPress repository.
Select a plugin that will turn your online store into a marketplace.
WooCommerce allows you to sell the products of only one seller. Magento
Open Source is suited for medium- to large-scale enterprises but offers
an open-source edition for small businesses.

Shopify has a \"Buy\" button to add to a custom or template website. It
shows users product images, descriptions, and prices. It allows them to
stay on your website while making a purchase. You can customize this
button to make it a part of your website. The solution costs a few
dollars monthly and requires little effort to integrate into the
existing website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image088.webp"
  alt="Steps to add the Shopify Buy button."
  style="width:500px;"/>
</p>

Here are the steps to add the Shopify Buy button to your website. 
  - Add the Buy Button sales channel. Select the plus button next to the Sales
  channels heading in your Shopify admin. 
  - In the Add sales channel dialog box, select the Buy Button to learn more about 
  the Sales channel. 
  - Select Add channel. 
  - To create a Buy button, go back to your Shopify admin and go to the Buy Button. 
  - Select Create a Buy Button.
  - Select the Product Buy Button.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image089.webp"
  alt="Drag-and-drop website builder software."
  style="width:500px;"/>
</p>

An e-commerce store has two parts: the front-end store and the back-end
dashboard. The former is what everyone sees when they visit your site,
including your inventory, deals, shopping cart, checkout system, and so
on. You see the latter, including sales, inventory, and other things.
You need to find an e-commerce partner that enables you to have an
attractive e-commerce store and an intuitive back-end dashboard.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image090.webp"
  alt="Wix, Weebly, Squarespace."
  style="width:500px;"/>
</p>

There are various options available for website builders. This session
will discuss the popular platforms: Wix, Weebly, and Squarespace. 

Wix is one of the most popular website builders that cater to a wide range of
users. You do not need programming skills to create a website on Wix. It
provides various templates to customize your website. 

Weebly is a popular platform that has over forty million users. It has a no-frills
approach to website design. You can create a mobile-responsive website
using their templates. Moreover, you can study your progress using their
back-end metrics. 

Squarespace is another easy-to-use tool that offers various templates to build and 
launch a customized online store and website in minutes.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image091.webp"
  alt="Adding E-commerce to your Website."
  style="width:500px;"/>
</p>

In this module (07), you learned that:

-   Having an online presence makes testing new markets and
    complementing existing store footprints less risky.

-   E-commerce allows you to sell more not only locally but also
    globally.

-   Installing a plugin is the most viable way to add e-commerce
    features to a website.

-   An e-commerce store has two parts: the front-end store and the
    back-end dashboard.

-   Wix, Weebly, and Squarespace are popular platforms for website
    building.

# Week 1 Summary: Content Management Systems (CMS)

## **Content Management Systems (CMSs)**

In this week (01), you learned that:

-   A content management system (CMS) aids developers in the creation of
    websites.

-   A CMS&apos;s features include page design, blog content, and content
    storage.

-   Web content management systems (WCMS), digital asset management
    systems (DAMS), and enterprise content management systems are the
    three types of content management systems (ECMS).

-   A WCMS allows users to create, manage, and modify web page content.

-   A successful website is built with CMS, the optimizer tool, the
    insights tool, fonts, JavaScript, and CSS.

-   CMS platforms that are popular include Joomla, Squarespace, Wix,
    Shopify, Drupal, and Adobe Commerce.

-   WordPress is a user-friendly platform that allows web developers to
    create a professional website without any coding knowledge.

-   E-commerce enables businesses to sell more locally and globally.

<!-- # [Week 2:]{.mark} -->

<h1 name="ch2">WEEK 2</h1>

<h2 name="ch2-08">08. Introduction to Search Engine Optimization (SEO)</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image092.webp"
  alt="2-08. Introduction to Search Engine Optimization (SEO)"
  style="width:500px;"/>
</p>

Welcome to "Introduction to Search Engine Optimization (SEO)."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image093.webp"
  alt="SEO (08): Describe SEO and its types, and Identify the benefits of using SEO (and all the time wasted)."
  style="width:500px;"/>
</p>

After reading this module (08), you will be able to:

-   Describe search engine optimization (SEO) and its types, and

-   Identify the benefits of using SEO.

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image094.webp"
  alt="SEO refers to techniques that help a website rank higher, and which make it more visible."
  style="width:500px;"/>
</p>

  - Search engine optimization (SEO) refers to techniques that help a
  website rank higher in organic search results, making it more visible to
  people looking for the product or service online. 

  - Search engines scan the Internet for text that matches certain criteria. 
  This text, a crucial website element, is called a keyword. 
	- The titles, headings, and links that form the content of a webpage 
	are also important factors that a search engine considers when ranking a website. 

  - SEO is a subset of Search Engine Marketing (SEM), a broad term that contains all search 
  marketing strategies. Organic and paid searches are both included in SEM. 
	- Paid search requires you to pay to have your website listed on a search engine so 
	that it appears when someone types a specific keyword or phrase.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image095.webp"
  alt="How a search engine works (according to Google and other deuschebags)"
  style="width:500px;"/>
</p>

Let's describe how a search engine works;

  - A search engine needs an archive of available information to choose from to display 
  results when someone types a query. Every search engine has proprietary methods to
  gather and prioritize website content, known as indexing. 
  - A search engine index is a data collection used to generate the final search
  result. 
  - Search engines scan the Internet and index all the information displayed to users when 
  they enter a search query. 
  - Every search engine has bots, or crawlers, that crawl the web constantly, indexing 
  websites for content and following links on each webpage to other web pages. 
  - Indexing your website is essential as it will only appear in search results if it is done.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image096.webp"
  alt="Types of SEO: Technical, On-page, Off-page."
  style="width:500px;"/>
</p>

Now that you know how search engines work, let's explore the types of
SEO. Some of these include technical SEO, on-page SEO, and off-page SEO.
Let's discuss each of them in detail.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image097.webp"
  alt="Technical SEO: Settings that need to be set to facilitate the task of search engine 
  crawlers. On-page SEO: Concerned with content."
  style="width:500px;"/>
</p>

Technical SEO, as the name suggests, relates to the settings that need
to be set up to facilitate the task of search engine crawlers. Note that
crawling and indexing issues can harm your rankings. 

Another type of SEO is on-page SEO, which is primarily concerned with the content and 
other elements found on a page. Unlike technical SEO, on-page SEO primarily aims to 
provide enough signals to search engine crawlers so that they can understand the 
meaning and context of the content. This is done using website structure, SEO 
keywords, title optimizations, headings, internal links, image SEO, structured 
data markup, and other techniques.  When done correctly, on-page SEO will improve 
a website&apos;s or blog&apos;s usability and credibility.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image098.webp"
  alt="Off-page SEO: Actions taken away to influence rankings on SEO Pages (SERPs).  Uses backlinks to determine quality of website."
  style="width:500px;"/>
</p>

The last type of SEO we will discuss is off-page SEO. It refers to
actions taken away from the website to influence the rankings on Search
Engine Result Pages or (SERPs). Off-page SEO is commonly associated with
the creation of backlinks. Search engines use backlinks to determine the
quality of the connected content. Hence, a website with many high-value
backlinks usually ranks higher than an otherwise equal website with
fewer backlinks.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image099.webp"
  alt="Benefits of using SEO and best practices."
  style="width:500px;"/>
</p>

Now, we will talk about the benefits of using SEO. Most users click one
of the top five SERP suggestions. The website must rank among the top
results to capitalize on this and attract visitors. SEO is about search
engines and good SEO practices, which help improve a website&apos;s user
experience and usability. Users trust search engines. Having a presence
in the top positions for the keywords the user searches for enables the
website to earn the users' trust.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image100.webp"
  alt="Additional benefits of using SEO."
  style="width:500px;"/>
</p>

There are additional benefits of using SEO. SEO is essential for the
social promotion of a website. People who find a website through a
Google or Bing search are more likely to share it on Facebook, Twitter,
or other social media platforms. SEO enables the smooth operation of a
large website. Websites with multiple authors can benefit from SEO
directly and indirectly. The direct benefit is increased organic
traffic, and the indirect benefit is a common structure or checklist to
utilize before publishing content on the website. SEO can help get a
competitive edge. If two websites sell the same product, the
search-engine-optimized website will have more customers and make more
sales.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image101.webp"
  alt="SEO Summary (08)."
  style="width:500px;"/>
</p>

In this module (08), you learned that:

-   SEO refers to techniques that assist a website in ranking higher in
    search results,

-   Technical SEO involves configuring the settings of a website to make
    it easier for search engine crawlers,

-   On-page SEO provides signals to search engine crawlers so that they
    can understand the meaning and context behind the content,

-   Off-page SEO are actions taken away from the website to influence
    its rankings in SERPs, and

-   Good SEO practices also improve a website&apos;s user experience and
    usability.

<h2 name="ch2-09">09. Popular SEO Tools</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image102.webp"
  alt="2-09. Popular SEO Tools"
  style="width:500px;"/>
</p>

Welcome to "Popular SEO Tools."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image103.webp"
  alt="Summary popular SEO tools, how to select a tool, benefits of SEO and some free/paid tools."
  style="width:500px;"/>
</p>

After reading this module (09), you will be able to:

-   Define Search Engine Optimization (SEO) tools,

-   Describe how to select an SEO tool,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Explain the benefits of using SEO tools, and

-   Identify some free and paid SEO tools.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image104.webp"
  alt="SEO tools enable business owners to know their websites' overall health and success."
  style="width:500px;"/>
</p>

SEO tools enable business owners to know their websites&apos; overall health
and success. They: Help develop and implement an organic online search
strategy Assist in boosting a website's search ranking. Offer customers
a comprehensive set of features and functionalities. Provide users with
powerful keyword research tools, backlink assistance, rank tracking
tools, and reports, among other things. Enable you to research what your
competitors are doing, and Provide insights into industry niches,
allowing you to identify what works and what doesn&apos;t.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image105.webp"
  alt="Factors when selecting the best SEO software."
  style="width:500px;"/>
</p>

You need to consider a few factors when selecting the best SEO software.
They are: Ongoing assistance Features and functionalities. Learning
curve Cost, and Support.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image106.webp"
  alt="Detailed factors when selecting the best SEO software."
  style="width:500px;"/>
</p>

Let's explore each in detail. The main factor to consider is whether you
require ongoing SEO assistance. It is an effective method of increasing
relevant traffic to your website through regular site reviews and
updates. Many of the best SEOs include tools to help you improve your
site over time with ongoing optimizations, site audits, and reports.
Another important factor is features and functionalities. As SEO aims to
help a website rank higher in search engine results, tools like keyword
research, SERP rank tracking, content evaluation tools, competitor
analysis, backlink monitoring, and website audit functionality play an
important role.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image107.webp"
  alt="More detailed factors when selecting the best SEO software."
  style="width:500px;"/>
</p>

The learning curve is another crucial factor to consider. The best SEO
tools are usually so feature-rich that they require some learning. Some
tools, however, are more user-friendly than others and should be
considered when developing a website as a beginner. You also need to
consider cost when selecting the best SEO tool. While some SEO tools are
free, the most powerful ones require a fee. It is necessary to check if
the tool fee is reasonable compared to the value of the tool. The last
important consideration is support. Customers care about the types and
quality of support available through online learning resources and
direct support channels such as email, chat, and phone.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image108.webp"
  alt="Benefits of using the best SEO tools."
  style="width:500px;"/>
</p>

We will now discuss the benefits of using the best SEO tools online.
These include reporting, higher search ranking, improvements, and
higher-quality website traffic.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image109.webp"
  alt="Detailed benefits of using the best SEO tools."
  style="width:500px;"/>
</p>

Let's explore each in detail.

Reporting: The best SEO tools help automate all types of reporting by
automatically retrieving data points. They help create custom reports
and can view almost any type of data.

Higher Search Rankings: Many believe that SEO tools are only good for
one thing---higher search rankings. In contrast, they enable you to
create an SEO strategy for various purposes.

Improvements: In addition to the main keyword research tools, it should
also include a social media campaign, website updates, and high-quality
backlinks.

Higher-Quality Website Traffic: The best SEO tools enable a website to
connect to its target audience. This involves focusing on the right
leads, which results in higher-quality website traffic.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image110.webp"
  alt="Best free SEO tools available: Google Analytics, Google Search Console, and Bing Webmaster."
  style="width:500px;"/>
</p>

Now, we&apos;ll discuss some of the best free SEO tools available.

Google Analytics is a free dashboard that allows seamless control over
Google Search settings and other services such as Search Console and
Data Studio.

Google Search Console is a tool to track a website&apos;s performance on
Google and find additional resources to achieve success with Google SEO.

Bing Webmaster Tools provides an easy-to-use dashboard, simple report
configuration to track SEO results over time, diagnostic tools to
address SEO strategy flaws, and a configurable notification system to
track your Bing account in real time.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image111.webp"
  alt="PageSpeed Insights and Google Keyword Planner."
  style="width:500px;"/>
</p>

PageSpeed Insights is another useful tool that shows how your website
performs on various devices. It is based on Google technology and easily
integrates with other daily SEO tools.

Users who are SEO experts and frequently purchase Google ads should use
Google Keyword Planner. You can improve your keyword settings using this
free tool as it integrates seamlessly into your Google suite of
applications.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image112.webp"
  alt="Best Paid SEO Tools."
  style="width:500px;"/>
</p>

Let's now explore some of the best paid SEO tools available.

The Semrush SEO toolkit provides access to detailed keyword analysis
reports and a domain summary for any domain you manage. It enables you
to compare the performance of your pages to see where you stand compared
to the competition.

Ahrefs is a popular tool for keyword research, competitor analysis,
backlink audits, and other purposes. Using the site audit feature, you
can analyze your competitors&apos; website traffic and search engine
rankings and use this information to improve your SEO strategies.

Moz Pro monitors a website's ranking, analyses backlinks, performs site
audits, and employs keyword tools.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image113.webp"
  alt="Serpstat and SpyFu."
  style="width:500px;"/>
</p>

Serpstat is a comprehensive tool that can help you analyze competitors
perform SEO tasks, and manage your in-house SEO team.

SpyFu helps conduct the best competitor analysis. It allows you to
legally spy on your competitors&apos; SEO practices. Regardless of what kind
of services you sign up for, you will have access to all the data they
uncover.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image114.webp"
  alt="In this module (09) you learned about SEO tools, how to select, and which is best (paid and free)."
  style="width:500px;"/>
</p>

In this module (09), you learned that:

-   SEO tools aid in the development and implementation of online search
    strategies,

-   When selecting an SEO tool, consider the assistance, features and
    functionalities, learning curve, cost, and support factors,

-   Google Analytics, Google Search Console, Bing Webmaster Tools,
    PageSpeed Insights, and Google Keyword Planner are some of the best
    free SEO tools available, and

-   SEMrush SEO Toolkit, Ahrefs, Moz Pro, Serpstat, and SpyFu are some
    of the best-paid SEO tools available.

<h2 name="ch2-10">10. SEO Strategies</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image115.webp"
  alt="2-10. SEO Strategies"
  style="width:500px;"/>
</p>

Welcome to SEO Strategies.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image116.webp"
  alt="In this module (10), you will learn SEO strategies and steps to develop an SEO strategy."
  style="width:500px;"/>
</p>

After reading this module (10), you will be able to:

-   Define an SEO strategy, and

-   Define the steps to develop an SEO strategy.

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image117.webp"
  alt="SEO strategy is a plan of action for a company to optimize its website and rank higher in google search results."
  style="width:500px;"/>
</p>

An SEO strategy is a plan of action for a company to optimize its
website and rank high in Google search results. It&apos;s a combination of
layered on-page, off-page, and technical SEO tactics designed to boost
rankings for primary and secondary keywords, pages, and websites.
Knowing what works best for you and your business, as well as connecting
with your ideal audience, is an important part of developing an SEO
strategy.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image118.webp"
  alt="Developing an SEO strategy."
  style="width:500px;"/>
</p>

There is no one-size-fits-all approach to developing an SEO strategy, as
it greatly depends on the website, content, and audience. However, some
useful points should be considered before developing an SEO strategy to
make your website more searchable online. These include: Assessing the
current SEO strategy, Analyzing the competition, Setting goals and KPIs,
Executing the improved strategy, and Monitoring the execution.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image119.webp"
  alt="First step in SEO strategy: Evaluate current strategy and performance."
  style="width:500px;"/>
</p>

The first step is to evaluate your current SEO strategy and its
performance. You should assess your website&apos;s organic visibility,
keyword rankings, and branded vs. non-branded traffic split.

There are several tools available online to show you this information.
You can use them to track the performance of your website's organic
traffic and keyword rankings over time. You can also easily spot trends
and gather detailed information on all aspects of the business to
maximize sales and profits by conducting business research. Customer
research will reveal how current customers perceive your company and
will allow you to create detailed purchasing behavior profiles.
Understanding the difference between branded and non-branded traffic on
your website will help you identify opportunities. Increasing
non-branded traffic allows you to acquire new users who may not have
previously heard of you. You&apos;ll also be able to identify areas that
need improvement for your next SEO strategy.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image120.webp"
  alt="Analyze competitors' strategies and identify how well their keywords rank."
  style="width:500px;"/>
</p>

After you&apos;ve assessed your current SEO strategy, you should analyze the
competitors&apos; SEO strategies. This will give you a sense of what is and
isn&apos;t working for them, as well as areas where you can capitalize to
gain an advantage. Begin by compiling a list of your main competitors,
which should include those in your service area and the ones who
consistently rank high in the SERPs for your main keywords. Next, you
need to determine which of their pages receive the most traffic. This
can help you decide what type of content should be added to your website
to improve your ranking. Keep track of whether the competitors'
best-performing pages are blogs, product pages, or other pages.

Then, you need to identify how well their keywords rank. Analyzing their
keyword rankings will tell you if your competitors are ranked for
keywords that you are not. This will help you identify opportunities to
boost your keyword rankings.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image121.webp"
  alt="Analyze link profiles of your competitors' websites."
  style="width:500px;"/>
</p>

Finally, you need to analyze the link profiles of your competitors&apos;
websites. This will help you understand where their backlinks are coming
from and identify the link gap between their website and yours. This
will enable you to develop your link-building strategy to build a strong
backlink profile.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image122.webp"
  alt="Set goals you wish to achieve."
  style="width:500px;"/>
</p>

After your strategy is developed, you need to set goals you want to
achieve. Like: What aspects of the company do you want to improve? and
Is there more traffic? How about more clicks or perhaps more down-funnel
activity?

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image123.webp"
  alt="More about goals."
  style="width:500px;"/>
</p>

Addressing these questions will help you consider what readers might be
looking for that would persuade them to visit or interact with your
website.

Keeping these metrics in mind throughout the development of your
business strategy will allow you to track your progress in real-time.
Each goal should be mapped to a unique tactic that you can employ to
help optimize your strategy, which is why knowing your goals ahead of
time is crucial.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image124.webp"
  alt="Now optimize your website using goals defined."
  style="width:500px;"/>
</p>

After your goals are set, you should begin optimizing your website for
positive page experience. Begin by brainstorming potential keywords and
researching competitors using the Google AdWords keyword tool. Remember
that meta tags are still useful in SEO.

Google considers the title and description of your page to be an
indication of keyword relevance. You will be able to effectively rank
your keywords while also providing a positive user experience if you
create high-quality content.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image125.webp"
  alt="Submit press releases."
  style="width:500px;"/>
</p>

Next, on a monthly or bimonthly basis, you should submit press releases
on any company initiatives and contact popular blogs in your niche to
see how you can collaborate to get a backlink from their website.

Many content websites are focused primarily on community. As a result,
you should cultivate a strong social media presence that sends signals
of authority and influence to search engines. Finally, note that when
customers search for products online, they frequently look at both web
and image results. If you have high-quality product images on your
website and include relevant keywords in the file names, the images will
rank higher in search engines.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image126.webp"
  alt="New trends and best practices?"
  style="width:500px;"/>
</p>

Finally, you need to be on the lookout for new trends and best
practices. Some of these include:

Optimizing for entities (not keywords) -- Focus on building pages around
topics and including topic variants. Focusing on user engagement
signals, particularly speed. Prioritizing indexing and crawling -- The
number of pages indexed is increasing exponentially, and Google is
shifting from indexing everything to indexing quality content. Link
building -- Focus on gaining authoritative links that your competitors
do not already have. Analyzing your metrics and making actionable
experiments based on your findings.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image127.webp"
  alt="In this module (10): SEO strategies and tips."
  style="width:500px;"/>
</p>

In this module (10), you learned that:

-   SEO strategy assists in website optimization and ranking high in
    search results, and

-   There are five tips to consider when developing an SEO strategy:

    -   Plan and assess the current SEO strategy and performance,

    -   Analyze competitor's SEO strategies to capitalize on and gain an
        advantage,

    -   Consider and set the types of goals to achieve,

    -   Execute strategies and optimize the website for a positive
        experience, and

    -   Monitor and be on the lookout for new trends and best practices.

<h2 name="ch2-11">11. Mobile Friendly SEO</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image128.webp"
  alt="2-11. Mobile Friendly SEO"
  style="width:500px;"/>
</p>

Welcome to "Mobile friendly SEO."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image129.webp"
  alt="Mobile friendly SEO (10) defines mobile SEO, difference with desktop, is it mobile friendly and best practices."
  style="width:500px;"/>
</p>

After reading this module (11), you will be able to:

-   Define mobile SEO and its importance,

-   Differentiate between mobile and desktop SEO,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Describe how to check if a website is mobile friendly, and

-   Identify the best practices.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image130.webp"
  alt="Mobile SEO is the process of optimizing websites for mobile devices such as smartphones and tables."
  style="width:500px;"/>
</p>

Mobile SEO is the process of optimizing websites for mobile devices such
as smartphones and tablets. This includes optimizing the
website&apos;s design and content, as well as making the website resources
available to search engine spiders.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image131.webp"
  alt="Mobile SEO considers: How a user interacts with SERPS compared to desktop computer."
  style="width:500px;"/>
</p>

Mobile SEO considers:

How a user interacts with search engine results (SERPs) on a mobile
device versus a desktop computer.

The differences in intent between desktop and mobile for the same query.

If the pages load quickly and do not contain data-sapping resources,
such as bloated images and extra script,

and How to include usability best practices for mobile content access
and provide the best visual experience

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image132.webp"
  alt="Most users access a website with mobile device."
  style="width:500px;"/>
</p>

Due to significant increase in mobile usage, most users access a
website through a mobile device rather than a desktop. This makes mobile
SEO important because it allows you to reach your customers at the right
time and provide them with the best possible experience. According to
studies, people frequently use the nearest device to look something up
quickly, which is usually their smartphone. They use it to research
products before making purchases. According to Google research,
smartphone users are more likely to purchase than desktop users. It is
your responsibility to be available when they are looking for your
products or services.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image133.webp"
  alt="Difference between mobile and desktop SEO."
  style="width:500px;"/>
</p>

Let's now discuss the significant differences between desktop and mobile
SEO.

Location - Desktop SEO focuses on the general public, with no geographic
restrictions. While most mobile users are looking for local results,
mobile SEO is typically focused on local searches.

Operating system - Depending on the device you are using; different
results may appear for the same search query. This is because Google
considers the mobile device&apos;s operating system when displaying the most
relevant search results. When the keyword has a strong app-oriented
intent, search engines display app packs that are compatible with the
device.

Screen size - The differences in search layout for desktop and mobile
due to screen space can also affect how people view your website.
Because mobile device screens are vertical and much smaller than desktop
screens, search results have a fraction of the search space that a
desktop screen has.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image134.webp"
  alt="Best tool to determine if mobile-friendly is Google Search Console."
  style="width:500px;"/>
</p>

The best tool to use to determine whether your website is
mobile-friendly is Google Search Console. Its search tools are extremely
useful if you want to know how your website ranks in search results. For
example, you can see how mobile and desktop users use keywords to find
what they need by using the Search Analytics feature. Googlebot must be
able to crawl your JavaScript, CSS, and image files in order to properly
index them. URL Inspection is a useful tool in Search Console for this.
By using this tool, you can see how Googlebot interprets and displays
your content. The Mobile Usability tool is another Google Search Console
feature that scans your site and displays a list of posts and pages that
do not adhere to Google&apos;s mobile-friendly guidelines.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image135.webp"
  alt="Other mobile SEO tools."
  style="width:500px;"/>
</p>

Other excellent mobile SEO tools include Google&apos;s Mobile-Friendly Test
& Analytics, SEMrush, Ahrefs, ScreamingFrog, and SimilarWeb.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image136.webp"
  alt="Page speed, CSS, JS, or image blocking, avoid popups and flash."
  style="width:500px;"/>
</p>

If your site is already well optimized for search engines, there are
only a few things to consider when optimizing for mobile devices. They
are as follows:

Page speed - Because of hardware and connectivity issues, mobile users
value page speed even more than desktop users. Aside from optimizing
images, you should also minify code, use browser caching, and reduce
redirects.

CSS, JavaScript, or image blocking - The Smartphone Googlebot wishes to
be able to see and categorize the same content as humans. So don&apos;t try
to hide these elements. They are also important in determining whether
you have a responsive site or a different mobile solution.

Avoid Popups and Flash - The plugin may not be available on your user&apos;s
phone, causing them to miss out on all the fun. Use HTML5 instead if you
want to create special effects.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image137.webp"
  alt="Design for touch screen."
  style="width:500px;"/>
</p>

Design for Touch screen - Touch screen navigation can result in
accidental clicks if your buttons are too big, too small, or in the path
of a finger attempting to scroll the page. Optimize titles and meta
descriptions - Keep in mind that when a user searches on a mobile
device, you have less screen space to work with. Be concise when
creating titles, URLs, and Meta descriptions to showcase your best work
in SERPS. Optimize for local search - If your business has a local
element, make sure your mobile content is optimized for local search.
This includes standardizing your name, address, and phone number, as
well as including your city and state name in the metadata of your
website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image138.webp"
  alt="Best practices for mobile SEO."
  style="width:500px;"/>
</p>

Mobile site configuration - Choosing whether to use a responsive,
dynamic serving, or separate site configuration is an important decision
when setting up a site. Google prefers responsive design, but all three
options are acceptable as long as they are properly configured. Finally,
create a separate mobile URL - Another option is to create a separate
site for mobile users. This enables you to create entirely unique
content for mobile visitors.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image139.webp"
  alt="Summary module (11): mobile SEO."
  style="width:500px;"/>
</p>

In this module (11), you learned that:

-   Mobile SEO is the process of optimizing websites for mobile devices
    such as smartphones and tablets,

-   SEO enables websites to reach customers at the ideal times and
    locations to give them the best experiences,

-   Best tool for determining whether a website is mobile-friendly is
    Google Search Console,

-   Creating a mobile-specific website allows you to create content that
    is completely unique for mobile viewers.

<h2 name="ch2-12">12. Page Optimization for SEO</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image140.webp"
  alt="2-12. Page Optimization for SEO"
  style="width:500px;"/>
</p>

Welcome to "Page optimization for SEO."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image141.webp"
  alt="Define ono-page SEO and Identify on-page SEO components."
  style="width:500px;"/>
</p>

After finishing this module (12), you will be able to:

-   Define on-page SEO and list its importance, and

-   Identify the various on-page SEO components.
<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image142.webp"
  alt="What is page optimization for SEO?"
  style="width:500px;"/>
</p>

Page Optimization for SEO, also known as on-page SEO or on-site SEO, is
the process of improving a website&apos;s ranking and visibility in search
engines by optimizing various front-end and back-end components such as
page speed, keyword density, and external backlinks. Search engines like
Google use keywords and other on-page SEO cues to determine whether a
page matches a user&apos;s search intent. The better a search engine
understands a website&apos;s content, the higher it will rank in the search
results, resulting in a more organic traffic, conversions, and revenue.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image143.webp"
  alt="The importance of on-page SEO.  Make it easy for search engines and users."
  style="width:500px;"/>
</p>

On-page SEO aims to make it easy for both search engines and users to:
Understand the purpose of a website. Determine whether the page is
relevant to one or more search queries. Identify whether the page is
useful enough to rank higher on a SERP, and Assist in website
optimization by informing Google about how the website adds value to
visitors and customers.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image144.webp"
  alt="Page optimization for SEO. Key components of on-page SEO."
  style="width:500px;"/>
</p>

Text and HTML changes are required to optimize a website page fully. The
following are the key components of on-page SEO. Content elements, HTML
elements which include: Page Titles, Headers, Meta Descriptions, Image
Alt-text, and Structured Markup. And Site structure elements which
include: Page URLs, Internal Linking, Mobile Responsiveness, and Site
Speed.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image145.webp"
  alt="Content elements."
  style="width:500px;"/>
</p>

Let's explore each in detail. The first type of on-page SEO component
that we are going to discuss is Content elements. Content elements are
the elements of your website&apos;s copy and content. It provides
information about your website and business to both search engines and
readers.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image146.webp"
  alt="More Content elements."
  style="width:500px;"/>
</p>

Let&apos;s consider some guidelines for creating high-quality page content.
Use short and long-tail keywords naturally Include visually appealing
and relevant content. Create content for your specific buyer persona(s).
Make content that people will want to share and link to. Create brief,
compelling introductions. Clearly articulate both the problem and your
solution.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image147.webp"
  alt="Even more content elements."
  style="width:500px;"/>
</p>

Avoid using lengthy sentences and paragraphs. However, if you eliminate
paragraphs entirely, your content will not flow properly. Break up
sections that are longer than 300 words using subheadings. Naturally
incorporate the target SEO keyword throughout the page copy. Match
content to search intent, and always write with your readers in mind.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image148.webp"
  alt="HTML elements: Page titles and Headers."
  style="width:500px;"/>
</p>

Another type of on-page SEO component is HTML elements. It refers to the
elements in your source code. Let's discuss each of them in detail. One
of the most important SEO elements are your web page titles, also known
as title tags.

Titles inform both visitors and search engines about what is available
on the corresponding pages. Make sure to include the focus keyword for
each page in the title to ensure your site pages rank for the correct
intent.

The HTML elements h1, h2, till h6 are referred to as headers, also known
as body tags. These tags help web developers organize content for
readers, and search engines determine which parts of your content are
the most important and relevant based on search intent. Include
important keywords in your headers, but not the same ones as in your
page title. In your h1 and h2 headers, include your most important
keywords.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image149.webp"
  alt="HTML elements: Meta description, image alt-text, and structured markup."
  style="width:500px;"/>
</p>

Meta descriptions are the short page descriptions that appear beneath
the title in search results. It can influence whether or not users click
on your page. When your content is shared on social media, meta
descriptions can be copied over to encourage click-throughs from there
as well.

Image alt-text is similar to SEO for images. It informs Google and other
search engines about the content of the images, which is important
because Google now delivers nearly as many image-based results as
text-based results.

Structured markup, also known as structured data, is the process of
\"marking up\" a website's source code so that Google can easily find
and understand different elements of the content. Structured markup is
responsible for the featured snippets, knowledge panels, and other
content features that appear when you search for something on Google.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image150.webp"
  alt="Site structure elements: Page URLs and Internal linking."
  style="width:500px;"/>
</p>

The last type of on-page SEO component is Site structure elements. It
refers to the components of your website and site pages. Let's discuss
each of them in detail.

Your page URLs should be easy to remember for both readers and search
engines. They are also important for maintaining the consistency of your
site hierarchy as you create subpages, blog posts, and other types of
internal pages.

The process of hyperlinking to other useful pages on your website is
known as internal linking. Internal linking is important for on-page SEO
because it directs readers to other pages on your website, which keeps
them on your site longer and tells Google that your site is valuable and
helpful. Besides that, the more time visitors spend on your website, the
more time Google has to crawl and index your site pages. This allows
Google to learn more about your website and potentially rank it higher
in search engine results pages.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image151.webp"
  alt="Site structure elements: Mobile responsiveness and Site speed."
  style="width:500px;"/>
</p>

Mobile responsiveness is important. Sites that are optimized for faster
mobile speeds are now given preference by Google. It is critical to
select a mobile-friendly website hosting service, website design and
theme, and content layout.

Your site must load quickly, whether viewed on a mobile device or a
desktop computer. On-page SEO relies heavily on page speed. Google is
concerned with the user experience first and foremost. Visitors are
unlikely to stick around if your site loads slowly or haphazardly.
Moreover, site speed has an impact on conversions and ROI.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image152.webp"
  alt="Summary module 12, On-page SEO to improve a websites ranking."
  style="width:500px;"/>
</p>

In this module (12), you learned that:

-   On-page SEO is the process of improving a website&apos;s ranking and
    visibility in search engines,

-   It helps Google understand website content for higher ranking in
    search results,

-   The key components of on-site SEO are: Content Elements, HTML
    Elements, and Site Structural Optimization,

-   Content elements are the elements of your website&apos;s copy and
    content,

-   HTML elements are the elements of your source code, and

-   Site structure elements are components of the website.

<h2 name="ch2-13">13. Running Campaigns and Tracking Results</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image153.webp"
  alt="2-13. Running Campaigns and Tracking Results"
  style="width:500px;"/>
</p>

Welcome to "Running Campaigns and Tracking Results."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image154.webp"
  alt="Module 13: Define SEO campaign and tracking, Best practices, and Identify key SEO tracking tools."
  style="width:500px;"/>
</p>

After reading this module (13), you will be able to:

-   Define SEO campaign and SEO tracking,

-   Explain the best practices for running an SEO campaign, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify the key SEO tracking tools.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image155.webp"
  alt="What is a SEO campaign? Keywords, Quality content, Backlinks, and Social media."
  style="width:500px;"/>
</p>

An SEO campaign is a planned effort to raise a website&apos;s ranking in
search results. This includes optimizing webpages for specific keywords,
creating quality content, building backlinks, and promoting the site via
social media. Keywords help in the discovery of relevant content on your
website and are used to predict how much traffic you will receive from
search engines. Regularly updating your website informs search engines
that you are active and helps boost your website. Backlinks are external
links that direct to your website. When someone shares a link to your
website, search engines learn that you have interesting content. Social
media platforms are excellent for promoting your content. People enjoy
sharing interesting articles and videos, so this is a great way to reach
many people.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image156.webp"
  alt="What is SEO tracking?  Organic traffic and Organic conversions."
  style="width:500px;"/>
</p>

SEO tracking is the process of assessing the effectiveness and
development of a campaign. This step is used to establish specific and
measurable campaign goals. Here are some of the key metrics.

Organic Traffic: One of the best indicators of an SEO campaign&apos;s
effectiveness is the amount of organic traffic it generates for a
website.

Organic Conversions: One of the most effective ways to assess the
quality of organic traffic is to track the number of conversions it
generates. To track conversions and the conversion rate from organic
traffic, create a relevant \"Goal\" in Google Analytics.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image157.webp"
  alt="What is SEO tracking?  Keyword rankings, Competitor analysis, and SEO site health."
  style="width:500px;"/>
</p>

Keyword Rankings: Daily keyword tracking is an excellent way to stay on
top of the overall direction of the SEO efforts and also provides a
clear snapshot of which pages can be improved.

Competitor Analysis: You can identify new opportunities to rank your own
website by tracking the keywords your competitors are ranking for, their
domain authority, and other SEO metrics.

SEO Site Health: One important ranking factor is the site&apos;s SEO
friendliness, which includes having a way to identify and address common
technical problems.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image158.webp"
  alt="Best practices to run SEO campaigns."
  style="width:500px;"/>
</p>

When you use SEO in your content, you can increase organic traffic to
your website. There are a few best practices that can assist you in
running an SEO campaign smoothly. They are as follows:

Monitoring website traffic, Tracking content's effectiveness, Tracking
top-performing pages, and Monitoring paid campaigns.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image159.webp"
  alt="Best practices to run SEO campaigns: Monitoring website traffic and Tracking content's effectiveness."
  style="width:500px;"/>
</p>

Monitoring website traffic can help you make quick decisions and gain
immediate insights. Unusual spikes or drops, for example, can be caused
by website bugs or changes to the code in a recent update. Keeping an
eye on these numbers daily allows you to quickly identify and address
such issues. SEO&apos;s primary function is to increase visibility in search
results and direct visitors to the website. Analyzing search engines as
a traffic source can provide the data required to build an image of a
customer&apos;s behavior and intent. Knowing your overall traffic and which
pages are being visited will assist you in developing new content and
optimizing what you already have.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image160.webp"
  alt="Best practices to run SEO campaigns: Tracking top performing pages and Monitoring paid campaigns."
  style="width:500px;"/>
</p>

It&apos;s handy to have all of the data about individual page performance in
one place. Entries and time on a page indicate how engaging your content
is, while bounce rate indicates whether users continue browsing your
site or leave. When it comes to paid campaigns, ensuring that your
budget is spent strategically requires real-time feedback that provides
clear results and insights. Tagging campaign URLs correctly is a sure
way to avoid cluttered reports and keep incoming visitors organized.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image161.webp"
  alt="SEO tracking tools: Google Analytics and Google Search Console."
  style="width:500px;"/>
</p>

Now that you know the best practices for running an SEO campaign, here
are two key SEO tracking tools to help you manage and track the results
of your website. They are: Google Analytics and Google Search Console.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image162.webp"
  alt="SEO tracking tools: Google Analytics."
  style="width:500px;"/>
</p>

Google Analytics can be viewed as an SEO tracking tool for everything
that happens after someone visits your website. This includes SEO
metrics such as time on site, bounce rate, and exit rate, among others.
Setting up Goals in Google Analytics allows you to track important
website events such as purchases, email signups, trial signups, and any
other event you want to track. There are four types of custom goals to
consider when creating one: Destination: This goal considers a page view
or screen view to be a conversion. Duration: This metric measures user
engagement by considering a conversion to be the minimum session
duration. Pages/screens per session: This metric assesses user
engagement by identifying conversions as users who view more than a set
number of pages or screens per session. Event: This classifies a
specific user interaction with your website or app as a conversion.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image163.webp"
  alt="SEO tracking tools: Google Search Console."
  style="width:500px;"/>
</p>

Google Search Console (GSC) is another free tool that lets you monitor
your site&apos;s search traffic and performance, troubleshoot problems, and
optimize it for search results. The platform monitors SEO metrics such
as:

Top Queries: It consists of the most popular search terms that drive
traffic to a website. Top Pages: It lists the pages with the highest
impressions and clicks so that you know which ones to prioritize when it
comes to optimizing the user experience. CTR (Click-Through-Rate):
Another useful metric to track over time because it frequently allows
you to identify \"quick wins\" by simply changing the title or meta
description, resulting in a significant increase in traffic.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image164.webp"
  alt="Recap: SEO campaign, tracking, monitoring traffice, google analytics and google search console."
  style="width:500px;"/>
</p>

In this section (13), you learned that:

-   SEO campaign is a strategic effort to improve a website&apos;s ranking
    in search results.

-   SEO tracking is the process of assessing the effectiveness and
    development of a campaign.

-   Monitoring website traffic helps in making quick decisions and
    gaining immediate insights,

-   Google Analytics keeps track of everything that happens after a user
    visits a website, and

-   Google Search Console monitors website&apos;s search traffic and
    performance, troubleshoots problems, and optimizes search results.

<h2 name="ch2-14">14. Do's and Don'ts of Search Engine Optimization</h2>

## Introduction

While SEO is a component of Internet marketing, it affects almost every
aspect of a website and has an impact on user experience (UX). There are
many details to keep in mind, and the internet provides a wealth of
information on the subject. Unfortunately, because SEO is ever-changing,
some practices become obsolete or even unacceptable over time. The
following are some of the most important and current SEO \"do&apos;s and
don&apos;ts\" to keep in mind when developing your online strategy.

| <b>Do's<b>                      | <b>Don'ts</b>                      |
| :------------------------------ | :--------------------------------- |
| <b>Do include meta descriptions | <b>Don't use all of your keywords</b> |
| <b>and title tags.</b>          | <b>on the same page.</b>           |
|                                 |                                    |
| Meta descriptions and title     | Instead, make sure that each page  |
| tags are critical components of | contains specific, relevant        |
| your website&apos;s content. Title  | keywords. This keeps your own      |
| tags are important because they | pages from competing for rankings  |
| are the primary factor in       | and communicates to search engines |
| determining whether a user      | and visitors what each page is     |
| clicks on your content in the   | about.                             |
| search results. Use titles that |                                    |
| pique users&apos; interest.         |                                    |
|                                 |                                    |
| <b>Do include keywords that are</b> | <b>Don't overuse keywords.</b> |
| <b>pertinent to the page.</b>   |                                    |

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<p>cont'd</p>

| <b>Do's<b>                      | <b>Don'ts</b>                      |
| :------------------------------ | :--------------------------------- |
|                                 | Search engines do prefer content   |
| The keywords in your content    | with a clear theme, but overusing  |
| should be related to the title  | a keyword tends to put off         |
| of your page. Search engines    | customers and reduces conversions. |
| look for consistency.           | Although Google does not directly  |
|                                 | penalize this, when repetitive     |
|                                 | content leads to a poor user       |
|                                 | experience, it may result in your  |
|                                 | website being ranked lower.        |
|                                 |                                    |
| <b>Do allow other websites to</b> | <b>Don&apos;t copy large amounts of</b>|
| <b>link to your website, but do</b> | <b>outside content.</b>        |
| <b>not link back to them.</b>   |                                    |
|                                 | Duplicating your own content does  |
| Google dislikes link exchanges. | not harm your SEO but copying      |
| Search engines want to see      | someone else&apos;s content almost     |
| websites get links because      | always leads to your website being |
| their content is useful to      | pushed down the rankings by search |
| searchers, not because the      | engines. Try to come up with a new |
| webmaster has a link trading    | way to present your content in a   |
| network.                        | way that is more engaging to your  |
|                                 | buyer.                             |

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<p>cont'd</p>

| <b>Do's<b>                      | <b>Don'ts</b>                      |
| :------------------------------ | :--------------------------------- |
| <b>Do have a presence on</b>    | <b>Don't ignore bad reviews.</b>   |
| <b>relevant social media</b>    |                                    |
| <b>platforms.</b>               | Responding to every comment,       |
|                                 | whether positive or negative, is   |
| It is critical to update        | crucial, even if it seems outdated |
| profiles on a regular basis,    | or untrue to you. While searchers  |
| interact with other users, and  | are unaware of the context, they   |
| post new content. When used     | will watch you interact with both  |
| correctly, social media can be  | happy and unhappy customers.       |
| an extremely effective business |                                    |
| tool.                           |                                    |
| <b>Do monitor site metrics.</b> | <b>Don&apos;t be alarmed if your</b>   |
|                                 | <b>rankings appear to drop</b>     |
| None of the other SEO do&apos;s and | <b>suddenly.</b>                   |
| don&apos;ts will be much use unless |                                    |
| you verify that they are        | Any change in rankings can always  |
| working for you. Once           | be explained, and it might be as   |
| everything else is in place,    | easy as Google experimenting with  |
| monitor site metrics that can   | a new algorithm.                   |
| help you see where you can      |                                    |
| improve, such as the following: |                                    |
|   - Traffic flow                |                                    |
|   - Conversion rate             |                                    |

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<p>cont'd</p>

| <b>Do's<b>                      | <b>Don'ts</b>                      |
| :------------------------------ | :--------------------------------- |
|   - Bounce rate                 |                                    |
|   - Click-through rate          |                                    |
| The most convenient way to      |                                    |
| track your metrics is to use a  |                                    |
| tool like Google Analytics.     |                                    |
|                                 |                                    |
|                                 | <b>Don&apos;t skip user search</b>     |
|                                 | <b>intention.</b>                  |
|                                 | Google&apos;s ultimate goal with       |
|                                 | search results is to serve a       |
|                                 | user&apos;s search intent.             |
|                                 |   - If the user wants information, |
|                                 |     create content that provides   |
|                                 |     it.                            |
|                                 |   - If they want to buy something, |
|                                 |     direct them to your            |
|                                 |     product/service page.          |
|                                 |   - If they want to navigate to a  |
|                                 |     specific page via a search     |
|                                 |     query, make sure you own the   |
|                                 |     navigational query for your    |
|                                 |     own brand.                     |

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<p>cont'd</p>

<table style="width: 100%">
    <colgroup>
       <col span="1" style="width: 50%;">
       <col span="1" style="width: 50%;">
    </colgroup>
    
    <!-- Put <thead>, <tbody>, and <tr>'s here! -->
    <tbody>
        <tr>
            <td style="background-color: #777">Do's</td>
            <td style="background-color: #aaa">Don'ts</td>
        </tr>
    </tbody>
</table>

<p>cont'd</p>

| <b>Do's<b>                      | <b>Don'ts</b>                      |
| :------------------------------ | :--------------------------------- |
| ______________________________  |                                    |
|                                 | <b>Don&apos;t link to external websites</b>|
|                                 | <b>too frequently.</b>             |
|                                 | The only drawback of having too    |
|                                 | many outbound links today is that  |
|                                 | it makes your content more         |
|                                 | difficult to read. This leads to   |
|                                 | higher bounce rates, which search  |
|                                 | engines will notice.               |

## Conclusion 

These \"do&apos;s and don&apos;ts\" are a good starting point for SEO reviews.
Google&apos;s ranking algorithm considers over 200 factors, but these
guidelines will help you stay on top of the basics.

## Hands-on Lab: Optimizing a Website for Search Ranking

Welcome to the **Optimizing a Website for Search Ranking** lab!

In this lab, you will learn how to add elements to your HTML page to
optimize it for search engines.

The lab starts with a sample application, which is a fresh fruit
marketplace on our ecommerce website.

You will then be guided through six simple steps to implement those
changes.

Skills Network Labs (SN Labs) is a virtual lab environment used in this
course. Upon clicking \"Open Tool\" in accordance with IBM Skills
Network Privacy policy your Username and Email will be passed to Skills
Network Labs and will only be used for communicating important
information to enhance your learning experience.

In case you need to download the lab instructions click
[HERE](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-WD0231EN-SkillsNetwork/labs/lab.md.html)
to open in a new tab.

This course uses a third-party app, Hands-on Lab: Optimizing a Website
for Search Ranking, to enhance your learning experience. The app will
reference basic information like your name, email, and Coursera ID.

# Week 2 Summary: Search Engine Optimization (SEO)

## **Search Engine Optimization (SEO)**

In this module, you learned that:

-   Search engine optimization (SEO) refers to techniques that help a
    website rank higher in search results.

-   A search engine index is a collection of data used to generate a
    search result.

-   SEO tools aid in the creation and execution of an online search
    strategy.

-   SEO strategy aids in website optimization and achieving high
    rankings in search results.

-   The process of optimizing websites for mobile devices such as
    smartphones and tablets is known as mobile SEO.

-   On-page SEO is the process of increasing a website&apos;s visibility and
    ranking in search engines.

-   An SEO campaign is a planned effort to boost a website&apos;s ranking in
    search results.

-   SEO tracking is the process of evaluating a campaign&apos;s
    effectiveness and development.

<!-- # [Week 3:]{.mark} -->

<h1 name="ch3">WEEK 3</h1>

<h2 name="ch3-15">15. Introduction to Web Build and Automated Tools</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image165.webp"
  alt="3-15. Introduction to Web Build and Automated Tools"
  style="width:500px;"/>
</p>

Welcome to \"Introduction to Web Build and Automated Tools."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image166.webp"
  alt="In this module (15) you will learn:  Define build automation, identify it's benefits, 
  discuss it's uses, and describe popular web build tools."
  style="width:500px;"/>
</p>

After reading this module (15), you will be able to:

-   Define build automation,

-   Identify the benefits of build automation,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Discuss the use of automated web build tools and bundlers in a given
    situation, and

-   Describe some popular web build tools and bundlers.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image167.webp"
  alt="Introduction to Build Automation."
  style="width:500px;"/>
</p>

Build automation is the process of preparing the source code for
production so that users can interact with it comfortably. 
It could include compilation, database schema updates, creating an installer or
executable file, etc. 
Automation helps to standardize builds, speed them up, and minimize mistakes done 
manually. It is a process where retrieving the source code is automated, the code 
is compiled into binary code, automated tests are executed, and the code is published
into a shared, centralized repository. 
Build automation is essential for Continuous Integration (CI) to take place. Continuous Integration is a
practice that a developer follows to integrate code into a shared
repository multiple times in a period. The integration is then verified
by an automated build and automated tests. Due to this regular
integration, errors are identified quickly and easily.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image168.webp"
  alt="A scenario."
  style="width:500px;"/>
</p>

Scenario
Suppose you have a 300-line JavaScript script. You simply insert the old
script tag into your page. 
We start adding more functionality to the page, and before you know it, your single 
script file contains 10000 lines of code.
It becomes difficult to manage all that amount of code with multiple people working 
on the same file. 

A natural solution is that you split the code in multiple scripts with different 
script tags.
You have to put the smaller files in a particular order to ensure that
the utility function is available. This is not an ideal situation if you
need to keep making changes in the same file to ensure that the order
remains unchanged. 
We can link all our files in a single script tag but
will still need to monitor the code updates and the order of the
existing and additional files. Simply concatenating all the files in the
right order would not be enough. 
A better strategy would be each file to indicate which other file it needs 
(its dependencies), which is a point at which we could incorporate that 
mapping into our previous concatenation strategy. At this point, the 
functionality of an automated build tool and bundler comes into prominence.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image169.webp"
  alt="JavaScript build tools."
  style="width:500px;"/>
</p>

Let&apos;s quickly go through the functions of JavaScript tools. Using these
build tools, your JavaScript and dependencies are prepared for use in a
browser. Some of the functions include transformation, bundling,
minification, and serving.

<b><i>Transformation</i></b> translates various forms of JavaScript/TypeScript (and
additional assets like HTML, CSS, and images) into browser-compatible,
standard packages.

<b><i>Bundling</i></b> implies compiling multiple source components into a few
browser-friendly JavaScript bundles. Certain build tools launched
recently can avoid this step to enhance performance.

<b><i>Minification</i></b> reduces the size of the JavaScript bundle by eliminating
redundant code, renaming variables, and adopting a variety of other
optimization approaches.

<b><i>Serving</i></b> provides the content to browsers in development mode, including
the feature like "hot" reloading. Note that not all tools do all these
steps or do them in exactly the same way. However, these are some of the
core problems that most build tools address in one way or another.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image170.webp"
  alt="Benefits of Build Automation."
  style="width:500px;"/>
</p>

Build automation offers five main benefits:

  - Increased productivity, 
  - Accelerated delivery, 
  - Enhanced quality, 
  - Record maintenance, and 
  - Saving time and money.

Let's discuss each of these benefits in detail.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image171.webp"
  alt="Benefits of Build Automation: Increased productivity and Accelerated delivery."
  style="width:500px;"/>
</p>

One of the major benefits of build automation is <b><i>increased productivity</i></b>.
Build automation leads to quick feedback. This means that developers
spend less time dealing with tools or processes and invest more time in
delivering value.

Another benefit of build automation is <b><i>accelerated delivery</i></b>. Build
automation eradicates unnecessary tasks and enables you to identify
issues faster, which helps expedite the delivery process.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image172.webp"
  alt="Benefits of Build Automation: Enhances quality and record maintenance."
  style="width:500px;"/>
</p>

<b><i>Enhanced quality</i></b> is another important benefit of build automation. Build
automation helps prevent bad builds by enabling you to identify and
address issues faster. This results in enhanced quality of your product.

Furthermore, it <b><i>records maintenance</i></b>. Build automation enables you to
maintain a complete history of files and changes made. Maintaining a
complete history enables you to track issues back to their core.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image173.webp"
  alt="Benefits of Build Automation: Saving time and money."
  style="width:500px;"/>
</p>

The last benefit we will discuss in this session is <b><i>saving time and
money</i></b>. As build automation ensures increased productivity, accelerated
delivery, and enhanced quality, it enables you to save time and money
spent in delivering quality products and services.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image174.webp"
  alt="Popular web build tools and bundlers."
  style="width:500px;"/>
</p>

Now, we will explore some popular web build tools and bundlers:

  - Grunt, 
  - Gulp, 
  - Browserify, 
  - Webpack, 
  - npm, and 
  - RequireJS.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image175.webp"
  alt="Popular web build tools and bundlers: Grunt and Gulp."
  style="width:500px;"/>
</p>

Let's take a brief look at each of these tools.

<b><i>Grunt</i></b> is the first well-known task runner for front-end developers. Its
popularity was aided by the plugin architecture. As plugins are often
complex, it might be challenging to comprehend what is happening
whenever configuration increases.

<b><i>Gulp</i></b> is another JavaScript task runner built on Node streams. What
differentiates Gulp from others is that the former uses Node streams,
which means piping the output derived from one task as an input for the
next. Unlike Grunt, it deals with actual code rather than relying on
plugin configuration.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image176.webp"
  alt="Popular web build tools and bundlers: Browserify and Webpack."
  style="width:500px;"/>
</p>

<b><i>Browserify</i></b> is a build tool that allows using Node.js modules directly in
a browser. It allows you to bundle all your JavaScript modules into one
file that can be referenced within a script tag. It can be connected to
Gulp, and there are smaller transformation tools available that let you
go beyond the fundamental uses. The Browserify ecosystem is composed of
a lot of small modules.

<b><i>Webpack</i></b> offers a core that provides more functionalities straight out of
the box compared to Browserify&apos;s collection of several little tools.
Therefore, it is claimed that Webpack offers a clearer strategy compared
to Browserify. Webpack core can also be extended using specific loaders
and plugins. It provides flexibility in resolving modules and enables
you to modify your build to suit certain circumstances and get around
packages that don&apos;t function properly in difficult situations.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image177.webp"
  alt="Popular web build tools and bundlers: Node Package Manager (npm) and RequireJS."
  style="width:500px;"/>
</p>

<b><i>Node package manager (npm)</i></b> functions as a package manager for
JavaScript. It serves as the default package manager for the JavaScript
runtime environment, also called node.js. It consists of a command line
client and an online database of both free and paid private packages.
Users can use this tool to download and share JavaScript modules stored
in the registry. Packages are kept in the common JS format and have
JSON-formatted metadata files in the npm registry. Both the packages
installed globally and the local dependencies of specific objects can be
managed by npm.

<b><i>RequireJS</i></b> is a JavaScript library and file loader that manages the
dependencies between JavaScript files and modular programming. It
enhances both the speed and quality. RequireJS offers asynchronous
module loading and the ability to load layered dependencies. For a
better user experience, it merges and minifies modules into a single
script. It can compile JavaScript files from many modules and
load several JavaScript files.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image178.webp"
  alt="Recap (15): Introduction to Web Build and Automated Tools."
  style="width:500px;"/>
</p>

In this module (15), you learned about:

-   Build automation and its process,

-   The use of automated web build tools and bundlers in a given
    situation,

-   Some important functions of build JavaScript tools,

-   The five main benefits of Build automation, and

-   Some popular web build tools and bundlers used in web development.

<h2 name="ch3-16">16. Introduction to Webpack 5</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image179.webp"
  alt="3-16. Introduction to Webpack"
  style="width:500px;"/>
</p>

Welcome to the "Introduction to Webpack 5."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image180.webp"
  alt="Describe Webpack 5, it's advantages, functions, how it works and why its used."
  style="width:500px;"/>
</p>

After reading this module (16), you will be able to:

-   Describe Webpack 5,

-   Explain some advantages of Webpack 5,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Explain the functions of Webpack 5,

-   Explain how Webpack 5 works, and

-   Describe why to use Webpack 5.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image181.webp"
  alt="Intro to Webpack 5."
  style="width:500px;"/>
</p>

Webpack 5 is a module bundler that assists, in handling the bundling of
assets, modules, and dependencies into a single bundle while allowing
developers to concentrate on the development. Instead of being dependent
on online solutions, you can use Webpack 5 to build your own custom
solutions or boilerplates.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image182.webp"
  alt="Advantages of Webpack 5."
  style="width:500px;"/>
</p>

Now that you understand what Webpack 5 is, let us see some of its
advantages. Webpack 5 has the following advantages:

It neatly bundles your code. It enables you to write the most recent
JavaScript code using Babel or TypeScript and compiles it for
cross-browser compatibility, and then cleanly minifies it.

It allows the import of static assets into your JavaScript, and Also
offers a development server for development, which can instantly update
modules and styles as you save.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image183.webp"
  alt="What Webpack 5 does."
  style="width:500px;"/>
</p>

Now that you understand what Webpack 5 is and its advantages, let us
discuss what it does.

Webpack 5:

-   Helps assemble your resources,

-   Keeps track of modifications and reruns tasks,

-   Converts inline images into data URIs,

-   Uses require () for CSS files,

-   Runs a development web server,

-   Supports live updates or hot module replacement during development.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image184.webp"
  alt="How Webpack 5 works."
  style="width:500px;"/>
</p>

Webpack 5 is a command line tool and essentially a module bundler that
unifies all sources and module types to import everything in the
JavaScript code, resulting in a transferable output. It does so by
taking multiple files and combining them into one big file, as shown
here. The output file that Webpack generates can be sent to the client's
browser by a server.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image185.webp"
  alt="Why to use Webpack 5."
  style="width:500px;"/>
</p>

We will now explore the benefits of using Webpack 5. Webpack 5 is
powerful and has unique plugin system. Its latest features have overcome
flaws and shortcomings evident in its predecessors. It allows you to
bundle JavaScript files even without a configuration file.

Webpack 5 regulates different application entry points or parts and
offers shared bundles between them. Additional distinct bundle for each
portion can be loaded. Webpack 5 converts static assets into build
bundles and generates them for development and consistency. It is simple
to cache assets as Webpack 5 allows each file&apos;s assets to have their
own version.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image186.webp"
  alt="Recap (16): Webpack 5."
  style="width:500px;"/>
</p>

In this module (16), you learned that:

-   Webpack 5 is a command line tool that assists in handling the
    bundling of assets, modules, and dependencies into a single bundle,

-   There are several advantages of using Webpack 5,

-   Numerous functions can be performed by Webpack 5,

-   Webpack 5 works by taking multiple files and combining them into one
    big file, and

-   Webpack 5 is powerful and has a unique plugin system as well as
    numerous other benefits.

<h2 name="ch3-17">17. Essential Concepts of Webpack</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image187.webp"
  alt="3-17. Eseential Concepts of Webpack"
  style="width:500px;"/>
</p>

Welcome to "Essentials Concepts of Webpack"

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image188.webp"
  alt="Explain 4 core concepts of Webpack and define components that optimize the functioning of Webpack."
  style="width:500px;"/>
</p>

After reading this module (17), you will be able to:

-   Explain the four core concepts of Webpack,

-   Define components that optimize the functioning of Webpack.

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image189.webp"
  alt="Webpack: A module bunder: Webpack and Core Concepts."
  style="width:500px;"/>
</p>

Let us start by discussing Webpack's role in combining modules into
bundles. Webpack is a module bundler and allows you to create codes in
modules. If one file is dependent on another, it is treated as a
dependency by Webpack. The initial configuration starts from a single
module. It then processes all its dependencies, which can be either
direct or indirect. This gives shape to a dependency graph on which it
will bundle all the webpack modules. Considering this, we will learn the
core concepts in detail. They are: Entry Output Loaders and Plugins In
addition, we will touch upon some components related to Webpack.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image190.webp"
  alt="First concepts: Entry."
  style="width:500px;"/>
</p>

The first concept is Entry. The initial point from which the frontend
project&apos;s dependencies are gathered is known as an entry point. This is
a basic JavaScript file. These dependencies then create a dependency
graph. The default entry point for Webpack is src/index.js, and it is
configurable. Webpack can have multiple entry points that produce
modules through each dependency, and it repeats this procedure
throughout the application. See example (above).

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image191.webp"
  alt="Next concept: Output."
  style="width:400px;"/>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image192.webp"
  alt="Concept: Output: Example."
  style="width:400px;"/>
</p>

The second concept is Output. The static and JavaScript files produced
by the build process are gathered in Output. The default output folder
for Webpack is webpack dist/. and it can also be customized. The output
configuration tells Webpack how and where it should put the bundles. In
this example (above), you are instructing Webpack to place the bundles
in a JavaScript file called My-Webpack.bundle.js in the same directory
as Webpack.config.js.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image193.webp"
  alt=""
  style="width:500px;"/>
</p>

Let us now understand the third concept, Loader. As Webpack only
understands JavaScript and JSON files, Loaders are used to process other
types of files and convert them into valid modules. They transform the
source code of non-JavaScript modules, allowing us to preprocess those
files before they're added to the dependency graph. They help Webpack
deal with various file extensions.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image194.webp"
  alt=""
  style="width:500px;"/>
</p>

Let us look at an example (above).

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image195.webp"
  alt=""
  style="width:500px;"/>
</p>

The last concept is Plugins. It allows Webpack to perform a wide range
of tasks like bundle optimization, asset management, injection of
environment variables, and minifying files. They are third-party
extensions that can alter how Webpack functions.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image196.webp"
  alt=""
  style="width:500px;"/>
</p>

For example, there are plugins for extracting HTML and CSS or setting up
environment variables.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image197.webp"
  alt=""
  style="width:500px;"/>
</p>

Along with these, there are some additional concepts that optimize the
functioning of Webpack. Let us briefly touch upon them.

Chunk refers to the code extracted from modules. They are commonly used
when performing code-splitting with Webpack.

Assets refer to the static files bundled during the build process. These
can be in the form of images, fonts, or even videos.

Webpack supports a configuration file for projects with complex
structures. This is more efficient than having to type in a lot of
commands in the terminal manually.

Bundles separate the source code from the distribution code. The source
code is what we write and edit, whereas the distribution code is the
optimized output that is finally loaded in the browser.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image198.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (17), you learned that:

-   Webpack is a module bundler and depends on the dependency graph.

-   Entry point for Webpack is the initial point for creating dependency
    graphs.

-   Static and JavaScript files produced by the build process are
    collected in the output.

-   Loaders transform other file extensions to JavaScript and JSON
    files.

-   Plugins allow Webpack to perform a wide range of tasks.

<h2 name="ch3-18">18. Working with Webpack</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image199.webp"
  alt="3-18. Working with Webpack"
  style="width:500px;"/>
</p>

Welcome to "Working with Webpack."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image200.webp"
  alt=""
  style="width:500px;"/>
</p>

After reading this module (18), you will be able to:

-   Explain the importance of Webpack configuration,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify how assets are handled in a configuration file,

-   Discuss code splitting and the three ways to accomplish it,

-   Explain Preload and Prefetch for resource navigation, and

-   Describe the three main Webpack modes.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image201.webp"
  alt="Webpack: functions and how to configure."
  style="width:500px;"/>
</p>

Let's first understand the functions of Webpack and why we need
configuration. Webpack is a module bundler for web applications that
bundles, minifies, and transpiles JavaScript code to a browser-friendly
code. Webpack assumes that your code begins at src/index.js and will be
bundled to dist/main.js by default. Configuration helps to determine
whether code should be compressed for quicker execution or packed with
source maps for better error tracking.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image202.webp"
  alt="Webpack sample config file."
  style="width:500px;"/>
</p>

Webpack supports a configuration file for projects with complex
structures. This is more efficient than manually typing numerous
commands in the terminal. You can see a sample config file on the
screen.

The configuration JavaScript module belongs to CommonJS. Output from
this file is an object that Webpack will consider.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image203.webp"
  alt="Webpack creates project in development mode and includes comments and non-minimized code while running."
  style="width:500px;"/>
</p>

The configuration mentioned above instructs Webpack to create the
project in development mode to include comments and non-minimized code
in the output bundle while it is running.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image204.webp"
  alt="How to manage assets in Webpack 5.  Now built-in.  No additional configuration required."
  style="width:500px;"/>
</p>

Let's learn how assets can be easily managed using Webpack Your project
will often contain assets such as images, fonts, icons, and other
assets. In Webpack 4, we had to install one or more loaders to work with
assets. This is not needed in Webpack 5 because the new version comes
with built-in asset modules. They allow you to use asset files without
configuring additional loaders.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image205.webp"
  alt="How each asset type is handled in Webpack's config file."
  style="width:500px;"/>
</p>

Let's now explore how each asset type is handled in the Webpack
configuration file. A CSS file can be imported by installing and adding
the style-loader and CSS loader to your module configuration. Images and
icons can be incorporated using built-in asset modules. The asset
modules can incorporate any font through your build directory. Data can
be incorporated in the form of JSON files, CSVs, TSVs, and XML.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image206.webp"
  alt="Code splitting in Webpack for resource load prioritization."
  style="width:500px;"/>
</p>

Now that you have learned about asset management, let's understand code
splitting. The code splitting feature in Webpack is used to achieve
smaller bundles and control resource load prioritization. The reduced
main bundle size will speed up the initial load time and enable the
users to engage with your application more quickly.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image207.webp"
  alt="Code Splitting in Webpack 5 can be accomplished in 3 ways: Entry points, Prevent duplication &amp; Dynamic imports."
  style="width:500px;"/>
</p>

Code Splitting in Webpack 5 can be accomplished in three ways:

1.  Entry points: Manually split code using entry configuration,

2.  Prevent duplication: Remove identical entries and split chunks with
    SplitChunksPlugin,

3.  Dynamic imports: Split code using inline function calls within
    modules.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image208.webp"
  alt="Preload is declarative request which enables the browser to request resource without interrupting onload events."
  style="width:500px;"/>
</p>

Now that you have a clear understanding of code splitting let's learn
about Preload and Prefetch.

Preload is a declarative request that enables you to instruct the
browser to request a resource without interrupting the document's onload
event. These are the modules needed for current navigation and are
loaded in parallel to the parent chunk.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image209.webp"
  alt="Prefetch for future navigation."
  style="width:500px;"/>
</p>

Prefetch serves as an indication to the browser that a resource may be
required, but it leaves it to the browser to determine if it is to be
loaded or not. These are the modules needed for future navigation. They
start loading after the parent chunk finishes loading. Developers must
be careful when employing it since improper configuration might result
in poor performance.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image210.webp"
  alt="Three main config modes for Webpack 5: Development, Production, none."
  style="width:500px;"/>
</p>

Lastly, let's identify the three main configuration modes for Webpack. A
mode configuration option instructs Webpack to make appropriate use of
its built-in optimizations. The three main configuration modes are:
Development, Production, And none.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image211.webp"
  alt="Development mode is used specifically in the development phase of an 
  application.  Source maps are used to link produced code to original source code."
  style="width:500px;"/>
</p>

Development mode is used specifically in the development phase of an
application. Webpack offers source maps in the development code that
link your produced code to the original source code. This makes
debugging simpler and speeds up the process of fixing bugs and errors in
your code.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image212.webp"
  alt="Production is the default mode value and is used to deliver the final code for production."
  style="width:500px;"/>
</p>

Production is the default mode value and is used to deliver the final
code for production. Webpack, in production mode, tries its best to
optimize the build by automatically minifying the code with the help of
TerserPlugin. It encourages Webpack to give you access to all the
optimizations possible, such as tree shaking, performance hints, or
minification with the TerserWebpackPlugin. It is helpful at the time of
building an application. In this mode, none of the default optimization
options are applied.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image213.webp"
  alt="Webpack 5 is a module bundler for web applications.  Among other things."
  style="width:500px;"/>
</p>

In this module (18), you learned about:

-   Webpack and its role as a module bundler for web applications,

-   Webpack configuration and its importance,

-   Asset management and how assets are handled in a configuration file,

-   Code splitting and the three ways to accomplish it,

-   The functions of Preload and Prefetch, and

-   The three main configuration modes for Webpack.

<h2 name="ch3-19">19. Setting up Production with Webpack</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image214.webp"
  alt="3-19. Setting up Production with Webpack"
  style="width:500px;"/>
</p>

Welcome to "Setting up Production with Webpack."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image215.webp"
  alt="Configuration modes in Webpack and best practices."
  style="width:500px;"/>
</p>

After reading this module (19), you will be able to:

-   Identify the different configuration modes in Webpack, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Discuss the best practices related to Webpack in production.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image216.webp"
  alt="Mode configuration option instructs Webpack to make appropriate use of built-in optimizations."
  style="width:500px;"/>
</p>

A mode configuration option instructs Webpack to make appropriate use of
its built-in optimizations. You can set it to \"none\" to disable any
default behavior.

There are two main configuration options for Webpack: the development
and production modes.

The development mode simplifies debugging by activating
NamedChunksPlugin and preventing minification, among other things. In
development mode, the bundle will be descriptive and will include more
comments. As a result of Webpack&apos;s adoption of the software engineering
paradigm convention over configuration, you can basically acquire a
useful configuration by simply setting the mode to production.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image217.webp"
  alt="Production mode encourages Webpack to optimize."
  style="width:500px;"/>
</p>

Production is the default mode value. It encourages Webpack to give you
access to all the optimizations possible, such as tree shaking,
performance hints, or minification with the TerserWebpackPlugin. It is
really helpful at the time of building an application. Webpack, in
production mode, tries its best to optimize the build by automatically
minifying the code. It is recommended to create distinct Webpack
settings for each scenario.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image218.webp"
  alt="Development mode encourages strong source mapping."
  style="width:500px;"/>
</p>

Development and production builds have numerous different objectives. In
the case of development, the goal is to have strong source mapping and a
local host server with live reloading or hot module replacement. In the
case of production, the goal shifts to minified bundles, lighter-weight
source maps, and optimized assets to improve the load time. We still
prefer a "common" configuration to make things uniform.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image219.webp"
  alt="Best practices with Webpack in production."
  style="width:500px;"/>
</p>

We will now discuss the best practices related to Webpack in production.
Webpack, in the production mode, tries its best to optimize the build by
automatically minifying the code. Some of the best production practices
to improve a website's performance include: Minifying CSS, Webpack
source maps, File hashing, and Cleanup of old assets. Let's discuss each
of these practices in detail.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image220.webp"
  alt="Minifying CSS in production to improve load time."
  style="width:500px;"/>
</p>

Minifying CSS means to remove unnecessary characters, such as comments,
whitespaces, and indentation. Minifying your assets in production is a
good practice as it can drastically improve the website's load time.
Here are the steps to minify CSS: Add another plugin to help Webpack
minify your CSS files. Open your command line. Run npm install
optimize-css-assets-Webpack-plugin. Finally, save dev.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image221.webp"
  alt=""
  style="width:500px;"/>
</p>

Source maps are generated alongside built files, which are minified
already. These maps let you trace back the minified code to its original
location and help in debugging the code live. Webpack has built-in
support for source map generation via the devtool property.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image222.webp"
  alt=""
  style="width:500px;"/>
</p>

Files essentially consist of data chunks. This data is changed via
hashing into a key or value that is much shorter and fixed in length. It
is called file hashing. It is important as it allows making changes in a
file even after the website is published. Adding hashing or content
hashing is known as long-term caching, as the files could be cached
forever.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image223.webp"
  alt=""
  style="width:500px;"/>
</p>

One of the best practices related to production is to install a plugin
to create a build folder and to clean that folder every time it runs.
This is done to avoid the minification of all the files in the public
folder. To install a cleanup plugin, follow these steps: Install a
plugin. Open your command line and run npm install clean-Webpack-plugin.
Finally, save dev.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image224.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (19), you learned that:

-   Webpack in production mode allows many practices that are helpful at
    the time of building an application. These include:

    -   Minifying CSS to remove unnecessary characters, such as
        comments, whitespaces, and indentation,

    -   Generating source maps to trace back the minified code to its
        original location,

    -   File hashing to make changes in a file even after a website is
        published,

    -   Clean up old assets to avoid the minification of all the files
        in the public folder.

<h2 name="ch3-20">20. Using Webpack Tools</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image225.webp"
  alt="3-20. Using Webpack Tools"
  style="width:500px;"/>
</p>

Welcome to "Using Webpack Tools."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image226.webp"
  alt=""
  style="width:500px;"/>
</p>

After reading this module (20), you will be able to:

-   Explain the need for Webpack tools, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Describe five popular Webpack bundle size tools.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image227.webp"
  alt=""
  style="width:500px;"/>
</p>

Webpack is a module bundler used to bundle JavaScript files to be used
in a browser. Bundle size is an important metric determining how fast a
web application will load. Growth in applications results in large
bundle sizes, creating a problem for the developers. An increase in
bundle size results in an increase in download time and a bigger
overhead in execution time during initialization.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image228.webp"
  alt=""
  style="width:500px;"/>
</p>

Let's now discuss the benefits of reducing the build size. Reduced build
size leads to the website loading quickly. JavaScript execution and
processing   will be quicker, which is essential in the case of mobile
applications. Ultimately, the user&apos;s mobile data plan cost is reduced.
Developers use different Webpack tools to reduce the bundle size. Let's
explore five such tools.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image229.webp"
  alt=""
  style="width:500px;"/>
</p>

The five popular Webpack tools that we are going to explore in this
session include:

Bundlephobia, Webpack Visualizer, Webpack Analyzer, Source Map Explorer,
and Webpack Bundle Analyzer.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image230.webp"
  alt=""
  style="width:500px;"/>
</p>

Now, let's discuss each in detail.

One of the most popular Webpack tool that developers use is
Bundlephobia. It is a build-size tool that can be used as a website or
plugin. It offers various benefits. Bundlephobia enables you to
understand the performance cost of installing a new NPM package before
it becomes a part of your bundle. It evaluates the package size
beforehand and helps select the best option available. Bundlephobia also
displays how this package will affect users and browsers when it is used
in your application.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image231.webp"
  alt=""
  style="width:500px;"/>
</p>

For example, it helps determine the download and render times. To use
Bundlephobia as a website, upload the package.json file to the website.
It will give you all the details, including the file size, download
time, dependency information, and statistics for various plugin
versions. To use Bundlephobia as a plugin, install it with NPM using the
following command:

-   Npm -g bundle-phobia-cli

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image232.webp"
  alt=""
  style="width:500px;"/>
</p>

Another popular Webpack tool is Webpack Visualizer. It is an analysis
tool used to create a visual representation of your final bundle. This
tool also detects modules used in our project and offers insights into
which modules can be duplicated. It shows the visualized separation of
components. It determines how much space they take up and their
percentage allocation to the overall amount of the chunk.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image233.webp"
  alt=""
  style="width:500px;"/>
</p>

There are two ways of using Webpack Visualizer. You can upload your
stats.json file on chrisbateman.github.io/webpack-visualizer. Or you
could just install it using 

-   npm webpack-visualizer-plugin 

and then import it to the webpack config file.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image234.webp"
  alt=""
  style="width:500px;"/>
</p>

The next popular Webpack tool we will explore is Webpack Analyzer. It is
an interactive tool that helps you visualize your bundle sizes. Webpack
Analyzer offers a more detailed examination of your bundle by generating
a dependency graph. Webpack Analyzer results display the warnings and
errors from the Webpack build with suggestions on how to enhance it.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image235.webp"
  alt=""
  style="width:500px;"/>
</p>

To use Webpack Analyzer, generate a stat file using the Webpack ---
profile --- json \> stats.json command and upload it to the website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image236.webp"
  alt=""
  style="width:500px;"/>
</p>

Source Map Explorer is another popular Webpack tool that offers a visual
representation of any JavaScript bundle that has a source map. It
informs you about the file size of the minified JavaScript bundle and
helps you identify the origin of the minified code. Source Map
Explorer allows you to inspect your final bundle in a graphical manner.
It provides a treemap visualization to help you debug where all the code
is coming from.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image237.webp"
  alt=""
  style="width:500px;"/>
</p>

To use Source Map Explorer: Install Source Map Explorer globally using
npm. Then, try to generate a responsive treemap of your bundle using
the bundle.js and bundle.js.map files.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image238.webp"
  alt=""
  style="width:500px;"/>
</p>

The last Webpack tool we will explore is Webpack Bundle Analyzer. It
provides guidance on which modules may be trimmed and helps identify
modules used in your project. It also supports minified bundles. Webpack
bundle Analyzer helps to identify modules that are large or can be
removed.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image239.webp"
  alt=""
  style="width:500px;"/>
</p>

To use this tool: Install the plugin, Create the Webpack stats JSON
file, and Use the analyzer.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image240.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (20), you learned that:

-   Developers use different Webpack tools to reduce the bundle size for
    improving the performance of web applications,

-   BundlePhobia enables you to understand the performance cost of
    installing a package to an application,

-   Webpack visualizer is used for creating a visual representation of
    your final bundle,

-   Webpack Analyzer visualizes your bundle sizes by creating dependency
    graphs,

-   Source Map Explorer identifies the origin of minified code, and

-   Webpack Bundle Analyzer helps to acknowledge the contents of the
    bundle and discover large modules.

<h2 name="ch3-21">21. Using Webpack with Front-end Frameworks</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image241.webp"
  alt="3-21. Using Webpack with Front-end Frameworks"
  style="width:500px;"/>
</p>

Welcome to "Using Webpack with Front-end Frameworks.\"

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image242.webp"
  alt=""
  style="width:500px;"/>
</p>

After reading this module (21), you will be able to:

-   Explain the need for using Webpack with front-end frameworks, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Describe how to configure Webpack with Angular, Vue, and React.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image243.webp"
  alt=""
  style="width:500px;"/>
</p>

Let's begin by understanding a front-end framework. A front-end
framework is a pre-prepared library meant to be used for the development
of a website. It is a collection of CSS, JavaScript, and other files
designed to make building web applications faster and more consistent.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image244.webp"
  alt=""
  style="width:500px;"/>
</p>

Webpack is commonly used with frontend frameworks. It has several
features that are useful for building and deploying web applications.
Some of these features include: Code bundling, Module management, Code
optimization, and Easy integration.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image245.webp"
  alt=""
  style="width:500px;"/>
</p>

Let's discuss each of these features in detail. The first feature is
code bundling. Webpack can bundle all JavaScript and CSS files for a web
application into a single file, making it efficient to load and run on a
browser.

The next feature is module management. Webpack can manage the
dependencies of a web application, ensuring that all the necessary
modules are included and loaded in the correct order.

Another important feature is code optimization. Webpack can be
configured to optimize and minify the code for a production build,
making it faster to load and run.

The last feature that we are going to discuss is easy integration.
Webpack can be easily integrated with a wide range of frontend
frameworks, making it a versatile tool for building web applications.
These features make the development process more efficient and the final
product robust.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image246.webp"
  alt=""
  style="width:500px;"/>
</p>

Now, let's discuss how to configure Webpack with Angular. However,
before that, we need to understand what Angular is. Angular is a
JavaScript framework developed and maintained by Google. It is used to
create Single-Page Applications (SPAs) that can dynamically update
content without requiring a page refresh.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image247.webp"
  alt=""
  style="width:500px;"/>
</p>

Configuring Webpack with Angular involves a few steps. Let's explore
these steps. First, you need to create an application folder and name
it. Click to open the folder, and then create a file named package.json.
This file contains project configuration information, including package
dependencies. To install Angular libraries when configuring Webpack with
Angular, you need to use Node Package Manager (npm). Use the command as
shown here:

-   Npm install \<library name\>

Note that, like Angular libraries, dependencies can be installed when
configuring Webpack with Angular using npm. Webpack is a JavaScript
module bundler that can be extended with loaders to handle other file
types (for example, TypeScript, HTML, and CSS) and plugins to perform
other tasks, such as injecting generated JS bundles into an HTML
template (html-webpack-plugin).

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image248.webp"
  alt=""
  style="width:500px;"/>
</p>

Here are the remaining steps of configuring Webpack with Angular: Now,
create a new component and a root module to define the entry point of
your application while configuring Webpack with Angular. Note that an
entry point is used by Angular to bootstrap/launch the application&apos;s
root module. Create the main index.html file, which is the initial page
loaded by a browser. To ensure that the scripts are loaded and run by
the browser, Webpack groups all of the JavaScript files together and
injects them into the body of the index.html page. Next, click to open
the project folder, and then create a file named webpack.config.js. This
file specifies the configuration options used by Webpack to compile and
bundle an Angular app. Now, you can run the application. Use the
command, as shown here:

-   ng serve

\- to run the application.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image249.webp"
  alt=""
  style="width:500px;"/>
</p>

Now we will discuss the process of configuring Webpack with Vue. Before
we proceed, let's try to understand what Vue.js is. Vue.js is an
open-source JavaScript framework for building user interfaces. It is
designed to be approachable and easy to learn.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image250.webp"
  alt=""
  style="width:500px;"/>
</p>

Let's talk about the steps of configuring Webpack with Vue in detail.
First, create a new application folder. Note that all of your project
files will be stored in this folder. Now, create a package.json
configuration file. The primary point of contact between Webpack and
your code is this file. The entry point and output are specified. Next,
you need to install dependencies. For this, you can use the npm package
manager. Now, you need to configure Webpack to use the Babel loader and
the Vue loader.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image251.webp"
  alt=""
  style="width:500px;"/>
</p>

Here are the remaining steps of configuring Webpack with Vue: Write the
code to start your server. This can be done in package.json using
webpack-dev-serve. Use third-party extensions in your Webpack
configuration, such as loaders, plugins, and code splitting. For this,
you need to install them before adding them to your webpack.config.js
file. Check your Webpack configuration. You can run the command, as
shown here, in your terminal.

-   webpack \--config webpack.config.js \--display-modules
    \--display-reasons

All the modules that Webpack is using, along with the reason why they
are included, will appear. Also, you can use webpack-validator, a tool
that will validate your Webpack configuration file and highlight any
errors or potential issues.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image252.webp"
  alt=""
  style="width:500px;"/>
</p>

And lastly, we will discuss the process of configuring Webpack with
React. However, before that, we need to be aware of React. React is a
JavaScript library used to build user interfaces. It was developed and
is maintained by Facebook. It focuses on the declarative approach to
programming, making it easier to understand and debug code.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image253.webp"
  alt=""
  style="width:500px;"/>
</p>

Now let&apos;s explore the steps of configuring Webpack with React. The
first step in this process is setting up React. To set react, perform
the following steps:

Set up the folder with npm and git. Command to setup folder with npm:

-   mkdir my-app

-   cd my-app

-   npm init

Npm will now ask you a few brief questions about your project before
creating the package.json file in the root directory.

To set up git for your project, use this command:

-   git init.

Create a new source folder and add HTML and JavaScript files.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image254.webp"
  alt=""
  style="width:500px;"/>
</p>

The second step of configuring Webpack with React is to install and set
up Webpack. To install Webpack to our project, use the command as shown
here.

-   npm install webpack webpack-cli webpack-dev-server \--save-devSetup
    configuration file -- webpack.config.js

This will install three packages: the
main Webpack package, webpack-cli to run Webpack commands,
and Webpack-dev-server to run React locally. Use the webpack.config.js
command to add the Webpack configuration file to the root folder.

The third step of configuring Webpack with React is to instruct Webpack
where to begin combining the JavaScript files, which means specifying
the entry point for Webpack.

The fourth step of configuring Webpack with React is to define the
output path for the bundled file after the entry point is defined.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image255.webp"
  alt=""
  style="width:500px;"/>
</p>

Here are the remaining steps of configuring Webpack with React: Add the
bundled JavaScript file to the HTML file. Install Babel, which is the
core transpiler, using the command shown here Configure Webpack to use
Babel.

Now that a configuration file is created, you can build and run the
application.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image256.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (21), you learned about;

-   The need for using Webpack with front-end frameworks,

-   The steps to configure Webpack with Angular, Vue, and React.

## Hands on Lab: Build and Deploy a website using Webpack

## Welcome to the **Build and Deploy a website using Webpack** lab! 

In this lab, you will learn how to package your web application using
Webpack. The lab is a continuation of the Fruit Marketplace.

Skills Network Labs (SN Labs) is a virtual lab environment used in this
course. Upon clicking \"Open Tool\" in accordance with IBM Skills
Network Privacy policy your Username and Email will be passed to Skills
Network Labs and will only be used for communicating important
information to enhance your learning experience.

In case you need to download the lab instructions click
[HERE](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-WD0231EN-SkillsNetwork/labs/webpack.md.html)
to open in a new tab.

This course uses a third-party app, Hands on Lab: Build and Deploy a
website using Webpack, to enhance your learning experience. The app will
reference basic information like your name, email, and Coursera ID.

<h2 name="ch3-22">22. Webpack Best Practices</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image257.webp"
  alt="3-22. Webpack Best Practices"
  style="width:500px;"/>
</p>

Welcome to "Webpack Best Practices."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image258.webp"
  alt="Webpack: Identify some best practices for optimizing Webpack."
  style="width:500px;"/>
</p>

After reading this module (22), you will be able to:

-   Identify some important best practices for optimizing Webpack, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Describe the benefits of implementing some key best practices in
    Webpack.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image259.webp"
  alt="Webpack: Aids in building effective and optimized web apps, and is an excellent tool
    for creating applications."
  style="width:500px;"/>
</p>

Webpack is a widely used module bundler that aids developers in building
effective and optimized web applications. It is an excellent tool for
creating applications; however, it can be challenging to get the most
out of it.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image260.webp"
  alt="Optimizing Webpack."
  style="width:500px;"/>
</p>

In this module (22), we will learn about a few best practices for
optimizing Webpack to ensure that your applications are optimized and
efficient. 
The best practices we will explore in this session include:

  - Production builds, 
  - Using source maps, 
  - Lazy loading modules, 
  - Exclusion and inclusion of files, 
  - Reusing modules, 
  - Splitting vendor bundles,
  - Caching approach, and 
  - Tree shaking.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image261.webp"
  alt="Production builds."
  style="width:500px;"/>
</p>

The first best practice that we will explore is using the production
mode in Webpack. Using this mode has several benefits. 
It helps in performance optimization. Webpack implements a number of performance
improvements when used in the production mode, including code
minification, tree shaking, and scope hoisting. These improvements
accelerate the loading of your application and help reduce the size of
the final output. 

Using the production mode also helps in debugging.
When running in the development mode, Webpack generates source maps that
can trace back errors to their original source. 

The optimizations applied in the production mode can lead to a faster, more 
responsive user experience, as the application loads faster and runs more
efficiently.

To use the production mode in Webpack, you need to set the mode configuration option 
to \"production.\"
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image262.webp"
  alt=""
  style="width:500px;"/>
</p>

Another best practice related to using Webpack is the use of source maps.
Webpack combines all the code in one or more bundles. These bundles can be difficult 
to debug as the code is minified, making it hard to read and understand. 

Source maps are a way to map the code back to its original source. 

This makes debugging simpler and effective as it enables developers to test their 
code in the same manner they would if it weren&apos;t bundled. 

Hence, source maps provide an easier way to debug and understand the code, 
especially in complex web development projects.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image263.webp"
  alt=""
  style="width:500px;"/>
</p>

The third best practice is lazy loading.

It is a technique of loading JavaScript modules only when they are needed, 
rather than loading them all at once when the application starts. After using the lazy-loaded
modules, a large JavaScript file is divided into multiple small
JavaScript files and the web page is loaded on demand. This accelerates
the initial loading of the application and reduces its overall weight as
some blocks may never even be loaded.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image264.webp"
  alt=""
  style="width:500px;"/>
</p>

Now, we will discuss the exclusion and inclusion of files. 

In Webpack, you can use the \"exclude\" and \"include\" options to specify which
files should be included in the build output. The \"exclude\" option
specifies the files not required to be compiled. 

For example: node modules. The \"include option\" specifies the files required to be
compiled. 

For example: the src folder. By using the \"exclude\" and \"include\" options in 
Webpack, you can have greater control over which files are processed, which helps 
enhance compilation efficiency.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image265.webp"
  alt=""
  style="width:500px;"/>
</p>

The fifth best practice is reusing modules. 

Reusing modules in Webpack is a way to optimize your build by sharing common code 
between multiple parts of your application. This can help reduce the size of the final
bundle, which makes it easier to maintain and debug. Reusing modules also helps save 
time and effort when building new projects. Additionally, by using pre-existing modules, 
programmers may ensure that their code complies with the latest standards and best 
practices related to improving the performance of your application.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image266.webp"
  alt=""
  style="width:500px;"/>
</p>

Next, we will discuss bundle splitting in Webpack. 

It is a way of breaking your application into smaller, independent chunks that can be
loaded on demand, rather than loading the entire code of your application at once. A 
chunk is a group of modules that directly corresponds with the output bundle. 

Using SplitChunksPlugin, we can split up a chunk into smaller chunks. Bundle splitting 
is an effective way to optimize the performance of your Webpack builds and is
particularly useful for large applications with many dependencies. This
helps reduce the size of the initial load, improving the performance of
your application.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image267.webp"
  alt=""
  style="width:500px;"/>
</p>

Another popular practice is caching.

Caching in Webpack is a technique that allows the build process to save the results 
of previous builds so that future builds can be completed quickly. This helps improve
performance by reducing the amount of time spent on loading resources and reducing the 
amount of bandwidth used. By employing caching techniques, developers can ensure that 
each bundle contains only the necessary files, thereby reducing the bundle size and 
accelerating builds. 

To implement caching strategies with Webpack, developers should use the 
webpack-bundle-analyzer plugin. Developers may use this plugin to examine their 
bundles and determine which files are duplicated or unnecessary. 

After these files are identified, developers can create an appropriate 
caching strategy for them.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image268.webp"
  alt=""
  style="width:500px;"/>
</p>

The last best practice to optimize Webpack that we are going to discuss
is tree shaking. 

It is an optimization technique used in Webpack to eliminate unused code from the 
final bundle. It analyzes the imported and exported modules in the code and removes 
the parts of the code not actually used by the application. This results in a smaller 
and more efficient bundle, which can improve performance and reduce the size of
the application for the end user. 

In Webpack5, tree shaking is enabled by default in the production mode.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image269.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (22), you learned that:

-   Production mode helps in Webpack performance optimization,

-   Source maps help in tracing minified code back to its original
    location,

-   Lazy loading refers to the practice of loading JavaScript modules
    only when they are required,

-   The \"exclude\" and \"include\" options control which files are
    included in the build output,

-   Reusing modules reduces build time by sharing common code across
    multiple parts of your application,

-   Splitting vendor bundles is a method of dividing your application
    into smaller, self-contained chunks,

-   Caching enables the build process to save previous build results, and

-   Tree shaking removes unnecessary code from the final bundle.

<h2 name="ch3-23">23. Reading: HTTPS & SSL Certificates</h2>

## What is HTTPS?

Hypertext transfer protocol secure (HTTPS) is the secure version of
HTTP, which is the primary protocol used to send data between a web
browser and a website. HTTPS is encrypted in order to increase the
security of data transfer. This is particularly important when users
transmit sensitive data by logging into a bank account, email service,
or health insurance provider.

Any website, especially those that require login credentials, should use
HTTPS. In modern web browsers such as Chrome, websites that do not use
HTTPS are marked differently than those that are.

Look for a padlock in the URL bar to signify that the webpage is secure.
Web browsers take HTTPS seriously; Google Chrome and other browsers flag
all non-HTTPS websites as not secure.

## How does HTTPS work?

HTTPS uses an encryption protocol to encrypt communications. The
protocol is called Transport Layer Security (TLS), formerly known as
Secure Sockets Layer (SSL). This protocol secures communications by
using what's known as an asymmetric public key infrastructure. This type
of security system uses two different keys to encrypt communications
between two parties:

The private key - this key is controlled by the owner of a website, and
it's kept, as the reader may have speculated, private. This key lives on
a web server and is used to decrypt information encrypted by the public
key.

The public key - this key is available to everyone who wants to interact
with the server in a way that's secure. Information that's encrypted by
the public key can only be decrypted by the private key.

## How does a website start using HTTPS?

Many website hosting providers and other services will offer TLS/SSL
certificates for a fee. These certificates will often be shared amongst
many customers. More expensive certificates are available, which can be
individually registered to particular web properties.
<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

## What is an SSL Certificate?

SSL stands for Secure Sockets Layer, and, in short, it&apos;s the standard
technology for keeping an internet connection secure and safeguarding
any sensitive data that is being sent between two systems, preventing
criminals from reading and modifying any information transferred,
including potential personal details. 

The two systems can be a server and a client (for example, a shopping website and 
browser) or server to server (for example, an application with personal identifiable
information or with payroll information).

It does this by making sure that any data transferred between users and sites or 
between two systems remain impossible to read. It uses encryption algorithms to 
scramble data in transit, preventing hackers from reading it as it is sent over 
the connection. This information could be anything sensitive or personal which 
can include credit card numbers and other financial information, names, and 
addresses.

TLS (Transport Layer Security) is just an updated, more secure version of SSL.

## How Does an SSL Certificate Work?

SSL certificates protect data transfer using two different encryption
techniques: asymmetric and symmetric.

Asymmetric encryption uses two separate keys: a public and a private
key. The public key is used to encrypt the message, which can only be
decrypted by the private key, and vice versa. On the other hand,
symmetric encryption uses one shared key, or a pair of keys, to encrypt
and decrypt the message.

To give a better understanding of how those encryption techniques work,
here's an overview of the process:

-   First, a website owner purchases an SSL certificate from a
    Certificate Authority (CA) and installs it on their site,

-   When a visitor navigates through the website, the browser and the
    web server establish an SSL connection using a method called <b>SSL
    handshake</b>,

-   During the SSL handshake, the browser asks the server for its SSL
    certificate and public key to prove its validity,

-   Once the certificate is verified, the browser and web server
    exchange private and public keys to create a symmetric session key, and

-   Both parties then use this symmetric key to encrypt all
    communications. This key will remain valid for a limited time and
    only for that particular session.

# Week 3 Summary: Introduction to Automated Build Tools (Webpack)

In this separate section, you learned that:

-   Build automation is preparing the source code for production so that
    users can interact with it comfortably.

-   Webpack 5 is a command line tool that assists in handling the
    bundling of assets, modules, and dependencies into a single bundle.

-   Webpack comprises concepts that optimize its functioning.

-   Configuring Webpack tracks errors efficiently and helps in quicker
    execution.

-   Webpack comprises three main configuration modes.

-   Webpack in production mode allows many practices that are helpful at
    the time of building an application.

-   Developers use different Webpack tools to reduce the bundle size to
    improve the performance of web applications.

-   Many frontend frameworks use Webpack to build and deploy web
    applications.

-   Some best practices can be implemented to optimize Webpack.

<!-- # [Week 4:]{.mark} -->

<h1 name="ch4">WEEK 4</h1>

<h2 name="ch4-24">24. JavaScript Optimization</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image270.webp"
  alt="4-24. JavaScript Optimization."
  style="width:500px;"/>
</p>

Welcome to JavaScript Optimization.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image271.webp"
  alt="Module 24; define, explain and identify web optimization. Then define how JS can 
    improve performance."
  style="width:500px;"/>
</p>

After reading this module (24), you will be able to: 
  - Define web optimization and JavaScript, 
  - Explain how web optimization impacts website success factors, 

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

  - Identify some popular web performance optimization methods, and 
  - Define how JavaScript can improve a web application's performance.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image272.webp"
  alt="What is javascript and web optimization?"
  style="width:500px;"/>
</p>

Web optimization determines how quickly a website loads and becomes
responsive and interactive and how smoothly the content is presented
when users interact with it. 

JavaScript is capable of producing highly interactive websites that actively engage 
the user. However, increased engagement levels can negatively impact a website's 
usability. 

It is important to minimize loading and response times and add additional
features to conceal inactivity by making the experience as available and
interactive as possible.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image273.webp"
  alt="Key factors of web optimization."
  style="width:500px;"/>
</p>

Web optimization impacts the crucial factors that determine website
success. 

The first factor is conversion rate. This metric is crucial for
a business&apos;s success as it indicates that the target audience completes
the actions you want them to perform, such as purchasing a product,
subscribing to a newsletter, registering for a webinar, or downloading a
step-by-step guide. The higher the conversion rate, the faster the
loading time. 

Another important factor is visibility. Page speed is a
critical ranking factor. A low-performing website with poor user
experience and long loading times will be penalized by search engines
and have a lower SERP ranking. 

The last factor is website usability, which helps to increase or establish customer 
loyalty. The better the website behaves, the happier the end users are.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image274.webp"
  alt="Web performance optimization tips."
  style="width:500px;"/>
</p>

Let's now talk about a few web performance optimization methods.

<b><i>Content delivery networks (CDNs)</i></b> 

CDNs were created to address the issues associated with network communication delays. 
A version of the content is stored in various geographical locations by CDN. By 
handling the performance middle mile, a CDN brings the user closer to resources. 
The number of trips the server makes is significantly reduced, resulting in
a faster loading process.

<b><i>File Compression</i></b>

The HTML, JS, and CSS code files are the foundation of
every website. The longer it takes to load a page, the more complex it
is. These large code files should be compressed to their original size
to improve site responsiveness. You can use GZip and other well-known
programs for data compression and decompression.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image275.webp"
  alt="Web performance optimization tips."
  style="width:500px;"/>
</p>

<b><i>Resource minification</i></b>

Resource minification removes unnecessary code
redundancy from CSS, HTML, and JavaScript, resulting in smaller page
sizes. Reducing the amount of code that needs to be fetched from the
server speeds up front-end loading. The tool used to generate minified
codes for JavaScript is JSMin, CSS is cssmin and YUI Compressor, and for
HTML is PageSpeed Insights.

<b><i>Optimize Images and videos</i></b>

High-resolution images and videos significantly slow down the rendering process.
Compressing images without sacrificing quality is possible with tools
like Compressor.io, JPEGmini, and TinyPNG. HTML responsive images and
attributes can also be used as it adjusts image size based on the
display properties of the user's device. Animated WebP can be used for
videos or replaced with an HTML5 video tag.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image276.webp"
  alt="Web performance optimization tips."
  style="width:500px;"/>
</p>

<b><i>Use caching</i></b>

When a user visits a website, the elements are saved in a
temporary hard drive storage area known as a cache. Caching saves a copy
of the latest version of the website on the hosting server and allows
the user to access the cached copy rather than the original copy later.
This practice enables the pages to load faster. There are various types
of caching, such as browser cache, cache server, memory cache, and disc
cache, that help to increase delivery speed. 

<b><i>Minimize HTTP Requests</i></b>

If your website makes a lot of HTTP requests, the web pages will take
longer to load. Determine the number of HTTP requests and then use some
techniques to reduce the number of requests. Avoid using extra plugins,
images, JavaScript, and CSS. Combine your JavaScript and CSS files into
a single package. Only use third-party frameworks when necessary.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image277.webp"
  alt="Javascript optimization tips."
  style="width:500px;"/>
</p>

JavaScript is becoming a popular language for creating web applications.
Here are some important points on how JavaScript can improve the
performance of your web application. 

<b><i>Asynchronous programming</i></b>

The async.js feature of JavaScript aids in the efficient management of
asynchronous codes. As a result, async code is pushed to an event queue,
where it executes after all other code has been completed.

<b><i>Light and small code files</i></b>

Keeping the code light and small reduces latency and increases speed. Multiple JS 
files can be combined into one to improve application performance. 

<b><i>Gzip compression</i></b>

Most clients and servers use Gzip as a compression and decompression software 
application. It compresses large JavaScript files and saves bandwidth, reducing 
latency and time lag and improving overall application performance.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image278.webp"
  alt="Javascipt optimization tips."
  style="width:500px;"/>
</p>

<b><i>Utilize HTTP/2</i></b>

HTTP/2 uses multiplexing, allowing multiple responses and
requests to be sent simultaneously. It improves not only JavaScript
performance but also website speed.

<b><i>Avoid Unnecessary Loops</i></b>

Unnecessary looping is unfavorable. Try to do as much work as possible outside of
loops because the faster the loops get, the less you loop. Loops place
additional strain on the browser and slow down the entire process.

<b><i>Placement of Scripts</i></b>

JavaScript should be placed at the bottom of the page to improve both rendering 
progress and download parallelization. It will save the total amount of code 
required and make the page load faster.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image279.webp"
  alt="Recap module 24; Web site performance."
  style="width:500px;"/>
</p>

In this module (24), you learned that:

-   Web performance assesses site load time and responsiveness of the
    displayed content.

-   JavaScript produces highly interactive websites that actively engage
    the user.

-   Key factors of web optimization are conversion rate, visibility, and
    usability.

-   Web performance optimization provides user information quickly while
    ensuring a smooth interactive experience, and

-   JavaScript tips affect the performance of a web application and how
    to improve it.

<h2 name="ch4-25">25. Popular Optimization Tools</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image280.webp"
  alt="4-25. Popular Optimization Tools"
  style="width:500px;"/>
</p>

Welcome to Popular Optimization Tools!

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image281.webp"
  alt="Module 25; Identify approaches to web optimization and list tools to be used."
  style="width:500px;"/>
</p>

After reading this module (25), you'll be able to:

-   Identify the various approaches to web optimization, and
<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>
-   List the key optimization tools used in each approach.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image282.webp"
  alt="Approach to web optimization; make website appealing, determine what's wrong with current site 
    and select tools for potential problems."
  style="width:500px;"/>
</p>

The goal of website optimization is to make a website as appealing to
search engines and users as possible. To achieve this, the first step is
to identify problems. Before any great optimization process begins, it
is necessary to determine what is wrong with the current website. Simply
brainstorming potential issues is not enough. Instead, we need to use
available software tools to look for potential issues.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image283.webp"
  alt="Approach to web optimization."
  style="width:500px;"/>
</p>

Some of the factors that require the use of optimization tools include:
Page speed, User experience (UX), Mobile, Web accessibility, and
JavaScript. Let's discuss some of the best, most-used, and most
productive website optimization tools you should consider adding to your
website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image284.webp"
  alt="Page Speed Optimization.  Assess what is slowing the page down."
  style="width:500px;"/>
</p>

Let&apos;s start with page speed optimization tools. A slow website can
drive users away and affect search rankings. Web page speed tools do not
automatically fix your slow site. Instead, they measure the page speed
and show you what&apos;s slowing it down. You&apos;ll be able to determine how
to improve page load times by implementing certain measures. These
include: Reducing and compressing HTML, CSS, JavaScript, and images,
Caching content, and Using faster hosting servers.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image285.webp"
  alt="Page Speed Optimization Tools; PageSpeed insights, GTmetrix, Pingdom, and webpagetest."
  style="width:500px;"/>
</p>

Some of the popular page speed optimization tools include: PageSpeed
Insights, Gtmetrix, Pingdom, and WebPageTest.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image286.webp"
  alt="UX Optimization Tools."
  style="width:500px;"/>
</p>

Next, we'll discuss user experience (UX) optimization tools. Great UX
will keep visitors happy and reduce friction on your website, resulting
in higher conversion rates and revenue. Usability testing will help you
understand user behavior and diagnose problems so you can optimize pages
and give people what they need to continue browsing and purchasing from
your website smoothly. UX tools aid in every stage of the page
optimization process, from identifying where users are getting stuck to
conducting user research.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image287.webp"
  alt="Popular User Optimization tools include; Hotjar, UserTesting, TryMyUI, and UsabilityHub."
  style="width:500px;"/>
</p>

Some of the popular UX optimization tools include: Hotjar, UserTesting, 
TryMyUI, and UsabilityHub.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image288.webp"
  alt=""
  style="width:500px;"/>
</p>

Let&apos;s look at mobile optimization tools now. Mobile-first optimization
can help you ensure that users see your site properly on smartphones and
tablets, as more people use mobile devices than desktop computers to
browse the web. Pop-ups, image-heavy pages, and small texts can make
your website difficult to navigate on smartphones. Analyze your
analytics data to determine what percentage of your users and customers
browse on mobile devices, so you can determine how important mobile
optimization is to your business.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image289.webp"
  alt=""
  style="width:500px;"/>
</p>

Some of the popular mobile optimization tools include:

PageSpeed Insights Google Search Console Google Analytics, and
WebPageTest.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image290.webp"
  alt=""
  style="width:500px;"/>
</p>

Next, we will discuss web accessibility optimization tools. An
accessible website is simple to use for everyone, which is a win-win
situation for both you and your visitors: great UX for them and more
satisfied customers for you. Accessibility tools can show you how your
landing pages appear on a screen reader or to people with different
impairments (for example, different types of colorblindness). The tools
can also provide optimization recommendations to make your website more
inclusive.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image291.webp"
  alt=""
  style="width:500px;"/>
</p>

Some of the popular web accessibility optimization tools include: WAVE
EqualWeb, and Functional Accessibility Evaluator.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image292.webp"
  alt=""
  style="width:500px;"/>
</p>

Finally, let's talk about JavaScript optimization tools. If it is
discovered that the functionality is not being used by users, the best
practice is to remove it along with all associated JavaScript code sets.
This will reduce not only the transmission time but also the time the
browser takes to analyze and compile the code.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image293.webp"
  alt=""
  style="width:500px;"/>
</p>

Some of the popular JavaScript optimization tools include: JS Minifier
is a web-based tool to compress JavaScript code to make it as light as
possible. JSMIN is a popular JavaScript minifier that removes
unnecessary characters (such as spaces and tabs) and comments, reducing
the file size of your script. 

Flow, which is a static type of JavaScript
code checker that works hard to increase your productivity, making your
code faster, smarter, more confident, and more broadly applicable.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image294.webp"
  alt=""
  style="width:500px;"/>
</p>

ESLint, which is a linting tool that helps automatically check your code
for potential problems, and Optimize-js, which optimizes a JavaScript
file for faster initial execution and parsing by enclosing all functions
that are immediately invoked or are likely to be invoked in parentheses.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image295.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (25), you learned that:

-   Web optimization makes a website appealing to search engines and
    users.

-   It helps select an appropriate software tool for potential problems.

-   Page speed optimization tools assess the page speed and determine
    what is slowing it down.

-   UX optimization tools keep visitors engaged and reduce friction on
    websites.

-   Mobile optimization tools ensure that users see websites properly on
    smartphones and tablets.

-   Web accessibility optimization tools preview landing screens and
    provide optimized recommendations, and

-   JavaScript optimization tools remove unnecessary codes, which
    reduces the time required for browsers to analyze and compile code.

<h2 name="ch4-26">26. Testing Frameworks</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image296.webp"
  alt="4-26. Testing Frameworks"
  style="width:500px;"/>
</p>

Welcome to Testing Frameworks.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image297.webp"
  alt=""
  style="width:500px;"/>
</p>

After reading this module (26), you will be able to:

-   Define testing frameworks and their components,
<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>
-   List the key benefits of testing a framework, and

-   Identify the popular JavaScript testing frameworks.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image298.webp"
  alt=""
  style="width:500px;"/>
</p>

A testing framework is a set of rules or guidelines that can be used to
develop and design test cases. While a test automation framework is a
collection of components that make it easier to run tests and report on
test results. Coding standards, test-data handling methods, object
repositories, processes for storing test results, and information on how
to access external resources are all covered in the testing framework
guidelines.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image299.webp"
  alt=""
  style="width:500px;"/>
</p>

The JavaScript testing framework is a JS-based dynamic framework that is
well-known for its ease of use in front-end and back-end development.
Front-end testing is a method of testing the Graphical User Interface
(GUI), functionality, and usability of web applications or software. The
goal of front-end testing is to ensure that the presentation layer of
web applications or software is defect free with subsequent updates.

Front-end testing is also performed for: CSS Regression Testing for
minor CSS changes that break the front-end layout. JS file changes that
render the front-end unusable. and performance evaluations.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image300.webp"
  alt=""
  style="width:500px;"/>
</p>

Let&apos;s now explore the various components of a testing framework. Let's
first learn about testing data management. The most
challenging aspect of software testing automation is gathering data and
extracting useful information. The availability of data to conduct tests
is typically a major issue. A strategic approach to testing data
management is required to ensure the success of automation efforts.

Next, we will learn about testing libraries. A testing library is where
test cases are created and stored. Unit testing, integration testing,
end-to-end testing, and behavior-driven development are all examples of
testing libraries.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image301.webp"
  alt=""
  style="width:500px;"/>
</p>

Following that, we will learn about Integration testing. Testing units
in isolation is valuable and necessary, but you must also test the
integrations between both units, as well as between units and external
dependencies, if you want to ensure that your application works as
intended. 

Finally, let's learn about behavior-driven development (BBD).
BDD is not related to development. It's a collection of best practices.
BDD enables you to write great test cases when those practices are
applied to automation testing. It&apos;s written in an English-like language
that everyone can understand. It helps turn scenarios and expected
behavior features into code. BDD allows code to be aligned with the
intent and scope of automated tests.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image302.webp"
  alt=""
  style="width:500px;"/>
</p>

Let&apos;s look at some of the benefits of the testing framework.

The first benefit is that testing frameworks help to make the project more agile.
When you add a new feature, you may need to change the old code.
Changing previously tested code is both expensive and risky. Testing
frameworks assist you in running unit tests on new code to ensure that
it does not break any existing features. 

The next benefit is that it helps find bugs early. As a developer, you can 
use the testing framework to find and fix bugs on your own, which will 
improve code quality and make testing easier.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image303.webp"
  alt=""
  style="width:500px;"/>
</p>

Next, we will discuss how it helps with code integrity. The term code
integrity refers to achieving the results that the developer intended.
The results should also be repeatable in any scenario in which the code
or program is likely to be used. By automating the task of running tests
after code changes, testing frameworks reduce manual overhead.

Lastly, we will discuss how it helps with code optimization. The best
way to achieve the desired result is to use optimized code. Testing
assists developers in optimizing their code so that their program uses
fewer resources while still providing the necessary functionality.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image304.webp"
  alt=""
  style="width:500px;"/>
</p>

We will now learn about some of the popular JavaScript testing
frameworks. First, let's learn about Jest. The React development team
officially supports Jest. Jest is a JavaScript testing framework that
places an emphasis on simplicity. It is compatible with projects written
in Babel, TypeScript, Node, React, Angular, Vue, and other languages.

Next, we will learn about Playwright. Playwright is a web testing and
automation framework. It enables the testing of Chromium, Firefox, and
WebKit using a single API. Playwright is designed to enable
cross-browser web automation and automation that is always
up-to-date, reliable, and fast.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image305.webp"
  alt=""
  style="width:500px;"/>
</p>

The next framework is Mocha. Mocha is a feature-rich JavaScript test
framework that runs on Node.js and in the browser to make asynchronous
testing easy and fun. Mocha tests are executed sequentially, allowing
for flexible and accurate reporting while mapping undetected exceptions
to the appropriate test cases. 

Let's now look at Cypress. Cypress is a
JavaScript-based end-to-end testing framework built on Mocha that makes
asynchronous testing simple and easy. To pair with any JavaScript
testing framework, the Cypress testing library also employs a BDD/TDD
assertion library and a browser.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image306.webp"
  alt=""
  style="width:500px;"/>
</p>

The next JavaScript framework that we will discuss is Jasmine. Jasmine
is a behavior-driven development framework for JavaScript code testing.
It is independent of any other JavaScript framework. It does not require
the use of a DOM. It also has a clear syntax that makes it simple to
write tests. 

The last framework that we will discuss is Puppeteer.
Puppeteer is a Node.js library that allows you to control
Chrome/Chromium via the DevTools Protocol. Puppeteer is designed to run
in headless mode by default, but it can also be configured to run in
full (non-headless) Chrome/Chromium mode.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image307.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (26), you learned that:

-   A testing framework is a set of rules or guidelines that can be used
    to develop and design test cases,

-   JavaScript testing framework is dynamic and well-known for its ease
    of use in front-end and back-end development,

-   Components of a framework are a group of tools and processes that
    work together to support automated application testing,

-   Testing framework helps make the project agile, fixes bugs, and
    helps achieve code integrity and optimization, and

-   Some popular JavaScript testing frameworks are Jest, Playwright,
    Mocha, Cypress, Jasmine, and Puppeteer.

<h2 name="ch4-27">27. Testing Tools -- Mocha and Jasmine</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image308.webp"
  alt="4-27. Testing Tools -- Mocha and Jasmine"
  style="width:500px;"/>
</p>

Welcome to \"Testing Tools -- Mocha and Jasmine.\"

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image309.webp"
  alt=""
  style="width:500px;"/>
</p>

After reading this module (27), you'll be able to:

-   Define Mocha and Jasmine testing frameworks,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   List their advantages and disadvantages, and

-   Recognize the differences between the two frameworks.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image310.webp"
  alt=""
  style="width:500px;"/>
</p>

Mocha is a NodeJS-based open-source JavaScript testing framework. It
prioritizes core features and extensibility. Mocha tests are executed
sequentially, allowing for flexible and accurate reporting while mapping
uncaught exceptions to the appropriate test cases. Mocha allows you to
write structured code to thoroughly test your applications,
categorizing them into test suites and test cases.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image311.webp"
  alt=""
  style="width:500px;"/>
</p>

Mapping errors to corresponding test cases enables us to generate a test
report following the run. Mocha supports a wide range of test
interfaces, such as TSS, Exports, QUnit, and Require. The default
interface is a BDD interface, which aims to assist developers in
creating predictable and resilient to-change software rather than
error-prone software.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image312.webp"
  alt=""
  style="width:500px;"/>
</p>

Mocha is a simple and adaptable framework that works with any assertion
library. The most popular assertion libraries with Mocha are Chai,
Sinon, Express.js, and Should.js. Mocha provides the framework for
running your tests, whether they are low-level Unit tests against
back-end services or JavaScript functions or full-stack tests focused on
component integration. Mocha can be used to run any type of test within
describe functions by including code and assertions to determine a pass
or fail status. Mocha will report the test as failed if an assertion
fails.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image313.webp"
  alt=""
  style="width:500px;"/>
</p>

If a code throws an exception, it is marked as failed as well. It will
report a pass if everything runs smoothly and all assertions are valid.
Because of Node&apos;s asynchronous behavior, Mocha can also notify you if
your tests run too long.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image314.webp"
  alt=""
  style="width:500px;"/>
</p>

Let&apos;s take a look at some of the advantages of using the Mocha testing
framework. It encourages Test Driven Development (TDD) and Behavior
Driven Development (BDD). It runs tests serially, and the results are
always accurate. It can be configured to run test cases in the web
browser. It offers several ways to generate test reports and can even
create custom reports.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image315.webp"
  alt=""
  style="width:500px;"/>
</p>

It can be set up for either synchronous or asynchronous testing. It
includes a wide variety of plugins that can be used to extend your
framework. Following the test run, it highlights the slow-running tests.
It supports the retry failed tests feature, which allows you to
configure re-running failed tests.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image316.webp"
  alt=""
  style="width:500px;"/>
</p>

The following are some of Mocha&apos;s drawbacks. The developer must spend
time configuring the Mocha framework. Snapshot testing is not supported
by default; you must rely on external libraries. Despite having good
documentation, the search feature is not user-friendly. Since you need
to integrate different frameworks for assertions, the test scripts can
be confusing at times.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image317.webp"
  alt=""
  style="width:500px;"/>
</p>

Mocha is slow to release new features and support developer tools. Mocha
requires more configuration than other frameworks, making it less
flexible. In the case of Mocha, if you cannot afford flexibility, you
must explicitly select an assertion library. Mocha snapshot testing can
be challenging. To do it correctly, you&apos;ll need to use the
chai-jest-snapshot library.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image318.webp"
  alt=""
  style="width:500px;"/>
</p>

Jasmine is an open-source JavaScript framework that can test any
JavaScript application. Jasmine uses the BDD procedure to ensure that
each line of JavaScript code is unit tested. Instead of testing the
entire application, it offers a small syntax to test the smallest unit
of the application. It also includes utilities for running automated
tests on both synchronous and asynchronous code. Jasmine is tested in a
variety of browsers, including Safari, Chrome, Firefox, and Microsoft
Edge, as well as Node.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image319.webp"
  alt=""
  style="width:500px;"/>
</p>

Jasmine has many features, including: It&apos;s fast, has low overhead, and
has no external dependencies. It&apos;s a batteries-included library with
everything you need to test your code. It is available for both Node and
browser. It is compatible with other languages, such as Python and Ruby.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image320.webp"
  alt=""
  style="width:500px;"/>
</p>

It does not require the DOM. It has a clean and simple syntax as well as
a rich and straightforward API. We can describe the tests and the
expected results using natural language.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image321.webp"
  alt=""
  style="width:500px;"/>
</p>

The following are some of the advantages of using Jasmine: It has lower
overhead due to no external dependencies. It proceeds with nearly every
required tool by default. It maintains front-end and back-end tests
similarly.

The coding is pretty similar to writing in natural language.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image322.webp"
  alt=""
  style="width:500px;"/>
</p>

It provides wide documentation for use with a variety of frameworks. It
supports asynchronous testing. It marks the use of spies for applying
test doubles.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image323.webp"
  alt=""
  style="width:500px;"/>
</p>

Now, let&apos;s look at the main disadvantages of using Jasmine they are:
Asynchronous testing is difficult. All test files must have a specific
suffix.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image324.webp"
  alt=""
  style="width:500px;"/>
</p>

Now that we&apos;ve learned about the Mocha and Jasmine frameworks, let&apos;s
compare them. Jasmine includes an assertion library, whereas Mocha must
be combined with other assertion libraries. Jasmine and Mocha both have
command-line test runners. For reporting, Jasmine creates
karma-jasmine-html-reporter or jasmine-pretty-html-reporter, whereas
Mocha creates mocha-simple-html-reporter and mochawesome. Jasmine and
Mocha both have documentation and forum support.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image325.webp"
  alt=""
  style="width:500px;"/>
</p>

Jasmine does not include built-in support for rerunning a failed test,
whereas Mocha does. Slow tests can be highlighted in Jasmine using
jasmine-slow-reporter, whereas Mocha has built-in support. Asynchronous
testing is challenging in Jasmine but simple in Mocha. Jasmine and Mocha
both support parallel execution. Jasmine&apos;s plug-in support and
extensibility are limited, whereas Mocha&apos;s are good.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image326.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (27), you learned that:

-   Mocha is a NodeJS-based open-source JavaScript testing framework,

-   It is compatible with assertion libraries like Chai, Sinon,
    Express.js, and Should.js,

-   It uses code and assertions to determine a pass or fail status,

-   Jasmine is an open-source JavaScript framework that can test any
    JavaScript application,

-   It is fast, has low overhead, has no external dependencies, and

-   Slow tests can be highlighted in Jasmine using
    jasmine-slow-reporter, whereas Mocha has it built-in.

<h2 name="ch4-28">28. Using Jasmine</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image327.webp"
  alt="4-28. Using Jasmine"
  style="width:500px;"/>
</p>

Welcome to Using Jasmine!

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image328.webp"
  alt="Define Jasmine and it's fundamental concepts, and identify the steps to test code and React with Jasmine."
  style="width:500px;"/>
</p>

After reading this module (28), you will be able to:

-   Define Jasmine and its fundamental concepts, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify the steps to test code and React with Jasmine.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image329.webp"
  alt="Jasmine: Open-source framework for unit testing JavaScript."
  style="width:500px;"/>
</p>

Jasmine is an open-source framework for unit testing JavaScript that is
readily accessible in a variety of formats, including stand-alone, ruby
gem, Node.js, and so on. It is simple to set up and easy to write tests.
JS Spec, Rspec, and Jspec have a significant impact on Jasmine. It makes
an attempt to describe tests in a human-readable format so that
non-technical people understand what is being tested.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image330.webp"
  alt="Jasmine suite is a collection of test cases used to verify the behavior of a JS object or function."
  style="width:500px;"/>
</p>

Let's look at the fundamental concepts of Jasmine. A Jasmine suite is a
collection of test cases that can be used to verify the behavior of a
JavaScript object or function. This starts with a call to the Jasmine
global function, which has two parameters: the first is the title of the
test suite, and the second is a function that implements the test suite.
A Jasmine spec is a test case within a test suite. This begins with a
call to the Jasmine global function with two parameters: the first is
the title of the spec, and the second is a function that implements the
test case. The spec includes one or more expectations. Each expectation
represents a statement that can be true or false. To pass the spec, all
of the expectations within the spec must be met. If one or more
expectations within a spec are incorrect, the spec fails.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image331.webp"
  alt="Jasmine: Expectation is an assertion that is True or False."
  style="width:500px;"/>
</p>

In Jasmine, an expectation is an assertion that is either true or false.
Expectations are described as \"expect\" within the function that takes
a value, which is referred to as the \"toBe\" value. Matchers is a
comparison between the actual value and the expected value, either if
the expectation is \"true\" or \"false."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image332.webp"
  alt="Jasmine: Describe function is used to group related specs."
  style="width:500px;"/>
</p>

The describe function in Jasmine is used to group related specs. The
string parameter is used to name the collection of specs and will be
integrated with specs to form the full name of a spec. This helps in
locating specs in a large suite. Jasmine has spies, which are test
double functions. A spy can stub any function and track all calls and
arguments to it. A spy exists only in the describe or it block in which
it is defined and is removed after each spec. Spies are mocks. Mocks are
objects that are created to represent or mimic the real thing. Mocks are
required to avoid the overhead cost of creating the actual object they
represent.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image333.webp"
  alt="Steps to begin testing in Jasmine."
  style="width:500px;"/>
</p>

The steps to begin testing with Jasmine are as follows. Download Jasmine
(standalone version). Give Jasmine access to your code by manually
downloading it or using a package manager. Initialize Jasmine. Create a
spec (test) file, and Make the source code available to your spec file.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image334.webp"
  alt="Steps for testing React with Jasmine."
  style="width:500px;"/>
</p>

Let us now try to understand the steps for testing React with Jasmine.
First, install and set up Jasmine. Next, set up React with add-ons.
Depending on your React version and environment, you will either need to
use a version of React that includes add-ons or the
react-addons-test-utils npm package. In either case, the version of
React that Jasmine runs must be included in the JS bundle.

The next step is to leverage Test Utils. ReactTestUtils makes it simple
to test React components in your preferred testing framework.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image335.webp"
  alt="Structure of a React test in Jasmine."
  style="width:500px;"/>
</p>

Then, in Jasmine, learn the structure of a React test. There is a
specific sequence of calls that must be made in order to render and test
a full instance of your component.

Discover how to use new matchers and utilities. Finally, as needed, add
new React test utils methods and Jasmine matchers. You don&apos;t have to be
familiar with every matcher and method in the React test utilities.

After you&apos;ve mastered the basics of writing unit tests, you can move on
to using React event simulation and Jasmine spies to see what happens
when users interact with your components.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image336.webp"
  alt="Module 28 - Jasmine summary."
  style="width:500px;"/>
</p>

In this module (28), you learned that:

-   Jasmine is an open-source framework for unit testing JavaScript.

-   It is accessible in a variety of formats, including stand-alone,
    ruby gem, and Node.js.

-   The fundamental concepts of Jasmine are suite, spec, matchers,
    expectations, describe functions, and spies, and

-   There are five steps to testing codes and React with Jasmine.

<h2 name="ch4-29">29. Front-end Testing Best Practices</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image337.webp"
  alt="4-29. Front-end Testing Best Practices"
  style="width:500px;"/>
</p>

Welcome to \"Front-end Testing Best Practices.\"

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image338.webp"
  alt="Define front-end testing and its advantages, identify aspect, list best practices."
  style="width:500px;"/>
</p>

After reading this module (29), you will be able to:

-   Define front-end testing and its advantages,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify what aspect of an application&apos;s front end should be
    tested, and

-   List some of the best front-end testing practices.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image339.webp"
  alt="What is front-end testing?  Test usability and functioning of an app's GUI, 
  validate menus, forms, buttons and other app elements visible to users, and consists 
  of 3-tier architecture containing clients, servers, and information systems."
  style="width:500px;"/>
</p>

The front end of a program is the client-side section. Front-end testing
is the process of testing the usability and functionality of an
application&apos;s graphical user interface (GUI). This usually includes
validating menus, forms, buttons, and other application elements visible
to end users. Every web application is built with a three-tier
architecture. Clients, servers, and information systems or resources are
all included. The client is part of the presentation layer. This layer
is tested by front-end testers.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image340.webp"
  alt="Advantages of front-end testing; provides accurate interactions, offers accessibility to all users."
  style="width:500px;"/>
</p>

We will now discuss some of the advantages of using front-end testing.
First, an app should provide accurate interaction. It should be fast and
error-free, regardless of the device or browser used. Front-end testers
perform the test using a variety of devices and browsers. They declare
an app error-free only if it meets all the testing criteria. Next, your
HTML code must adhere to certain standards, and your website should be
accessible to all users, particularly those with disabilities.
Accessibility testing is a required component of front-end testing and
must be completed prior to the deployment of a website.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image341.webp"
  alt="Front-end testing ensures consistent behavior and protects application from regression."
  style="width:500px;"/>
</p>

With the widespread use of interconnected versions of an app on
different devices such as a smartwatch, smartphone, and smart TV,
front-end testing helps ensure consistent behavior of the app across the
multitier architecture. Front-end tests also protect your app from
regression. There may be times when you write code to deploy large or
complex features, but it crashes another part of the application that
you were unaware of. Front-end testing ensures that the code is
consistent and that the front-end functionality is intact.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image342.webp"
  alt="Front-end testing fixes bugs and keeps well-maintained test codes."
  style="width:500px;"/>
</p>

Next, if a bug is discovered, whether by your team or by users, you need
to fix it and prevent its recurrence unexpectedly by adding an
additional test suite through front-end testing. Finally, a thorough
explanation of the test&apos;s functionality is necessary when writing
tests. Front-end testing helps in keeping well-maintained tests which is
beneficial as they serve as live documentation.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image343.webp"
  alt="What should be tested in front-end testing? Cross-broser &amp; platform 
  functionality, accessibility, and end-to-end checks."
  style="width:500px;"/>
</p>

Let us now try to understand which aspects of an application&apos;s front
end you need to focus on while performing front-end testing. When
testing cross-browser and cross-platform functionality, you should look
at your app&apos;s features and its responsiveness across different
browsers, platforms, and devices. Accessibility checks help you
determine whether everyone, including those with visual or auditory
impairments, can use the application. End-to-end checks are required for
checking and confirming the application&apos;s back-end to front-end
workflow by simulating real-world actions that users are likely to take.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image344.webp"
  alt="Additional tests; image analysis testing and Cascade Style Sheet (CSS) testing."
  style="width:500px;"/>
</p>

Image analysis testing is performed to determine where you can
optimize the images to help the app run faster. Most websites and apps
these days have a large number of images, which significantly increases
the size of the application. CSS testing ensures the performance of two
important CSS elements: syntax and display. While syntax is more of a
developer&apos;s day-to-day responsibility, displayed views must be tested
for regression after changes to specific parts of the app.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image345.webp"
  alt="Best practices of front-end testing"
  style="width:500px;"/>
</p>

Now we&apos;ll explore some of the best front-end testing practices. These
include: Focusing on front-end elements, using actual browsers and
devices, Performing deterministic tests, striving for coverage and not
100% code coverage, Encouraging shorter and more readable unit tests,
Keeping tests independent, and Testing a variety of input parameters.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image346.webp"
  alt="Focus on front-end elements.  Use actual browsers and devices."
  style="width:500px;"/>
</p>

Let us now discuss each in detail. Focusing on front-end elements
Front-end testing involves examining and validating hundreds or
thousands of UI and functional elements. Before moving on to graphics
and pop-ups, it&apos;s a good idea to test the page load speed, basic text,
images, and essential functions. Using actual browsers and devices Use
real browsers and devices instead of emulators and simulators to save
time and money and enhance the reliability of your software testing
results.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image347.webp"
  alt="Perform deterministic tests. Striving for coverage and not 100% code coverage."
  style="width:500px;"/>
</p>

Performing deterministic tests Deterministic tests are the ones that can
be repeated. They produce the same results every time a specific code is
executed. A non-deterministic test passes and fails randomly.
Non-deterministic tests can be handled in a variety of ways, including
polling, fake timers, and mocks. Striving for coverage and not 100% code
coverage In theory, complete test coverage sounds like a great idea.
However, it doesn&apos;t work in practice. A high level of test coverage
provides a false sense of security. Good tests are simple to maintain
and provide you with the confidence to make changes to your code.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image348.webp"
  alt="Encouraging shorter and more readable unit tests. Keep test independent. Test a variety of
  input parameters."
  style="width:500px;"/>
</p>

Encouraging shorter and more readable unit tests.  A unit test should only
test a single unit of code. If there is only one reason for the test to
fail, less time is spent determining the root cause of the test's
failure. Keeping tests independent the outcome of one test should have
no impact on the results of any other tests. Sharing state or mock
instances between tests may result in brittle or \"flaky\" tests that
pass incorrectly. Testing a variety of input parameters Tests should
validate all possible code paths through the code under test. You must
be confident that the deployed code can handle the full range of inputs
that a user may enter.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image349.webp"
  alt="Common best and most used front-end testing tools."
  style="width:500px;"/>
</p>

There are numerous vendors offering front-end testing tools, making it
difficult to decide which one to use. For your convenience, here is a
list of some of the best and most widely used front-end testing tools.
Jest, Selenium WebDriver, Cypress, WebDriverIO, WebDriverJS, and
Jasmine.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image350.webp"
  alt="Module 29 educates you on Front-end testing and tools."
  style="width:500px;"/>
</p>

In this module (29), you learned that:

-   Front-end testing is the process of testing the usability and
    functionality of an application&apos;s GUI,

-   It validates menus, forms, buttons, and other app elements visible
    to users,

-   It provides accurate interactions, offers accessibility, ensures
    consistent behavior and others,

-   There are certain aspects of an application&apos;s front end that need
    to be focused on while performing front-end testing, and

-   Front-end testing tools ensure proper functionality of critical
    elements of a web page.

# Hands-on Lab: Testing a React Application using Jasmine

## Welcome to the **Testing a React Application using Jasmine** lab! 

In this lab, you will learn how to test your logic in React with
Jasmine.

Skills Network Labs (SN Labs) is a virtual lab environment used in this
course. Upon clicking \"Open Tool\" in accordance with IBM Skills
Network Privacy policy your Username and Email will be passed to Skills
Network Labs and will only be used for communicating important
information to enhance your learning experience.

In case you need to download the lab instructions click
[HERE](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-WD0231EN-SkillsNetwork/labs/jasmine.md.html)
to open in a new tab.

This course uses a third-party app, Hands-on Lab: Testing a React
Application using Jasmine, to enhance your learning experience. The app
will reference basic information like your name, email, and Coursera ID.

# Week 4 Summary: Cross-Browser JavaScript Optimization and Testing Frameworks

In this module, you learned that:

-   Web optimization makes a website appealing to search engines and
    users.

-   JavaScript produces highly interactive websites that actively engage
    the user.

-   A testing framework is a set of rules or guidelines to develop and
    design test cases.

-   Testing frameworks helps make the project agile, fixes bugs, and
    helps achieve code integrity and optimization.

-   Mocha is a NodeJS-based open-source JavaScript testing framework
    that is compatible with various assertion libraries.

-   Jasmine is an open-source JavaScript framework that can test any
    JavaScript application. 

-   Jasmine is accessible in a variety of formats, including
    stand-alone, ruby gem, and Node.js.

-   Front-end testing is the process of testing the usability and
    functionality of an application&apos;s GUI.

-   Front-end testing tools ensure proper functionality of the critical
    elements of a web page.

<!-- # [Week 5:]{.mark} -->

<h1 name="ch5">WEEK 5</h1>

<h2 name="ch5-30">30. JavaScript Debugging</h2>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image351.webp"
  style="width:500px;"
  alt="5-30. JavaScript Debugging" />
</p>

Welcome to "JavaScript Debugging."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image352.webp"
  alt="Module 30; describe debugging, process of debugging, benefits and common bugs."
  style="width:500px;"/>
</p>

After reading this module (30), you will be able to:

-   Describe debugging,

-   Describe the process of debugging JavaScript,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Explain the benefits of debugging, and

-   Identify some common JavaScript bugs.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image353.webp"
  alt=""
  style="width:500px;"/>
</p>

Errors are common while writing programs. These errors or flaws are
bugs. If your JavaScript does not function the way you want it to, there
is a high possibility that you have a bug in your code. Therefore, we
use debugging, which identifies and fixes bugs in your code.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image354.webp"
  alt=""
  style="width:500px;"/>
</p>

In computer programming and engineering, debugging is essential to
software development. It is necessary to remove bugs that occur
accidentally or unexpectedly in software applications. Tightly coupled
modules can make debugging difficult at times. In this case, changing
one module can cause more bugs to appear in another. There can be more
challenges involved in debugging such a program, than coding a single
program.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image355.webp"
  alt=""
  style="width:500px;"/>
</p>

Let&apos;s try to understand why bugs occur in JavaScript. If your script
isn&apos;t working, first check the punctuation. Ensure there is a closing
bracket for every opening bracket. Second, check the character string.
Always enclose the text in quotation marks when working on JavaScript.
You can either use single or double quotation marks to enclose the text.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image356.webp"
  alt=""
  style="width:500px;"/>
</p>

Now that you know why bugs occur in JavaScript and how to prevent them,
let's explore the debugging process. Debugging JavaScript in a
production environment can be challenging as the error reports are
sometimes vague, and identifying the underlying causes can be difficult.
Nevertheless, identifying and fixing bugs can be done by following a few
steps. These are:

-   Attempting to replicate the bug,

-   Hypothesis testing,

-   Increasing the number of logging-of statements, and

-   Adjusting test scenarios and trying again.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image357.webp"
  alt=""
  style="width:500px;"/>
</p>

Let's discuss each step in detail. The first step in debugging is to
replicate the circumstances. In most programming languages, it is
facilitated by reviewing logs preceding an error. If you have access to
production logs, you must establish some testing guidelines before
replicating any circumstances of an issue. The operating system,
production database, and user accounts are all replicated in this
process. After identifying the conditions, you believe will result in
the exception or error you&apos;re looking for, you must put them to the
test. Development and staging environments are breakable without
affecting end users, therefore, you should always try to break your code
in a safe environment.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image358.webp"
  alt=""
  style="width:500px;"/>
</p>

Next, you need to log more data to diagnose the problem. You can observe
everything before and after the issue arises. The issues you are facing
likely have possible warnings attached to them, which don&apos;t always
appear in the logs by default. Every error is difficult to reproduce,
and replicating them in a non-production environment can be difficult
due to time constraints or other factors. Return to the first step and
try it all over again.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image359.webp"
  alt=""
  style="width:500px;"/>
</p>

Now that you know how to debug JavaScript errors, let's discuss the
importance of debugging. Errors can occur while writing codes, and it is
important to fix the errors. Debugging helps by breaking down complex
problems into smaller ones and expediting the process of writing codes
for the software. While implementing the code, avoid making any
syntactic or other types of errors. The process continues in stages,
combining the code with other programming units to form a software
product. Debugging allows you to stop your code when it reaches a point
where you suspect a logic or implementation problem and investigate
whether it is doing what you expected. You can achieve the same result
by including printouts in your code.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image360.webp"
  alt=""
  style="width:500px;"/>
</p>

Debugging offers various benefits. It immediately reports an error
condition. As a result, the error is found early, ensuring the software
development process is less stressful. It provides critical information
about data structures and facilitates interpretation. It helps the
developer reduce unnecessary and distracting information. It allows the
developer to avoid writing complex one-time testing codes, saving time
and energy required for software development.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image361.webp"
  alt=""
  style="width:500px;"/>
</p>

Let's explore some reasons for JavaScript bugs in your code. These
include: Incorrect data types, Incorrect use of assignment operators,
Incorrect use of quotation marks, Incorrect use of brackets, Incorrect
Indexing, Misspelling of function and variable names, and Incorrect use
of variable assignment. Let's discuss each reason in detail.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image362.webp"
  alt=""
  style="width:500px;"/>
</p>

The interaction of variables of different types can result in many bugs
in your code. For example, if you use a string with a number. It is
important to check the places where the equal sign is used instead of an
equality operator because it is an assignment operator in JavaScript. In
contrast, the double and the triple equal signs check if values are
equal. In JavaScript, you can use different quotation marks to enclose
quotation marks within quotation marks. You may face issues if you use
double quotations.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image363.webp"
  alt=""
  style="width:500px;"/>
</p>

Another error that we see quite often is the incorrect use of brackets.
There must be an opening bracket and a closing bracket for the script.
JavaScript employs base zero indexing. You can obtain the first value of
an array by using index zero. As the result is off by one, this
frequently results in an \"index out of range\" reference error in
JavaScript.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image364.webp"
  alt=""
  style="width:500px;"/>
</p>

Missing letters and wrong capitalization also lead to bugs in the code.
Coders can use code editors to reduce misspelled function names and
variables. Global variables are created outside and can be used
everywhere, in contrast to local variables, created inside a function to
be utilized by the function. The distinction between global and local
variables is that creating global variables is outside. Its usage can be
everywhere, whereas local variables are created inside a function. Its
usage is by function.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image365.webp"
  alt=""
  style="width:500px;"/>
</p>

In this module (30), you learned about:

-   Debugging is an essential part of the software development process,

-   A few steps are used to recognize and fix bugs,

-   Debugging has many benefits, and

-   You can encounter JavaScript bugs in your code due to some factors.

<h2 name="ch5-31">31. Basic Debugging Concepts</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image366.webp"
  alt="5-31. Basic Debugging Concepts"
  style="width:500px;"/>
</p>

Welcome to "Basic Debugging Concepts."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image367.webp"
  alt="Module 31: Describe debugging strategies, identify types of bugs, and explain terminologies used in debugging."
  style="width:500px;"/>
</p>

After reading this module (31), you will be able to:

-   Describe debugging strategies,

-   Identify the types of bugs, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Explain the terminologies used in debugging.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image368.webp"
  alt="Introduction to debugging."
  style="width:500px;"/>
</p>

If your program does not generate the desired output, there is a high
possibility that your code contains errors. This is why debugging is a
crucial step in the software development process, as it identifies and
fixes bugs. A major part of the debugging process involves identifying
the cause based on the symptoms.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image369.webp"
  alt="Debugging strategies: 9 useful strategies."
  style="width:500px;"/>
</p>

Different strategies can be employed to localize the error, as there is
no best method for doing it. Each strategy is suited to a different
situation; therefore, it is beneficial to be aware of these strategies.
Some of these include: Incremental development, Debuggers, Binary
search, Instrumentation, Assertions, Backtracking, Simplify,
Error-finding tools, and Hypotheses.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image370.webp"
  alt="Debugging strategies: Incremental development and Debuggers."
  style="width:500px;"/>
</p>

Let's review each of them in detail. In this strategy, the program is
developed progressively, with frequent testing performed as each new
piece of code is added. As the final chunk of code is small in
incrementally developed programs, the search for bugs is constrained to
small code fragments. As a result, there are fewer errors, and the
programmer is not burdened with long lists of errors. This strategy
involves providing all the necessary run-time information without
generating voluminous difficult-to-read log files by observing program
expressions, setting program breakpoints, and analyzing the memory
content at selected points during execution.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image371.webp"
  alt="Debugging strategies: Binary search and Instrumentation."
  style="width:500px;"/>
</p>

This strategy places a check halfway through a large piece of code.

If the error does not appear at that point, the bug is in the second
half. As a result, the amount of code that must be inspected reduces by
half. The process quickly leads to the actual problem if repeated. This
strategy involves inserting print statements. Although printed
information is useful in some cases, it can be challenging to examine
when the amount of information grows significantly. In this case,
automated scripts can be used to sort through the data and provide
pertinent portions in a more concise style.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image372.webp"
  alt="Debugging strategies: Assertions and Backtracking."
  style="width:500px;"/>
</p>

This strategy is used to verify that the program maintains the
properties or invariants on which your code is based. The point at which
the program terminates is likely to be much closer to the cause and a
good indicator of what the issue is, as the program terminates as soon
as an assertion fails.

The next strategy is backtracking. This involves starting at the
problem&apos;s origin and working your way back through the code to
determine how it occurred.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image373.webp"
  alt="Debugging strategies: Simplify and Error finding tools."
  style="width:500px;"/>
</p>

This strategy involves removing the sections of the code irrelevant to
the bug and simplifying the code in the body of the buggy function. As
the process continues, the code becomes increasingly simpler. The bug
will eventually be discovered. Data can also be simplified using a
similar method. If the input data is too big, continuously remove parts
of it to check if the bug still exists. Here, programmers can quickly
identify violations of particular classes of errors using error-finding
tools. For example, tools that check safety properties. Error-finding
tools use either static analysis or dynamic analysis.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image374.webp"
  alt="Debugging strategies: Hypotheses."
  style="width:500px;"/>
</p>

This strategy involves a few steps. First, review the test case results.
Next, develop a hypothesis that fits the data, and then create and
execute a simple test to refute the hypothesis. If the hypothesis is
rejected, generate another one and repeat the process. Finding the
simplest hypotheses and associated test cases is an effective strategy.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image375.webp"
  alt="Type of bugs: Types of erros one may experience; Type errors, Minor errors, Implementation errors, and Conceptual errors."
  style="width:500px;"/>
</p>

Let's now explore different types of bugs. A program may contain bugs
even after meticulous planning and defensive programming. There are
different types of errors that one may experience. These are: Type
errors, Minor errors, Implementation errors, and Conceptual errors.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image376.webp"
  alt="Types of bugs: Type erros and Minor errors."
  style="width:500px;"/>
</p>

Let's discuss each type of error in detail. The compiler always detects
and reports such errors via error messages. An error message typically
includes information about the root cause of the error, such as the
incorrect piece of code, the line number, and an explanation. These
notifications typically provide sufficient details of the nature of the
issue and what needs to be done. Errors such as typos or other simple
errors may escape detection by the type checker or other compiler
checks. These are simple to fix after they are identified.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image377.webp"
  alt="Types of bugs: Implementation erros and Conceptual errors."
  style="width:500px;"/>
</p>

While a program&apos;s high-level algorithm may follow the correct logic,
some low-level, tangible data structures may be mishandled, violating
certain internal representation invariants. This can lead to
implementation errors. The programmer must reconsider the algorithm if
it has logical errors. Fixing such issues is more challenging,
particularly if the program only fails in a small number of corner
cases. One must carefully consider the algorithm and attempt to develop
a justification for its effectiveness. If the algorithm is too complex,
it may be better to redo it from scratch and create a cleaner design.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image378.webp"
  alt="Summary Debugging terminologies; Application log, Debugger, Stepping, Stack, Breakpoints, and Current line."
  style="width:500px;"/>
</p>

Let's now discuss some important terminologies used in debugging. These
are: Application log, Debugger, Stepping, Stack, Breakpoints, and
Current Line.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image379.webp"
  alt="Debugging terminologies; Application log, Debugger."
  style="width:500px;"/>
</p>

It's a passage of text that describes an action that occurs in an
application. Logs are important to verify what the program did right
before an issue occurred so that we can learn more about the bug. We can
use the console log in JavaScript to debug using logs. A debugger is a
program that programmers use to test and debug a target program. It
allows the investigation of objects in a more flexible manner by going
through the code line by line. To accomplish this, simply add the line
debugger to the script. The browser pauses execution on that line and
displays the source of the code currently being executed if the
developer tools console is opened. The browser will now provide
debugging methods and tools for debugging.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image380.webp"
  alt="Debugging terminologies; Stepping and Stack."
  style="width:500px;"/>
</p>

The action of telling the debugger to run through the program one line
at a time is called stepping. A computer program comprises of many small
steps that are integrated together. There can be a possibility that one
of these steps is incorrect. A \"stack\" of functions is created as your
program enters more and more \"functions.\" For your software, this
serves as a \"trail\" of function calls. This allows you to see how
"calling" one function affects the "current" function.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image381.webp"
  alt="Debugging terminologies; Breakpoints and Current line."
  style="width:500px;"/>
</p>

Breakpoints instruct the debugger where to \"stop\" your program&apos;s
execution so that you can see what&apos;s happening. This enables you to
access the proper location in your application quickly rather than going
through the entire program. Computers can only perform one task at a
time. As a result, computers follow the concept of the \"current line\"
when running your program. The control of the program typically flows
from the current line to the next line down the screen, to the following
line, and so on.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image382.webp"
  alt="Summary module 31; Debugging strategies, Types of errors, and Important debugging terminologies."
  style="width:500px;"/>
</p>

In this module (31), you learned about:

-   Debugging strategies used to localize an error,

-   Types of errors that one can experience while programming, and

-   Important debugging terminologies.

<h2 name="ch5-32">32. Introduction to Debugging Tools</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image383.webp"
  alt="5-32. Introduction to Debugging Tools"
  style="width:500px;"/>
</p>

Welcome to "Introduction to Debugging Tools."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image384.webp"
  alt="Summary module 32; Explain web development tools, Describe debugging tools, and Identify a few common debugging tools."
  style="width:500px;"/>
</p>

After reading this module (32), you will be able to:

-   Explain web development tools,

-   Describe debugging tools, and

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Identify a few common debugging tools.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image385.webp"
  alt="Introduction to web development tools."
  style="width:500px;"/>
</p>

Browsers today are equipped with a variety of web development tools
referred to as add-ons or extensions. These are commonly used for web
development as well as a variety of other tasks, debugging being one of
the most important. These tools simplify your work by analyzing
potential issues with CSS, HTML, and JavaScript used in the code.

In this module, we will

-   Discuss some browser debugging tools which can help you not only
    debug and analyze your code but also inspect HTTP headers,

-   Gain access to other FTP source files, and

-   Assess a web page&apos;s accessibility.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image386.webp"
  alt="What a debugging tool does."
  style="width:500px;"/>
</p>

A debugging tool is a software program that enables you to debug a
program without having to recompile it or modify its source code.
Programmers use debugging tools to deal with programming errors or to
make changes before a program is released. These tools enable them to
attempt a fix without changing the source code. Debugging tools can also
be used for troubleshooting issues with other applications, such as web
browsers and operating systems.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image387.webp"
  alt="Common debugging tools."
  style="width:500px;"/>
</p>

Some of the common debugging tools include Chrome Developer Tools,
Firefox developer tools, Safari Develop Menu, React Developer Tools,
console debugging, and Integrated Development Environment (IDE)/Visual
Studio Code.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image388.webp"
  alt="Chrome developer tools built directly into the Chrome browser."
  style="width:500px;"/>
</p>

Let's discuss each in detail. Chrome developer tools are a set of tools
for web developers which is built directly into the Chrome browser.
Which allows you to debug your JavaScript code quickly. Many developers
rely on these tools, which are the best in the industry. The default
JavaScript console is included in Chrome developer tools, along with
tools for network and performance monitoring and security features. The
Console and Network activity tabs are where most JavaScript debugging
happens.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image389.webp"
  alt="Keyboard shortcuts to open console in Google Chrome."
  style="width:500px;"/>
</p>

The keyboard shortcuts mentioned here can be used to open the developer
console in Google Chrome: macOS \`CMD\`+\`OPT\`+\`I\` Windows
\`CTRL\`+\`SHIFT\`+\`I\`

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image390.webp"
  alt="Firefox developer tools."
  style="width:500px;"/>
</p>

In the past, Firefox users relied on Firebug, an extension that provided
them with a set of competitive developer tools. The functionality of
firebug was incorporated into the Firefox Developer Tools available in
the latest versions of Firefox. This put Google Chrome and the Firefox
browser's integrated toolkit on an equal level.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image391.webp"
  alt="Steps to access the Firefox developer tools in Mozilla Firefox."
  style="width:500px;"/>
</p>

To access the developer tools in Mozilla Firefox, open the browser,
click the Firefox menu in the upper right corner, and click \"More
Tools.\" Next, select \"Web Developer Tools.\" Finally, click
\"Console.\"

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image392.webp"
  alt="Safari develop menu."
  style="width:500px;"/>
</p>

There are options in the Develop menu to display the JavaScript console,
a network, a debugger, a page element inspector, and a network traffic
monitor. The JavaScript debugging tools provided by Chrome are
comparable to the developer tools in Safari. All browser developer tools
are progressively getting better as they become better equipped to
fulfill developers&apos; demands.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image393.webp"
  alt="Safari develop menu - steps to enable."
  style="width:500px;"/>
</p>

To utilize Safari's built-in developer tools, users must enable the
Safari Develop menu. - First click the \"Safari\" tab and then click
\"Settings.\" - Next, click \"Advanced.\" - Finally, select \"Show
Develop menu in the menu bar.\" The Develop menu will appear in the menu
bar.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image394.webp"
  alt="React developer tools: Is a chrome DevTools extension and Displays props and stats 
  values for any element you click."
  style="width:500px;"/>
</p>

React Developer Tools, an extension of Chrome DevTools, is a great
source of help if you need to inspect the props or state values in your
React-built application. If you visit a website created using React
after adding the extension, a React tab will be added to the developer
console, displaying properties and state values for any element you
click.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image395.webp"
  alt="Console debugging: most common."
  style="width:500px;"/>
</p>

This is the most commonly used JavaScript console method. Error handling
or throwing are not done using this method. Instead, it is employed to
print statements in the console. There is console.log() which is the
most common one you&apos;ll see.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image396.webp"
  alt="IDE/Visual studio code (microsoft POS)."
  style="width:500px;"/>
</p>

When debugging Java applications, you do not always need to use an IDE.
Visual Studio Code, Microsoft&apos;s cross-platform source code editor, also
supports Java debugging via a simple debugger for Java extensions.
Visual studio code is an excellent option if you already use it for
development and require a compact and user-friendly Java debugging tool.
Visual Studio Code provides sufficient features for a quick debugging
session of your Java application despite all the complex debugging
features that IDE's debuggers provide.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image397.webp"
  alt="In this module (32), you learned that browsers are equipped with a variety of web dev tools, among others."
  style="width:500px;"/>
</p>

In this module (32), you learned that:

-   Browsers are equipped with a variety of web development tools
    referred to as add-ons or extensions,

-   Debugging tool is a software program that enables you to debug a
    program, and

-   There are some common debugging tools used by developers.

<h2 name="ch5-33">33. Troubleshooting with Chrome DevTools</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image398.webp"
  alt="5-33. Troubleshooting with Chrome DevTools"
  style="width:500px;"/>
</p>

Welcome to Troubleshooting with Chrome DevTools!

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image399.webp"
  alt="Summary module 33; Define/describe DevTools and how to access some of the panels' features."
  style="width:500px;"/>
</p>

After reading this module (33), you will be able to:

-   Describe Chrome DevTools and its various panels, and

-   Determine how to access some of the panels&apos; features.
<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image400.webp"
  alt="Chrome DevTools; Edit codes, add breakpoints, and debug code quickly."
  style="width:500px;"/>
</p>

Explain how to use Chrome DevTools to debug HTML and CSS The Google
Chrome browser includes built-in developer tools, also known
as DevTools, that allow developers to edit code directly in the browser,
add breakpoints to detect issues, and debug their code quickly.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image401.webp"
  alt="Chrome DevTools panels; Elements, Console, Sources, Network, Performance, and six more."
  style="width:500px;"/>
</p>

There are eleven panels in the DevTools UI. Here&apos;s a quick listing of
what each panel oversees.

Elements: Examine and modify DOM nodes and style attributes.

Console: View and execute JavaScript code.

Sources: Debug JavaScript, set breakpoints, and so on.

Network: Monitor and troubleshoot network-related activities.
Performance: Evaluate speed and optimization Memory: Monitor memory
usage and resolve any issues that arise. Application: Examine local
Storage, session Storage, cookies, Index DB, and so on. Security: Debug
certificate issues and other security concerns Lighthouse: Examine the
app&apos;s quality, performance, accessibility, SEO, and so on. Recorder
panel: Helps you can record the checkout flow once and measure it
regularly Performance Insights panel: Highlights the key insights in the
Insights pane, with actionable feedback on how to fix issues.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image402.webp"
  alt="How to access Chrome DevTools."
  style="width:500px;"/>
</p>

Let&apos;s first try to understand how to access Chrome DevTools. To access
Chrome DevTools: Right-click on any website and select \"inspect." The
DevTools will open the Elements panel and highlight the selected DOM
element. To open the console panel, use the keyboard shortcut CMD +
Option + J on Mac or CTRL + SHIFT + J on Windows.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image403.webp"
  alt="How to access elements panel, right-click, element panel, highlighted in the DOM tree."
  style="width:500px;"/>
</p>

Let&apos;s now learn how to access the elements panel. To access the
elements panel: Right-click any element on the page and select
\"inspect\" or Click on the elements panel inside Chrome DevTools. That
element should now be highlighted in the DOM tree.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image404.webp"
  alt="How to access elements panel, Hover and click."
  style="width:500px;"/>
</p>

To select another element on the page: Hover over an element on the page
and Click once on the highlighted area that corresponds to the element
you want to inspect.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image405.webp"
  alt="Editing HTML."
  style="width:500px;"/>
</p>

Now that we know how to access the Elements panel let&apos;s look at how to
use it to edit HTML and CSS. We will first look at how to edit HTML.
When you right-click on an element and choose \"Edit as HTML,\" you are
presented with a text field in which you can fully edit the HTML content
that comprises that element. This is useful if you want to change the
behavior of an element by adding or removing HTML elements inside or
around any element on the page.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image406.webp"
  alt="More Editing HTML and CSS."
  style="width:500px;"/>
</p>

Since these changes aren&apos;t saved in your application&apos;s source code,
they&apos;re ideal for quickly testing a new HTML structure without adding
and deleting these elements in your code. Simply refreshing the page
allows you to edit the same component multiple times. You can easily
delete and reorder elements in addition to editing them.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image407.webp"
  alt="Editing CSS."
  style="width:500px;"/>
</p>

Let's now look at how to edit CSS. The Styles panel is useful for
debugging CSS and understanding how CSS works. The styles panel allows
you to preview changes without affecting the appearance of your website
for other visitors. It is not necessary to refresh your browser to see
the changes because they are updated in real-time.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image408.webp"
  alt="Editing HTML and CSS."
  style="width:500px;"/>
</p>

In fact, if you refresh your browser after making changes, the browser
will reload the unmodified version of your website, wiping out your
changes. Using the styles panel for live CSS testing ensures that the
actual code of your live website is not altered.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image409.webp"
  alt="Setting breakpoints."
  style="width:500px;"/>
</p>

Let&apos;s now understand the process of setting a breakpoint in your codes.
To create a breakpoint: Click on the side of the file near the line
number and Run the code that will trigger the breakpoint. The
highlighted line of code indicates that the code has paused execution on
that line. So, at this point, you can inspect specific data in the code
by hovering over the variables you want to examine. This is essential
for debugging because quickly viewing your app's current state at any
point will provide you with valuable insight into how it works.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image410.webp"
  alt="Setting programmatic breakpoints."
  style="width:500px;"/>
</p>

Another way to trigger a breakpoint is to simply add the following code
line to a Javascript program: debugger; When the code reaches this line,
the debugger is triggered in the same way that a breakpoint would be set
in that line.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image411.webp"
  alt="Using logging function."
  style="width:500px;"/>
</p>

Let's now look at the logging function. The code has a console.log
function that can be used to output variables or data to the console.
For example, this code outputs the values from 0 to 4 to the console: //
open console to see for (let i = 0; i \< 5; i++)
{console.log(\"value,\", i); } To see the output, either open the
DevTools Console panel or press Esc while in another panel. This opens
the console at the bottom of the screen.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image412.webp"
  alt="Searching an object for properties."
  style="width:500px;"/>
</p>

Let's now learn how to find properties in an object. The grep.js snippet
searches an object and its prototypical chain for properties that match
a set of criteria.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image413.webp"
  alt="Searching an object for properties."
  style="width:500px;"/>
</p>

For example, this instruction will look for all properties in the
document object that match get: grep(document, &apos;get&apos;);

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image414.webp"
  alt="Visualizing the website on devices."
  style="width:500px;"/>
</p>

When you switch to developer mode in Chrome, it renders a half-sized
version of your webpage. Fortunately, Chrome DevTools allows you to
switch between different mobile screen types and versions in addition to
changing the screen size of a webpage.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image415.webp"
  alt="Visualizing the website on devices; switch between different mobile screen types and versions."
  style="width:500px;"/>
</p>

To access that option: First, toggle on the Inspect mode.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image416.webp"
  alt="Visualizing websites on different mobile screen types."
  style="width:500px;"/>
</p>

Next, select Responsive from the drop-down menu in the top-left corner
of the DevTools. Lastly, choose your preferred mobile device.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image417.webp"
  alt="Monitoring resources using devtools."
  style="width:500px;"/>
</p>

The webpage is then rendered and adjusted to fit the size of the mobile
device you chose. Aside from debugging JavaScript, Chrome DevTools
includes a feature that allows you to assess your website&apos;s overall
performance based on specific parameters. To use that feature, follow
these steps: In the DevTools window, select the Lighthouse option. Next,
choose the parameters you want to test. Select either Mobile or Desktop
to see how your website performs on different platforms.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image418.webp"
  alt="Recap module 33; devtools."
  style="width:500px;"/>
</p>

In this module (33), you learned that:

-   DevTools allows developers to edit code directly in the browser, add
    breakpoints to detect issues, and debug their code more quickly.,

-   The elements panel is used to examine and modify DOM nodes and style
    attributes,

-   The elements panel is used to edit HTML and CSS,

-   Setting breakpoints is essential for debugging as it provides
    valuable insights into how the app works,

-   The console.log function can be used to output something to the
    console, and

-   Chrome DevTools helps switch between different mobile screen types
    and versions in addition to changing the screen size of a webpage.

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<h2 name="ch5-34">34. Monitoring your Website</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image419.webp"
  alt="5-34. Monitory your Website"
  style="width:500px;"/>
</p>

Welcome to "Monitoring your Website."
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image420.webp"
  alt="Module 34; Explain, describe, discuss and define website monitoring."
  style="width:500px;"/>
</p>

After reading this module (34), you will be able to:

-   Explain website monitoring and its advantages,

-   Describe automated website monitoring,

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

-   Discuss the types of website monitoring, and

-   Define popular website monitoring metrics.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image421.webp"
  alt="Introduction to website monitoring."
  style="width:500px;"/>
</p>

Website monitoring implies evaluating a website or web service for
functionality, performance, or availability. Website monitoring service
ensures that the website is operational and that users are able to
access and interact with it as intended. Continuous monitoring helps
organizations prevent downtime and proactively respond to potential
errors that could have a negative impact.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image422.webp"
  alt="Advantages of website monitoring."
  style="width:500px;"/>
</p>

One of the main advantages of monitoring websites is increased website
uptime. Regular monitoring makes it easier to identify and fix issues
like server issues, network outages, and software bugs that could bring
down the website. Website monitoring helps minimize downtime by quickly
identifying the problems and taking appropriate action. Website
monitoring can also help optimize website performance by identifying and
addressing performance issues at the earliest. Quickly and accurately
diagnosing problems in real time helps websites run efficiently and
quickly. Downtime and slow-loading pages can result in lost sales and
revenue. Monitoring helps send alerts when your search, forms, or logins
go wrong. Website monitoring helps prevent these issues and keeps
revenue flowing.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image423.webp"
  alt="Methods of website monitoring."
  style="width:500px;"/>
</p>

Website monitoring can be done in two ways: automated monitoring and
real user monitoring.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image424.webp"
  alt="Automated monitoring."
  style="width:500px;"/>
</p>

Let's discuss each of them in detail. Automated monitoring means
monitoring the performance and availability of a web application by
simulating real user interactions with it. A network of computers
situated close to the site&apos;s end users is used for automated website
monitoring. This checkpoint network communicates with a website or
service to confirm that it performs as intended. The checkpoint performs
various steps to complete the process of web monitoring.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image425.webp"
  alt="Steps to automated website monitoring."
  style="width:500px;"/>
</p>

Let's discuss each step in detail. The first step that the checkpoint
performs is configuration. The checkpoint initiates a connection with
the website or service and checks the website at specific intervals. The
second step is testing. The checkpoint tests the website by sending
requests to the server and evaluating the server&apos;s response time. Other
website features are also examined by the program, including error
rates, page load times, and server resource utilization. Next, the
checkpoint checks the return for specified content. The fourth step is
Real Browser Monitoring (RBM). The checkpoint loads the content into a
real browser. RBM launches a browser and monitors a web application,
mimicking the user&apos;s interaction with the site.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image426.webp"
  alt="Additional steps to automated website monitoring."
  style="width:500px;"/>
</p>

After real browser monitoring is completed, the checkpoint collects the
data on the website&apos;s performance and availability and stores it in a
database for analysis. The load time of each element of the page is
recorded when the browser loads the page. This is called performance
monitoring. After performance monitoring is completed, web application
monitoring is performed. It implies tracking various performance metrics
and user behaviors of a web application in real-time. The checkpoint
attempts to sign in, carry out a search, use a shopping cart, or even
finish a transaction while performing web application monitoring.
Finally, the checkpoint reports its findings to the monitoring service
and uses the information to resolve any issues and improve the
website&apos;s performance and availability.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image427.webp"
  alt="Real User Monitoring."
  style="width:500px;"/>
</p>

Let's now discuss the other way of website monitoring, which is Real
User Monitoring (RUM). It is a method of monitoring the performance and
behavior of a web application as experienced by actual users.

It involves tracking and analyzing data generated by the interactions of
real users with the web application, such as page load times, error
rates, and user actions. Script files, agents, cookies, and server-side
code track the website's performance as each site visitor accesses the
site.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image428.webp"
  alt="Summary: Type of website monitoring; Availability, Performance, and Functionality."
  style="width:500px;"/>
</p>

There are several types of website monitoring that indicate a \"larger
picture\" of the website's performance.

These include: Availability monitoring, Performance monitoring, and
Functionality monitoring.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image429.webp"
  alt="First type of website monitoring: Availability monitoring."
  style="width:500px;"/>
</p>

Let's explore each type in detail. Availability monitoring or uptime
monitoring checks if a website is available and accessible to users,
ensuring that the website is running and can always be used by users. It
checks the availability of web services, domains, and pages.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image430.webp"
  alt="Second type of website monitoring: Performance monitoring."
  style="width:500px;"/>
</p>

Performance monitoring checks the speed of a website or service. The
frontend and backend connection tracks the browser load time by
performance monitors. Performance monitors may use RUM technology or
synthetic monitoring. RUM and the Full-Page Check provide the most
comprehensive performance data set.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image431.webp"
  alt="Third type of website monitoring: Functionality monitoring."
  style="width:500px;"/>
</p>

The third type is functionality monitoring.

A web application monitor or transaction monitor tests the functionality
of a website.

Script files are used by these monitors to interact with forms, site
searches, shopping carts, and payment systems. The transaction monitors
interact with a web application in the same way as regular users, and an
alert is sent to the supporting staff in case of any error or downtime
faced.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image432.webp"
  alt="Summary: Popular website monitoring metrics."
  style="width:500px;"/>
</p>

We will now explore some of the popular website monitoring metrics.
These include:

Page Speed, Time to Title, Time to Start Render, Time to Interact, DNS
Lookup Speed, Bounce Rate, and Requests Per Second.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image433.webp"
  alt="Popular website monitoring metrics: A page's speed."
  style="width:500px;"/>
</p>

Let's discuss each of them. A page&apos;s speed is determined by its loading
time and consists of three different metrics: Server response time,
which is the time the server takes to respond and is also called time to
first byte (TTFB); Transfer time, which is the time taken to download an
HTML web page; and Time taken to render a web page in a browser.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image434.webp"
  alt="Popular website monitoring metrics: Time to title, Time to start render, Time to interact."
  style="width:500px;"/>
</p>

Time to Title is the time that a website's title takes to appear in a
browser. 
Time to Start Render is the time the content takes to begin
loading, even if it doesn&apos;t fully load after an individual makes a
request. 
Time to Interact measures the time taken before users are able
to click links, type in text fields, scroll, or interact with a website
in other ways.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image435.webp"
  alt="Popular website monitoring metrics: DNS lookup speed, Bounce rate, and Requests per second."
  style="width:500px;"/>
</p>

DNS Lookup Speed is the time the Domain Name System (DNS) provider takes
to translate a domain name into an IP address. A slow DNS provider
results in a slow DNS Lookup speed.

Bounce Rate is a website metric that measures the percentage of visitors
who leave a website after only viewing a single page. A high bounce rate
indicates that a large number of visitors are leaving the site quickly,
potentially due to a poor user experience or not finding what they were
looking for. Requests Per Second refers to the number of requests the
server receives every second. It is also referred to as "Throughput" or
"Average Load."

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image436.webp"
  alt="In this Module (34): Website monitoring, Website monitors, Steps to automated monitoring, types of website monitoring."
  style="width:500px;"/>
</p>

In this module (34), you learned about:

-   Website monitoring and its advantages,

-   The two methods of website monitoring,

-   The steps to complete the process of automated website monitoring,

-   The three types of website monitoring:

    -   availability monitoring,

    -   performance monitoring,

    -   functionality monitoring, and

-   Some popular website monitoring metrics.

<h2 name="ch5-35">35. Popular Monitoring Tools</h2>
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image437.webp"
  alt="5-35. Popular Monitory Tools"
  style="width:500px;"/>
</p>

Welcome to Popular Monitoring Tools!

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image438.webp"
  alt="This module (35) describes how to select a website monitoring tool, and some of the most popular monitoring tools."
  style="width:500px;"/>
</p>

After reading this module (35), you will be able to:

-   Describe how to select a website monitoring tool, and

-   Identify some of the most popular monitoring tools.
<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image439.webp"
  alt="Website monitoring tools for: effectiveness, problem resolution, and performance."
  style="width:500px;"/>
</p>

Your website&apos;s effectiveness directly impacts your business, so
choosing the best website monitoring service is essential. Monitoring
tools run regular tests and notify you when your site is down, making
identifying and resolving problems easier. There are numerous options
available, ranging from simple uptime or transaction monitoring
solutions to complex web performance monitoring solutions.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image440.webp"
  alt="Factors when selecting best monitoring tools: live monitoring and free trial."
  style="width:500px;"/>
</p>

Certain factors need to be considered when selecting the best monitoring
tool. These include: 
  - Live performance monitoring capability, 
  - Monitoring of full stack, including supporting services, 
  - Monitoring of uptime,
  - Administrating the web server, 
  - Monitoring the page load time, 
  - Providing a free trial or demo that allows for an evaluation prior to the purchase, and 
  - Additional capabilities for monitoring other assets, such as physical servers and network devices.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image441.webp"
  alt="Popular monitoring tools: Pingdom, Uptime Robot, Datadog Synthetics, Site24x7, Uptrends, Uptimia and New Relic."
  style="width:500px;"/>
</p>

Let's now explore some of the most popular monitoring tools. They
include:

Pingdom, Uptime Robot, Datadog Synthetics, Site24x7, Uptrends, Uptimia,
and New Relic.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image442.webp"
  alt="Pingdon: PAID uptime monitoring service, sends alerts when apps go down, SSL certificate outdated and performance."
  style="width:500px;"/>
</p>

Let&apos;s discuss each in detail. Pingdom is a paid uptime monitoring
service that sends detailed alerts whenever an application or website
goes down. It provides a wide range of capabilities, including SSL
certificate monitoring and website performance monitoring, and has an
easy-to-use interface and a low price.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image443.webp"
  alt="Pingdom: Offers real-time user monitoring services.  Hands-on spies I guess."
  style="width:500px;"/>
</p>

Pingdom offers real-time user monitoring solutions that track real-time
visits to your website and allows you to improve your performance using
data collected from actual people. Geographical performance is also
monitored to ensure that your website performs optimally regardless of
where users access it.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image444.webp"
  alt="Uptime Robot: FREE! Notifies users when services are unavailable, 
  includes 50 monitors, 3 months log storage, and runs synthetic checks every 5 minutes."
  style="width:500px;"/>
</p>

Uptime Robot is the best option if you are looking for a simple tool
that will notify you when your services are down. The free account
includes 50 monitors, which is sufficient for most small websites or web
apps, and 3 months of log storage. It can run synthetic checks on your
website and APIs every 5 minutes from 12 locations worldwide and sends
alerts via various integrations with tools such as Slack, Pagerduty,
OpsGenie, Telegram, and VictorOps.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image445.webp"
  alt="Datadog Synthetics: Allows proactive monitoring of API endpoints &amp; sends 
  alerts, enables you to breakdown network timings, integrates directly into the CI pipeline."
  style="width:500px;"/>
</p>

Datadog Synthetics tests allow you to proactively monitor your API
endpoints and send alerts based on predefined parameters. You&apos;ll be
able to break down network timings, allowing you to find the underlying
cause of your problems faster. These tests can be integrated directly
into your CI pipeline to ensure early problem detection, allowing you to
evaluate the state of your production environment after each deployment
and minimize downtime by eliminating errors before your users see them.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image446.webp"
  alt="Datadog Synthetics: Monitors critical transactions, screenshots &ampp; waterfall visualizations, and elements after UI changes."
  style="width:500px;"/>
</p>

With Datadog Synthetics, you can monitor all of your critical
transactions without writing a single line of code using the web
recorder.

End-user screenshots and step-by-step waterfall visualizations are
combined with an intelligent system that identifies elements even after
UI changes, resulting in fewer broken tests.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image447.webp"
  alt="Site 24x7: Provides website performance monnitoring, is cloud-based, detects website code errors, and performance timing."
  style="width:500px;"/>
</p>

Site 24x7 provides website performance monitoring via periodic checks
from 90 locations worldwide. A subscription is required to use this
platform for cloud-based website monitoring. A Domain Expiry Monitor, an
SSL/TLS Certificate Monitor, and a Website Defacement Monitor detect
errors in your website&apos;s code. DNS fetches, connection establishment
times, first-byte time, download time, and SSL handshake time are all
included in performance timings.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image448.webp"
  alt="Site 24x7: Key features: Monitor bundles, SaaS platform, 90 test launch 
  locations, DNS checks &amp; SSL certificate verification."
  style="width:500px;"/>
</p>

Some of the features include: Monitoring bundles, SaaS platform, 90 test
launch locations, DNS checks, and SSL certificate verification.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image449.webp"
  alt="Uptrands: Monitoring service for network and internet performance, masquerades as a user to accesss web servers."
  style="width:500px;"/>
</p>

Uptrends is a website monitoring service that also monitors network and
internet performance. As a remote server, it can access your web
servers while masquerading as a user and report on its findings. It can
even test your competitors&apos; websites and tell you how theirs performs
compared to yours. DNS records and DNS fetch times are some other checks
performed by Uptime. It also monitors SSL certificates to ensure that
they do not become outdated.
<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image450.webp"
  alt="Uptrends: Monitors performance of FTP servers and other shit."
  style="width:500px;"/>
</p>

It also monitors the performance of FTP servers for download delivery.
The monitor also tracks user journeys through a site and records load
times for each page visited. It will also evaluate your site&apos;s mobile
friendliness.

Performance tests are performed once every minute. The monitor&apos;s
console displays real-time test results, which can also be exported to a
PDF or Excel format. Uptrends stores test results for two years to allow
for historical analysis.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image451.webp"
  alt="Uptimia: Monitoring service provider for small and large businesses.  Uptime monitoring is only service free."
  style="width:500px;"/>
</p>

Uptimia provides monitoring services for both small and large
businesses, including uptime and speed monitoring, transaction
monitoring, and real-time user monitoring. The company provides a
free-forever plan that allows you to monitor one website in five-minute
increments. The free plan only includes uptime monitoring.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image452.webp"
  alt="New Relic: Helps you monitor, debug and enhance your stack. I question it's claims."
  style="width:500px;"/>
</p>

New Relic is an observability platform that helps you in monitoring,
debugging, and enhancing your stack. It enables developers to create
more effective software by providing a diverse set of tools. It combines
tools for monitoring, analytics, and optimization. Key features include:

-   Telemetry data with AI insights that transcend the traditional
    website performance monitor,

-   Full-stack observability, and

-   Applied intelligence with quick incident response.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<p align="center">
  <img src="./assets/images/image453.webp"
  alt="In this module (35), you learned about monitoring tools and tests, API endpoints, and so much more."
  style="width:500px;"/>
</p>

In this module (35), you learned that:

-   Monitoring tools run regular tests and send notifications when a
    website is down, making identifying and resolving problems easier,

-   Some monitoring tools provide these features:

-   Monitoring service that sends detailed alerts whenever an
    application or website goes down,

-   Running synthetic checks on websites and APIs every few minutes from
    various locations worldwide,

-   Allows the monitoring of API endpoints proactively and sends alerts
    based on predefined parameters, and

-   Allows developers to create effective software by providing a
    diverse set of tools.

## Hands on Lab: Troubleshooting Common Errors with Chrome Dev Tools

## Welcome to the **Troubleshooting Common Errors with Chrome Dev Tools** lab!

In this lab, you will learn how to use Chrome DevTools by working
directly in the Elements, Console, and Sources panels.

**PRE-REQUISITE**: This labs requires the Chrome Web Browser.

Skills Network Labs (SN Labs) is a virtual lab environment used in this
course. Upon clicking \"Open Tool\" in accordance with IBM Skills
Network Privacy policy your Username and Email will be passed to Skills
Network Labs and will only be used for communicating important
information to enhance your learning experience.

In case you need to download the lab instructions click
[HERE](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-WD0231EN-SkillsNetwork/labs/Chrome_DevTools.md.html)
to open in a new tab.

This course uses a third-party app, Hands on Lab: Troubleshooting Common
Errors with Chrome Dev Tools, to enhance your learning experience. The
app will reference basic information like your name, email, and Coursera
ID.

# Week 5 Summary: Debugging and Troubleshooting

In week 5, you learned that:

-   Debugging is an integral part of the software development process
    that involves identifying the cause based on the symptoms.

-   Debugging begins when the software code is written and has numerous
    advantages.

-   Browsers include various web development tools known as add-ons or
    extensions.

-   A debugging tool is software that allows you to debug a program.

-   Chrome DevTools enables developers to edit code directly in the
    browser, add breakpoints to detect problems, and quickly debug their
    code.

-   It also allows you to switch between different mobile screen types
    and versions and change the size of a webpage&apos;s screen.

-   Website monitoring assesses a web service&apos;s functionality,
    performance, and availability.

-   Monitoring tools perform regular tests and send alerts when a
    website is unavailable, making identifying and resolving issues
    easier.

-   By providing various tools, monitoring tools enable developers to
    create compelling software.

<!-- # [Week 6:]{.mark} -->

<h1 name="ch6">WEEK 6</h1>

<h2 name="ch6-36">36. Interest Rate Calculator</h2>

Welcome to the hands- on lab for **Interest Rate Calculator**.

Skills Network Labs (SN Labs) is a virtual lab environment used in this
course.  Upon clicking \"Open Tool\" in accordance with IBM Skills
Network Privacy policy, your Username and Email will be passed to Skills
Network Labs and will only be used for communicating important
information to enhance your learning experience.

In case you are having issues with the Lab environment, <a href="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMSkillsNetwork-WD0231EN-SkillsNetwork/labs/FinalProject/02-Instructions.md.html">you can view the
lab by clicking this Lab Link</a>.

<!--~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~-->
<!-- <p align="center"> -->
<!--   <img src="./assets/images/image454.webp" -->
<!--  alt="Semi-circle with 'We're starting up your lab environment now.'." -->
<!--  style="width:500px;"/> -->
<!-- </p> -->

This course uses a third-party app, Final Project: Interest Rate
Calculator, to enhance your learning experience. The app will reference
basic information like your name, email, and Coursera ID.

# Assignment: Summary and Evaluation

There are 10 points for nine tasks in this final project. Your peers who
will grade your final assignment are also completing this assignment
within the same session. You need to complete the following and submit
your responses for peer review.

This guided final project is divided into three parts: (1) Fix the
existing errors, where you first start with the code provided and fix
the deliberate errors in HTML and JavaScript. (2) To save yourself from
testing every code change manually, you will then make your business
logic in JavaScript testable with the help of Jasmine. Write test specs,
fix your logic, and do unit tests every time you make a change. (3)
Finally, in the last part, you will improve on Search Engine
Optimization and enhance your deployment package with the help of
Webpack.

You will need to submit screenshots when requested.

*To take a screenshot in Windows, use the snipping tool by going to the
start menu and opening the snipping tool. Click "New," then click and
drag over the area of the screen you want to screenshot. Save the file
as a .png or a .jpg file.*

*Click shift+command+4, then click and drag over the area of the screen
you want to screenshot on MacOS. The file will be saved to your
desktop.*

*To upload the file, click upload file, navigate to the file, or drag
and drop the file icon onto the window.*

## Review criteria

1.  Show favicon working, upload a screenshot of your browser tab and
    save it as 01-favicon-visible as a .png file or a .jpg file (see
    instructions above on how to take a screenshot.) (1 pt)

2.  Show missing CSS referenced correctly, once added to the html,
    upload a screenshot of the output showing CSS working; by means of
    correct colors and layout and save it as 02-css-working. (1 pt)

3.  Show how missing JavaScript reference error displayed in Chrome
    DevTools and upload a screenshot of the same and save it as
    03-calculate-missing. (1 pt)

4.  Show how to use Chrome DevTools' debugging capability, show how you
    "pause on exceptions" and save it as 04-pause-on-exception. (1 pt)

5.  Show "Watch" on a variable in your code, upload a screenshot showing
    \`p\` added in Watch and save it as 05-watch-on-p. (1 pt)

6.  Show Jasmine is initialized and will work, show in terminal "no spec
    found," upload a screenshot of it and save it as 06-no-spec. (1 pt)

7.  Introduce two unit tests as instructed, show both of them pass in
    Jasmine; upload a screenshot of Jasmine output and save it as
    07-both-tests-passed. (1 pt)

8.  Show Webpack is generating the expected output in your "dist"
    directory, upload a screenshot of it from Cloud IDE and save it as
    08-dist-directory. (1 pt)

9.  Show achieving the goal state, upload a screenshot of your final
    solution along with source, and save it as 09-final-output. (2 pts)

<div align="right">
  <b><a href="#table-of-contents">↥ Back To Top</a></b>
</div>

<!-- Oct 8, 2023 8:29pm -->
