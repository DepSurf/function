# Function: <code>napi_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171b760)
Location: net/core/dev.c:4362
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff8171b760-ffffffff8171b871: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81784010)
Location: net/core/dev.c:4637
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff81784010-ffffffff81784121: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b1620)
Location: net/core/dev.c:4660
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
```
**Symbols:**

```
ffffffff817b1620-ffffffff817b1731: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d17d0)
Location: net/core/dev.c:4882
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff817d17d0-ffffffff817d18af: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184ba10)
Location: net/core/dev.c:5023
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff8184ba10-ffffffff8184baf2: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81895d90)
Location: net/core/dev.c:5153
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81895d90-ffffffff81895e7d: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b7ae0)
Location: net/core/dev.c:5689
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff818b7ae0-ffffffff818b7c35: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81903950)
Location: net/core/dev.c:5699
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81903950-ffffffff81903aac: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81936710)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81936710-ffffffff8193686c: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0b340)
Location: net/core/dev.c:6005
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81a0b340-ffffffff81a0b4cf: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0c9f0)
Location: net/core/dev.c:6106
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_receive
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81a0c9f0-ffffffff81a0cb63: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f3240)
Location: net/core/dev.c:6225
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff819f3240-ffffffff819f3426: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa4ba0)
Location: net/core/dev.c:6207
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81aa4ba0-ffffffff81aa4d83: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81c54700)
Location: net/core/gro.c:629
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81c54700-ffffffff81c54903: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e09e80)
Location: net/core/gro.c:646
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81e09e80-ffffffff81e0a083: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81e7c650)
Location: net/core/gro.c:600
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81e7c650-ffffffff81e7c871: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gro.c (ffffffff81f3c9a0)
Location: net/core/gro.c:600
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81f3c9a0-ffffffff81f3cbc1: napi_gro_receive (STB_GLOBAL)
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
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd4d68)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffff800010bd4d68-ffff800010bd4f2c: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cef250)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
c0cef250-c0cef3fc: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb4050)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
c000000000cb4050-c000000000cb4288: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075e98c)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffe00075e98c-ffffffe00075eaec: napi_gro_receive (STB_GLOBAL)
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
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d66e0)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff818d66e0-ffffffff818d683c: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890520)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81890520-ffffffff8189067c: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81927710)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81927710-ffffffff8192786c: napi_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
gro_result_t napi_gro_receive(struct napi_struct *napi, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81948d80)
Location: net/core/dev.c:5622
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81948d80-ffffffff81948f01: napi_gro_receive (STB_GLOBAL)
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
