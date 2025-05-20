# Function: <code>xhci_drop_endpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164e580)
Location: drivers/usb/host/xhci.c:1643
Inline: True
```
**Symbols:**

```
ffffffff8164e580-ffffffff8164e7e8: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816aeea0)
Location: drivers/usb/host/xhci.c:1609
Inline: True
```
**Symbols:**

```
ffffffff816aeea0-ffffffff816af127: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dd040)
Location: drivers/usb/host/xhci.c:1599
Inline: True
```
**Symbols:**

```
ffffffff816dd040-ffffffff816dd2c7: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816eef30)
Location: drivers/usb/host/xhci.c:1546
Inline: True
```
**Symbols:**

```
ffffffff816eef30-ffffffff816ef1a0: xhci_drop_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8175b780)
Location: drivers/usb/host/xhci.c:1552
Inline: True
```
**Symbols:**

```
ffffffff8175b780-ffffffff8175ba0b: xhci_drop_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8179c130)
Location: drivers/usb/host/xhci.c:1678
Inline: True
```
**Symbols:**

```
ffffffff8179c130-ffffffff8179c3de: xhci_drop_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c24f0)
Location: drivers/usb/host/xhci.c:1695
Inline: True
```
**Symbols:**

```
ffffffff817c24f0-ffffffff817c279e: xhci_drop_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81801eee)
Location: drivers/usb/host/xhci.c:1720
Inline: True
```
**Symbols:**

```
ffffffff81801eb0-ffffffff81802111: xhci_drop_endpoint (STB_LOCAL)
ffffffff81807a58-ffffffff81807aa3: xhci_drop_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8183311e)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
ffffffff818330e0-ffffffff81833341: xhci_drop_endpoint (STB_LOCAL)
ffffffff8183894f-ffffffff8183899a: xhci_drop_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81905ee0)
Location: drivers/usb/host/xhci.c:1732
Inline: True
```
**Symbols:**

```
ffffffff81905ee0-ffffffff81905f29: xhci_drop_endpoint (STB_LOCAL)
ffffffff81905c60-ffffffff81905ed1: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff8190b2a1-ffffffff8190b2ec: xhci_drop_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190e690)
Location: drivers/usb/host/xhci.c:1867
Inline: True
```
**Symbols:**

```
ffffffff8190e690-ffffffff8190e6d9: xhci_drop_endpoint (STB_LOCAL)
ffffffff8190e410-ffffffff8190e681: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff81c20cce-ffffffff81c20d19: xhci_drop_endpoint.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f1b80)
Location: drivers/usb/host/xhci.c:1872
Inline: True
```
**Symbols:**

```
ffffffff818f1910-ffffffff818f1b7c: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff81c12cf6-ffffffff81c12d41: xhci_drop_endpoint.part.0.cold (STB_LOCAL)
ffffffff818f1b80-ffffffff818f1bc9: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198e9c0)
Location: drivers/usb/host/xhci.c:1884
Inline: True
```
**Symbols:**

```
ffffffff8198e690-ffffffff8198e9c0: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff81d1f9ee-ffffffff81d1fa39: xhci_drop_endpoint.part.0.cold (STB_LOCAL)
ffffffff8198e9c0-ffffffff8198ea09: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81aeae10)
Location: drivers/usb/host/xhci.c:1922
Inline: True
```
**Symbols:**

```
ffffffff81aeaaf0-ffffffff81aeae0e: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff81eeb595-ffffffff81eeb5dc: xhci_drop_endpoint.part.0.cold (STB_LOCAL)
ffffffff81aeae10-ffffffff81aeae69: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c76f50)
Location: drivers/usb/host/xhci.c:1920
Inline: True
```
**Symbols:**

```
ffffffff81c76f50-ffffffff81c772a7: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff81c772c0-ffffffff81c77319: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cde030)
Location: drivers/usb/host/xhci.c:1760
Inline: True
```
**Symbols:**

```
ffffffff81cde030-ffffffff81cde387: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff81cde3a0-ffffffff81cde3f9: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d93420)
Location: drivers/usb/host/xhci.c:1797
Inline: True
```
**Symbols:**

```
ffffffff81d93420-ffffffff81d93777: xhci_drop_endpoint.part.0 (STB_LOCAL)
ffffffff81d93790-ffffffff81d937e9: xhci_drop_endpoint (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a6ec90)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
ffff800010a6ec90-ffff800010a6efcc: xhci_drop_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b43948)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
c0b43948-c0b43c18: xhci_drop_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b43850)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
c000000000b43850-c000000000b43bec: xhci_drop_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe000688782)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
ffffffe000688782-ffffffe000688a06: xhci_drop_endpoint (STB_LOCAL)
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
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817eb4fe)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
ffffffff817eb4c0-ffffffff817eb721: xhci_drop_endpoint (STB_LOCAL)
ffffffff817f0cff-ffffffff817f0d4a: xhci_drop_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817b060e)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
ffffffff817b05d0-ffffffff817b0831: xhci_drop_endpoint (STB_LOCAL)
ffffffff817b5e95-ffffffff817b5ee0: xhci_drop_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81827f9e)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
ffffffff81827f60-ffffffff818281c1: xhci_drop_endpoint (STB_LOCAL)
ffffffff8182d7cf-ffffffff8182d81a: xhci_drop_endpoint.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xhci_drop_endpoint(struct usb_hcd *hcd, struct usb_device *udev, struct usb_host_endpoint *ep);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81841f5e)
Location: drivers/usb/host/xhci.c:1729
Inline: True
```
**Symbols:**

```
ffffffff81841f20-ffffffff81842181: xhci_drop_endpoint (STB_LOCAL)
ffffffff818478b8-ffffffff81847903: xhci_drop_endpoint.cold (STB_LOCAL)
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
