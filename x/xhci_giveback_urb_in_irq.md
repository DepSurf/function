# Function: <code>xhci_giveback_urb_in_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816576a0)
Location: drivers/usb/host/xhci-ring.c:596
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816576a0-ffffffff81657752: xhci_giveback_urb_in_irq.isra.28 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff816b7dd0)
Location: drivers/usb/host/xhci-ring.c:578
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff816b7dd0-ffffffff816b7e7c: xhci_giveback_urb_in_irq.isra.36 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff816e6080)
Location: drivers/usb/host/xhci-ring.c:642
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_stop_endpoint_command_watchdog
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff816e6080-ffffffff816e611d: xhci_giveback_urb_in_irq.isra.43 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff816f9da0)
Location: drivers/usb/host/xhci-ring.c:642
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff816f9da0-ffffffff816f9e88: xhci_giveback_urb_in_irq.isra.45 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817667e0)
Location: drivers/usb/host/xhci-ring.c:631
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817667e0-ffffffff817668cb: xhci_giveback_urb_in_irq.isra.40 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817a7960)
Location: drivers/usb/host/xhci-ring.c:631
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817a7960-ffffffff817a7a49: xhci_giveback_urb_in_irq.isra.41 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817cd720)
Location: drivers/usb/host/xhci-ring.c:631
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817cd720-ffffffff817cd809: xhci_giveback_urb_in_irq.isra.43 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8180d7a0)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8180d7a0-ffffffff8180d88f: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8183e890)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8183e890-ffffffff8183e97f: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff819112d0)
Location: drivers/usb/host/xhci-ring.c:662
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff819112d0-ffffffff8191138a: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81918a40)
Location: drivers/usb/host/xhci-ring.c:662
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_endpoint_urbs
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81918a40-ffffffff81918ae9: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff818fbbc0)
Location: drivers/usb/host/xhci-ring.c:719
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff818fbbc0-ffffffff818fbc69: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8199aa40)
Location: drivers/usb/host/xhci-ring.c:755
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8199aa40-ffffffff8199aae6: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81af7ea0)
Location: drivers/usb/host/xhci-ring.c:747
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81af7ea0-ffffffff81af7f65: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c85c10)
Location: drivers/usb/host/xhci-ring.c:747
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81c85c10-ffffffff81c85cd5: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ceca60)
Location: drivers/usb/host/xhci-ring.c:778
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81ceca60-ffffffff81cecb26: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da20a0)
Location: drivers/usb/host/xhci-ring.c:786
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81da20a0-ffffffff81da2166: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffff800010a7ca40)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffff800010a7ca40-ffff800010a7cbb8: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_giveback_urb_in_irq(struct xhci_hcd *xhci, struct xhci_td *cur_td, int status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b4f618)
Location: drivers/usb/host/xhci-ring.c:638
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
c0b4f618-c0b4f760: xhci_giveback_urb_in_irq (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (c000000000b54560)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
c000000000b54560-c000000000b54740: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffe000693e72)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffe000693e72-ffffffe000693fc8: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817f6c40)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817f6c40-ffffffff817f6d2f: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff817bbde0)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff817bbde0-ffffffff817bbecf: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81833710)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff81833710-ffffffff818337ff: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff8184d370)
Location: drivers/usb/host/xhci-ring.c:638
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_td_cleanup
  - drivers/usb/host/xhci-ring.c:xhci_kill_ring_urbs
```
**Symbols:**

```
ffffffff8184d370-ffffffff8184d471: xhci_giveback_urb_in_irq.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
