---
title: Upgrade from Debian 11 to Debian 12
date: 2023-06-29 00:00:00 Z
description: Upgrade your Debian 11 Operating System running Passbolt to Debian 12
categories: [hosting,upgrade,ce]
sidebar: [hosting, upgrade]
passbolt_version: ce
slug: from-debian-11-to-debian-12-ce
permalink: /:categories/:slug.html
archived: true
layout: default
---

{% assign product = 'ce' %}
{% assign distribution = 'debian' %}
{% assign distributionVersionOld = '11' %}
{% assign distributionVersion = '12' %}
{% assign distributionVersionNameOld = 'bullseye' %}
{% assign distributionVersionName = 'bookworm' %}
{% assign distributionSlug = 'debian' %}
{% assign distributionLabel = 'Debian' %}
{% assign distributionUpgradeGuide = 'https://www.debian.org/releases/stable/amd64/release-notes/ch-upgrading.html' %}
{% assign databaseEngine = 'mariadb' %}

{% include layout/row_start.html %}
{% include layout/col_start.html column="7" %}

{% include hosting/upgrade/upgrade-debian12-new-specs.md %}
{% include date/updated.html %}

{% include layout/col_end.html %}
{% include layout/col_start.html column="4 last push1" %}

{% include aside/message.html
    class="tldr notice"
    content="Are you experiencing issues when updating passbolt?"
    link="https://community.passbolt.com/c/installation-issues"
    ask="Ask the community!"
    button="primary"
%}

{% include aside/message.html %}
{% include aside/contribute.html %}
{% include layout/row_end.html %}
