# Function: <code>handle_tx_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8165b090)
Location: drivers/usb/host/xhci-ring.c:2256
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8165b090-ffffffff8165c5c6: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816bb930)
Location: drivers/usb/host/xhci-ring.c:2285
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816bb930-ffffffff816bcdca: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e9c90)
Location: drivers/usb/host/xhci-ring.c:2232
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816e9c90-ffffffff816eacdf: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fdfe0)
Location: drivers/usb/host/xhci-ring.c:2281
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff816fdfe0-ffffffff816ff104: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff8176ab60)
Location: drivers/usb/host/xhci-ring.c:2275
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8176ab60-ffffffff8176bcf2: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817abeb0)
Location: drivers/usb/host/xhci-ring.c:2195
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817abeb0-ffffffff817ad0de: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d1f10)
Location: drivers/usb/host/xhci-ring.c:2258
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817d1f10-ffffffff817d33ac: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81811880-ffffffff8181296b: handle_tx_event (STB_LOCAL)
ffffffff818136c1-ffffffff81813ac6: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81842a80-ffffffff81843bcd: handle_tx_event (STB_LOCAL)
ffffffff8184488a-ffffffff81844cab: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2337
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81914290-ffffffff81914e9e: handle_tx_event (STB_LOCAL)
ffffffff8191725a-ffffffff81917480: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2343
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff8191b8b0-ffffffff8191c46d: handle_tx_event (STB_LOCAL)
ffffffff81c22182-ffffffff81c22393: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2523
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff818fee70-ffffffff818ff92c: handle_tx_event (STB_LOCAL)
ffffffff81c1439f-ffffffff81c145af: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2588
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff8199e4f0-ffffffff8199ef8c: handle_tx_event (STB_LOCAL)
ffffffff81d2137f-ffffffff81d21724: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2522
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81afb8f0-ffffffff81afc4d6: handle_tx_event (STB_LOCAL)
ffffffff81eecf53-ffffffff81eed373: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2521
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81c8a1f0-ffffffff81c8afeb: handle_tx_event (STB_LOCAL)
ffffffff820a5939-ffffffff820a5ad5: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_interrupter *ir, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2541
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81cf0e70-ffffffff81cf1b37: handle_tx_event (STB_LOCAL)
ffffffff82126df3-ffffffff82126f41: handle_tx_event.cold (STB_LOCAL)
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
Location: drivers/usb/host/xhci-ring.c:2565
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_handle_event
```
**Symbols:**

```
ffffffff81da66c0-ffffffff81da74a5: handle_tx_event.isra.0 (STB_LOCAL)
ffffffff82208724-ffffffff82208879: handle_tx_event.isra.0.cold (STB_LOCAL)
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
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a81a90)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffff800010a81a90-ffff800010a82cac: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b54f4c)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c0b54f4c-c0b56544: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5af80)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
c000000000b5af80-c000000000b5c5b8: handle_tx_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe0006980cc)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffe0006980cc-ffffffe000699116: handle_tx_event (STB_LOCAL)
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
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817fae30-ffffffff817fbf7d: handle_tx_event (STB_LOCAL)
ffffffff817fcc3a-ffffffff817fd05b: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff817bffd0-ffffffff817c111d: handle_tx_event (STB_LOCAL)
ffffffff817c1dda-ffffffff817c21fb: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81837900-ffffffff81838a4d: handle_tx_event (STB_LOCAL)
ffffffff8183970a-ffffffff81839b2b: handle_tx_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int handle_tx_event(struct xhci_hcd *xhci, struct xhci_transfer_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2304
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81851d30-ffffffff81852e99: handle_tx_event (STB_LOCAL)
ffffffff81853b5d-ffffffff81853f7e: handle_tx_event.cold (STB_LOCAL)
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
