# Function: <code>dwc2_pick_first_frame</code>

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
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168d4e0)
Location: drivers/usb/dwc2/hcd_queue.c:1081
Inline: False
```
**Symbols:**

```
ffffffff8168d4e0-ffffffff8168d624: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bb5b0)
Location: drivers/usb/dwc2/hcd_queue.c:1084
Inline: False
```
**Symbols:**

```
ffffffff816bb5b0-ffffffff816bb6f3: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf820)
Location: drivers/usb/dwc2/hcd_queue.c:1081
Inline: False
```
**Symbols:**

```
ffffffff816cf820-ffffffff816cf92b: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173be70)
Location: drivers/usb/dwc2/hcd_queue.c:1082
Inline: False
```
**Symbols:**

```
ffffffff8173be70-ffffffff8173bf7b: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c6e0)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
```
**Symbols:**

```
ffffffff8177c6e0-ffffffff8177c7cb: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2c40)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
```
**Symbols:**

```
ffffffff817a2c40-ffffffff817a2d2b: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff817e1d50-ffffffff817e1e50: dwc2_pick_first_frame (STB_LOCAL)
ffffffff817e32c2-ffffffff817e32e8: dwc2_pick_first_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812c20)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81812c20-ffffffff81812d03: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e3f70)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff818e3f70-ffffffff818e4053: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ed450)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_schedule_periodic
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff818ed450-ffffffff818ed533: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d0c20)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff818d0c20-ffffffff818d0d03: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff8196b130-ffffffff8196b21f: dwc2_pick_first_frame (STB_LOCAL)
ffffffff81d1e056-ffffffff81d1e06a: dwc2_pick_first_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81ac54c0-ffffffff81ac55e3: dwc2_pick_first_frame (STB_LOCAL)
ffffffff81ee9a92-ffffffff81ee9aa6: dwc2_pick_first_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1056
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81c4f560-ffffffff81c4f683: dwc2_pick_first_frame (STB_LOCAL)
ffffffff820a4c71-ffffffff820a4c85: dwc2_pick_first_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1056
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81cb6b00-ffffffff81cb6c23: dwc2_pick_first_frame (STB_LOCAL)
ffffffff821261ad-ffffffff821261c1: dwc2_pick_first_frame.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (0)
Location: drivers/usb/dwc2/hcd_queue.c:1056
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_add
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81d6b850-ffffffff81d6b973: dwc2_pick_first_frame (STB_LOCAL)
ffffffff822079b6-ffffffff822079ca: dwc2_pick_first_frame.cold (STB_LOCAL)
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
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4bc88)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffff800010a4bc88-ffff800010a4bdd0: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c0b1df34)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
c0b1df34-c0b1e08c: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c000000000b12c50)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
c000000000b12c50-c000000000b12df4: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668b48)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffe000668b48-ffffffe000668c40: dwc2_pick_first_frame (STB_LOCAL)
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
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cb000)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff817cb000-ffffffff817cb0e3: dwc2_pick_first_frame (STB_LOCAL)
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
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81807aa0)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81807aa0-ffffffff81807b83: dwc2_pick_first_frame (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dwc2_pick_first_frame(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821bb0)
Location: drivers/usb/dwc2/hcd_queue.c:1086
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81821bb0-ffffffff81821c93: dwc2_pick_first_frame (STB_LOCAL)
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
