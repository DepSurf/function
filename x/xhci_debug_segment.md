# Function: <code>xhci_debug_segment</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_debug_segment(struct xhci_hcd *xhci, struct xhci_segment *seg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff81660a50)
Location: drivers/usb/host/xhci-dbg.c:329
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-dbg.c:xhci_debug_ring
  - drivers/usb/host/xhci-dbg.c:xhci_debug_ring
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ep_rings
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ep_rings
```
**Symbols:**

```
ffffffff81660a50-ffffffff81660add: xhci_debug_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_debug_segment(struct xhci_hcd *xhci, struct xhci_segment *seg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff816c0d60)
Location: drivers/usb/host/xhci-dbg.c:329
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ep_rings
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ep_rings
  - drivers/usb/host/xhci-dbg.c:xhci_debug_ring
  - drivers/usb/host/xhci-dbg.c:xhci_debug_ring
```
**Symbols:**

```
ffffffff816c0d60-ffffffff816c0de3: xhci_debug_segment (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_debug_segment(struct xhci_hcd *xhci, struct xhci_segment *seg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-dbg.c (ffffffff816eecd0)
Location: drivers/usb/host/xhci-dbg.c:329
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ep_rings
  - drivers/usb/host/xhci-dbg.c:xhci_dbg_ep_rings
  - drivers/usb/host/xhci-dbg.c:xhci_debug_ring
  - drivers/usb/host/xhci-dbg.c:xhci_debug_ring
```
**Symbols:**

```
ffffffff816eecd0-ffffffff816eed53: xhci_debug_segment (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
