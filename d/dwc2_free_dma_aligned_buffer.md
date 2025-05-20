# Function: <code>dwc2_free_dma_aligned_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81685ba0)
Location: drivers/usb/dwc2/hcd.c:2541
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81685ba0-ffffffff81685bf7: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816b3df0)
Location: drivers/usb/dwc2/hcd.c:2572
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff816b3df0-ffffffff816b3e47: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c81b0)
Location: drivers/usb/dwc2/hcd.c:2585
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff816c81b0-ffffffff816c8206: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81734680)
Location: drivers/usb/dwc2/hcd.c:2591
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81734680-ffffffff817346d6: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81773c22)
Location: drivers/usb/dwc2/hcd.c:2668
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81773bb0-ffffffff81773c07: dwc2_free_dma_aligned_buffer.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817998b2)
Location: drivers/usb/dwc2/hcd.c:2658
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81799840-ffffffff81799897: dwc2_free_dma_aligned_buffer.part.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817d8ad3)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff817d8a60-ffffffff817d8ab7: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81809963)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff818098f0-ffffffff81809947: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818db053)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
```
**Symbols:**

```
ffffffff818da480-ffffffff818da4d7: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e4f13)
Location: drivers/usb/dwc2/hcd.c:2475
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
```
**Symbols:**

```
ffffffff818e43a0-ffffffff818e43f7: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c7de3)
Location: drivers/usb/dwc2/hcd.c:2473
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
  - drivers/usb/dwc2/hcd.c:dwc2_map_urb_for_dma
```
**Symbols:**

```
ffffffff818c7260-ffffffff818c72b7: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8195ef53)
Location: drivers/usb/dwc2/hcd.c:2473
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff8195eb30-ffffffff8195eb87: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ab89c0)
Location: drivers/usb/dwc2/hcd.c:2469
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81ab89c0-ffffffff81ab8a37: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c41fa0)
Location: drivers/usb/dwc2/hcd.c:2440
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81c41fa0-ffffffff81c42017: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ca9550)
Location: drivers/usb/dwc2/hcd.c:2440
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81ca9550-ffffffff81ca95c8: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d5e200)
Location: drivers/usb/dwc2/hcd.c:2440
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81d5e200-ffffffff81d5e278: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a40230)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffff800010a40188-ffff800010a40204: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b12dd8)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
c0b12d4c-c0b12dbc: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (c000000000b00cbc)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
c000000000b00be0-c000000000b00c88: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_free_dma_aligned_buffer(struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065be98)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffe00065be98-ffffffe00065bf72: dwc2_free_dma_aligned_buffer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c1d43)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff817c1cd0-ffffffff817c1d27: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817fe7e3)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff817fe770-ffffffff817fe7c7: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818188f3)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_unmap_urb_for_dma
```
**Symbols:**

```
ffffffff81818880-ffffffff818188d7: dwc2_free_dma_aligned_buffer.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
