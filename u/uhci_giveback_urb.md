# Function: <code>uhci_giveback_urb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81645cc0)
Location: drivers/usb/host/uhci-q.c:1517
Inline: False
```
**Symbols:**

```
ffffffff81645cc0-ffffffff81645f42: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a67f0)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff816a67f0-ffffffff816a6a6d: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d4910)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff816d4910-ffffffff816d4b8d: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816e8d80)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff816e8d80-ffffffff816e8fd3: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81755570)
Location: drivers/usb/host/uhci-q.c:1517
Inline: False
```
**Symbols:**

```
ffffffff81755570-ffffffff817557c3: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81798350)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff81798350-ffffffff817985ab: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817be820)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff817be820-ffffffff817bea7b: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817fe180)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff817fe180-ffffffff817fe3e6: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182efd0)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff8182efd0-ffffffff8182f236: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81900650)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81900650-ffffffff819007eb: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81908f20)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81908f20-ffffffff819090bb: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ed790)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff818ed790-ffffffff818ed9ea: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81989ea0)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81989ea0-ffffffff8198a13d: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae51f0)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81ae51f0-ffffffff81ae5497: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70e10)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81c70e10-ffffffff81c710b7: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd83f0)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81cd83f0-ffffffff81cd8688: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8d400)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81d8d400-ffffffff81d8d698: uhci_giveback_urb (STB_LOCAL)
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
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a698f8)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffff800010a698f8-ffff800010a69bb8: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b3b554)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
c0b3b554-c0b3b7d4: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3a6d0)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
c000000000b3a6d0-c000000000b3aa58: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000684a6a)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffe000684a6a-ffffffe000684cc8: uhci_giveback_urb (STB_LOCAL)
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
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e73b0)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff817e73b0-ffffffff817e7616: uhci_giveback_urb (STB_LOCAL)
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
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81823e50)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff81823e50-ffffffff818240b6: uhci_giveback_urb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uhci_giveback_urb(struct uhci_hcd *uhci, struct uhci_qh *qh, struct urb *urb, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183b590)
Location: drivers/usb/host/uhci-q.c:1516
Inline: False
```
**Symbols:**

```
ffffffff8183b590-ffffffff8183b7f4: uhci_giveback_urb (STB_LOCAL)
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
