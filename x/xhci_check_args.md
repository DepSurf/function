# Function: <code>xhci_check_args</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164b800)
Location: drivers/usb/host/xhci.c:1197
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
  - drivers/usb/host/xhci.c:xhci_alloc_streams
```
**Symbols:**

```
ffffffff8164b800-ffffffff8164b981: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ac200)
Location: drivers/usb/host/xhci.c:1204
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff816ac200-ffffffff816ac361: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816da330)
Location: drivers/usb/host/xhci.c:1207
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff816da330-ffffffff816da491: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ee8d0)
Location: drivers/usb/host/xhci.c:1173
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff816ee8d0-ffffffff816eea18: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175b110)
Location: drivers/usb/host/xhci.c:1179
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff8175b110-ffffffff8175b258: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179add0)
Location: drivers/usb/host/xhci.c:1287
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff8179add0-ffffffff8179af2e: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c1160)
Location: drivers/usb/host/xhci.c:1304
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817c1160-ffffffff817c12be: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81800b40)
Location: drivers/usb/host/xhci.c:1326
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81800b40-ffffffff81800ca3: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81831bf0)
Location: drivers/usb/host/xhci.c:1335
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81831bf0-ffffffff81831d53: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81904240)
Location: drivers/usb/host/xhci.c:1337
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_calculate_streams_and_bitmask
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81904240-ffffffff8190439e: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190c350)
Location: drivers/usb/host/xhci.c:1474
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_calculate_streams_and_bitmask
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff8190c350-ffffffff8190c4ae: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818ef910)
Location: drivers/usb/host/xhci.c:1474
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff818ef910-ffffffff818efa6f: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198c4d0)
Location: drivers/usb/host/xhci.c:1483
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff8198c4d0-ffffffff8198c672: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ae8730)
Location: drivers/usb/host/xhci.c:1524
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81ae8730-ffffffff81ae88db: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c748a0)
Location: drivers/usb/host/xhci.c:1522
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c748a0-ffffffff81c74a4b: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdb9a0)
Location: drivers/usb/host/xhci.c:1362
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81cdb9a0-ffffffff81cdbb4b: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d909c0)
Location: drivers/usb/host/xhci.c:1409
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81d909c0-ffffffff81d90b6b: xhci_check_args (STB_LOCAL)
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
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6e068)
Location: drivers/usb/host/xhci.c:1335
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffff800010a6e068-ffff800010a6e218: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b42d00)
Location: drivers/usb/host/xhci.c:1335
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
c0b42d00-c0b42e74: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b42640)
Location: drivers/usb/host/xhci.c:1335
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
c000000000b42640-c000000000b4286c: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000687bd4)
Location: drivers/usb/host/xhci.c:1335
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffe000687bd4-ffffffe000687d32: xhci_check_args (STB_LOCAL)
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
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817e9fd0)
Location: drivers/usb/host/xhci.c:1335
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817e9fd0-ffffffff817ea133: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817af0e0)
Location: drivers/usb/host/xhci.c:1335
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff817af0e0-ffffffff817af243: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81826a70)
Location: drivers/usb/host/xhci.c:1335
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81826a70-ffffffff81826bd3: xhci_check_args (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xhci_check_args(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep, int check_ep, bool check_virt_dev, const char *func);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81840950)
Location: drivers/usb/host/xhci.c:1335
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_free_dev
  - drivers/usb/host/xhci.c:xhci_alloc_streams
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81840950-ffffffff81840ab3: xhci_check_args (STB_LOCAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
