# Function: <code>dwc2_hc_init_xfer</code>

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
In drivers/usb/dwc2/hcd.c (ffffffff81628225)
Location: drivers/usb/dwc2/hcd.c:602
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff81686548)
Location: drivers/usb/dwc2/hcd.c:2443
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff816b4785)
Location: drivers/usb/dwc2/hcd.c:2474
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff816c8b0d)
Location: drivers/usb/dwc2/hcd.c:2487
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
In drivers/usb/dwc2/hcd.c (ffffffff81735010)
Location: drivers/usb/dwc2/hcd.c:2493
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
In drivers/usb/dwc2/hcd.c (ffffffff817754e4)
Location: drivers/usb/dwc2/hcd.c:2547
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff8179aa84)
Location: drivers/usb/dwc2/hcd.c:2537
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817d9c3d)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff8180aad1)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818d9220)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff818d9220-ffffffff818d93c8: dwc2_hc_init_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e3170)
Location: drivers/usb/dwc2/hcd.c:2354
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff818e3170-ffffffff818e3318: dwc2_hc_init_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c64e0)
Location: drivers/usb/dwc2/hcd.c:2352
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff818c64e0-ffffffff818c668d: dwc2_hc_init_xfer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2352
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff8195e740-ffffffff8195e979: dwc2_hc_init_xfer (STB_LOCAL)
ffffffff81d1a70d-ffffffff81d1a761: dwc2_hc_init_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2348
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81ab8b30-ffffffff81ab8d90: dwc2_hc_init_xfer (STB_LOCAL)
ffffffff81ee584a-ffffffff81ee589e: dwc2_hc_init_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81c41c80-ffffffff81c41ee0: dwc2_hc_init_xfer (STB_LOCAL)
ffffffff820a1264-ffffffff820a12b8: dwc2_hc_init_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81ca9250-ffffffff81ca9483: dwc2_hc_init_xfer (STB_LOCAL)
ffffffff82122837-ffffffff8212288b: dwc2_hc_init_xfer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_hc_init_xfer(struct dwc2_hsotg *hsotg, struct dwc2_host_chan *chan, struct dwc2_qtd *qtd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:2319
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
```
**Symbols:**

```
ffffffff81d5df00-ffffffff81d5e133: dwc2_hc_init_xfer (STB_LOCAL)
ffffffff8220400e-ffffffff82204062: dwc2_hc_init_xfer.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a4139c)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (c0b13a20)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (c000000000b01e80)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffe00065d308)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817c2eb1)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff817ff951)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
In drivers/usb/dwc2/hcd.c (ffffffff81819a61)
Location: drivers/usb/dwc2/hcd.c:2353
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_assign_and_init_hc
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
