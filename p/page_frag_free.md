# Function: <code>page_frag_free</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811b7bf0)
Location: mm/page_alloc.c:4018
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
**Symbols:**

```
ffffffff811b7bf0-ffffffff811b7c55: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811bfa30)
Location: mm/page_alloc.c:4305
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
**Symbols:**

```
ffffffff811bfa30-ffffffff811bfa96: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811d4560)
Location: mm/page_alloc.c:4424
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - kernel/bpf/cpumap.c:__cpu_map_queue_destructor
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
```
**Symbols:**

```
ffffffff811d4560-ffffffff811d45c6: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff811f5f80)
Location: mm/page_alloc.c:4556
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff811f5f80-ffffffff811f5fe7: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81209460)
Location: mm/page_alloc.c:4727
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff81209460-ffffffff812094d2: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81270770)
Location: mm/page_alloc.c:4894
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff81270770-ffffffff812707e1: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127f5b0)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff8127f5b0-ffffffff8127f621: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812b1500)
Location: mm/page_alloc.c:5015
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff812b1500-ffffffff812b1571: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812bd5e0)
Location: mm/page_alloc.c:5194
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff812bd5e0-ffffffff812bd653: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c2570)
Location: mm/page_alloc.c:5397
Inline: False
Direct callers:
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:skb_release_data
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff812c2570-ffffffff812c25e3: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81305f40)
Location: mm/page_alloc.c:5578
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff81305f40-ffffffff81305fbb: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8136dfc0)
Location: mm/page_alloc.c:5633
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff8136dfc0-ffffffff8136e0b3: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff813ea300)
Location: mm/page_alloc.c:5772
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff813ea300-ffffffff813ea3f3: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8141f2e0)
Location: mm/page_alloc.c:4700
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff8141f2e0-ffffffff8141f3b7: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8144bfa0)
Location: mm/page_alloc.c:4789
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
```
**Symbols:**

```
ffffffff8144bfa0-ffffffff8144c077: page_frag_free (STB_GLOBAL)
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
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff800010317228)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffff800010317228-ffff8000103172c4: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531928)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
c0531928-c05319b8: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003e95b0)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
c0000000003e95b0-c0000000003e9664: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe00021d484)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffe00021d484-ffffffe00021d510: page_frag_free (STB_GLOBAL)
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
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81277c00)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff81277c00-ffffffff81277c71: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81269b10)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff81269b10-ffffffff81269b81: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812759a0)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff812759a0-ffffffff81275a11: page_frag_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void page_frag_free(void *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81285560)
Location: mm/page_alloc.c:4912
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_free_head
  - net/core/skbuff.c:__napi_alloc_skb
  - net/core/skbuff.c:__netdev_alloc_skb
  - net/core/xdp.c:__xdp_return
  - net/xdp/xsk_queue.c:xskq_destroy
```
**Symbols:**

```
ffffffff81285560-ffffffff812855d1: page_frag_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
