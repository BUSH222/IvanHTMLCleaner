# IvanHTMLCleaner
An application that removes useless information from ivan's html text.
The returned text is published in the [Information System "History of Geology and Mining"](http://higeo.ginras.ru/)


### Tags or text getting modified or replaced

1. Removes `<span>` and `</span>` tags.
2. Removes `<span>` and `</span>` tags.
3. Removes `<div>` and `</div>` tags.
4. Replaces any text between `<style>` and `</style>` tags with the `rightstyle` string.
5. Replaces the unicode character `\u2013` (en dash) with a hyphen `-`.
6. Replaces any text between `<title>` and `</title>` tags with a specific string.
7. Replaces `MsoNormalCxSpFirst` with `GIN`.
8. Replaces `MsoNormalCxSpMiddle` with `GIN`.
9. Replaces `MsoNormalCxSpLast` with `GIN`.
10. Replaces the HTML entity `&nbsp;` (non-breaking space) with a regular space.
11. Replaces `</i><i>` with an empty string.
12. Replaces `</b><b>` with an empty string.
13. Replaces space followed by `<p>` with just `<p>`.
14. Replaces space followed by `</p>` with just `</p>`.
15. Removes `double quotes`.
16. Removes `single quotes`.
17. Replaces the cap `&#774` from a russian cyrillic character with the character
18. Replaces `<em>` tags with `<i>` tags.
19. Replaces `</em>` tags with `</i>` tags.
20. Replaces `double spaces` with `single spaces`.
21. Replaces `triple line breaks` with `double line breaks`.
22. Replaces the unicode character `\u00A0` (non-breaking space) with a `regular space`.
23. Removes a specific meta tag `<meta name=Generator content=Microsoft Word 15 (filtered)>`.
24. Replaces `<body lang=RU link=blue vlink=purple style=word-wrap:break-word>` with `<body lang=RU>`.