This is a clunky workaround to address the issue captured here:
https://issuetracker.google.com/issues/323011272

In summary, the latest release of Google maps Platform removed the ability to import JSON styles. This provides an alternative, albeit pretty ugly.

Video of the steps is available here:
https://youtu.be/YyuyqPVQNrs


When inserting the JSON into request (I fluff this at around 2:20 in the video), search for these two strings and place the JSON between them: 

**start:** `rules:\":` *(keep the open square bracket immediately after this string)* 

**end:** `],\"` *(keep the close square bracket at the start this string)*
