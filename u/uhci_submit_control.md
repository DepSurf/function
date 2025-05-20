# Function: <code>uhci_submit_control</code>

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
In drivers/usb/host/uhci-hcd.c (ffffffff81648d57)
Location: drivers/usb/host/uhci-q.c:790
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff816a9818)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff816d7958)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff816ebd86)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81758576)
Location: drivers/usb/host/uhci-q.c:790
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81797a92)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff817bdfd2)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff817fd33a)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff8182e18a)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81901d70)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81901d70-ffffffff819020ec: uhci_submit_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8190a640)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff8190a640-ffffffff8190a9bc: uhci_submit_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff818eca40)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff818eca40-ffffffff818ecdbc: uhci_submit_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81989160)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81989160-ffffffff819894dc: uhci_submit_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81ae6d10)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81ae6d10-ffffffff81ae70af: uhci_submit_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81c72c10)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c72c10-ffffffff81c72faf: uhci_submit_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81cda200)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81cda200-ffffffff81cda5a0: uhci_submit_control (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uhci_submit_control(struct uhci_hcd *uhci, struct urb *urb, struct uhci_qh *qh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8f230)
Location: drivers/usb/host/uhci-q.c:789
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81d8f230-ffffffff81d8f5d0: uhci_submit_control (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffff800010a6be68)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (c0b3c974)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (c000000000b3bca0)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffe0006840b4)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff817e656a)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff8182300a)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff8183e72a)
Location: drivers/usb/host/uhci-q.c:789
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
