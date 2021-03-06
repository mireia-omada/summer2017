---
layout: session
title: Better dependency management - leverage composer to the limit
permalink: /en/session/better-dependency-management-leverage-composer-for-good/
language: en
tid: rodrigoaguilera1
seo:
 description: Better dependency management - leverage composer to the limit
 keys:

date: Sábado 01 de julio
place: Citilab, Auditori
time:  "13:00 a 14:00"
seatingCapacity:
speaker:
  pic:
  name: Rodrigo Aguilera
  drupal:
  facebook:
  twitter:

sesionSlides:
  - src: http://rodrigoaguilera.github.io/talk_composer/#/
---
Drush make days are over. Drupal in its effort to "get off the island" has adopted a new but popular tool for dependency management in the PHP ecosystem: composer.

I will quickly go through the basics of how to use this tool and some interesting features like caching, semantic versioning, class autoloading, etc.

Then I will folllow with the main ways I found to leverage composer and do more with it&#58;

 - Scaffold your Drupal project (initializing) with the drupal composer project.

 - Apply patches from the community to Drupal core, modules, themes, libraries, etc.

 - Differentiate dependencies for development from the rest.

 - Get exact same version of libraries for all developers.

 - Download frontend libraries.

 - Download compiled binary tools for the architecture of your machine.

And if the time allows it we can open a discussion about good practices and tricks to make our composer experience better.

This session is aimed at&#58;

 - developers who alredy had some experience with composer and see the potential of the tool.

 - People who are used to Drupal 7 workflows and want to bring them to 2017

I have been using composer for every Drupal 8 project since the pre 1.0 stable days and have always advocated the use of this tool while discovering new things people were bringing into their composer files to make their workflows easier and saner.
