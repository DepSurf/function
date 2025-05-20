# Function: <code>xhci_queue_new_dequeue_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff81659fd0)
Location: drivers/usb/host/xhci-ring.c:4105
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff81659fd0-ffffffff8165a1ed: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816ba770)
Location: drivers/usb/host/xhci-ring.c:4004
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816ba770-ffffffff816ba991: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, unsigned int stream_id, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816e89e0)
Location: drivers/usb/host/xhci-ring.c:3904
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816e89e0-ffffffff816e8c01: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff816fcc40)
Location: drivers/usb/host/xhci-ring.c:4004
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff816fcc40-ffffffff816fce4f: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817697c0)
Location: drivers/usb/host/xhci-ring.c:4008
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817697c0-ffffffff817699cd: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817aaa80)
Location: drivers/usb/host/xhci-ring.c:3927
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817aaa80-ffffffff817aac80: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffff817d0a30)
Location: drivers/usb/host/xhci-ring.c:3991
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
  - drivers/usb/host/xhci-ring.c:handle_cmd_completion
```
**Symbols:**

```
ffffffff817d0a30-ffffffff817d0c30: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4057
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff8181357b-ffffffff818135d4: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff818107b0-ffffffff81810954: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff8184477d-ffffffff818447d6: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff818419a0-ffffffff81841b44: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4132
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff819174ca-ffffffff81917523: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff81915bb0-ffffffff81915d56: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4161
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff81c223dd-ffffffff81c22436: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff8191d1a0-ffffffff8191d346: xhci_queue_new_dequeue_state (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffff800010a80840)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffff800010a80840-ffff800010a80a30: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c0b53b38)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
c0b53b38-c0b53d34: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (c000000000b59640)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
c000000000b59640-c000000000b59978: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci-ring.c (ffffffe0006970b4)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffe0006970b4-ffffffe0006972a4: xhci_queue_new_dequeue_state (STB_GLOBAL)
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
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff817fcb2d-ffffffff817fcb86: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff817f9d50-ffffffff817f9ef4: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff817c1ccd-ffffffff817c1d26: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff817beef0-ffffffff817bf094: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff818395fd-ffffffff81839656: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff81836820-ffffffff818369c4: xhci_queue_new_dequeue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void xhci_queue_new_dequeue_state(struct xhci_hcd *xhci, unsigned int slot_id, unsigned int ep_index, struct xhci_dequeue_state *deq_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/usb/host/xhci-ring.c (0)
Location: drivers/usb/host/xhci-ring.c:4086
Inline: False
Direct callers:
  - drivers/usb/host/xhci.c:xhci_cleanup_stalled_ring
```
**Symbols:**

```
ffffffff81853a50-ffffffff81853aa9: xhci_queue_new_dequeue_state.cold (STB_LOCAL)
ffffffff81850ba0-ffffffff81850d44: xhci_queue_new_dequeue_state (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int stream_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>xhci, slot_id, ep_index, stream_id, deq_state</code> ➡️ <code>xhci, slot_id, ep_index, deq_state</code>
</li>
</ul>
</details>
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
