# Function: <code>dwc2_hs_pmap_schedule</code>

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
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168d490)
Location: drivers/usb/dwc2/hcd_queue.c:654
Inline: False
```
**Symbols:**

```
ffffffff8168d490-ffffffff8168d4dd: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bb560)
Location: drivers/usb/dwc2/hcd_queue.c:657
Inline: False
```
**Symbols:**

```
ffffffff816bb560-ffffffff816bb5ad: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff816cf7d0)
Location: drivers/usb/dwc2/hcd_queue.c:654
Inline: False
```
**Symbols:**

```
ffffffff816cf7d0-ffffffff816cf817: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173be20)
Location: drivers/usb/dwc2/hcd_queue.c:655
Inline: False
```
**Symbols:**

```
ffffffff8173be20-ffffffff8173be67: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177c690)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
```
**Symbols:**

```
ffffffff8177c690-ffffffff8177c6d7: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a2bf0)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
```
**Symbols:**

```
ffffffff817a2bf0-ffffffff817a2c37: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e1d00)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff817e1d00-ffffffff817e1d47: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812bd0)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81812bd0-ffffffff81812c17: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e4897)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff818edd74)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d1534)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196baed)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac5f31)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c5004e)
Location: drivers/usb/dwc2/hcd_queue.c:628
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb75fe)
Location: drivers/usb/dwc2/hcd_queue.c:628
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6c34e)
Location: drivers/usb/dwc2/hcd_queue.c:628
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_uframe_schedule_split
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
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4bc10)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffff800010a4bc10-ffff800010a4bc84: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c0b1decc)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
c0b1decc-c0b1df34: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (c000000000b12bd0)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
c000000000b12bd0-c000000000b12c4c: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668ae8)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffe000668ae8-ffffffe000668b48: dwc2_hs_pmap_schedule (STB_LOCAL)
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
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cafb0)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff817cafb0-ffffffff817caff7: dwc2_hs_pmap_schedule (STB_LOCAL)
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
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81807a50)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81807a50-ffffffff81807a97: dwc2_hs_pmap_schedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dwc2_hs_pmap_schedule(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh, bool only_one_period, int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821b60)
Location: drivers/usb/dwc2/hcd_queue.c:658
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81821b60-ffffffff81821ba7: dwc2_hs_pmap_schedule (STB_LOCAL)
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
