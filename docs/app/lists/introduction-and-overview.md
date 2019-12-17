---
title: Introduction and Overview
---

Email lists are used to group a collection of subscribers. You can use tags and segments to further divide a list into parts that you want to target.

## Overview

// TODO // Screenshot index

On the lists index page, you get an overview of all the email lists you can manage, with the amount of active subscribers shown. If you have double opt-in enabled, this number only includes subscribers that have confirmed their subscription. People that have unsubscribed, or don't have a valid email address (anymore), will not be counted in the "active" subscribers amount.

## Creating a list

// TODO // Screenshot "create list"

When creating a new list, you must enter a name for the list, and the email and name that campaigns will be sent from. The _From email_ will be the sender for any email campaigns that target this list. This will usually be an email address that you configured while setting up your mail configuration with Mailgun / Amazon SES / SendGrid / … .

The _From name_ value is used as the sender's name in received emails. If you leave this field empty, the subscribers' mail client will fill this in according to their defaults. We suggest using the name of your organisation for this field.