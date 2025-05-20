# Function: <code>xdp_return_frame_rx_napi</code>

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
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818babc0)
Location: net/core/xdp.c:355
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_xmit
```
**Symbols:**

```
ffffffff818babc0-ffffffff818babde: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1b30)
Location: net/core/xdp.c:370
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_xmit
```
**Symbols:**

```
ffffffff818e1b30-ffffffff818e1b4e: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819305b0)
Location: net/core/xdp.c:442
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffffffff819305b0-ffffffff819305ce: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81962710)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffffffff81962710-ffffffff8196272e: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a35f00)
Location: net/core/xdp.c:377
Inline: False
```
**Symbols:**

```
ffffffff81a35f00-ffffffff81a35f1c: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a37de0)
Location: net/core/xdp.c:381
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/xen-netfront.c:xennet_xdp_xmit
```
**Symbols:**

```
ffffffff81a37de0-ffffffff81a37dfe: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1ef80)
Location: net/core/xdp.c:382
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81a1ef80-ffffffff81a1ef9e: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3020)
Location: net/core/xdp.c:383
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81ad3020-ffffffff81ad303e: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c51ef0)
Location: net/core/xdp.c:429
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81c51ef0-ffffffff81c51fa0: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e07160)
Location: net/core/xdp.c:427
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_act
```
**Symbols:**

```
ffffffff81e07160-ffffffff81e0720c: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e79930)
Location: net/core/xdp.c:429
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
**Symbols:**

```
ffffffff81e79930-ffffffff81e799f7: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81f39a50)
Location: net/core/xdp.c:429
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue_multi
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/devmap.c:dev_map_bpf_prog_run
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/tun.c:tun_xdp_act
  - drivers/net/virtio_net.c:virtnet_xdp_handler
```
**Symbols:**

```
ffffffff81f39a50-ffffffff81f39b17: xdp_return_frame_rx_napi (STB_GLOBAL)
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
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c07000)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffff800010c07000-ffff800010c07038: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d2020c)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_xdp_xmit
  - drivers/net/ethernet/ti/cpsw.c:cpsw_xdp_tx_frame
  - drivers/net/ethernet/ti/cpsw.c:cpsw_xdp_tx_frame
```
**Symbols:**

```
c0d2020c-c0d20238: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000cf18a0)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
c000000000cf18a0-c000000000cf18c8: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe0007853f4)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffffffe0007853f4-ffffffe000785426: xdp_return_frame_rx_napi (STB_GLOBAL)
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
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff819026e0)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffffffff819026e0-ffffffff819026fe: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bc510)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffffffff818bc510-ffffffff818bc52e: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81953710)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffffffff81953710-ffffffff8195372e: xdp_return_frame_rx_napi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xdp_return_frame_rx_napi(struct xdp_frame *xdpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81975230)
Location: net/core/xdp.c:409
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_xmit_all
  - kernel/bpf/cpumap.c:bq_flush_to_queue
```
**Symbols:**

```
ffffffff81975230-ffffffff8197524e: xdp_return_frame_rx_napi (STB_GLOBAL)
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
