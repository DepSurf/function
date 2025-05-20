# Function: <code>dwc2_alloc_dma_aligned_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81686a9b)
Location: drivers/usb/dwc2/hcd.c:2560
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b4ccb)
Location: drivers/usb/dwc2/hcd.c:2591
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c902b)
Location: drivers/usb/dwc2/hcd.c:2604
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8173553b)
Location: drivers/usb/dwc2/hcd.c:2610
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81774601)
Location: drivers/usb/dwc2/hcd.c:2694
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81799901)
Location: drivers/usb/dwc2/hcd.c:2684
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817d8b51)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818099e1)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818da360)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
```
**Symbols:**

```
ffffffff818da360-ffffffff818da400: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e4280)
Location: drivers/usb/dwc2/hcd.c:2503
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
```
**Symbols:**

```
ffffffff818e4280-ffffffff818e4320: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c7140)
Location: drivers/usb/dwc2/hcd.c:2501
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
```
**Symbols:**

```
ffffffff818c7140-ffffffff818c71e0: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8195e680)
Location: drivers/usb/dwc2/hcd.c:2501
Inline: False
```
**Symbols:**

```
ffffffff8195e680-ffffffff8195e720: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ab8a70)
Location: drivers/usb/dwc2/hcd.c:2497
Inline: False
```
**Symbols:**

```
ffffffff81ab8a70-ffffffff81ab8b0e: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c42070)
Location: drivers/usb/dwc2/hcd.c:2468
Inline: False
```
**Symbols:**

```
ffffffff81c42070-ffffffff81c4210e: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ca9620)
Location: drivers/usb/dwc2/hcd.c:2468
Inline: False
```
**Symbols:**

```
ffffffff81ca9620-ffffffff81ca96dd: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dwc2_alloc_dma_aligned_buffer(struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d5e2d0)
Location: drivers/usb/dwc2/hcd.c:2468
Inline: False
```
**Symbols:**

```
ffffffff81d5e2d0-ffffffff81d5e38d: dwc2_alloc_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a402cc)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b12e60)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b00db8)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065c1b6)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c1dc1)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817fe861)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81818971)
Location: drivers/usb/dwc2/hcd.c:2502
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
