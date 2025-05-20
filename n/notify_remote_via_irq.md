# Function: <code>notify_remote_via_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff814c8130)
Location: drivers/xen/events/events_base.c:363
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
```
**Symbols:**

```
ffffffff814c8130-ffffffff814c8191: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81518bd0)
Location: drivers/xen/events/events_base.c:363
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81518bd0-ffffffff81518c31: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815450c0)
Location: drivers/xen/events/events_base.c:362
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815450c0-ffffffff81545121: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81558ff0)
Location: drivers/xen/events/events_base.c:354
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81558ff0-ffffffff81559051: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815bd3d0)
Location: drivers/xen/events/events_base.c:354
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815bd3d0-ffffffff815bd431: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff815f5a80)
Location: drivers/xen/events/events_base.c:354
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff815f5a80-ffffffff815f5ae1: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81610b40)
Location: drivers/xen/events/events_base.c:354
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81610b40-ffffffff81610ba1: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81645e32)
Location: drivers/xen/events/events_base.c:355
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff816447c0-ffffffff8164480c: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816683b2)
Location: drivers/xen/events/events_base.c:355
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81666d70-ffffffff81666dbc: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81718542)
Location: drivers/xen/events/events_base.c:369
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81716310-ffffffff81716399: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81735ae6)
Location: drivers/xen/events/events_base.c:534
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit_one
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81732e00-ffffffff81732e7c: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817192c6)
Location: drivers/xen/events/events_base.c:551
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff817167c0-ffffffff8171683c: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff817970d7)
Location: drivers/xen/events/events_base.c:551
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81793c20-ffffffff81793cb7: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff818d0077)
Location: drivers/xen/events/events_base.c:551
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff818cc5e0-ffffffff818cc689: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a217f7)
Location: drivers/xen/events/events_base.c:553
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a1dbd0-ffffffff81a1dc79: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81a6ab87)
Location: drivers/xen/events/events_base.c:554
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81a66f70-ffffffff81a67019: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff81aba430)
Location: drivers/xen/events/events_base.c:538
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_connect
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff81aba430-ffffffff81aba4d9: notify_remote_via_irq (STB_GLOBAL)
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
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffff800010830a10)
Location: drivers/xen/events/events_base.c:355
Inline: False
Direct callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffff800010830a10-ffff800010830a80: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8162e0e2)
Location: drivers/xen/events/events_base.c:359
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8162caa0-ffffffff8162caec: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff8165c1f2)
Location: drivers/xen/events/events_base.c:355
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff8165abb0-ffffffff8165abfc: notify_remote_via_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void notify_remote_via_irq(int irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/events/events_base.c (ffffffff816767e2)
Location: drivers/xen/events/events_base.c:355
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_send_IPI_one
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:netback_changed
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_alloc_rx_buffers
```
**Symbols:**

```
ffffffff816751a0-ffffffff816751ec: notify_remote_via_irq (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
