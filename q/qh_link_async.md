# Function: <code>qh_link_async</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81633130)
Location: drivers/usb/host/ehci-q.c:976
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff81633130-ffffffff81633208: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81693e40)
Location: drivers/usb/host/ehci-q.c:985
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81693e40-ffffffff81693f1b: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c1f20)
Location: drivers/usb/host/ehci-q.c:983
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff816c1f20-ffffffff816c1ffb: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d6310)
Location: drivers/usb/host/ehci-q.c:983
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff816d6310-ffffffff816d63d4: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81742a40)
Location: drivers/usb/host/ehci-q.c:970
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81742a40-ffffffff81742b04: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81783550)
Location: drivers/usb/host/ehci-q.c:970
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81783550-ffffffff81783614: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817aa4b0)
Location: drivers/usb/host/ehci-q.c:970
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff817aa4b0-ffffffff817aa574: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:970
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff817e9650-ffffffff817e9714: qh_link_async (STB_LOCAL)
ffffffff817f2a26-ffffffff817f2a39: qh_link_async.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8181a510)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff8181a510-ffffffff8181a5db: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f13b0)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff818f13b0-ffffffff818f147b: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f9110)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff818f9110-ffffffff818f91db: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818dd4b0)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff818dd4b0-ffffffff818dd57b: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81979030)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81979030-ffffffff819790fb: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6980)
Location: drivers/usb/host/ehci-q.c:982
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81ad6980-ffffffff81ad6a69: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c601f0)
Location: drivers/usb/host/ehci-q.c:982
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81c601f0-ffffffff81c602d9: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc75b0)
Location: drivers/usb/host/ehci-q.c:982
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81cc75b0-ffffffff81cc7697: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7c450)
Location: drivers/usb/host/ehci-q.c:982
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81d7c450-ffffffff81d7c537: qh_link_async (STB_LOCAL)
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
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a55e70)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffff800010a55e70-ffff800010a55f48: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b268f0)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
c0b268f0-c0b269d8: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1fba0)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
c000000000b1fba0-c000000000b1fcdc: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00067414c)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffe00067414c-ffffffe000674204: qh_link_async (STB_LOCAL)
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
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817d28f0)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff817d28f0-ffffffff817d29bb: qh_link_async (STB_LOCAL)
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
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff8180f390)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff8180f390-ffffffff8180f45b: qh_link_async (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void qh_link_async(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81829e60)
Location: drivers/usb/host/ehci-q.c:981
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:end_unlink_async
  - drivers/usb/host/ehci-hcd.c:ehci_clear_tt_buffer_complete
```
**Symbols:**

```
ffffffff81829e60-ffffffff81829f2b: qh_link_async (STB_LOCAL)
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
