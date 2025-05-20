# Function: <code>xhci_link_segments</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81652ac0)
Location: drivers/usb/host/xhci-mem.c:98
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81652ac0-ffffffff81652b2e: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b33a0)
Location: drivers/usb/host/xhci-mem.c:108
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff816b33a0-ffffffff816b340e: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e1550)
Location: drivers/usb/host/xhci-mem.c:108
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff816e1550-ffffffff816e15be: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f56b0)
Location: drivers/usb/host/xhci-mem.c:108
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff816f56b0-ffffffff816f5718: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817620f0)
Location: drivers/usb/host/xhci-mem.c:97
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff817620f0-ffffffff81762158: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a2ab0)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff817a2ab0-ffffffff817a2b1f: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c8c80)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
```
**Symbols:**

```
ffffffff817c8c80-ffffffff817c8cef: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81808a50)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81808a50-ffffffff81808abf: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81839910)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81839910-ffffffff8183997f: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190c350)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff8190c350-ffffffff8190c3bf: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81915041)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f8560)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81996c56)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af3b60)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c81140)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce7e65)
Location: drivers/usb/host/xhci-mem.c:100
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d637)
Location: drivers/usb/host/xhci-mem.c:102
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
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
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a77448)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffff800010a77448-ffff800010a774e0: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4af70)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
c0b4af70-c0b4b004: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4fa2c)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
c000000000b4dc80-c000000000b4dce8: xhci_link_segments.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe000690172)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffe00068ef0c-ffffffe00068ef92: xhci_link_segments.part.0 (STB_LOCAL)
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
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f1cc0)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff817f1cc0-ffffffff817f1d2f: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b6e60)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff817b6e60-ffffffff817b6ecf: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182e790)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff8182e790-ffffffff8182e7ff: xhci_link_segments (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xhci_link_segments(struct xhci_hcd *xhci, struct xhci_segment *prev, struct xhci_segment *next, enum xhci_ring_type type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81848880)
Location: drivers/usb/host/xhci-mem.c:99
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_ring_expansion
  - drivers/usb/host/xhci-mem.c:xhci_alloc_segments_for_ring
```
**Symbols:**

```
ffffffff81848880-ffffffff818488ef: xhci_link_segments (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
