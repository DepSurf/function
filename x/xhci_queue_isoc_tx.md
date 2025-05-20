# Function: <code>xhci_queue_isoc_tx</code>

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
In drivers/usb/host/xhci-ring.c (ffffffff816594d7)
Location: drivers/usb/host/xhci-ring.c:3691
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
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
In drivers/usb/host/xhci-ring.c (ffffffff816b9dc2)
Location: drivers/usb/host/xhci-ring.c:3611
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
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
In drivers/usb/host/xhci-ring.c (ffffffff816e8032)
Location: drivers/usb/host/xhci-ring.c:3512
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
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
In drivers/usb/host/xhci-ring.c (ffffffff816fc23e)
Location: drivers/usb/host/xhci-ring.c:3612
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
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
In drivers/usb/host/xhci-ring.c (ffffffff81768db0)
Location: drivers/usb/host/xhci-ring.c:3616
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
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
In drivers/usb/host/xhci-ring.c (ffffffff817aa070)
Location: drivers/usb/host/xhci-ring.c:3535
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
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
In drivers/usb/host/xhci-ring.c (ffffffff817d0020)
Location: drivers/usb/host/xhci-ring.c:3599
Inline: True
Inline callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3665
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff8180dad0-ffffffff8180e268: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff8181300f-ffffffff8181308a: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff8183ebc0-ffffffff8183f358: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff81844239-ffffffff818442b4: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3740
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81913420-ffffffff81913a15: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff81917091-ffffffff819170b2: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3772
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff8191aa30-ffffffff8191b03a: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff81c21fba-ffffffff81c21fda: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3965
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff818fdbf0-ffffffff818fe203: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff81c13f8c-ffffffff81c13fb3: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4035
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff8199cf20-ffffffff8199d5e2: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff81d20ed3-ffffffff81d20f4b: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3970
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81afa550-ffffffff81afac8a: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff81eecac2-ffffffff81eecb56: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3977
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81c88970-ffffffff81c890f0: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff820a58e0-ffffffff820a5939: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3997
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81cefb80-ffffffff81cf02e7: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff82126d9a-ffffffff82126df3: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4040
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81da53a0-ffffffff81da5b07: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff822086cb-ffffffff82208724: xhci_queue_isoc_tx.cold (STB_LOCAL)
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
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7d510)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffff800010a7d510-ffff800010a7dd4c: xhci_queue_isoc_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b507d0)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
c0b507d0-c0b510a8: xhci_queue_isoc_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b55a00)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
c000000000b55a00-c000000000b56430: xhci_queue_isoc_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe0006942ce)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffe0006942ce-ffffffe000694a04: xhci_queue_isoc_tx (STB_LOCAL)
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
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff817f6f70-ffffffff817f7708: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff817fc5e9-ffffffff817fc664: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff817bc110-ffffffff817bc8a8: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff817c1789-ffffffff817c1804: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81833a40-ffffffff818341d8: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff818390b9-ffffffff81839134: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_queue_isoc_tx(struct xhci_hcd *xhci, gfp_t mem_flags, struct urb *urb, int slot_id, unsigned int ep_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3694
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff8184dd10-ffffffff8184e4cb: xhci_queue_isoc_tx (STB_LOCAL)
ffffffff81853515-ffffffff81853587: xhci_queue_isoc_tx.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
