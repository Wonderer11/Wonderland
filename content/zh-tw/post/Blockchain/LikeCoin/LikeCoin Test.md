---
title: LikeCoin 測試 Markdown
description: 這是測試LikeCoin插件的頁面。
categories:
  - Test
tags:
  - LikeCoin
  - LikeCoin Button
  - Like Pay
---
# Like Button

## Iframe
```
<iframe class="LikeCoin"
 src="https://button.like.co/in/embed/h47388304/button?referrer={{ .Permalink }}"
 width="100%"
 frameborder=0>
</iframe>
```

<iframe class="LikeCoin"
 src="https://button.like.co/in/embed/h47388304/button?referrer={{ .Permalink }}"
 width="100%"
 frameborder=0>
</iframe>

```
<iframe class="LikeCoin"
 src="https://button.like.co/in/embed/{{ .Site.Params.LikerID }}/button?referrer={{ .Permalink }}"
 width="100%"
 frameborder=0>
</iframe>
```

<iframe class="LikeCoin"
 src="https://button.like.co/in/embed/{{ .Site.Params.LikerID }}/button?referrer={{ .Permalink }}"
 width="100%"
 frameborder=0>
</iframe>

## LikeCoin button SDK demo
```
<div class="likecoin-embed likecoin-button"
 data-liker-id="h47388304"
 data-href="https://docs.like.co/developer/likecoin-button/">
</div>
<script src="https://static.like.co/sdk/v1/button.js"></script>
```

<div class="likecoin-embed likecoin-button"
 data-liker-id="h47388304"
 data-href="https://docs.like.co/developer/likecoin-button/">
</div>
<script src="https://static.like.co/sdk/v1/button.js"></script>

```
<div class="likecoin-embed likecoin-button"
 data-liker-id= {{ .Site.Params.LikerID }}
 data-href="https://docs.like.co/developer/likecoin-button/">
</div>
<script src="https://static.like.co/sdk/v1/button.js"></script>
```

<div class="likecoin-embed likecoin-button"
 data-liker-id= {{ .Site.Params.LikerID }}
 data-href="https://docs.like.co/developer/likecoin-button/">
</div>
<script src="https://static.like.co/sdk/v1/button.js"></script>

# Likepay
```
<iframe class="Like Pay"
 src="https://like.co/h47388304"
 width="100%"
 frameborder=0>
</iframe>
```

<iframe class="Like Pay"
 src="https://like.co/h47388304"
 width="100%"
 frameborder=0>
</iframe>

```
<iframe class="Like Pay 10"
 src="https://like.co/in/widget/pay?to=h47388304&amount=10"
 width="100%"
 frameborder="0">
</iframe>
```

<iframe class="Like Pay 10"
 src="https://like.co/in/widget/pay?to=h47388304&amount=10"
 width="100%"
 frameborder="0">
</iframe>

