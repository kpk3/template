---
layout: project
type: project
image: images/kai-image.jpg
title: Kai Word Add-in
permalink: projects/archiver
date: 2016
labels:
  - C#
  - XML
  - Visual Studio
summary: A means of quickly returning client information for new proposals.
---

<img class="ui medium right floated rounded image" src="http://www.kaihawaii.com/images/logo.jpg">

Kai Word Add-in is a project I developed during the summer of 2016. The purpose of Kai Word Add-in is to provide a means of searching through a preexisting excel spreadsheet of all of Kai's previous clients and of quickly getting all of the necessary information for any new proposals(contracts).

This was the second assignment I was given at Kai Hawaii. At this point I was already well versed in C# and had already produced another add-in, albeit for Outlook. However, Outlook is actually a much more difficult product to work around because in Outlook you're dealing with actual emails, which have the communication/multiple user dimension. Thus I was quickly able to produce a working version in only three weeks.

In this instance the difficulty/disappointment came when I learned that the program, at least with the time I was allotted, couldn't improve much past what I had initially produced. This is because of the fact that the company keeps a list of all previous clients on an excel spreadsheet kept on their personal server. There was no other way of retrieving this data without making it infinitely more difficult for the secretaries to re-input all three thousand of the previous client info into a new form that Word could use effectively. Therefore, the product is merely a simple search algorithm based on user input. It has no real mind of its own because the data it draws from is too simple. There's no way to provide a "smart search" capability without creating a massive startup time, which Word doesn't allow anyway, otherwise it'll simply disable your add-in.

Link: <a href="https://bitbucket.org/kpk3/word-add-in">Repository</a>

