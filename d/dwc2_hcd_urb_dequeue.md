# Function: <code>dwc2_hcd_urb_dequeue</code>

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
In drivers/usb/dwc2/hcd.c (ffffffff81627bd0)
Location: drivers/usb/dwc2/hcd.c:422
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff81687ab8)
Location: drivers/usb/dwc2/hcd.c:2040
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff816b5ce8)
Location: drivers/usb/dwc2/hcd.c:2070
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff816ca019)
Location: drivers/usb/dwc2/hcd.c:2087
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff81736549)
Location: drivers/usb/dwc2/hcd.c:2093
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff81775f98)
Location: drivers/usb/dwc2/hcd.c:2138
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff8179b6b8)
Location: drivers/usb/dwc2/hcd.c:2128
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff817da7b8)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff8180b6d8)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818dc3d0)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff818dc3d0-ffffffff818dc5f6: dwc2_hcd_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e6260)
Location: drivers/usb/dwc2/hcd.c:1939
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff818e6260-ffffffff818e6485: dwc2_hcd_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818c8650)
Location: drivers/usb/dwc2/hcd.c:1937
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff818c8650-ffffffff818c8876: dwc2_hcd_urb_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1937
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff81960e10-ffffffff81960f99: dwc2_hcd_urb_dequeue (STB_LOCAL)
ffffffff81d1b26d-ffffffff81d1b281: dwc2_hcd_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1933
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff81abb230-ffffffff81abb395: dwc2_hcd_urb_dequeue (STB_LOCAL)
ffffffff81ee64fc-ffffffff81ee6511: dwc2_hcd_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1904
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff81c44730-ffffffff81c44895: dwc2_hcd_urb_dequeue (STB_LOCAL)
ffffffff820a1d8e-ffffffff820a1da3: dwc2_hcd_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1904
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff81cabd20-ffffffff81cabe85: dwc2_hcd_urb_dequeue (STB_LOCAL)
ffffffff82123361-ffffffff82123376: dwc2_hcd_urb_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_urb_dequeue(struct dwc2_hsotg *hsotg, struct dwc2_hcd_urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.c:1904
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
```
**Symbols:**

```
ffffffff81d609d0-ffffffff81d60b35: dwc2_hcd_urb_dequeue (STB_LOCAL)
ffffffff82204b38-ffffffff82204b4d: dwc2_hcd_urb_dequeue.cold (STB_LOCAL)
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
In drivers/usb/dwc2/hcd.c (ffff800010a43adc)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (c0b16404)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (c000000000b06590)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffe00066027c)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff817c3ab8)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff81800558)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
In drivers/usb/dwc2/hcd.c (ffffffff8181a668)
Location: drivers/usb/dwc2/hcd.c:1938
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_dequeue
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
