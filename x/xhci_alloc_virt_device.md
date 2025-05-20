# Function: <code>xhci_alloc_virt_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816555a0)
Location: drivers/usb/host/xhci-mem.c:967
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff816555a0-ffffffff81655877: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816b5fb0)
Location: drivers/usb/host/xhci-mem.c:982
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff816b5fb0-ffffffff816b6276: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816e4250)
Location: drivers/usb/host/xhci-mem.c:1016
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff816e4250-ffffffff816e44ec: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff816f8240)
Location: drivers/usb/host/xhci-mem.c:967
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff816f8240-ffffffff816f84c8: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817637e0)
Location: drivers/usb/host/xhci-mem.c:962
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff817637e0-ffffffff81763a9b: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817a3a30)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff817a3a30-ffffffff817a3cfd: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff817c9d60)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff817c9d60-ffffffff817ca03e: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff8180c873-ffffffff8180c890: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff8180a180-ffffffff8180a429: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff8183d86e-ffffffff8183d88b: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff8183b100-ffffffff8183b3a9: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff8191014b-ffffffff81910167: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff8190de50-ffffffff8190e116: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:981
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff81c217f3-ffffffff81c2180f: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff819159e0-ffffffff81915c93: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:964
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff81c1389e-ffffffff81c138ba: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff818f8e70-ffffffff818f9137: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:964
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff81d206e2-ffffffff81d206fe: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff81997800-ffffffff81997c68: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:955
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff81eec262-ffffffff81eec27d: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff81af4740-ffffffff81af4ba7: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81c81e70)
Location: drivers/usb/host/xhci-mem.c:964
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff81c81e70-ffffffff81c823b1: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81ce8b80)
Location: drivers/usb/host/xhci-mem.c:946
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff81ce8b80-ffffffff81ce90c1: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffff81d9e3a0)
Location: drivers/usb/host/xhci-mem.c:957
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff81d9e3a0-ffffffff81d9e8f9: xhci_alloc_virt_device (STB_GLOBAL)
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
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffff800010a78d48)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffff800010a78d48-ffff800010a79070: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c0b4c83c)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
c0b4c83c-c0b4cb50: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (c000000000b50240)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
c000000000b50240-c000000000b505d4: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-mem.c (ffffffe0006907a2)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffe0006907a2-ffffffe000690a20: xhci_alloc_virt_device (STB_GLOBAL)
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
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff817f5c1e-ffffffff817f5c3b: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff817f34b0-ffffffff817f3759: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff817badbe-ffffffff817baddb: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff817b8650-ffffffff817b88f9: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff818326ee-ffffffff8183270b: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff8182ff80-ffffffff81830229: xhci_alloc_virt_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_alloc_virt_device(struct xhci_hcd *xhci, int slot_id, struct usb_device *udev, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-mem.c (0)
Location: drivers/usb/host/xhci-mem.c:972
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_alloc_dev
```
**Symbols:**

```
ffffffff8184c8ce-ffffffff8184c8eb: xhci_alloc_virt_device.cold (STB_LOCAL)
ffffffff8184a120-ffffffff8184a3e2: xhci_alloc_virt_device (STB_GLOBAL)
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
