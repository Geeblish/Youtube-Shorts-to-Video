# Youtube-Shorts-to-Video
Opens a YouTube Short as a regular YouTube Video


I binge YouTube shorts a lot but sometimes I want to save that one short to the a playlist or open it as a regular video to be able to scroll through it. I made a nifty bookmark that allows you to do just that .

Here's the code and all you need to do is drag it to the bookmark bar and you're all set:

`javascript:!window.location.href.includes("shorts") ? console.error("Short not found") :window.open(window.location.href.replace('/shorts/','/watch?v='));`

Try going to a short and test it yourself!


![brave_58SYwf7JWD](https://github.com/Geeblish/Youtube-Shorts-to-Video/assets/60635068/d772128a-3039-4d82-9120-cd71047c2449)
