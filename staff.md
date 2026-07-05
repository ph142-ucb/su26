---

## layout: page
title: Staff
nav_order: 3
description: A listing of all the course staff members.

# Staff

## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} {% for staffer in instructors %} {{ staffer }} {% endfor %}

## Lead GSI

{% assign lead_gsi = site.staffers | where: 'role', 'Lead GSI' %} {% for staffer in lead_gsi %} {{ staffer }} {% endfor %}

## GSIs

{% assign gsis = site.staffers | where: 'role', 'GSI' %} {% for staffer in gsis %} {{ staffer }} {% endfor %}

## Tech GSI

{% assign tech_gsi = site.staffers | where: 'role', 'Tech GSI' %} {% for staffer in tech_gsi %} {{ staffer }} {% endfor %}



