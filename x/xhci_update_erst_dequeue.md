# Function: <code>xhci_update_erst_dequeue</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8183ddd0-ffffffff8183de6e: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81843fb3-ffffffff81843fcd: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2795
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81911df0-ffffffff81911e8e: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81916d85-ffffffff81916d9f: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2802
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81919460-ffffffff819194fe: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81c21ca1-ffffffff81c21cbb: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2978
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff818fc4c0-ffffffff818fc55e: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81c13cb0-ffffffff81c13cca: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3043
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8199b3d0-ffffffff8199b46e: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81d20b6c-ffffffff81d20b86: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2977
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81af8bb0-ffffffff81af8c59: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81eec71a-ffffffff81eec734: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c86ba0)
Location: drivers/usb/host/xhci-ring.c:2979
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81c86ba0-ffffffff81c86c4f: xhci_update_erst_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, struct xhci_interrupter *ir, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81ced9d0)
Location: drivers/usb/host/xhci-ring.c:2997
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81ced9d0-ffffffff81ceda7e: xhci_update_erst_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, struct xhci_interrupter *ir, union xhci_trb *event_ring_deq, bool clear_ehb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da3790)
Location: drivers/usb/host/xhci-ring.c:3039
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81da3790-ffffffff81da384d: xhci_update_erst_dequeue (STB_LOCAL)
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
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7c718)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffff800010a7c718-ffff800010a7c81c: xhci_update_erst_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b4f528)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c0b4f528-c0b4f618: xhci_update_erst_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b555a0)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c000000000b555a0-c000000000b55774: xhci_update_erst_dequeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe0006941de)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffe0006941de-ffffffe0006942ce: xhci_update_erst_dequeue (STB_LOCAL)
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
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817f6180-ffffffff817f621e: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff817fc363-ffffffff817fc37d: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817bb320-ffffffff817bb3be: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff817c1503-ffffffff817c151d: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81832c50-ffffffff81832cee: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81838e33-ffffffff81838e4d: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xhci_update_erst_dequeue(struct xhci_hcd *xhci, union xhci_trb *event_ring_deq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2749
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8184ce50-ffffffff8184ceee: xhci_update_erst_dequeue (STB_LOCAL)
ffffffff81853293-ffffffff818532ad: xhci_update_erst_dequeue.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct xhci_interrupter *ir</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, event_ring_deq</code> ➡️ <code>xhci, ir, event_ring_deq</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool clear_ehb</code>
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
