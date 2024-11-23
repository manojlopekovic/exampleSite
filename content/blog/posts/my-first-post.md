---
title: "My First Post"
date: 2024-11-23T14:33:08+01:00
draft: true
ShowToc: true
tags: ["hugo", "web", "blog"]
categories: ["tech"]
keywords: ["static site", "tutorial"]
summary: " "
---

#### Shows how to highlight 

{{< highlight go-html-template "lineNos=inline, lineNoStart=42" >}}
{{ range .Pages }}
  <h2><a href="{{ .RelPermalink }}">{{ .LinkTitle }}</a></h2>
{{ end }}
{{< /highlight >}}

#### How to add picture
{{< figure src="https://cdn.pixabay.com/photo/2016/05/28/08/32/elephant-1421167_1280.jpg" caption="An elephant at sunset" height="200vh">}}


#### Display an instagram post with url
<!-- https://www.instagram.com/p/CxOWiQNP2MO/ -->
{{< instagram CxOWiQNP2MO >}}

#### ref shortcode returns permalink of the given page reference
[Post 1]({{% ref "/blog/posts/my-first-post.md" %}})

#### relef shortcode returns permalink of the given page reference, relative
[Post 1]({{% relref "/blog/posts/my-first-post.md" %}})

#### To display a twitter post with URL
<!-- https://x.com/SanDiegoZoo/status/1453110110599868418 -->
{{< twitter user="SanDiegoZoo" id="1453110110599868418" >}}

#### To display a Vimeo video with link
<!-- https://vimeo.com/channels/staffpicks/55073825 -->
{{< vimeo id="146022717" class="my-vimeo-wrapper-class" title="My vimeo video" >}}

#### To display a Youtube video with link
<!-- https://www.youtube.com/watch?v=0RKpf3rK57I -->
{{< youtube id=0RKpf3rK57I start=30 end=60 loading=lazy >}}