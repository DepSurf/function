# Function: <code>xhci_check_maxpacket</code>

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
In drivers/usb/host/xhci.c (ffffffff8164fc33)
Location: drivers/usb/host/xhci.c:1244
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff816b05df)
Location: drivers/usb/host/xhci.c:1251
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff816de785)
Location: drivers/usb/host/xhci.c:1254
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff816f41fa)
Location: drivers/usb/host/xhci.c:1220
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff817604b0)
Location: drivers/usb/host/xhci.c:1226
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff817a0e8b)
Location: drivers/usb/host/xhci.c:1334
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff817c714b)
Location: drivers/usb/host/xhci.c:1351
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff81806546)
Location: drivers/usb/host/xhci.c:1373
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff818373f6)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_check_maxpacket(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1384
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81909860-ffffffff819099f4: xhci_check_maxpacket (STB_LOCAL)
ffffffff8190b9b6-ffffffff8190b9da: xhci_check_maxpacket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_check_maxpacket(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct urb *urb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1521
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff819120d0-ffffffff81912264: xhci_check_maxpacket (STB_LOCAL)
ffffffff81c213bf-ffffffff81c213e3: xhci_check_maxpacket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_check_maxpacket(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1521
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff818f56e0-ffffffff818f5879: xhci_check_maxpacket (STB_LOCAL)
ffffffff81c13478-ffffffff81c1349c: xhci_check_maxpacket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_check_maxpacket(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1530
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81993620-ffffffff8199385c: xhci_check_maxpacket (STB_LOCAL)
ffffffff81d2025d-ffffffff81d20280: xhci_check_maxpacket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_check_maxpacket(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:1571
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81af00f0-ffffffff81af0350: xhci_check_maxpacket (STB_LOCAL)
ffffffff81eebdb1-ffffffff81eebdd4: xhci_check_maxpacket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xhci_check_maxpacket(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81c7cea0)
Location: drivers/usb/host/xhci.c:1569
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81c7cea0-ffffffff81c7d137: xhci_check_maxpacket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xhci_check_maxpacket(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct urb *urb, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81ce4110)
Location: drivers/usb/host/xhci.c:1409
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
```
**Symbols:**

```
ffffffff81ce4110-ffffffff81ce43a7: xhci_check_maxpacket (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/usb/host/xhci.c (ffff800010a75444)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (c0b48e58)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (c000000000b4b6f0)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffe00068d4c4)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff817ef7a6)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff817b48b6)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff8182c276)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
In drivers/usb/host/xhci.c (ffffffff8184625f)
Location: drivers/usb/host/xhci.c:1382
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_urb_enqueue
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>gfp_t mem_flags</code>
</li>
</ul>
</details>
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
</ul>
