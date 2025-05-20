# Function: <code>napi_disable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81715e60)
Location: net/core/dev.c:4758
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81715e60-ffffffff81715eba: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177dd60)
Location: net/core/dev.c:5098
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_freeze
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff8177dd60-ffffffff8177ddcc: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ab860)
Location: net/core/dev.c:5246
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff817ab860-ffffffff817ab8cc: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c9ed0)
Location: net/core/dev.c:5450
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff817c9ed0-ffffffff817c9f3c: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818437f0)
Location: net/core/dev.c:5591
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff818437f0-ffffffff8184385c: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188dba0)
Location: net/core/dev.c:5721
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff8188dba0-ffffffff8188dc0e: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818aea20)
Location: net/core/dev.c:6284
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff818aea20-ffffffff818aea91: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fa310)
Location: net/core/dev.c:6294
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff818fa310-ffffffff818fa381: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192c450)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff8192c450-ffffffff8192c4c1: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01c70)
Location: net/core/dev.c:6623
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81a01c70-ffffffff81a01ce1: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02f70)
Location: net/core/dev.c:6754
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81a02f70-ffffffff81a02fe8: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8bb0)
Location: net/core/dev.c:6925
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff819e8bb0-ffffffff819e8c2f: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a99b20)
Location: net/core/dev.c:6911
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81a99b20-ffffffff81a99b9f: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0d160)
Location: net/core/dev.c:6397
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81c0d160-ffffffff81c0d1e2: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbcd80)
Location: net/core/dev.c:6387
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81dbcd80-ffffffff81dbcdf7: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2d5b0)
Location: net/core/dev.c:6368
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81e2d5b0-ffffffff81e2d627: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeb8b0)
Location: net/core/dev.c:6484
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:__tun_detach
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_close
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/xen-netfront.c:xennet_destroy_queues
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff81eeb8b0-ffffffff81eeb927: napi_disable (STB_GLOBAL)
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
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcb270)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_enet_suspend
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_stop
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffff800010bcb270-ffff800010bcb388: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce4c30)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/ethernet/freescale/fec_main.c:fec_suspend
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_close
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_set_pauseparam
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_adjust_link
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_timeout_work
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_stop
```
**Symbols:**

```
c0ce4c30-c0ce4cbc: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca5230)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
c000000000ca5230-c000000000ca5368: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000755250)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffe000755250-ffffffe0007552e0: napi_disable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cc450)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff818cc450-ffffffff818cc4c1: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818864e0)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffff818864e0-ffffffff81886551: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191d450)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff8191d450-ffffffff8191d4c1: napi_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void napi_disable(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193e970)
Location: net/core/dev.c:6232
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_detach_all
  - drivers/net/tun.c:__tun_detach
  - drivers/net/xen-netfront.c:xennet_close
```
**Symbols:**

```
ffffffff8193e970-ffffffff8193e9d8: napi_disable (STB_GLOBAL)
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
