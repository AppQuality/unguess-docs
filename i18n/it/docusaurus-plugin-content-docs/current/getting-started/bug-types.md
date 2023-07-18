---
sidebar_position: 3
title: Bug types
---
## Recognize types, their severity and replicability

:::info
It's important to understand how to recognize different types of bugs, their severity and replicability
:::

The term *bug* identifies an error that alters the correct functioning of a piece of software by producing, for example, an unexpected or incorrect result. One of the fundamental characteristics of a good reporter is the ability to detect bugs and find a way to reproduce them. In order to do this, first of all, it is necessary to know how to recognize the various **types** of bugs and their relative **severity**, as these two parameters are deeply connected.

Let us begin by distinguishing the various **types of bugs**, which will be described according to the terminology for the Bug Form used to open bug reports.

### Bug Type
#### Malfunction
This is a type of bug that concerns the failure or incorrect functioning of a feature present inside the product.

> **Example:** dead buttons and/or links, inability to insert a product in the shopping cart, error 404, problems related to error messages with text not contextualized to the problem (generic error).

If the operation is generally correct but differs from the user’s expectations, then the bug falls into the USABILITY category.

:::info Mandatory attachments
Screenshot & Video.
:::

#### Crash

It causes the product to be closed or unresponsive. The user is forced to restart to continue using it.

> **Example:** application freezing completely or closing abruptly, endless loading.

:::info Mandatory attachments
Screenshot & Video.
:::

#### Usability

Problems related to the use of the product that make it difficult for the user to perform a certain action or task due to long, complex, non-ideal or unintuitive paths. This includes cases where the operation differs completely from the user’s expectations.

It also included the absence of checks on the insertion of data into fields and problems related to error messages with text that is out of context with the actual problem present (generic error).

> **Example:** too many clicks before a purchase can be concluded; too long and complex process to change the profile picture.

:::info Mandatory attachments
Screenshot & Video.
:::

#### Security

Problems only related to security and maintaining the confidentiality of saved data.

This includes sections with passwords in clear text, failure to expire logins, or even the free possibility to get data from other users via SQL injection or XSS attacks.

> **Example:** Inability to delete credentials from an account.

:::info Mandatory attachments
Screenshot & Video.
:::

#### Graphic

Problems related to a compromised display of the graphic layout, photographic components, images, icons, popups and alerts.

> **Example:** undefined photograph, partially or totally invisible image, compromised graphic layout, off-centre or misaligned popups, etc.

:::info Mandatory attachments
Screenshot & Video.
:::

#### Typo

Problems related to grammatical, spelling, semantic, lexical or syntax errors, incorrect or incomplete translations, incomplete (not graphically cut) or meaningless sentences, code in sight or not understandable.

> **Example:** lack of spaces between words, wrong accents.

:::info Mandatory attachments
Screenshot
:::

#### Performance

Problems strictly related to the speed of loading content or completing processes  in the digital product (lag, slowdowns, delays).

> **Example:** very slow loading times, presence of delays in videos that cannot be attributed to the speed of the user’s connection.

If this excessive loading never ends (loop), then the problem is due to a CRASH.

:::info Mandatory attachments
Screenshot & Video.
:::

#### Other

All the problems that don’t belong to the categories described so far. 

:::info Mandatory attachments
Screenshot & Video.
:::

It’s important that during the video recording or capturing the screenshot, the entire all visible area (browser, app, etc.) is captured and not a clipping.

Only in this way is it possible to have all the background information in addition to the bug itself, without the reporter being asked for it in the Bug Form (e.g. web address, browser, etc.)

 

### Severity
Another key parameter to consider is the bug’s severity, which is an estimation of problem’s impact on product use, taking into account the context in which it occurs (primary or secondary sections in relation to the core business of the digital product) and the conditions under which it was found in relation to average use.

#### Low
Problems with a minimal impact when using the product, in the face of which the user is always able to continue using the digital product without being particularly upset. 
:::tip
These are often USABILITY, TYPO or GRAPHIC bugs.
:::

#### Medium

Problem which have a low impact on product use, in front of which the user can complete the process 

Problems that have a limited impact on the use of the product, in the face of which the user manages to complete the process and is only partially disturbed.

:::tip
These can be any kind of bug.
:::

#### High

Problems that have a significant impact the use of the product and they happen mostly in the main sections, in the face of which the user may not be able to continue using the digital product in the way he/she wants (or as intended) and/or may be upset and limited.

:::tip
These are usually MALFUNCTION, CRASH, PERFORMANCE or SECURITY bugs.
:::

#### Critical

Problems preventing the completion of the strictly main actions, often resulting in a system crash. The user cannot in any way to continue using the digital product as he wishes, being severely disturbed and restricted.

:::tip
These are mainly MALFUNCTION or CRASH bugs.
:::

### Replicability
One time only
The bug occurred only once and it couldn’t be reproduced further on.

#### Sometimes

Given the same conditions and processes, the bug occurs sporadically/unpredictably, but can always be reproduced by making several attempts.

#### Always

The bug occurs, all the conditions and processes are the same, with each replication attempt. To be such, the bug must be successfully reproduced at least 3/3 times.