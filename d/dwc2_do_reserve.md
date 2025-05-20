# Function: <code>dwc2_do_reserve</code>

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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168de28)
Location: drivers/usb/dwc2/hcd_queue.c:1196
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bbef4)
Location: drivers/usb/dwc2/hcd_queue.c:1199
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff816d00f3)
Location: drivers/usb/dwc2/hcd_queue.c:1196
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173c739)
Location: drivers/usb/dwc2/hcd_queue.c:1197
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177d061)
Location: drivers/usb/dwc2/hcd_queue.c:1201
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a3604)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
ffffffff817e20b0-ffffffff817e279d: dwc2_do_reserve (STB_LOCAL)
ffffffff817e334b-ffffffff817e33dd: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81812f80-ffffffff81813685: dwc2_do_reserve (STB_LOCAL)
ffffffff818141c2-ffffffff818141e2: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic
```
**Symbols:**

```
ffffffff818e46e0-ffffffff818e4923: dwc2_do_reserve (STB_LOCAL)
ffffffff818e5252-ffffffff818e5272: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic
```
**Symbols:**

```
ffffffff818edbc0-ffffffff818ede00: dwc2_do_reserve (STB_LOCAL)
ffffffff81c1fe0c-ffffffff81c1fe2c: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
**Symbols:**

```
ffffffff818d1380-ffffffff818d15c0: dwc2_do_reserve (STB_LOCAL)
ffffffff81c11df5-ffffffff81c11e15: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
**Symbols:**

```
ffffffff8196b910-ffffffff8196bb5d: dwc2_do_reserve (STB_LOCAL)
ffffffff81d1e06a-ffffffff81d1e0b2: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
**Symbols:**

```
ffffffff81ac5d60-ffffffff81ac5ffd: dwc2_do_reserve (STB_LOCAL)
ffffffff81ee9aa6-ffffffff81ee9aed: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
**Symbols:**

```
ffffffff81c4fe40-ffffffff81c5010f: dwc2_do_reserve (STB_LOCAL)
ffffffff820a4c85-ffffffff820a4caf: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
**Symbols:**

```
ffffffff81cb73f0-ffffffff81cb76bf: dwc2_do_reserve (STB_LOCAL)
ffffffff821261c1-ffffffff821261eb: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1171
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
```
**Symbols:**

```
ffffffff81d6c140-ffffffff81d6c40f: dwc2_do_reserve (STB_LOCAL)
ffffffff822079ca-ffffffff822079f4: dwc2_do_reserve.cold (STB_LOCAL)
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
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4c010)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
ffff800010a4c010-ffff800010a4c714: dwc2_do_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c0b1e374)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
c0b1e374-c0b1eb28: dwc2_do_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c000000000b131c0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
c000000000b131c0-c000000000b13abc: dwc2_do_reserve (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668e7e)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
ffffffe000668e7e-ffffffe000669462: dwc2_do_reserve (STB_LOCAL)
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
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
ffffffff817cb360-ffffffff817cba65: dwc2_do_reserve (STB_LOCAL)
ffffffff817cc5a2-ffffffff817cc5c2: dwc2_do_reserve.cold (STB_LOCAL)
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
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81807e00-ffffffff81808505: dwc2_do_reserve (STB_LOCAL)
ffffffff81809042-ffffffff81809062: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int dwc2_do_reserve(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1201
Inline: False
```
**Symbols:**

```
ffffffff81821f10-ffffffff81822615: dwc2_do_reserve (STB_LOCAL)
ffffffff81823152-ffffffff81823172: dwc2_do_reserve.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
