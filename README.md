<h1>
  <img src="logo.png" alt="logo" style="height: 1em; vertical-align: middle">
  Minimo
</h1>

A maintained library of content-blocker filters for social media web-apps.

Minimo's lists filter content using CSS selectors. They work with any application that supports the Adblock filter syntax, including [Brave](https://brave.com/privacy-updates/10-custom-filter-lists/) and [uBlock](https://github.com/gorhill/uBlock/wiki/Dashboard:-Filter-lists).

## Usage
You can browse the repository and manually add the filters you want, updating them whenever there's a change to the codebase fixing outdated syntax. To do this automatically, if your content-blocker allows adding external lists, simply copy and paste the following `url` that applies.

### Instagram
* Mobile:
  ```
  https://raw.githubusercontent.com/vovirexu/minimo-social/refs/heads/main/instagram/instagram_mobile.txt
  ```
* Desktop:
  ```
  https://raw.githubusercontent.com/vovirexu/minimo-social/refs/heads/main/instagram/instagram_desktop.txt
  ```
  ### Filters
  * Mobile and desktop:
    * Home feed and stories
    * Reels
    * Explore
  * Mobile exclusive:
    * Create
  * Desktop exclusive:
    * More from Meta
   
## Roadmap
- [x] Instagram initial support
- [ ] YouTube initial support
