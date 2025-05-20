# Function: <code>virtqueue_add_outbuf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff814c0040)
Location: drivers/virtio/virtio_ring.c:311
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/char/virtio_console.c:__send_control_msg
  - drivers/net/virtio_net.c:start_xmit
```
**Symbols:**

```
ffffffff814c0040-ffffffff814c02c5: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815105e0)
Location: drivers/virtio/virtio_ring.c:481
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/net/virtio_net.c:start_xmit
```
**Symbols:**

```
ffffffff815105e0-ffffffff81510907: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8153c740)
Location: drivers/virtio/virtio_ring.c:481
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8153c740-ffffffff8153ca68: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81550420)
Location: drivers/virtio/virtio_ring.c:486
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81550420-ffffffff81550740: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815b3c10)
Location: drivers/virtio/virtio_ring.c:485
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff815b3c10-ffffffff815b3f45: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff815ebce0)
Location: drivers/virtio/virtio_ring.c:484
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff815ebce0-ffffffff815ebffa: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81606e70)
Location: drivers/virtio/virtio_ring.c:1754
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:report_free_page_func
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81606e70-ffffffff81606e9b: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81639440)
Location: drivers/virtio/virtio_ring.c:1759
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81639440-ffffffff81639ace: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8165b1c0)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8165b1c0-ffffffff8165babd: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170bd50)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8170bd50-ffffffff8170bd9c: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81728bc0)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81728bc0-ffffffff81728c0c: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8170c2e0)
Location: drivers/virtio/virtio_ring.c:1760
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8170c2e0-ffffffff8170c32c: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1858
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81cf4ce3-ffffffff81cf4d0d: virtqueue_add_outbuf.cold (STB_LOCAL)
ffffffff81788650-ffffffff817886c2: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:1862
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81ebce55-ffffffff81ebce80: virtqueue_add_outbuf.cold (STB_LOCAL)
ffffffff818bfc70-ffffffff818bfd09: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2148
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff820943db-ffffffff82094406: virtqueue_add_outbuf.cold (STB_LOCAL)
ffffffff81a0fb10-ffffffff81a0fba9: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2185
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
**Symbols:**

```
ffffffff8211516e-ffffffff82115199: virtqueue_add_outbuf.cold (STB_LOCAL)
ffffffff81a58c60-ffffffff81a58cf9: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_ring.c (0)
Location: drivers/virtio/virtio_ring.c:2262
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
  - drivers/net/virtio_net.c:xmit_skb
  - drivers/net/virtio_net.c:__virtnet_xdp_xmit_one
```
**Symbols:**

```
ffffffff821f2ddb-ffffffff821f2e06: virtqueue_add_outbuf.cold (STB_LOCAL)
ffffffff81aaa0f0-ffffffff81aaa189: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffff8000108244f8)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffff8000108244f8-ffff800010824c04: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c09428d4)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
c09428d4-c0943358: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (c0000000008ce070)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
c0000000008ce070-c0000000008ced04: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffe00051abcc)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffe00051abcc-ffffffe00051b3dc: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81621060)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81621060-ffffffff8162195d: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff816156b0)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff816156b0-ffffffff81615fad: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff8164f000)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff8164f000-ffffffff8164f8fd: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int virtqueue_add_outbuf(struct virtqueue *vq, struct scatterlist *sg, unsigned int num, void *data, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_ring.c (ffffffff81669690)
Location: drivers/virtio/virtio_ring.c:1758
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
  - drivers/virtio/virtio_balloon.c:init_vqs
  - drivers/virtio/virtio_balloon.c:update_balloon_stats_func
  - drivers/virtio/virtio_balloon.c:tell_host
  - drivers/char/virtio_console.c:__send_to_port
```
**Symbols:**

```
ffffffff81669690-ffffffff81669f8d: virtqueue_add_outbuf (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
