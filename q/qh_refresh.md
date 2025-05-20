# Function: <code>qh_refresh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816328e0)
Location: drivers/usb/host/ehci-q.c:122
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
```
**Symbols:**

```
ffffffff816328e0-ffffffff816329b5: qh_refresh.isra.49 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81693590)
Location: drivers/usb/host/ehci-q.c:122
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81693590-ffffffff816936a7: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816c1510)
Location: drivers/usb/host/ehci-q.c:122
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff816c1510-ffffffff816c1627: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff816d5170)
Location: drivers/usb/host/ehci-q.c:122
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff816d5170-ffffffff816d5253: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81741860)
Location: drivers/usb/host/ehci-q.c:109
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81741860-ffffffff81741943: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81782a50)
Location: drivers/usb/host/ehci-q.c:109
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81782a50-ffffffff81782b33: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff817a9400)
Location: drivers/usb/host/ehci-q.c:109
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff817a9400-ffffffff817a94e3: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:109
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff817e8bb0-ffffffff817e8c8c: qh_refresh (STB_LOCAL)
ffffffff817f29f3-ffffffff817f2a26: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff818194a0-ffffffff81819567: qh_refresh (STB_LOCAL)
ffffffff818238e3-ffffffff818238fe: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_intr
  - drivers/usb/host/ehci-hcd.c:qh_link_async
```
**Symbols:**

```
ffffffff818eaa80-ffffffff818eab3d: qh_refresh (STB_LOCAL)
ffffffff818f5444-ffffffff818f545f: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:end_unlink_intr
  - drivers/usb/host/ehci-hcd.c:qh_link_async
```
**Symbols:**

```
ffffffff818f3970-ffffffff818f3a2d: qh_refresh (STB_LOCAL)
ffffffff81c20134-ffffffff81c2014f: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff818d7020-ffffffff818d70dd: qh_refresh (STB_LOCAL)
ffffffff81c1211d-ffffffff81c12138: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81971e20-ffffffff81971ed9: qh_refresh (STB_LOCAL)
ffffffff81d1e9c9-ffffffff81d1e9e4: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81acd4a0-ffffffff81acd578: qh_refresh (STB_LOCAL)
ffffffff81eea4df-ffffffff81eea4fa: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c57d90)
Location: drivers/usb/host/ehci-q.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81c57d90-ffffffff81c57e95: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc0b50)
Location: drivers/usb/host/ehci-q.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81cc0b50-ffffffff81cc0c55: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d75910)
Location: drivers/usb/host/ehci-q.c:114
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81d75910-ffffffff81d75a15: qh_refresh (STB_LOCAL)
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
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffff800010a52788)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffff800010a52788-ffff800010a5289c: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b267f0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
c0b267f0-c0b268f0: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c000000000b1c960)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
c000000000b1c960-c000000000b1caac: qh_refresh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffe00066ec7e)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffe00066ec7e-ffffffe00066ed50: qh_refresh (STB_LOCAL)
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
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff817d1880-ffffffff817d1947: qh_refresh (STB_LOCAL)
ffffffff817dbcc3-ffffffff817dbcde: qh_refresh.cold (STB_LOCAL)
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
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff8180e320-ffffffff8180e3e7: qh_refresh (STB_LOCAL)
ffffffff81818763-ffffffff8181877e: qh_refresh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void qh_refresh(struct ehci_hcd *ehci, struct ehci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci-q.c:113
Inline: False
Direct callers:
  - drivers/usb/host/ehci-hcd.c:ehci_urb_enqueue
  - drivers/usb/host/ehci-hcd.c:qh_link_async
  - drivers/usb/host/ehci-hcd.c:ehci_handle_intr_unlinks
```
**Symbols:**

```
ffffffff81828af0-ffffffff81828bb7: qh_refresh (STB_LOCAL)
ffffffff81832753-ffffffff8183276e: qh_refresh.cold (STB_LOCAL)
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
