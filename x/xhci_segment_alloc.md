# Function: <code>xhci_segment_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81652e10)
Location: drivers/usb/host/xhci-mem.c:39
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81652e10-ffffffff81652f26: xhci_segment_alloc.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b4100)
Location: drivers/usb/host/xhci-mem.c:39
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff816b4100-ffffffff816b4232: xhci_segment_alloc.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e22b0)
Location: drivers/usb/host/xhci-mem.c:39
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff816e22b0-ffffffff816e23e2: xhci_segment_alloc.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f64a0)
Location: drivers/usb/host/xhci-mem.c:39
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff816f64a0-ffffffff816f65af: xhci_segment_alloc.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81762e20)
Location: drivers/usb/host/xhci-mem.c:28
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81762e20-ffffffff81762f2f: xhci_segment_alloc.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a2f70)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
```
**Symbols:**

```
ffffffff817a2f70-ffffffff817a30a1: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c9260)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
```
**Symbols:**

```
ffffffff817c9260-ffffffff817c939c: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81808fe0)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81808fe0-ffffffff8180911a: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81839ea0)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81839ea0-ffffffff81839fda: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190c930)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff8190c930-ffffffff8190ca68: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81914300)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81914300-ffffffff81914438: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f75d0)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff818f75d0-ffffffff818f7708: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81995c90)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81995c90-ffffffff81995e15: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af2b00)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81af2b00-ffffffff81af2cb6: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c80020)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81c80020-ffffffff81c801d1: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce6d00)
Location: drivers/usb/host/xhci-mem.c:29
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81ce6d00-ffffffff81ce6eb1: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, unsigned int num, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9c1f0)
Location: drivers/usb/host/xhci-mem.c:29
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81d9c1f0-ffffffff81d9c3d4: xhci_segment_alloc (STB_LOCAL)
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
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a77988)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffff800010a77988-ffff800010a77ac8: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4b520)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
c0b4b520-c0b4b65c: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4f320)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
c000000000b4f320-c000000000b4f4b0: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00068f548)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffe00068f548-ffffffe00068f626: xhci_segment_alloc (STB_LOCAL)
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
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f2250)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff817f2250-ffffffff817f238a: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b73f0)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff817b73f0-ffffffff817b752a: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182ed20)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff8182ed20-ffffffff8182ee5a: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct xhci_segment *xhci_segment_alloc(struct xhci_hcd *xhci, unsigned int cycle_state, unsigned int max_packet, gfp_t flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81848e90)
Location: drivers/usb/host/xhci-mem.c:28
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81848e90-ffffffff81848fca: xhci_segment_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>xhci, cycle_state, max_packet, flags</code> ➡️ <code>xhci, cycle_state, max_packet, num, flags</code>
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
