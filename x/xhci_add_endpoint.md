# Function: <code>xhci_add_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164e7f0)
Location: drivers/usb/host/xhci.c:1724
Inline: True
```
**Symbols:**

```
ffffffff8164e7f0-ffffffff8164ea80: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816af130)
Location: drivers/usb/host/xhci.c:1693
Inline: True
```
**Symbols:**

```
ffffffff816af130-ffffffff816af3cc: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dd2d0)
Location: drivers/usb/host/xhci.c:1682
Inline: True
```
**Symbols:**

```
ffffffff816dd2d0-ffffffff816dd56c: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ef1a0)
Location: drivers/usb/host/xhci.c:1629
Inline: True
```
**Symbols:**

```
ffffffff816ef1a0-ffffffff816ef41d: xhci_add_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175ba10)
Location: drivers/usb/host/xhci.c:1637
Inline: True
```
**Symbols:**

```
ffffffff8175ba10-ffffffff8175bcbe: xhci_add_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179c3e0)
Location: drivers/usb/host/xhci.c:1763
Inline: True
```
**Symbols:**

```
ffffffff8179c3e0-ffffffff8179c6a2: xhci_add_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c27a0)
Location: drivers/usb/host/xhci.c:1780
Inline: True
```
**Symbols:**

```
ffffffff817c27a0-ffffffff817c2a62: xhci_add_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818023b0)
Location: drivers/usb/host/xhci.c:1805
Inline: True
```
**Symbols:**

```
ffffffff818023b0-ffffffff8180240a: xhci_add_endpoint (STB_LOCAL)
ffffffff81802120-ffffffff818023a5: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81807aa3-ffffffff81807b14: xhci_add_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818335e0)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
ffffffff818335e0-ffffffff8183363a: xhci_add_endpoint (STB_LOCAL)
ffffffff81833350-ffffffff818335d5: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff8183899a-ffffffff81838a0b: xhci_add_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81905c00)
Location: drivers/usb/host/xhci.c:1817
Inline: True
```
**Symbols:**

```
ffffffff81905c00-ffffffff81905c5a: xhci_add_endpoint (STB_LOCAL)
ffffffff81905940-ffffffff81905bfc: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff8190b233-ffffffff8190b2a1: xhci_add_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190e3b0)
Location: drivers/usb/host/xhci.c:1952
Inline: True
```
**Symbols:**

```
ffffffff8190e3b0-ffffffff8190e40a: xhci_add_endpoint (STB_LOCAL)
ffffffff8190e140-ffffffff8190e3ae: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81c20c60-ffffffff81c20cce: xhci_add_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f18b0)
Location: drivers/usb/host/xhci.c:1955
Inline: True
```
**Symbols:**

```
ffffffff818f1640-ffffffff818f18ad: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81c12c88-ffffffff81c12cf6: xhci_add_endpoint.part.0.cold (STB_LOCAL)
ffffffff818f18b0-ffffffff818f190a: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198ece0)
Location: drivers/usb/host/xhci.c:1967
Inline: True
```
**Symbols:**

```
ffffffff8198ea10-ffffffff8198ecd2: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81d1fa39-ffffffff81d1faa7: xhci_add_endpoint.part.0.cold (STB_LOCAL)
ffffffff8198ece0-ffffffff8198ed3a: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81aeb140)
Location: drivers/usb/host/xhci.c:2005
Inline: True
```
**Symbols:**

```
ffffffff81aeae70-ffffffff81aeb132: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81eeb5dc-ffffffff81eeb646: xhci_add_endpoint.part.0.cold (STB_LOCAL)
ffffffff81aeb140-ffffffff81aeb1ba: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c77330)
Location: drivers/usb/host/xhci.c:2003
Inline: True
```
**Symbols:**

```
ffffffff81c77330-ffffffff81c7765d: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81c77670-ffffffff81c776ea: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cde410)
Location: drivers/usb/host/xhci.c:1843
Inline: True
```
**Symbols:**

```
ffffffff81cde410-ffffffff81cde73d: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81cde750-ffffffff81cde7ca: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d93800)
Location: drivers/usb/host/xhci.c:1880
Inline: True
```
**Symbols:**

```
ffffffff81d93800-ffffffff81d93b2d: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81d93b40-ffffffff81d93bba: xhci_add_endpoint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6fca0)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
ffff800010a70038-ffff800010a700bc: xhci_add_endpoint (STB_LOCAL)
ffff800010a6fca0-ffff800010a70034: xhci_add_endpoint.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (c0b43c18)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
c0b43f74-c0b43fd4: xhci_add_endpoint (STB_LOCAL)
c0b43c18-c0b43f74: xhci_add_endpoint.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b43bf0)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
c000000000b43fe0-c000000000b44084: xhci_add_endpoint (STB_LOCAL)
c000000000b43bf0-c000000000b43fd8: xhci_add_endpoint.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000688a06)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
ffffffe000688a06-ffffffe000688cea: xhci_add_endpoint (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817eb9c0)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
ffffffff817eb9c0-ffffffff817eba1a: xhci_add_endpoint (STB_LOCAL)
ffffffff817eb730-ffffffff817eb9b5: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff817f0d4a-ffffffff817f0dbb: xhci_add_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b0ad0)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
ffffffff817b0ad0-ffffffff817b0b2a: xhci_add_endpoint (STB_LOCAL)
ffffffff817b0840-ffffffff817b0ac5: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff817b5ee0-ffffffff817b5f51: xhci_add_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81828460)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
ffffffff81828460-ffffffff818284ba: xhci_add_endpoint (STB_LOCAL)
ffffffff818281d0-ffffffff81828455: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff8182d81a-ffffffff8182d88b: xhci_add_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_add_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81842430)
Location: drivers/usb/host/xhci.c:1814
Inline: True
```
**Symbols:**

```
ffffffff81842430-ffffffff8184248a: xhci_add_endpoint (STB_LOCAL)
ffffffff81842190-ffffffff8184242e: xhci_add_endpoint.part.0 (STB_LOCAL)
ffffffff81847903-ffffffff81847974: xhci_add_endpoint.part.0.cold (STB_LOCAL)
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
