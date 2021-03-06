---
title: 'Responsive redesign for Casey Trees'
layout: singel
theme: paper
category: 'projects'
tags:
  - 'design'
  - 'process'
  - 'responsive'
  - 'web'
updated: 2016-04-04 21:45
drafted: 2015-02-23 13:02
unique_id: 2012-03-06:casey-trees-redesign
period: 2011-11 to 2012-03
description: 'My work on a redesign for an urban forestry non-profit, in the early days of responsive web design.'
project:
  url: http://caseytrees.org/
image_index: index/2015-02-23-ct-logo.svg
image:
  - src: 2015-02-23-ct-logo.svg
    src_png: 2015-02-23-ct-logo.png
    background: 'site.shade.white'
    description: 'Logo SVG'
  - src: 2013-01-09-casey-trees-homepage-android.jpg
    alt: 'The Casey Trees home page on an Android mobile browser'
    date: 2013-01-09
    description: 'Taken on a Galaxy Nexus using Google Chrome for Android in 2013'
  - src: 2012-04-27-casey-trees-homepage-desktop.jpg
    alt: 'The Casey Trees home page on a desktop early on after the redesign, with a series of slides and all navigation items visible, including events and the Tree Report Card.'
    date: 2012-04-27
    caption: 'The home page less than two months after the redesign.'
    description: 'Taken with Google Chrome on a Windows computer in 2012, shortly after the redesign.'

---

In 2012, I managed a complete responsive website redesign for [Casey Trees](http://caseytrees.org/), an urban forestry non-profit dedicated to protecting the tree canopy of Washington, DC.

My primary responsibilities were:

- Project management and technical translation on the client side, working with external designers and developers at [Firefly Partners](http://www.fireflypartners.com) who were responsible for the bulk of design and development.
- Providing guidance on user experience and information architecture decisions.
- Writing, editing, photo curation, and content strategy – with hundreds of pages and dozens programs and projects to review, filter, and edit.
- Ongoing support after the redesign, supporting the organization’s content and design needs after the initial launch.

**My most important role on the project, however, was as an advocate for responsive web design.** Our goal was to develop a site that would cater to multiple screen sizes, without the false constraint of assuming only a “desktop” browser context. [^1] When we were planning to redesign the website in 2011, responsive design was not yet implemented widely. The web changes quickly. While the approach has become (by 2015) an *essential* part of designing for an uncertain future, back then we were taking a decisive step towards a more flexible experience, in our small corner of the web.

We turned the project around in only a few months, with design and content work starting in December 2011 and the website launching in March 2012.

<div class="grid--wide">
  {% assign image = page.image[1] %}
  {% include block/image.html class="grid-figure--33 screenshot" %}

  {% assign image = page.image[2] %}
  {% include block/image.html class="grid-figure--66 screenshot" %}
</div>

## The need for a new website

The previous iteration of the website had been designed in 2008. We faced a few significant issues that I worked with my fellow staff to identify:

- The information architecture for the site was based on internal organizational structure (by department), rather than being informed by our constituents’ view of the organization. The navigation on the 2008 site had major usability issues, and created a perception of the organization being split into disconnected silos. Programs that spanned departments could only be found within one department’s section of the website. Plenty of efforts, especially fundraising and events, had no visible home on the site. We received regular feedback from users of the website about these issues.
- The website was practically unusable on smaller devices, with no mobile-specific resources and no consideration for anything except for conventional desktop browsers. Text was illegible on both very large and very small screens. Interfaces were difficult or impossible to use with touch input. No content on the site responded at all to different browser sizes.
- Portions of the site relied on Adobe Flash for content and interaction. Portions of the site were not usable without Flash support. Even aside from accessibility issues, the organization also lacked the technical support to maintain these quickly aging resources.
- The organization’s blog was not integrated with the website. It ran on a different host and content management system. There was virtually no shared experience with the main site, and all of the resources on the blog were managed separately.
- The visual design reflected the organization as it existed years ago when it had fewer employees and programs. New programs were on the way: a tree farm, local advocacy, expanded education efforts, and new tree planting programs. Additionally, the communications and development team had larger design goals that could only be met with a substantial visual redesign.
- The site was maintained with Adobe Contribute: outdated and limited software that the communications staff did not enjoy using. The site’s design was not modular enough to flexibly design new pages or experiences, and content management was getting increasingly difficult as the site grew.

## Results

### A new content management system

We integrated more tightly with our existing Convio non-profit fundraising and sales tools, but we also adopted a new CMS: WordPress. Having a CMS would make it easier to manage a larger website, and the interface was more approachable and in some cases familiar for staff. Importantly, we had more control over layout and design with the new site. With more flexible styles, we had the ability to create more modular components and templates for changing programs, and respond to organizational needs to reform the information architecture.

### An improved experience

Feedback from users of the site was positive, and staff appreciated the easier administration and new design as well. After a refresh of our events management and fundraising systems, it was far easier to get fully subscribed events. “Mobile” device visits went from being about 6% of visitors to 12% (and even higher later on) as device user trends changed, and as our website became more friendly to visitors with different types of screens and contexts. It is fair to say that we would have been turning away a significant portion of our audience without a responsive redesign.

{% capture ancillary %}
## More on my work for Casey Trees

- [The responsive design process]({% post_url 2013-09-26-casey-trees-membership %}) for the later Membership campaign: a closer look at my approach to responsive design and implementation.
- [Technical documentation and training]({% post_url 2014-10-01-casey-trees-docs %}) for the Casey Trees website.

{% endcapture %}

{% include block/ancillary.html %}

### Long-term gain

With ever-shorter life spans of websites, the 2012 redesign has so far lasted quite a while without the need for a substantial overhaul. As I write this in early 2015, the site is entering its third year since the redesign. Nothing lasts forever on the web, but it is refreshing to see a smaller budget website last a few years before the organization’s needs outgrow the design.

One key to the relative success of the site was its forward-thinking approach: responsive design was the indispensable decision that allowed us to enter the next few years without feeling left behind by changes in technology and web design.

Responsive design is about more than merely reaching a diversity of screens.
{:.focus}

This approach gave Casey Trees not only a better experience for visitors to the site, but more flexibility in presenting its mission, and more effective methods of communicating with people. I do regret that we were not able to implement an even more universally accessible and high performance design. With hindsight and my subsequent experience, I realize that even more could have been accomplished even for a project of this scale.

Responsive thinking is a fundamentally more empathetic approach to an unknowable audience – one that can be felt directly regardless of user capabilities or the device they happen to be using.

[^1]: Technically, responsive design is about designing with a flexible grid layout, using fluid image widths, and using CSS media queries to conditionally control layout and presentation for different device sizes. As Ethan Marcotte put it in his foundational <i class="publication"><a href="http://www.abookapart.com/products/responsive-web-design">Responsive Web Design</a></i>): “… design that can adapt to the constraints of the browser window or device that renders it, creating a design that almost responds to the user’s needs.”
