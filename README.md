# YouTube Cleaner Filters 

A custom **uBlock Origin filter list** that removes Shorts, ads, comments, infinite scroll, and other distractions from YouTube.  

## Features

-  Hide YouTube **Shorts** everywhere (homepage, sidebar, search, subscriptions, channels)  
-  Remove **ads & promo banners**  
-  Hide **comments section** and engagement junk  
-  Disable **infinite scrolling** on homepage & search  
-  Remove **notification bell**, sidebars, “For You” sections  
-  Clean up UI for focus-friendly watching  

## Installation



Install [uBlock Origin](https://github.com/gorhill/uBlock).  



## Option 1:

Copy and paste the filtes.txt content in **My 
Filters** section of ublock origin and click apply changes. 

## Option 2:

1. Open **Dashboard → Filter lists → Custom → Import**.

2. Add this URL (replace with your repo’s raw link):  

https://github.com/Trazer09/YouTube-Focus-Mode/filters.txt


3. Click **Apply changes**.  

Your YouTube will now be distraction-free ✅.  

## Example Rules

```txt
! Hide all videos with the shorts indicator on the thumbnail
www.youtube.com##ytd-grid-video-renderer:has([overlay-style="SHORTS"])

! Remove masthead banner ad
www.youtube.com###masthead-ad

! Hide comments
www.youtube.com###comments
```


## Notes

Some filters are commented out (! in front) so you can enable them manually.

This list is actively maintained to keep up with YouTube’s UI changes.