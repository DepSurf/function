# Function: <code>uhci_unlink_qh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81645b80)
Location: drivers/usb/host/uhci-q.c:552
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81645b80-ffffffff81645cb5: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a66b0)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff816a66b0-ffffffff816a67e8: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d47d0)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff816d47d0-ffffffff816d4908: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816e8c60)
Location: drivers/usb/host/uhci-q.c:551
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff816e8c60-ffffffff816e8d76: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81755450)
Location: drivers/usb/host/uhci-q.c:552
Inline: True
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81755450-ffffffff81755566: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81795a40)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81795a40-ffffffff81795b60: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bc160)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff817bc160-ffffffff817bc280: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (0)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff817fb340-ffffffff817fb44b: uhci_unlink_qh (STB_LOCAL)
ffffffff817ffff6-ffffffff81800009: uhci_unlink_qh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182c180)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff8182c180-ffffffff8182c2a6: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ffd40)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff818ffd40-ffffffff818ffea6: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81908610)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81908610-ffffffff81908772: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818ebdf0)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff818ebdf0-ffffffff818ebf4e: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81988500)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81988500-ffffffff8198865e: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae5060)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81ae5060-ffffffff81ae51e6: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c70c70)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81c70c70-ffffffff81c70df6: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cd8250)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81cd8250-ffffffff81cd83d6: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8d260)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81d8d260-ffffffff81d8d3e6: uhci_unlink_qh (STB_LOCAL)
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
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a67a60)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffff800010a67a60-ffff800010a67b94: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b3b408)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
c0b3b408-c0b3b554: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b3a520)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
c000000000b3a520-c000000000b3a6d0: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe0006824c4)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffe0006824c4-ffffffe0006825c4: uhci_unlink_qh (STB_LOCAL)
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
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e4560)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff817e4560-ffffffff817e4686: uhci_unlink_qh (STB_LOCAL)
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
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81821000)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff81821000-ffffffff81821126: uhci_unlink_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uhci_unlink_qh(struct uhci_hcd *uhci, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183b460)
Location: drivers/usb/host/uhci-q.c:551
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_giveback_urb
  - drivers/usb/host/uhci-hcd.c:uhci_urb_dequeue
```
**Symbols:**

```
ffffffff8183b460-ffffffff8183b586: uhci_unlink_qh (STB_LOCAL)
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
