# Function: <code>xhci_td_cleanup</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fa3d0)
Location: drivers/usb/host/xhci-ring.c:1884
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff816fa3d0-ffffffff816fa539: xhci_td_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81766e10)
Location: drivers/usb/host/xhci-ring.c:1878
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81766e10-ffffffff81766f79: xhci_td_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a7b30)
Location: drivers/usb/host/xhci-ring.c:1803
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817a7b30-ffffffff817a7c95: xhci_td_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817cda00)
Location: drivers/usb/host/xhci-ring.c:1851
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817cda00-ffffffff817cdb65: xhci_td_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff8180d990-ffffffff8180dac4: xhci_td_cleanup (STB_LOCAL)
ffffffff81812fe4-ffffffff8181300f: xhci_td_cleanup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff8183ea80-ffffffff8183ebb4: xhci_td_cleanup (STB_LOCAL)
ffffffff8184420e-ffffffff81844239: xhci_td_cleanup.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1923
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81911390-ffffffff819114c0: xhci_td_cleanup.isra.0 (STB_LOCAL)
ffffffff81916ac0-ffffffff81916aeb: xhci_td_cleanup.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1928
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
```
**Symbols:**

```
ffffffff81918af0-ffffffff81918c20: xhci_td_cleanup.isra.0 (STB_LOCAL)
ffffffff81c219e5-ffffffff81c21a10: xhci_td_cleanup.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:773
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff818fbc70-ffffffff818fbda0: xhci_td_cleanup.isra.0 (STB_LOCAL)
ffffffff81c13b39-ffffffff81c13b60: xhci_td_cleanup.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:809
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff8199aaf0-ffffffff8199ac1d: xhci_td_cleanup.isra.0 (STB_LOCAL)
ffffffff81d209cd-ffffffff81d209f4: xhci_td_cleanup.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:801
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff81af7f70-ffffffff81af80c5: xhci_td_cleanup.isra.0 (STB_LOCAL)
ffffffff81eec546-ffffffff81eec56b: xhci_td_cleanup.isra.0.cold (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81c85cf0)
Location: drivers/usb/host/xhci-ring.c:801
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff81c85cf0-ffffffff81c85e6f: xhci_td_cleanup.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81cecb40)
Location: drivers/usb/host/xhci-ring.c:832
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff81cecb40-ffffffff81ceccbd: xhci_td_cleanup.isra.0 (STB_LOCAL)
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
In drivers/usb/host/xhci-ring.c (ffffffff81da2180)
Location: drivers/usb/host/xhci-ring.c:840
Inline: True
Direct callers:
  - drivers/usb/host/xhci-ring.c:xhci_giveback_invalidated_tds
```
**Symbols:**

```
ffffffff81da2180-ffffffff81da22fd: xhci_td_cleanup.isra.0 (STB_LOCAL)
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
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7cbb8)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffff800010a7cbb8-ffff800010a7cd40: xhci_td_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b50650)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
c0b50650-c0b507d0: xhci_td_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b550c0)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
c000000000b550c0-c000000000b552b4: xhci_td_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe0006940aa)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffe0006940aa-ffffffe0006941de: xhci_td_cleanup (STB_LOCAL)
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
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817f6e30-ffffffff817f6f64: xhci_td_cleanup (STB_LOCAL)
ffffffff817fc5be-ffffffff817fc5e9: xhci_td_cleanup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff817bbfd0-ffffffff817bc104: xhci_td_cleanup (STB_LOCAL)
ffffffff817c175e-ffffffff817c1789: xhci_td_cleanup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff81833900-ffffffff81833a34: xhci_td_cleanup (STB_LOCAL)
ffffffff8183908e-ffffffff818390b9: xhci_td_cleanup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xhci_td_cleanup(struct xhci_hcd *xhci, struct xhci_td *td, struct xhci_ring *ep_ring, int *status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:1897
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:handle_tx_event
  - drivers/usb/host/xhci-ring.c:finish_td
```
**Symbols:**

```
ffffffff8184dbd0-ffffffff8184dd04: xhci_td_cleanup (STB_LOCAL)
ffffffff818534ea-ffffffff81853515: xhci_td_cleanup.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
