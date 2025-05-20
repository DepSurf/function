# Function: <code>xhci_alloc_stream_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81654ef0)
Location: drivers/usb/host/xhci-mem.c:655
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81654ef0-ffffffff816552a8: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b58e0)
Location: drivers/usb/host/xhci-mem.c:667
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff816b58e0-ffffffff816b5cb4: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e3a90)
Location: drivers/usb/host/xhci-mem.c:667
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff816e3a90-ffffffff816e3e64: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f7aa0)
Location: drivers/usb/host/xhci-mem.c:621
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff816f7aa0-ffffffff816f7e34: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817647c0)
Location: drivers/usb/host/xhci-mem.c:608
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff817647c0-ffffffff81764b5d: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a4a80)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff817a4a80-ffffffff817a4e83: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817cae50)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff817cae50-ffffffff817cb1a5: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8180b220)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff8180b220-ffffffff8180b581: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8183c1e0)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff8183c1e0-ffffffff8183c541: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190ef60)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff8190ef60-ffffffff8190f2f8: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81916ac0)
Location: drivers/usb/host/xhci-mem.c:621
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81916ac0-ffffffff81916e58: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f9f40)
Location: drivers/usb/host/xhci-mem.c:604
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff818f9f40-ffffffff818fa2d8: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81998c60)
Location: drivers/usb/host/xhci-mem.c:604
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81998c60-ffffffff81999051: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af5c60)
Location: drivers/usb/host/xhci-mem.c:603
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81af5c60-ffffffff81af6030: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c83580)
Location: drivers/usb/host/xhci-mem.c:603
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81c83580-ffffffff81c83964: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81cea2c0)
Location: drivers/usb/host/xhci-mem.c:589
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81cea2c0-ffffffff81cea688: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9fb30)
Location: drivers/usb/host/xhci-mem.c:600
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81d9fb30-ffffffff81d9ff15: xhci_alloc_stream_info (STB_GLOBAL)
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
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a79fe0)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffff800010a79fe0-ffff800010a7a328: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4d954)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
c0b4d954-c0b4dc8c: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b517c0)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
c000000000b517c0-c000000000b51c00: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000691738)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffe000691738-ffffffe000691a14: xhci_alloc_stream_info (STB_GLOBAL)
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
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f4590)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff817f4590-ffffffff817f48f1: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b9730)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff817b9730-ffffffff817b9a91: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81831060)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff81831060-ffffffff818313c1: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xhci_stream_info *xhci_alloc_stream_info(struct xhci_hcd *xhci, unsigned int num_stream_ctxs, unsigned int num_streams, unsigned int max_packet, gfp_t mem_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8184b230)
Location: drivers/usb/host/xhci-mem.c:612
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff8184b230-ffffffff8184b591: xhci_alloc_stream_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int max_packet</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, num_stream_ctxs, num_streams, mem_flags</code> ➡️ <code>xhci, num_stream_ctxs, num_streams, max_packet, mem_flags</code>
</li>
</ul>
</details>
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
