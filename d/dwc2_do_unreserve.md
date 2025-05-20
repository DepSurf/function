# Function: <code>dwc2_do_unreserve</code>

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
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168d800)
Location: drivers/usb/dwc2/hcd_queue.c:1242
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff8168d800-ffffffff8168d8f9: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bb8d0)
Location: drivers/usb/dwc2/hcd_queue.c:1245
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff816bb8d0-ffffffff816bb9c9: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf9d0)
Location: drivers/usb/dwc2/hcd_queue.c:1242
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff816cf9d0-ffffffff816cfaa4: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173c020)
Location: drivers/usb/dwc2/hcd_queue.c:1243
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff8173c020-ffffffff8173c0ec: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c880)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff8177c880-ffffffff8177c94c: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2de0)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff817a2de0-ffffffff817a2eac: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff817e1ef0-ffffffff817e1fa2: dwc2_do_unreserve (STB_LOCAL)
ffffffff817e32fe-ffffffff817e334b: dwc2_do_unreserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812d90)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff81812d90-ffffffff81812e6f: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4a40)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff818e4a40-ffffffff818e4b3e: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818edf10)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff818edf10-ffffffff818ee00e: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d15c0)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff818d15c0-ffffffff818d16be: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff8196bb60-ffffffff8196bc70: dwc2_do_unreserve (STB_LOCAL)
ffffffff81d1e0b2-ffffffff81d1e0c7: dwc2_do_unreserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff81ac6000-ffffffff81ac611e: dwc2_do_unreserve (STB_LOCAL)
ffffffff81ee9aed-ffffffff81ee9b02: dwc2_do_unreserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1217
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff81c50120-ffffffff81c5023e: dwc2_do_unreserve (STB_LOCAL)
ffffffff820a4caf-ffffffff820a4cc4: dwc2_do_unreserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1217
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff81cb76d0-ffffffff81cb77ea: dwc2_do_unreserve (STB_LOCAL)
ffffffff821261eb-ffffffff82126200: dwc2_do_unreserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1217
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff81d6c420-ffffffff81d6c53a: dwc2_do_unreserve (STB_LOCAL)
ffffffff822079f4-ffffffff82207a09: dwc2_do_unreserve.cold (STB_LOCAL)
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
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4be90)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffff800010a4be90-ffff800010a4bf84: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c0b1e1e0)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
c0b1e1e0-c0b1e2fc: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c000000000b12ef0)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
c000000000b12ef0-c000000000b1302c: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668ce2)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffe000668ce2-ffffffe000668d9a: dwc2_do_unreserve (STB_LOCAL)
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
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cb170)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff817cb170-ffffffff817cb24f: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81807c10)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff81807c10-ffffffff81807cef: dwc2_do_unreserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_do_unreserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821d20)
Location: drivers/usb/dwc2/hcd_queue.c:1247
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_free
  - drivers/usb/dwc2/hcd_queue.c:dwc2_unreserve_timer_fn
```
**Symbols:**

```
ffffffff81821d20-ffffffff81821dff: dwc2_do_unreserve (STB_LOCAL)
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
