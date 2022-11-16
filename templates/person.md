---
tags: person
---
<%*
let title = tp.file.title
if (title.startsWith("Untitled")) {
title = await tp.system.prompt("Name");
}
await tp.file.rename(title);
tp.file.move("people/" + title);
-%>


## <mark style="background: #FFB8EBA6;">Literature</mark>
---

## <mark class="hltr-purple">Location</mark>
---

## <mark style="background: #FF5582A6;">Events</mark>
---

## <mark style="background: #BBFABBA6;">Characters</mark>
---

## <mark style="background: #ABF7F7A6;">Objects</mark>
---

## <mark style="background: #FFF3A3A6;">Mentions</mark>
---

## <mark style="background: #CACFD9A6;">After</mark>
---