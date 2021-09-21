---
title: plugins
tags:
---
Blockquote

{% blockquote [author[, source]] [link] [source_link_title] %}
content
{% endblockquote %}

Image

Inserts an image with specified size.

{% img [class names] /path/to/image [width] [height] '"title text" "alt text"' %}
Link

Inserts a link with target="_blank" attribute.

{% link text url [external] [title] %}

YouTube

Inserts a YouTube video.

{% youtube video_id [type] [cookie] %}
Examples

Embed a video

{% youtube lJIrF4YjHfQ %}
Embed a playlist

{% youtube PL9hW1uS6HUfscJ9DHkOSoOX45MjXduUxo 'playlist' %}
Enable privacy-enhanced mode

YouTube’s cookie is not used in this mode.

{% youtube lJIrF4YjHfQ false %}
{% youtube PL9hW1uS6HUfscJ9DHkOSoOX45MjXduUxo 'playlist' false %}


