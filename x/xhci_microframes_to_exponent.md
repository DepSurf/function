# Function: <code>xhci_microframes_to_exponent</code>

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
In drivers/usb/host/xhci-mem.c (ffffffff81654877)
Location: drivers/usb/host/xhci-mem.c:1243
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b35c0)
Location: drivers/usb/host/xhci-mem.c:1258
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff816b35c0-ffffffff816b3624: xhci_microframes_to_exponent.isra.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e1770)
Location: drivers/usb/host/xhci-mem.c:1291
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff816e1770-ffffffff816e17d4: xhci_microframes_to_exponent.isra.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f58b0)
Location: drivers/usb/host/xhci-mem.c:1238
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff816f58b0-ffffffff816f5918: xhci_microframes_to_exponent.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817622c0)
Location: drivers/usb/host/xhci-mem.c:1240
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff817622c0-ffffffff81762327: xhci_microframes_to_exponent.isra.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a2c80)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff817a2c80-ffffffff817a2ce4: xhci_microframes_to_exponent.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c9050)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff817c9050-ffffffff817c90b4: xhci_microframes_to_exponent.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81808e00)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81808e00-ffffffff81808e6a: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81839cc0)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81839cc0-ffffffff81839d2a: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8190bc40)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff8190bc40-ffffffff8190bcab: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff819136c0)
Location: drivers/usb/host/xhci-mem.c:1257
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff819136c0-ffffffff8191372b: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff818f6bc0)
Location: drivers/usb/host/xhci-mem.c:1244
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff818f6bc0-ffffffff818f6c2b: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81994fe0)
Location: drivers/usb/host/xhci-mem.c:1244
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81994fe0-ffffffff81995043: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81af1c90)
Location: drivers/usb/host/xhci-mem.c:1235
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81af1c90-ffffffff81af1d24: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c7ee80)
Location: drivers/usb/host/xhci-mem.c:1244
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81c7ee80-ffffffff81c7ef07: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce6100)
Location: drivers/usb/host/xhci-mem.c:1224
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81ce6100-ffffffff81ce6187: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9b200)
Location: drivers/usb/host/xhci-mem.c:1232
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81d9b200-ffffffff81d9b287: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a777c8)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffff800010a777c8-ffff800010a7789c: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int xhci_microframes_to_exponent(struct usb_device *udev, struct usb_host_endpoint *ep, unsigned int desc_interval, unsigned int min_exponent, unsigned int max_exponent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4aa8c)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: False
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
c0b4aa8c-c0b4ab20: xhci_microframes_to_exponent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b4e250)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
c000000000b4e250-c000000000b4e304: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe00068f2a4)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffe00068f2a4-ffffffe00068f386: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817f2070)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff817f2070-ffffffff817f20da: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817b7210)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff817b7210-ffffffff817b727a: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff8182eb40)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff8182eb40-ffffffff8182ebaa: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81848ca0)
Location: drivers/usb/host/xhci-mem.c:1249
Inline: True
Direct callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
**Symbols:**

```
ffffffff81848ca0-ffffffff81848d0a: xhci_microframes_to_exponent.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
