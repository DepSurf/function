# Function: <code>uhci_make_qh_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81647520)
Location: drivers/usb/host/uhci-q.c:587
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81647520-ffffffff816475ef: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a8030)
Location: drivers/usb/host/uhci-q.c:586
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816a8030-ffffffff816a80ff: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d6150)
Location: drivers/usb/host/uhci-q.c:586
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816d6150-ffffffff816d621f: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816e80f0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816e80f0-ffffffff816e81b0: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817548d0)
Location: drivers/usb/host/uhci-q.c:587
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817548d0-ffffffff81754990: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81794eb0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81794eb0-ffffffff81794f75: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bb370)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817bb370-ffffffff817bb435: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817face0-ffffffff817fad9e: uhci_make_qh_idle (STB_LOCAL)
ffffffff817fff7e-ffffffff817fff91: uhci_make_qh_idle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182bb20)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff8182bb20-ffffffff8182bbe5: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fdef0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818fdef0-ffffffff818fdfb5: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819067d0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff819067d0-ffffffff81906899: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9dd0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818e9dd0-ffffffff818e9e99: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81986470)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81986470-ffffffff81986539: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae2390)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81ae2390-ffffffff81ae2475: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6dd90)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c6dd90-ffffffff81c6de75: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd53a0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81cd53a0-ffffffff81cd5485: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8a380)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81d8a380-ffffffff81d8a465: uhci_make_qh_idle (STB_LOCAL)
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
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a673e8)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffff800010a673e8-ffff800010a674b0: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b39c18)
Location: drivers/usb/host/uhci-q.c:586
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
c0b39c18-c0b39ce4: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b38680)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
c000000000b38680-c000000000b38790: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000681468)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffe000681468-ffffffe000681504: uhci_make_qh_idle (STB_LOCAL)
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
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e3f00)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817e3f00-ffffffff817e3fc5: uhci_make_qh_idle (STB_LOCAL)
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
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818209a0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818209a0-ffffffff81820a65: uhci_make_qh_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uhci_make_qh_idle(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183aab0)
Location: drivers/usb/host/uhci-q.c:586
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff8183aab0-ffffffff8183ab75: uhci_make_qh_idle (STB_LOCAL)
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
