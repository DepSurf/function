# Function: <code>skb_add_rx_frag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817052c0)
Location: net/core/skbuff.c:531
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff817052c0-ffffffff81705340: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176be90)
Location: net/core/skbuff.c:532
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8176be90-ffffffff8176bf10: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799070)
Location: net/core/skbuff.c:532
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81799070-ffffffff817990f0: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7630)
Location: net/core/skbuff.c:531
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff817b7630-ffffffff817b76b1: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182fcb0)
Location: net/core/skbuff.c:502
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8182fcb0-ffffffff8182fd31: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81879a90)
Location: net/core/skbuff.c:502
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81879a90-ffffffff81879b11: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189a6e0)
Location: net/core/skbuff.c:509
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8189a6e0-ffffffff8189a758: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e53f0)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff818e53f0-ffffffff818e5466: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917580)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81917580-ffffffff819175f6: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eaa90)
Location: net/core/skbuff.c:542
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff819eaa90-ffffffff819eaafb: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea7d0)
Location: net/core/skbuff.c:556
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_fill_frags
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff819ea7d0-ffffffff819ea83b: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0d90)
Location: net/core/skbuff.c:603
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff819d0d90-ffffffff819d0e04: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a80d70)
Location: net/core/skbuff.c:605
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a80d70-ffffffff81a80de1: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf6030)
Location: net/core/skbuff.c:605
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81bf6030-ffffffff81bf60ee: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da4db0)
Location: net/core/skbuff.c:765
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81da4db0-ffffffff81da4e6e: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e13e70)
Location: net/core/skbuff.c:847
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81e13e70-ffffffff81e13f7b: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed10b0)
Location: net/core/skbuff.c:848
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:receive_mergeable
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/virtio_net.c:page_to_skb
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - net/xdp/xsk.c:xsk_build_skb
```
**Symbols:**

```
ffffffff81ed10b0-ffffffff81ed11b8: skb_add_rx_frag (STB_GLOBAL)
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
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0838)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffff800010bb0838-ffff800010bb08f4: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0ccdee0)
Location: net/core/skbuff.c:543
Inline: False
```
**Symbols:**

```
c0ccdee0-c0ccdf68: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c86a30)
Location: net/core/skbuff.c:543
Inline: False
```
**Symbols:**

```
c000000000c86a30-c000000000c86ad8: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741976)
Location: net/core/skbuff.c:543
Inline: False
```
**Symbols:**

```
ffffffe000741976-ffffffe000741a24: skb_add_rx_frag (STB_GLOBAL)
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
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7580)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff818b7580-ffffffff818b75f6: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818714d0)
Location: net/core/skbuff.c:543
Inline: False
```
**Symbols:**

```
ffffffff818714d0-ffffffff81871546: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908580)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81908580-ffffffff819085f6: skb_add_rx_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_add_rx_frag(struct sk_buff *skb, int i, struct page *page, int off, int size, unsigned int truesize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929560)
Location: net/core/skbuff.c:543
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81929560-ffffffff819295d6: skb_add_rx_frag (STB_GLOBAL)
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
