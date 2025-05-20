# Function: <code>xhci_setup_input_ctx_for_quirk</code>

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
In drivers/usb/host/xhci.c (ffffffff81651df0)
Location: drivers/usb/host/xhci.c:2886
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff816b26d8)
Location: drivers/usb/host/xhci.c:2865
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff816e0888)
Location: drivers/usb/host/xhci.c:2854
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff816f453e)
Location: drivers/usb/host/xhci.c:2794
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff817607fe)
Location: drivers/usb/host/xhci.c:2810
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff817a11e1)
Location: drivers/usb/host/xhci.c:2936
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff817c74a1)
Location: drivers/usb/host/xhci.c:2953
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff81806833)
Location: drivers/usb/host/xhci.c:2984
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff818376e3)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xhci_setup_input_ctx_for_quirk(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:2996
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff81903ee0-ffffffff81903fba: xhci_setup_input_ctx_for_quirk (STB_LOCAL)
ffffffff8190b036-ffffffff8190b087: xhci_setup_input_ctx_for_quirk.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xhci_setup_input_ctx_for_quirk(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci.c (0)
Location: drivers/usb/host/xhci.c:3130
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff8190c540-ffffffff8190c61a: xhci_setup_input_ctx_for_quirk (STB_LOCAL)
ffffffff81c20a82-ffffffff81c20ad3: xhci_setup_input_ctx_for_quirk.cold (STB_LOCAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffff800010a75758)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (c0b4922c)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (c000000000b4ba84)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffe00068d7e2)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff817efa93)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff817b4ba3)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff8182c563)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
In drivers/usb/host/xhci.c (ffffffff81846553)
Location: drivers/usb/host/xhci.c:2993
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
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
</ul>
