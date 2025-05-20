# Function: <code>prepare_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81656ea0)
Location: drivers/usb/host/xhci-ring.c:2804
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:prepare_transfer
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
```
**Symbols:**

```
ffffffff81656ea0-ffffffff816570f4: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816b7660)
Location: drivers/usb/host/xhci-ring.c:2834
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff816b7660-ffffffff816b785e: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e5910)
Location: drivers/usb/host/xhci-ring.c:2736
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff816e5910-ffffffff816e5b0e: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816f97c0)
Location: drivers/usb/host/xhci-ring.c:2838
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff816f97c0-ffffffff816f99a8: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81766320)
Location: drivers/usb/host/xhci-ring.c:2842
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81766320-ffffffff8176650e: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817a7060)
Location: drivers/usb/host/xhci-ring.c:2761
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff817a7060-ffffffff817a7256: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817ccf10)
Location: drivers/usb/host/xhci-ring.c:2825
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff817ccf10-ffffffff817cd101: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2871
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff8180cd80-ffffffff8180ceed: prepare_ring (STB_LOCAL)
ffffffff81812da3-ffffffff81812e15: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff8183de70-ffffffff8183dfdd: prepare_ring (STB_LOCAL)
ffffffff81843fcd-ffffffff8184403f: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2944
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81910940-ffffffff81910ab1: prepare_ring (STB_LOCAL)
ffffffff81916a1a-ffffffff81916a8c: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2953
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff819181c0-ffffffff81918331: prepare_ring (STB_LOCAL)
ffffffff81c2193f-ffffffff81c219b1: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3128
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff818fb690-ffffffff818fb830: prepare_ring (STB_LOCAL)
ffffffff81c13a72-ffffffff81c13b1e: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3198
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff8199a510-ffffffff8199a6b0: prepare_ring (STB_LOCAL)
ffffffff81d208ed-ffffffff81d20999: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:3133
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81af75e0-ffffffff81af7795: prepare_ring (STB_LOCAL)
ffffffff81eec47e-ffffffff81eec512: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81c851b0)
Location: drivers/usb/host/xhci-ring.c:3140
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81c851b0-ffffffff81c85403: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81cec0e0)
Location: drivers/usb/host/xhci-ring.c:3163
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81cec0e0-ffffffff81cec4a1: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81da1700)
Location: drivers/usb/host/xhci-ring.c:3206
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81da1700-ffffffff81da1ac1: prepare_ring (STB_LOCAL)
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
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a7bd50)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffff800010a7bd50-ffff800010a7bf88: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b4fbb8)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
c0b4fbb8-c0b4fde4: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b53d40)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
c000000000b53d40-c000000000b54050: prepare_ring (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe00069306a)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffe00069306a-ffffffe00069324c: prepare_ring (STB_LOCAL)
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
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff817f6220-ffffffff817f638d: prepare_ring (STB_LOCAL)
ffffffff817fc37d-ffffffff817fc3ef: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff817bb3c0-ffffffff817bb52d: prepare_ring (STB_LOCAL)
ffffffff817c151d-ffffffff817c158f: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff81832cf0-ffffffff81832e5d: prepare_ring (STB_LOCAL)
ffffffff81838e4d-ffffffff81838ebf: prepare_ring.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int prepare_ring(struct xhci_hcd *xhci, struct xhci_ring *ep_ring, u32 ep_state, unsigned int num_trbs, gfp_t mem_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:2898
Inline: False
Direct callers:
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:queue_command
  - drivers/usb/host/xhci-ring.c:xhci_queue_isoc_tx_prepare
  - drivers/usb/host/xhci-ring.c:prepare_transfer
```
**Symbols:**

```
ffffffff8184cef0-ffffffff8184d05d: prepare_ring (STB_LOCAL)
ffffffff818532ad-ffffffff8185331f: prepare_ring.cold (STB_LOCAL)
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
