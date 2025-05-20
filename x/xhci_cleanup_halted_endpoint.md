# Function: <code>xhci_cleanup_halted_endpoint</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff8165afff)
Location: drivers/usb/host/xhci-ring.c:1734
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:finish_td
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
In drivers/usb/host/xhci-ring.c (ffffffff816bb892)
Location: drivers/usb/host/xhci-ring.c:1759
Inline: True
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
In drivers/usb/host/xhci-ring.c (ffffffff816e9bb6)
Location: drivers/usb/host/xhci-ring.c:1775
Inline: True
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
In drivers/usb/host/xhci-ring.c (ffffffff816fde30)
Location: drivers/usb/host/xhci-ring.c:1822
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816fde30-ffffffff816fdef0: xhci_cleanup_halted_endpoint.isra.62 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8176a9b0)
Location: drivers/usb/host/xhci-ring.c:1816
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff8176a9b0-ffffffff8176aa6c: xhci_cleanup_halted_endpoint.isra.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817abd00)
Location: drivers/usb/host/xhci-ring.c:1741
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817abd00-ffffffff817abdb2: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d1d60)
Location: drivers/usb/host/xhci-ring.c:1789
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817d1d60-ffffffff817d1e12: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81811620)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81811620-ffffffff81811769: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81842820)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81842820-ffffffff81842969: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81911940)
Location: drivers/usb/host/xhci-ring.c:1852
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81911940-ffffffff81911a4d: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81919350)
Location: drivers/usb/host/xhci-ring.c:1857
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81919350-ffffffff8191945d: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a817f0)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffff800010a817f0-ffff800010a81960: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b54d08)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
c0b54d08-c0b54e54: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5ab90)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
c000000000b5ab90-c000000000b5ad7c: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe000697e86)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffe000697e86-ffffffe000697fc0: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817fabd0)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817fabd0-ffffffff817fad19: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817bfd70)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817bfd70-ffffffff817bfeb9: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818376a0)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff818376a0-ffffffff818377e9: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xhci_cleanup_halted_endpoint(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_td *td, enum xhci_ep_reset_type reset_type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81851ad0)
Location: drivers/usb/host/xhci-ring.c:1826
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81851ad0-ffffffff81851c19: xhci_cleanup_halted_endpoint (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
