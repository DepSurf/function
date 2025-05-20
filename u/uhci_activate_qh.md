# Function: <code>uhci_activate_qh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816458e0)
Location: drivers/usb/host/uhci-q.c:481
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816458e0-ffffffff81645a7f: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a6410)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816a6410-ffffffff816a65ad: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d4530)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816d4530-ffffffff816d46cd: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816ea410)
Location: drivers/usb/host/uhci-q.c:480
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816ea410-ffffffff816ea587: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81756c00)
Location: drivers/usb/host/uhci-q.c:481
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81756c00-ffffffff81756d77: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81797030)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81797030-ffffffff8179719a: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bbee0)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817bbee0-ffffffff817bc04a: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817fb0b0-ffffffff817fb226: uhci_activate_qh (STB_LOCAL)
ffffffff817fffdb-ffffffff817ffff6: uhci_activate_qh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182bf00)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff8182bf00-ffffffff8182c068: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fd310)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818fd310-ffffffff818fd478: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81905c10)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81905c10-ffffffff81905d78: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818e9400)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818e9400-ffffffff818e9568: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819858b0)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff819858b0-ffffffff81985a6a: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae1680)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81ae1680-ffffffff81ae1864: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6d010)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c6d010-ffffffff81c6d1f4: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd4620)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81cd4620-ffffffff81cd4804: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d89600)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81d89600-ffffffff81d897e4: uhci_activate_qh (STB_LOCAL)
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
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a677d8)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffff800010a677d8-ffff800010a67998: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b38cc8)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
c0b38cc8-c0b38e8c: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b37f00)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
c000000000b37f00-c000000000b380e0: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000680cf8)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffe000680cf8-ffffffe000680e30: uhci_activate_qh (STB_LOCAL)
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
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e42e0)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817e42e0-ffffffff817e4448: uhci_activate_qh (STB_LOCAL)
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
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81820d80)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81820d80-ffffffff81820ee8: uhci_activate_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uhci_activate_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183b1e0)
Location: drivers/usb/host/uhci-q.c:480
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff8183b1e0-ffffffff8183b348: uhci_activate_qh (STB_LOCAL)
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
