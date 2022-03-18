---
# This is a full listing of available Frontmatter options, available for any content (.md) file.
title: 
layout: page
excerpt: # used for page excerpts and META (will be overwritten if SEO used below)
#author: shane-robinson # only displayed on Post lists and detail views. Defaults to _data/meta.authorURL
eleventyNavigation: # Required if want to display in Main Nav Bar
  key: main # "main" is required
  title: Accueil # as it will appear in the nav
  order: 1 # order to display in the nav (index = 1)

---

<!-- We set out to build a starter project template for [11ty](https://11ty.dev '11ty Static Site Generator') that has [TailwindCSS](https://tailwindcss.com 'TailwindCSS Utility-First CSS Framework') and [Alpine.js](https://github.com/alpinejs/alpine 'Alpine.js : Think of it like Tailwind for JavaScript') baked in.

Version 1.0.0 morphed into a fully-configurable text-based CMS for managing small websites with easy-to-manage configuration files in the `/src/_data` directory.

{% wrap "mt-4 bg-indigo-100 border border-indigo-300 text-lg italic rounded-full text-center" %}

**[START HERE:](/blog/) The [Blog Posts](/blog/) cover the main features of the system.**

{% endwrap %}

## Install and Deploy

To automatically deploy this Template to [Netlify for free hosting](https://www.netlify.com/pricing/), make sure you're logged in to your Netlify account and then simply click the `Deploy to netlify` button below.

<a href="https://app.netlify.com/start/deploy?repository=https://github.com/11ta/11ta-template"><img src="https://www.netlify.com/img/deploy/button.svg" alt="Deploy to Netlify"></a>

**Want to install and develop locally?** Hop over to the [GitHub repo](https://github.com/11ta/11ta-template/) and follow the instructions in the README.

{% wrap "border-t border-b border-indigo-300 mt-4 "%}

|                            |                                                                                                                                                           |
| :------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------: |
| **Current Deploy Status:** | [![Netlify Status](https://api.netlify.com/api/v1/badges/e6eb38e1-d081-46ea-a4f6-4d3d36ab7036/deploy-status)](https://app.netlify.com/sites/11ta/deploys) |

{% endwrap %}

## :fire: Credit :fire:

First and foremost, I want to credit the [11ty](https://11ty.dev) community, especially those listed in the [starter projects](https://www.11ty.dev/docs/starter/)!

Specifically, the following starter projects helped me understand the power and flexibility of 11ty and from their examples I was able to extend the functionality to build this system:

- :fire: [eleventy-base-blog](https://github.com/11ty/eleventy-base-blog) by [Zach Leatherman](https://twitter.com/zachleat)
- :fire: [eastslopestudio-eleventy-starter](https://github.com/eastslopestudio/eleventy-starter) by [Ryan Scherler](https://twitter.com/ryanscherler)
- :fire: [eleventyone](https://github.com/philhawksworth/eleventyone) by [Phil Hawksworth](https://twitter.com/philhawksworth)
- :fire: [eleventy-tailwind-alpinejs-starter](https://github.com/gregwolanski/eleventy-tailwindcss-alpinejs-starter) by [Greg Wolanski](https://gregwolanski.com/)
- :fire: [jet](https://github.com/marcamos/jet) by [Marc Amos](https://twitter.com/marcamos)

## Features

In addition to the Structural, Color, and Frontmatter contols listed below, the system also has the following features baked in:

- **SIAB** _(site in a box)_ ... Update the site settings in `/src/_data/meta.js`, content on the `index.md` and `about.md` pages, replace the `/src/posts/*.md` files with your own content and your new site is fully functional and ready to publish!
- **100 Lighthouse scores** across the site's Pages and Posts (_not just on pages with a little text and no images_ :wink:).
- ATOM feed at [/feed.xml](/feed.xml).
- Inlined CSS for the [Prism Okaidia](https://prismjs.com/) syntax highlight theme.
- Webpack to bundle up [Alpine.js](https://github.com/alpinejs/alpine) and any custom JS you want to include.
- Purged CSS and Minified source on production builds.
- [Custom 404](/asdf) which lists 10 most recent Posts.
- Contact form automagically works if [hosted at Netlify](https://docs.netlify.com/forms/setup/).
- ...other things I'm probably forgetting but will add when I think of them.

## Structural and Color Controls

You can completely control:

- Multiple Authors in `/src/_data/authors.json`.
- FOUR native [Posts List](/blog/) and [Tags List](/tags/frontmatter/) layout in the `src/_data/structures.js` file via, `postListStyle:` and `tagListStyle:` keys.
- Colors of the NavBar, Headings, Buttons, etc. in `/src/_data/colors.js`.
- Site META and defaults in `/src/_data/meta.js`.
- Social Links icons in the Footer in `/src/_data/social.json`.
- Social Share icons in the `/src/_includes/components/socialshare.njk` file.
- And site-wide structures like max-width and display toggles of different content blocks in `/src/_data/structure.js`.

## Frontmatter Controls

The **Frontmatter** in your .md Posts and Pages files also allows you to manage:

- [Heros](/2020/09/11/manage-hero-graphics-carousels-splits-and-video/) _(like on this home page)_ of types: **carousel, graphic, video,** and **split**. _(Actually, you can add those Hero types to **ANY** Page or Post just be using the Frontmatter.)_
- [Featured Images](/2020/09/06/featured-post-images/) _(full-width banners at the top of the page just like in Wordpress)_.
- [SEO overrides for OG and Twitter cards](/2020/09/10/site-meta-og-and-twitter-cards/) for Title, Description, and Images.

## Native Shortcodes for Content Controls

There are several **Shortcodes** _(both single and paired)_ and **Filters** to allow Editors to manage:

- [Multi-column content](/2020/09/03/wrap-and-columns-shortcodes/) _(without writing CSS)_.
- [SVG Sprites](/2020/09/09/svg-shortcode/) controls across the system and for inserting in .md Posts and Pages files.
- Custom Date display formats at the point of use.
- [Description Lists](/2020/09/04/description-list-shortcodes/) for content like FAQs, Lists, etc.
- [Wrapper](/2020/09/03/wrap-and-columns-shortcodes/) for managing blocks with background images, borders, etc.
- [YouTube embed shortcode](/2020/09/08/youtube-video-embed/) that allows you to control and add an iFrame title _(required for accessability and Lighthouse scores)_, width/height ratio, and set the start time in "m:ss" format so you don't have to manually count the seconds.

## Planned

- Search
- More Structural controls for Index Page
- Easy add Collections: Projects, Services, Jobs, etc.
- "Themed" versions for Portfolios/Creatives, Agencies, Digital Gardens, etc.
- Fully documented migration of Wordpress to 11ty
- [Snipcart](https://snipcart.com/) integration -->



<!---
Le GAPI est un organisme communautaire autonome, sans but lucratif, fondé en 1987.

![Le Gapi](/assets/images/gapi/GAPI-LOGO-V-COUL.png "Le Gapi")

-->

![Le Gapi](/assets/images/gapi-entete2.jpg "Le Gapi")

###### Le GAPI est un organisme communautaire autonome qui dessert la grande région de Québec et de Portneuf depuis 1987. {.call-to-action}

Nous intervenons auprès d’hommes adultes ayant des comportements violents dans un contexte conjugal ou familial, peu importe le type d’union ou la situation.

### Nous aidons ces personnes à :

- Reconnaître leur problématique
- Arrêter leurs comportements et leurs attitudes de violence
- Développer des moyens pour gérer leurs conflits sans violence
- Vivre des relations harmonieuses, égalitaires et positives avec leurs proches

Au plan social et avec nos partenaires, nous contribuons aussi à la sensibilisation aux violences conjugales et familiales ainsi qu’à l’aide aux hommes par diverses activités de prévention et de formation.

Nous travaillons de façon concertée avec plusieurs partenaires afin d’offrir des interventions ajustées, cohérentes et tenant compte de contextes parfois complexes.

De plus, nous maintenons une implication active à divers projets de recherche dans une perspective d’amélioration des pratiques et des connaissances.

[En savoir plus](/services){.call-to-action}

<!----
## J’ai besoin d’aide parce que :

- Je m’interroge sur mon impulsivité et mes comportements;
- Ma conjointe ou mon conjoint pense à me quitter;
- J’ai peur que ma violence ait des répercussions négatives sur mes enfants, qu’ils la subissent directement ou qu’ils y soient exposés;
- Je cherche des trucs, des solutions pour régler des conflits sans que la situation ne dégénère;
- Je veux en connaître plus sur moi-même et sur la violence conjugale ou familiale;
- Je veux changer mes comportements;
- J’aurais dont dû… ;
- Je souhaite briser mon isolement et partager mon vécu avec d’autres hommes qui vivent le même problème que moi;
- Je suis « tanné » de perdre les gens que j’aime;
- Je veux être mieux dans ma peau;
- La violence ne m’apporte que des problèmes;
- Je ne me comprends plus.
- La violence ne m’apporte que des problèmes;
- Je ne me comprends plus.
- La violence ne m’apporte que des problèmes;
- Je ne me comprends plus.



## Information sur la problématique

### Définition de la violence

##### Relation conjugale

Relation entre deux personnes qui vivent (ou ont vécu) une union affective (fréquentation, mariage, union de fait), nonobstant l’orientation sexuelle.

##### Violence conjugale

Contrôle exercé par une personne auprès d’une autre personne à l’intérieur d’une relation conjugale. Ce contrôle peut se manifester par des comportements, des gestes, des paroles ou des attitudes qui sont répétés et continus dans le temps.

La violence est construite (apprise) socialement (valeurs véhiculées). Elle est cependant choisie individuellement puisque tout individu est responsable à 100 % des comportements, gestes, paroles et attitudes qu’il (elle) adopte.

La violence est un problème social et la violence conjugale en est une manifestation largement répandue.

-->

<!---

![Le Gapi](/assets/images/gapi/GAPI-LOGO-H-COUL.jpg "Le Gapi")
![Le Gapi](/assets/images/gapi-entete2.jpg "Le Gapi")
![Le Gapi](/assets/images/gapi-entete2.jpg "Le Gapi")
![Le Gapi](/assets/images/gapi-entete2.jpg "Le Gapi")
![Le Gapi](/assets/images/gapi-entete2.jpg "Le Gapi")
![Le Gapi](/assets/images/gapi-entete2.jpg "Le Gapi")
![Le Gapi](/assets/images/gapi-entete2.jpg "Le Gapi")

-->