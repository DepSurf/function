# Function: <code>xhci_handle_event</code>

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
Location: drivers/usb/host/xhci-ring.c:2612
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
In drivers/usb/host/xhci-ring.c (ffffffff816bce7a)
Location: drivers/usb/host/xhci-ring.c:2641
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
In drivers/usb/host/xhci-ring.c (ffffffff816ead8e)
Location: drivers/usb/host/xhci-ring.c:2544
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
In drivers/usb/host/xhci-ring.c (ffffffff816ff1c7)
Location: drivers/usb/host/xhci-ring.c:2640
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
In drivers/usb/host/xhci-ring.c (ffffffff8176bdb7)
Location: drivers/usb/host/xhci-ring.c:2644
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817ad19b)
Location: drivers/usb/host/xhci-ring.c:2563
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d346c)
Location: drivers/usb/host/xhci-ring.c:2627
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81812a32)
Location: drivers/usb/host/xhci-ring.c:2673
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81843c97)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2720
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff819165f0-ffffffff81916803: xhci_handle_event (STB_LOCAL)
ffffffff819175ac-ffffffff819175fd: xhci_handle_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2727
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8191dba0-ffffffff8191dd96: xhci_handle_event (STB_LOCAL)
ffffffff81c224b7-ffffffff81c22508: xhci_handle_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2903
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff819004c0-ffffffff819006e3: xhci_handle_event (STB_LOCAL)
ffffffff81c14649-ffffffff81c146ba: xhci_handle_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2968
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff8199fc40-ffffffff8199fe58: xhci_handle_event (STB_LOCAL)
ffffffff81d217c0-ffffffff81d21831: xhci_handle_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2902
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81afd2e0-ffffffff81afd4fb: xhci_handle_event (STB_LOCAL)
ffffffff81eed41a-ffffffff81eed483: xhci_handle_event.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c8bef0)
Location: drivers/usb/host/xhci-ring.c:2904
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81c8bef0-ffffffff81c8c165: xhci_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci, struct xhci_interrupter *ir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cf2a50)
Location: drivers/usb/host/xhci-ring.c:2922
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81cf2a50-ffffffff81cf2ce6: xhci_handle_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xhci_handle_event(struct xhci_hcd *xhci, struct xhci_interrupter *ir);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da83c0)
Location: drivers/usb/host/xhci-ring.c:2970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
**Symbols:**

```
ffffffff81da83c0-ffffffff81da862d: xhci_handle_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a82da4)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b56608)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b5c6d4)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe00069920a)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817fc047)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817c11e7)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81838b17)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81852f67)
Location: drivers/usb/host/xhci-ring.c:2674
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_irq
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
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
