# Function: <code>uhci_alloc_qh</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816486d0)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
  - drivers/usb/host/uhci-hcd.c:uhci_start
```
**Symbols:**

```
ffffffff816486d0-ffffffff81648858: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816a91c0)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816a91c0-ffffffff816a9320: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816d72e0)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816d72e0-ffffffff816d744a: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff816eb710)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff816eb710-ffffffff816eb86e: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81757f00)
Location: drivers/usb/host/uhci-q.c:246
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81757f00-ffffffff8175805e: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81797400)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81797400-ffffffff8179755e: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817bd940)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817bd940-ffffffff817bda9e: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817fcac0)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817fcac0-ffffffff817fcc2f: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8182d910)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff8182d910-ffffffff8182da7f: uhci_alloc_qh (STB_LOCAL)
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
In drivers/usb/host/uhci-hcd.c (ffffffff81901b26)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff8190a3f2)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff818ee9aa)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff8198b186)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81ae6a35)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81c72840)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81cd9e30)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
In drivers/usb/host/uhci-hcd.c (ffffffff81d8ee6f)
Location: drivers/usb/host/uhci-q.c:245
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
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
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffff800010a68fc8)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffff800010a68fc8-ffff800010a69120: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c0b394a4)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
c0b394a4-c0b39608: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (c000000000b38830)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
c000000000b38830-c000000000b389ec: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffe000681dde)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffe000681dde-ffffffe000681ede: uhci_alloc_qh (STB_LOCAL)
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
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff817e5cf0)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff817e5cf0-ffffffff817e5e5f: uhci_alloc_qh (STB_LOCAL)
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
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff81822790)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff81822790-ffffffff818228ff: uhci_alloc_qh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct uhci_qh *uhci_alloc_qh(struct uhci_hcd *uhci, struct usb_device *udev, struct usb_host_endpoint *hep);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/uhci-hcd.c (ffffffff8183deb0)
Location: drivers/usb/host/uhci-q.c:245
Inline: False
Direct callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_urb_enqueue
```
**Symbols:**

```
ffffffff8183deb0-ffffffff8183e01f: uhci_alloc_qh (STB_LOCAL)
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
