# Function: <code>xhci_drop_ep_from_interval_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8164eac0)
Location: drivers/usb/host/xhci.c:2386
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff8164eac0-ffffffff8164ec28: xhci_drop_ep_from_interval_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816af410)
Location: drivers/usb/host/xhci.c:2364
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff816af410-ffffffff816af572: xhci_drop_ep_from_interval_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff816dd5b0)
Location: drivers/usb/host/xhci.c:2353
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff816dd5b0-ffffffff816dd712: xhci_drop_ep_from_interval_table (STB_GLOBAL)
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
In drivers/usb/host/xhci.c (ffffffff816ee230)
Location: drivers/usb/host/xhci.c:2297
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff816ee230-ffffffff816ee38c: xhci_drop_ep_from_interval_table.isra.30 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff8175aa60)
Location: drivers/usb/host/xhci.c:2308
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff8175aa60-ffffffff8175abc2: xhci_drop_ep_from_interval_table.isra.30 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff8179b170)
Location: drivers/usb/host/xhci.c:2434
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff8179b170-ffffffff8179b290: xhci_drop_ep_from_interval_table.isra.31 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817c12c0)
Location: drivers/usb/host/xhci.c:2451
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff817c12c0-ffffffff817c13f0: xhci_drop_ep_from_interval_table.isra.25 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81800d00)
Location: drivers/usb/host/xhci.c:2480
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81800d00-ffffffff81800e44: xhci_drop_ep_from_interval_table.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81831db0)
Location: drivers/usb/host/xhci.c:2489
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81831db0-ffffffff81831ef4: xhci_drop_ep_from_interval_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81904f30)
Location: drivers/usb/host/xhci.c:2492
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81904f30-ffffffff81905061: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8190d7c0)
Location: drivers/usb/host/xhci.c:2625
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff8190d7c0-ffffffff8190d8ea: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff818f0d50)
Location: drivers/usb/host/xhci.c:2620
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff818f0d50-ffffffff818f0e81: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff8198d480)
Location: drivers/usb/host/xhci.c:2632
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff8198d480-ffffffff8198d6d8: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ae96d0)
Location: drivers/usb/host/xhci.c:2670
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81ae96d0-ffffffff81ae995e: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c75a30)
Location: drivers/usb/host/xhci.c:2668
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81c75a30-ffffffff81c75cbe: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81cdcb40)
Location: drivers/usb/host/xhci.c:2508
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81cdcb40-ffffffff81cdcdd0: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81d91b60)
Location: drivers/usb/host/xhci.c:2544
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81d91b60-ffffffff81d91dde: xhci_drop_ep_from_interval_table (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffff800010a6e2c0)
Location: drivers/usb/host/xhci.c:2489
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffff800010a6e2c0-ffff800010a6e498: xhci_drop_ep_from_interval_table.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c0b417d0)
Location: drivers/usb/host/xhci.c:2489
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
c0b417d0-c0b41938: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (c000000000b40e60)
Location: drivers/usb/host/xhci.c:2489
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
c000000000b40e60-c000000000b410a4: xhci_drop_ep_from_interval_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_drop_ep_from_interval_table(struct xhci_hcd *xhci, struct xhci_bw_info *ep_bw, struct xhci_interval_bw_table *bw_table, struct usb_device *udev, struct xhci_virt_ep *virt_ep, struct xhci_tt_bw_info *tt_info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffe0006865aa)
Location: drivers/usb/host/xhci.c:2489
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffe0006865aa-ffffffe000686738: xhci_drop_ep_from_interval_table (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817ea190)
Location: drivers/usb/host/xhci.c:2489
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff817ea190-ffffffff817ea2d4: xhci_drop_ep_from_interval_table.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff817af2a0)
Location: drivers/usb/host/xhci.c:2489
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff817af2a0-ffffffff817af3e4: xhci_drop_ep_from_interval_table.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81826c30)
Location: drivers/usb/host/xhci.c:2489
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81826c30-ffffffff81826d74: xhci_drop_ep_from_interval_table.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci.c (ffffffff81840b10)
Location: drivers/usb/host/xhci.c:2489
Inline: True
Direct callers:
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
  - drivers/usb/host/xhci.c:xhci_reserve_bandwidth
```
**Symbols:**

```
ffffffff81840b10-ffffffff81840c54: xhci_drop_ep_from_interval_table.isra.0 (STB_LOCAL)
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
