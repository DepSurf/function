# Function: <code>dwc2_hcd_qtd_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8162df80)
Location: drivers/usb/dwc2/hcd_queue.c:788
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff8162df80-ffffffff8162dfeb: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168ea20)
Location: drivers/usb/dwc2/hcd_queue.c:1995
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff8168ea20-ffffffff8168ea8b: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bcae0)
Location: drivers/usb/dwc2/hcd_queue.c:1998
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff816bcae0-ffffffff816bcb4b: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816d0b40)
Location: drivers/usb/dwc2/hcd_queue.c:1994
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff816d0b40-ffffffff816d0bab: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173d190)
Location: drivers/usb/dwc2/hcd_queue.c:1994
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff8173d190-ffffffff8173d1fb: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177db40)
Location: drivers/usb/dwc2/hcd_queue.c:2071
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff8177db40-ffffffff8177dbab: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a4120)
Location: drivers/usb/dwc2/hcd_queue.c:2076
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff817a4120-ffffffff817a418b: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff817e3450-ffffffff817e3470: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff817e3270-ffffffff817e32c2: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff8181422f-ffffffff8181424f: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff81814170-ffffffff818141c2: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff818e52bf-ffffffff818e52df: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff818e5200-ffffffff818e5252: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff81c1fe79-ffffffff81c1fe99: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff818ee6d0-ffffffff818ee722: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff81c11e5f-ffffffff81c11e7f: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff818d1ed0-ffffffff818d1f22: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff81d1e206-ffffffff81d1e226: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff8196c8f0-ffffffff8196c942: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff81ee9c67-ffffffff81ee9c87: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff81ac6d90-ffffffff81ac6dee: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c50f70)
Location: drivers/usb/dwc2/hcd_queue.c:2048
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff81c50f70-ffffffff81c50ff6: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb84f0)
Location: drivers/usb/dwc2/hcd_queue.c:2048
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff81cb84f0-ffffffff81cb8576: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6d260)
Location: drivers/usb/dwc2/hcd_queue.c:2048
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff81d6d260-ffffffff81d6d2e6: dwc2_hcd_qtd_add (STB_GLOBAL)
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
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4d390)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffff800010a4d390-ffff800010a4d418: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c0b1f51c)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
c0b1f51c-c0b1f590: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c000000000b148d0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
c000000000b148d0-c000000000b1498c: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000669e04)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffe000669e04-ffffffe000669e7a: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff817cc60f-ffffffff817cc62f: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff817cc550-ffffffff817cc5a2: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff818090af-ffffffff818090cf: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff81808ff0-ffffffff81809042: dwc2_hcd_qtd_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_hcd_qtd_add(struct dwc2_hsotg *hsotg, struct dwc2_qtd *qtd, struct dwc2_qh *qh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:2078
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
**Symbols:**

```
ffffffff818231bf-ffffffff818231df: dwc2_hcd_qtd_add.cold (STB_LOCAL)
ffffffff81823100-ffffffff81823152: dwc2_hcd_qtd_add (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
