# Function: <code>dwc2_init_isoc_dma_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8162ebac)
Location: drivers/usb/dwc2/hcd_ddma.c:537
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8168f76c)
Location: drivers/usb/dwc2/hcd_ddma.c:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816bd81c)
Location: drivers/usb/dwc2/hcd_ddma.c:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff816d186c)
Location: drivers/usb/dwc2/hcd_ddma.c:578
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8173deec)
Location: drivers/usb/dwc2/hcd_ddma.c:579
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8177e86f)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817a4fd0)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817e41b3)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81815073)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818e6280)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff818e6280-ffffffff818e64fc: dwc2_init_isoc_dma_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818eed80)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff818eed80-ffffffff818eefb8: dwc2_init_isoc_dma_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff818d24a0)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff818d24a0-ffffffff818d278a: dwc2_init_isoc_dma_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff8196cdf0)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff8196cdf0-ffffffff8196d0da: dwc2_init_isoc_dma_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81ac7300)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff81ac7300-ffffffff81ac761c: dwc2_init_isoc_dma_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81c515b0)
Location: drivers/usb/dwc2/hcd_ddma.c:550
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff81c515b0-ffffffff81c518ce: dwc2_init_isoc_dma_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81cb8b70)
Location: drivers/usb/dwc2/hcd_ddma.c:550
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff81cb8b70-ffffffff81cb8e8e: dwc2_init_isoc_dma_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dwc2_init_isoc_dma_desc(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, u16 skip_frames);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81d6d8e0)
Location: drivers/usb/dwc2/hcd_ddma.c:550
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
```
**Symbols:**

```
ffffffff81d6d8e0-ffffffff81d6dbfe: dwc2_init_isoc_dma_desc (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_ddma.c (ffff800010a4e2d8)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (c0b20464)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (c000000000b15ca4)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffe00066ac72)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff817cd453)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81809ef3)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
In drivers/usb/dwc2/hcd_ddma.c (ffffffff81824003)
Location: drivers/usb/dwc2/hcd_ddma.c:580
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_ddma.c:dwc2_hcd_start_xfer_ddma
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
