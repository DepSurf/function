# Function: <code>uhci_result_isochronous</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8164789b)
Location: drivers/usb/host/uhci-q.c:1370
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a8395)
Location: drivers/usb/host/uhci-q.c:1369
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d64b5)
Location: drivers/usb/host/uhci-q.c:1369
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
In drivers/usb/host/uhci-hcd.c (ffffffff816eac27)
Location: drivers/usb/host/uhci-q.c:1369
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
In drivers/usb/host/uhci-hcd.c (ffffffff81757417)
Location: drivers/usb/host/uhci-q.c:1370
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
In drivers/usb/host/uhci-hcd.c (ffffffff81798ba6)
Location: drivers/usb/host/uhci-q.c:1369
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bf06e)
Location: drivers/usb/host/uhci-q.c:1369
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
In drivers/usb/host/uhci-hcd.c (ffffffff817fea52)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff8182f8a0)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818fe150)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff818fe150-ffffffff818fe2f1: uhci_result_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81906a30)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81906a30-ffffffff81906bd1: uhci_result_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ea030)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff818ea030-ffffffff818ea1d1: uhci_result_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff819866d0)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff819866d0-ffffffff81986871: uhci_result_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae3030)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81ae3030-ffffffff81ae31f2: uhci_result_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c6eaf0)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81c6eaf0-ffffffff81c6ecb2: uhci_result_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd60b0)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81cd60b0-ffffffff81cd6272: uhci_result_isochronous (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uhci_result_isochronous(struct uhci_hcd *uhci, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8b090)
Location: drivers/usb/host/uhci-q.c:1369
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_scan_qh
```
**Symbols:**

```
ffffffff81d8b090-ffffffff81d8b252: uhci_result_isochronous (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffff800010a6a1c4)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
In drivers/usb/host/uhci-hcd.c (c0b3bd74)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
In drivers/usb/host/uhci-hcd.c (c000000000b3b2a0)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffe0006851c8)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e7c80)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff81824720)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183d450)
Location: drivers/usb/host/uhci-q.c:1369
Inline: True
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
