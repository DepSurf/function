# Function: <code>dwc2_uframe_schedule_split</code>

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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8168de4c)
Location: drivers/usb/dwc2/hcd_queue.c:703
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff816bbf18)
Location: drivers/usb/dwc2/hcd_queue.c:706
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff816d014b)
Location: drivers/usb/dwc2/hcd_queue.c:703
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8173c791)
Location: drivers/usb/dwc2/hcd_queue.c:704
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff8177d283)
Location: drivers/usb/dwc2/hcd_queue.c:708
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff817a383f)
Location: drivers/usb/dwc2/hcd_queue.c:708
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff817e20ea)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff81812fbe)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818e41a0)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff818e41a0-ffffffff818e46d4: dwc2_uframe_schedule_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818ed680)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff818ed680-ffffffff818edbb4: dwc2_uframe_schedule_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff818d0e50)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff818d0e50-ffffffff818d1380: dwc2_uframe_schedule_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff8196b330)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff8196b330-ffffffff8196b908: dwc2_uframe_schedule_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81ac5760)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81ac5760-ffffffff81ac5d5f: dwc2_uframe_schedule_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81c4f830)
Location: drivers/usb/dwc2/hcd_queue.c:678
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81c4f830-ffffffff81c4fe2f: dwc2_uframe_schedule_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81cb6dd0)
Location: drivers/usb/dwc2/hcd_queue.c:678
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81cb6dd0-ffffffff81cb73db: dwc2_uframe_schedule_split (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dwc2_uframe_schedule_split(struct dwc2_hsotg *hsotg, struct dwc2_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6bb20)
Location: drivers/usb/dwc2/hcd_queue.c:678
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
```
**Symbols:**

```
ffffffff81d6bb20-ffffffff81d6c12b: dwc2_uframe_schedule_split (STB_LOCAL)
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
In drivers/usb/dwc2/hcd_queue.c (ffff800010a4c04c)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
In drivers/usb/dwc2/hcd_queue.c (c0b1e3b8)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
In drivers/usb/dwc2/hcd_queue.c (c000000000b13224)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
In drivers/usb/dwc2/hcd_queue.c (ffffffe000668ec6)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff817cb39e)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff81807e3e)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
In drivers/usb/dwc2/hcd_queue.c (ffffffff81821f4e)
Location: drivers/usb/dwc2/hcd_queue.c:708
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_do_reserve
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
