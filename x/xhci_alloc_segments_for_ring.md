# Function: <code>xhci_alloc_segments_for_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81652f30)
Location: drivers/usb/host/xhci-mem.c:318
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff81652f30-ffffffff81653021: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b4240)
Location: drivers/usb/host/xhci-mem.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff816b4240-ffffffff816b4337: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e23f0)
Location: drivers/usb/host/xhci-mem.c:328
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff816e23f0-ffffffff816e24e7: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f65b0)
Location: drivers/usb/host/xhci-mem.c:327
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff816f65b0-ffffffff816f66a7: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81762f30)
Location: drivers/usb/host/xhci-mem.c:316
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81762f30-ffffffff81763027: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a30b0)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff817a30b0-ffffffff817a31a3: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c93a0)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff817c93a0-ffffffff817c9493: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81809120)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81809120-ffffffff81809219: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81839fe0)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81839fe0-ffffffff8183a0d9: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190ca70)
Location: drivers/usb/host/xhci-mem.c:318
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff8190ca70-ffffffff8190cb9c: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81914440)
Location: drivers/usb/host/xhci-mem.c:321
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81914440-ffffffff819145eb: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f7850)
Location: drivers/usb/host/xhci-mem.c:321
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff818f7850-ffffffff818f79fb: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81995e20)
Location: drivers/usb/host/xhci-mem.c:321
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81995e20-ffffffff81995fcb: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af2df0)
Location: drivers/usb/host/xhci-mem.c:321
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81af2df0-ffffffff81af2fb4: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c802e0)
Location: drivers/usb/host/xhci-mem.c:321
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81c802e0-ffffffff81c804a4: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce6fc0)
Location: drivers/usb/host/xhci-mem.c:321
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81ce6fc0-ffffffff81ce7184: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int num, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9c3f0)
Location: drivers/usb/host/xhci-mem.c:329
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81d9c3f0-ffffffff81d9c5cc: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a77ac8)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffff800010a77ac8-ffff800010a77bf4: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4b65c)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
c0b4b65c-c0b4b768: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4f4b0)
Location: drivers/usb/host/xhci-mem.c:318
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
c000000000b4f4b0-c000000000b4f670: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00068f626)
Location: drivers/usb/host/xhci-mem.c:318
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffe00068f626-ffffffe00068f70a: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f2390)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff817f2390-ffffffff817f2489: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b7530)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff817b7530-ffffffff817b7629: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182ee60)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff8182ee60-ffffffff8182ef59: xhci_alloc_segments_for_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xhci_alloc_segments_for_ring(struct xhci_hcd *xhci, struct xhci_segment **first, struct xhci_segment **last, unsigned int num_segs, unsigned int cycle_state, enum xhci_ring_type type, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81848fd0)
Location: drivers/usb/host/xhci-mem.c:318
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
```
**Symbols:**

```
ffffffff81848fd0-ffffffff818490c9: xhci_alloc_segments_for_ring (STB_LOCAL)
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
<code>xhci, first, last, num_segs, cycle_state, type, flags</code> ➡️ <code>xhci, first, last, num_segs, cycle_state, type, max_packet, flags</code>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, first, last, num_segs, cycle_state, type, max_packet, flags</code> ➡️ <code>xhci, first, last, num_segs, num, cycle_state, type, max_packet, flags</code>
</li>
</ul>
</details>
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
