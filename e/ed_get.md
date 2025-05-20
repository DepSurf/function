# Function: <code>ed_get</code>

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
In drivers/usb/host/ohci-hcd.c (ffffffff816417e7)
Location: drivers/usb/host/ohci-q.c:398
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff816a22d7)
Location: drivers/usb/host/ohci-q.c:399
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff816ceffd)
Location: drivers/usb/host/ohci-q.c:399
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff816e36d0)
Location: drivers/usb/host/ohci-q.c:399
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff8174fef0)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff8178fb88)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff817b6368)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff817f8de6)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff81829c46)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818f7b80)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff818f7b80-ffffffff818f7ddc: ed_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff819006d0)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff819006d0-ffffffff8190092c: ed_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff818e3c40)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff818e3c40-ffffffff818e3e97: ed_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff8197fee0)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff8197fee0-ffffffff81980137: ed_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81adbde0)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81adbde0-ffffffff81adc04a: ed_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81c670c0)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81c670c0-ffffffff81c6732a: ed_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81cce450)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81cce450-ffffffff81cce6c1: ed_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ed *ed_get(struct ohci_hcd *ohci, struct usb_host_endpoint *ep, struct usb_device *udev, unsigned int pipe, int interval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ohci-hcd.c (ffffffff81d83350)
Location: drivers/usb/host/ohci-q.c:400
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
**Symbols:**

```
ffffffff81d83350-ffffffff81d835c1: ed_get (STB_LOCAL)
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
In drivers/usb/host/ohci-hcd.c (ffff800010a63100)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (c0b373a4)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (c000000000b36220)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffe00067c228)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff817e2026)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff8181eac6)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/host/ohci-hcd.c (ffffffff81838a36)
Location: drivers/usb/host/ohci-q.c:400
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
