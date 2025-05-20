# Function: <code>handle_port_status</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff8165c676)
Location: drivers/usb/host/xhci-ring.c:1482
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
In drivers/usb/host/xhci-ring.c (ffffffff816bd0ee)
Location: drivers/usb/host/xhci-ring.c:1507
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
In drivers/usb/host/xhci-ring.c (ffffffff816eafd2)
Location: drivers/usb/host/xhci-ring.c:1523
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
In drivers/usb/host/xhci-ring.c (ffffffff816ff495)
Location: drivers/usb/host/xhci-ring.c:1570
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
In drivers/usb/host/xhci-ring.c (ffffffff8176c08c)
Location: drivers/usb/host/xhci-ring.c:1557
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
In drivers/usb/host/xhci-ring.c (ffffffff817a7ff0)
Location: drivers/usb/host/xhci-ring.c:1520
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817a7ff0-ffffffff817a85a9: handle_port_status.isra.46 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817cdec0)
Location: drivers/usb/host/xhci-ring.c:1553
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817cdec0-ffffffff817ce514: handle_port_status.isra.48 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8180e580-ffffffff8180ebee: handle_port_status.isra.0 (STB_LOCAL)
ffffffff818130d9-ffffffff8181316e: handle_port_status.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8183f670-ffffffff8183fcf7: handle_port_status.isra.0 (STB_LOCAL)
ffffffff81844303-ffffffff81844398: handle_port_status.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1590
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81911fd0-ffffffff81912610: handle_port_status (STB_LOCAL)
ffffffff81916d9f-ffffffff81916e2e: handle_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1595
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81919620-ffffffff81919c7e: handle_port_status (STB_LOCAL)
ffffffff81c21cbb-ffffffff81c21d50: handle_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1835
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff818fc6b0-ffffffff818fcd47: handle_port_status (STB_LOCAL)
ffffffff81c13d00-ffffffff81c13d93: handle_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1899
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff8199b5c0-ffffffff8199be60: handle_port_status (STB_LOCAL)
ffffffff81d20bbc-ffffffff81d20c99: handle_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1833
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81af8dd0-ffffffff81af9642: handle_port_status (STB_LOCAL)
ffffffff81eec76a-ffffffff81eec82c: handle_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1835
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81c86e30-ffffffff81c8776d: handle_port_status (STB_LOCAL)
ffffffff820a5875-ffffffff820a58b0: handle_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, struct xhci_interrupter *ir, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1857
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81cee160-ffffffff81cee932: handle_port_status (STB_LOCAL)
ffffffff82126cf2-ffffffff82126d5c: handle_port_status.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1865
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81da2900-ffffffff81da3057: handle_port_status.isra.0 (STB_LOCAL)
ffffffff822084cd-ffffffff8220853b: handle_port_status.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a7df08)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffff800010a7df08-ffff800010a7e6a4: handle_port_status.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void handle_port_status(struct xhci_hcd *xhci, union xhci_trb *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b5145c)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c0b5145c-c0b51bc4: handle_port_status (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c000000000b56600)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c000000000b56600-c000000000b56fd0: handle_port_status.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffe000694d26)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffe000694d26-ffffffe00069542e: handle_port_status.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817f7a20-ffffffff817f80a7: handle_port_status.isra.0 (STB_LOCAL)
ffffffff817fc6b3-ffffffff817fc748: handle_port_status.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817bcbc0-ffffffff817bd247: handle_port_status.isra.0 (STB_LOCAL)
ffffffff817c1853-ffffffff817c18e8: handle_port_status.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff818344f0-ffffffff81834b77: handle_port_status.isra.0 (STB_LOCAL)
ffffffff81839183-ffffffff81839218: handle_port_status.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1564
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8184e800-ffffffff8184ee95: handle_port_status.isra.0 (STB_LOCAL)
ffffffff818535d6-ffffffff8185366b: handle_port_status.isra.0.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_interrupter *ir</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, event</code> ➡️ <code>xhci, ir, event</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
