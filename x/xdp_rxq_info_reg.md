# Function: <code>xdp_rxq_info_reg</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818baeb0)
Location: net/core/xdp.c:136
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff818baeb0-ffffffff818baf62: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1f90)
Location: net/core/xdp.c:150
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff818e1f90-ffffffff818e2042: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81930dc0)
Location: net/core/xdp.c:213
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81930dc0-ffffffff81930e67: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81963070)
Location: net/core/xdp.c:187
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81963070-ffffffff81963117: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35cb0)
Location: net/core/xdp.c:160
Inline: False
Direct callers:
  - net/core/dev.c:netif_alloc_rx_queues
```
**Symbols:**

```
ffffffff81a35cb0-ffffffff81a35d57: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index, unsigned int napi_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37ed0)
Location: net/core/xdp.c:160
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_page_pool
  - net/core/dev.c:netif_alloc_rx_queues
```
**Symbols:**

```
ffffffff81a37ed0-ffffffff81a37f86: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index, unsigned int napi_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1f070)
Location: net/core/xdp.c:160
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81a1f070-ffffffff81a1f126: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index, unsigned int napi_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad39e0)
Location: net/core/xdp.c:161
Inline: True
Direct callers:
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81ad39e0-ffffffff81ad3ac5: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81a64771)
Location: include/net/xdp.h:364
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81a71fd3)
Location: include/net/xdp.h:364
Inline: True
```
```
In net/core/dev.c (ffffffff81c12cc6)
Location: include/net/xdp.h:364
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/bpf/test_run.c (ffffffff81cb4609)
Location: include/net/xdp.h:364
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bef9e1)
Location: include/net/xdp.h:364
Inline: True
```
```
In drivers/net/xen-netfront.c (ffffffff81c047a3)
Location: include/net/xdp.h:364
Inline: True
```
```
In net/core/dev.c (ffffffff81dc2dea)
Location: include/net/xdp.h:364
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/bpf/test_run.c (ffffffff81e72889)
Location: include/net/xdp.h:364
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c47f78)
Location: include/net/xdp.h:339
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81c53160)
Location: include/net/xdp.h:339
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_open
```
```
In drivers/net/xen-netfront.c (ffffffff81c69e9b)
Location: include/net/xdp.h:339
Inline: True
```
```
In net/core/dev.c (ffffffff81e3228f)
Location: include/net/xdp.h:339
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/bpf/test_run.c (ffffffff81ecea30)
Location: include/net/xdp.h:339
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfd8f8)
Location: include/net/xdp.h:338
Inline: True
```
```
In drivers/net/virtio_net.c (ffffffff81d09590)
Location: include/net/xdp.h:338
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_open
```
```
In drivers/net/xen-netfront.c (ffffffff81d1e84b)
Location: include/net/xdp.h:338
Inline: True
```
```
In net/core/dev.c (ffffffff81ef073f)
Location: include/net/xdp.h:338
Inline: True
Inline callers:
  - net/core/dev.c:alloc_netdev_mqs
```
```
In net/bpf/test_run.c (ffffffff81f92260)
Location: include/net/xdp.h:338
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run_xdp_live
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
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c06c20)
Location: net/core/xdp.c:187
Inline: False
Direct callers:
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffff800010c06c20-ffff800010c06cd4: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1ff34)
Location: net/core/xdp.c:187
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - drivers/net/ethernet/ti/cpsw.c:cpsw_create_xdp_rxqs
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
c0d1ff34-c0d20008: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf1300)
Location: net/core/xdp.c:187
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
c000000000cf1300-c000000000cf1404: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe00078508c)
Location: net/core/xdp.c:187
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffe00078508c-ffffffe000785134: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81903040)
Location: net/core/xdp.c:187
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81903040-ffffffff819030e7: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bce70)
Location: net/core/xdp.c:187
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff818bce70-ffffffff818bcf17: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81954070)
Location: net/core/xdp.c:187
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81954070-ffffffff81954117: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int xdp_rxq_info_reg(struct xdp_rxq_info *xdp_rxq, struct net_device *dev, u32 queue_index);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81975d20)
Location: net/core/xdp.c:187
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_attach
  - net/core/dev.c:alloc_netdev_mqs
```
**Symbols:**

```
ffffffff81975d20-ffffffff81975dc7: xdp_rxq_info_reg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int napi_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
