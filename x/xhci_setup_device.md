# Function: <code>xhci_setup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164c170)
Location: drivers/usb/host/xhci.c:3791
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_address_device
  - drivers/usb/host/xhci.c:xhci_enable_device
```
**Symbols:**

```
ffffffff8164c170-ffffffff8164c8d2: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816acaf0)
Location: drivers/usb/host/xhci.c:3773
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff816acaf0-ffffffff816ad211: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dada0)
Location: drivers/usb/host/xhci.c:3762
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff816dada0-ffffffff816db4f3: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816ef490)
Location: drivers/usb/host/xhci.c:3723
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff816ef490-ffffffff816efb58: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817612c0)
Location: drivers/usb/host/xhci.c:3723
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff817612c0-ffffffff81761a0a: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817a1ca0)
Location: drivers/usb/host/xhci.c:3916
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff817a1ca0-ffffffff817a23c5: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff817c7f70)
Location: drivers/usb/host/xhci.c:3933
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff817c7f70-ffffffff817c86bf: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3975
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff818071d0-ffffffff8180780e: xhci_setup_device (STB_LOCAL)
ffffffff818084f6-ffffffff818086a1: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81838090-ffffffff818386d4: xhci_setup_device (STB_LOCAL)
ffffffff818393d8-ffffffff81839569: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4050
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff8190a7f0-ffffffff8190ae47: xhci_setup_device (STB_LOCAL)
ffffffff8190bb12-ffffffff8190bc3e: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4188
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81913000-ffffffff81913569: xhci_setup_device (STB_LOCAL)
ffffffff81c2151e-ffffffff81c21649: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4115
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff818f64d0-ffffffff818f6a39: xhci_setup_device (STB_LOCAL)
ffffffff81c135d3-ffffffff81c136fe: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4135
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81994790-ffffffff81994d83: xhci_setup_device (STB_LOCAL)
ffffffff81d203e5-ffffffff81d20524: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4167
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81af1370-ffffffff81af19fd: xhci_setup_device (STB_LOCAL)
ffffffff81eebf1f-ffffffff81eec075: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c7e340)
Location: drivers/usb/host/xhci.c:4171
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81c7e340-ffffffff81c7eb73: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce55c0)
Location: drivers/usb/host/xhci.c:4011
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81ce55c0-ffffffff81ce5df4: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup, unsigned int timeout_ms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d9a630)
Location: drivers/usb/host/xhci.c:4068
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81d9a630-ffffffff81d9ae82: xhci_setup_device (STB_LOCAL)
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
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a763c0)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffff800010a763c0-ffff800010a76bd8: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b49e04)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
c0b49e04-c0b4a7dc: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b4c960)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
c000000000b4c960-c000000000b4d4b0: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe00068e23a)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffe00068e23a-ffffffe00068e964: xhci_setup_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff817f0440-ffffffff817f0a84: xhci_setup_device (STB_LOCAL)
ffffffff817f1788-ffffffff817f1919: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff817b55a0-ffffffff817b5be4: xhci_setup_device (STB_LOCAL)
ffffffff817b692e-ffffffff817b6abf: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff8182cf10-ffffffff8182d554: xhci_setup_device (STB_LOCAL)
ffffffff8182e258-ffffffff8182e3e9: xhci_setup_device.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_setup_device(struct usb_hcd *hcd, struct usb_device *udev, enum xhci_setup_dev setup);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:4046
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_enable_device
  - drivers/usb/host/xhci.c:xhci_address_device
```
**Symbols:**

```
ffffffff81846f40-ffffffff81847622: xhci_setup_device (STB_LOCAL)
ffffffff8184833e-ffffffff818484e0: xhci_setup_device.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int timeout_ms</code>
</li>
</ul>
</details>
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
