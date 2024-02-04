# Bili-Blocked

> Out of sight, out of mind. Block certain video information on Bilibili based on key details.

Original repository: [ZanwingMak/bilibili-out-of-sight-out-of-mind](https://github.com/ZanwingMak/bilibili-out-of-sight-out-of-mind.git)

## Requirements

- Fix the video blocking functionality implemented in the original repository, modify the blocking method to **append to the browser context menu**

    - Hover over a video, right-click to block the user (including all videos from that user), block the video (only that video, not the user).
    - Hover over a name
        - Block this uploader
        - (In the comment section) Block the commenter
    
    - Specify the blocking reason or use the default.
    - When encountering blocked content, display user and blocking reason when the mouse hovers over it.
- Official blacklists have limits, manually add users to the blacklist.
    - Danmaku: Delete directly.
    - Video: Replace cover and text as per the original repository.
    - Comment section: Replace text.
- Regarding keyword-related storage
    - Does it require server-side login?
    - Does the plugin user data area store it independently?
- Related pages (Adapt to the new version?)
    - Homepage
    - Search page
    - Individual video playback page, including recommended videos after playback.

## Expected Reference

![Reference Image 1](https://tuchuang.laji.blog/imgs/2020/08/211821308a0cafd6.png)

---

![Reference Image 2](https://tuchuang.laji.blog/imgs/2020/08/1d13c6ae5c040461.png)

## Expected Outcome

![Expected Effect 1](https://tuchuang.laji.blog/imgs/2020/08/c88071e4382d0388.png)

---

![Expected Effect 2](https://tuchuang.laji.blog/imgs/2020/08/a0303b7c587d8c82.png)

---

![Expected Effect 3](https://tuchuang.laji.blog/imgs/2020/08/456e2e5533b0414d.png)

---

![Expected Effect 4](https://tuchuang.laji.blog/imgs/2020/08/fa4f7cb8416914a0.png)
