
---
sidebar-position: 2
---

# Bug reporting rules

Refer to the rules shown in this article any time you have to fill in the different fields of a bug reporting form; in this way, your bugs will be approved faster and with less supplementary requests, you will also earn more experience points.

Bugs considered to be too concise or showing writing errors, or which don’t respect these rules might be directly refused: each bug must always be written in order to be understood without viewing the attachments.

### Bug title
The title must show the section or the process where the problem occurs written in square brackets (not the name or the number of the use case), followed by a brief and understandable overview of the problem, so that it can be clearly understood and identified.

:::danger Bad title

[Home] – Error

:::

:::tip Good title

[Login] – Impossible to access by using the correct credentials

:::

### Step-by-step description
The bug description must show a bulleted list of the actions to carry out to replicate the process that brought you to the problem. Every single step must be clearly reported in one line (preceded by its number), in order to identify the user behaviour on the product (e.g. tap, click, back on the smartphone or on the browser) and other choices made or the buttons clicked (the names of the sections or of the buttons must be written in quotation marks). Furthermore, any possible precondition must be made explicit in the first points.
Attention: the last step should not be the description of the Bug. This should be described in the “Actual result” field.

:::danger Bad description
 - Open the App;
 - Click on Login;
 - Loading.
:::

:::tip Good description
 - Open the newly installed app and land on the login page;
 - Fill in the fields with a correct credential;
 - Click on the “Login” button.
:::

### Expected result 
The expected result must exclusively describe the expected behaviour of the digital product, which did not occur, always referring to the context where the bug appeared.

:::danger Bad Expected result
Login.
:::

:::tip Good Expected result
The user is supposed to view the area reserved to the users who logged in.
:::


### Actual result
The actual result describes the product behaviour in a comprehensive manner, with reference to the bug which occurred within its replicability context.

Any similar behaviour which occurs by following slightly different procedures must be reported in this field, and you should also report any additional detail about the bug replicability.

:::danger Bad Actual result
The login does not work.
:::

:::tip Good Actual result
Endless display of loading icon, with no possibility to access. Even if I try with “recover credentials” the problem still occurs every time.
:::

### Additional comments
Additional comments are not always mandatory and they are reserved to general remarks which don’t detail the steps, but help better understand the context of the problem.

:::danger Bad Additional comments
None.
:::

:::tip Good Additional comments
The problem occurs only on the Android version of the app.
:::

### Upload files
Every bug must always be uploaded with some attachments to facilitate the understanding of the problem, then either 2 screenshots or 1 screenshot and 1 video where the actions carried out and the result obtained are shown. It is always mandatory to upload at least 1 screenshot and 1 video(*).

The video must be long enough to show the steps performed and the problem occurring;
When recording the video, it is prohibited to record audio telling what you are doing;
For more information, see the article about how to record the device screen.

:::info video (*)
Only in the TYPO case you can not attach the video, but 2 screenshots.
:::
