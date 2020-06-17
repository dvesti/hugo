---
title: "Shortcodes Notice Preview"
date: 2018-03-03T16:01:23+08:00
lastmod: 2018-03-04T16:01:23+08:00
draft: true
tags: ["preview", "shortcodes", "tag-6"]
categories: ["docs", "shortcodes", "index"]
---

Не все _шорккоды_ работают корректно. Скорее всего из-за их отсутствия: будем искать и исправлять пост.

**Дополнено**: Поменял `% %` на `< >` и дело пошло...  

## normal use

`Note` example:

```shortcode
{{</* notice note */>}}
<p>A notice disclaimer</p>
{{</* /notice */>}}
```

**Result:**

{{< notice note >}}
<p>A notice disclaimer</p>
{{< /notice >}}
<!--more-->
You could **custom title** :

```shortcode
{{</* notice note Примечание */>}}
<p>A notice disclaimer</p>
{{</* /notice */>}}
```

{{< notice note Примечание >}}
<p>A notice disclaimer</p>
{{< /notice >}}


## tip

```shortcode
{{</* notice tip */>}}
<p>A tip disclaimer</p>
{{</* /notice */>}}
```

{{< notice tip >}}
<p>A tip disclaimer</p>
{{< /notice >}}

## info
```shortcode
{{</* notice info */>}}
<p>A info disclaimer</p>
{{</* /notice */>}}
```

{{< notice info >}}
<p>An information disclaimer</p>
{{< /notice >}}

## warning
```shortcode
{{</* notice warning */>}}
<p>A warning disclaimer</p>
{{</* /notice */>}}
```

{{< notice warning >}}
<p>An warning disclaimer</p>
{{< /notice >}}
