# Function: <code>napi_complete_done</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8171ada0)
Location: net/core/dev.c:4637
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
```
**Symbols:**

```
ffffffff8171ada0-ffffffff8171ae49: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817832a0)
Location: net/core/dev.c:4918
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/dev.c:sk_busy_loop
```
**Symbols:**

```
ffffffff817832a0-ffffffff8178334c: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817b0b40)
Location: net/core/dev.c:4977
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
```
**Symbols:**

```
ffffffff817b0b40-ffffffff817b0c5b: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817d0ef0)
Location: net/core/dev.c:5196
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff817d0ef0-ffffffff817d0fc8: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8184afe0)
Location: net/core/dev.c:5337
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff8184afe0-ffffffff8184b0b8: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818953e0)
Location: net/core/dev.c:5467
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff818953e0-ffffffff818954b9: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b7040)
Location: net/core/dev.c:6017
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff818b7040-ffffffff818b713c: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81902e50)
Location: net/core/dev.c:6027
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81902e50-ffffffff81902f55: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81935bd0)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81935bd0-ffffffff81935cf3: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0a8c0)
Location: net/core/dev.c:6333
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81a0a8c0-ffffffff81a0aa5d: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0bad0)
Location: net/core/dev.c:6434
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_poll
  - net/core/dev.c:napi_poll
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81a0bad0-ffffffff81a0bc6b: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f2020)
Location: net/core/dev.c:6554
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cell_poll
  - net/mptcp/protocol.c:mptcp_napi_poll
```
**Symbols:**

```
ffffffff819f2020-ffffffff819f21c8: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa3980)
Location: net/core/dev.c:6540
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cell_poll
  - net/mptcp/protocol.c:mptcp_napi_poll
```
**Symbols:**

```
ffffffff81aa3980-ffffffff81aa3b28: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1c360)
Location: net/core/dev.c:6026
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cell_poll
  - net/mptcp/protocol.c:mptcp_napi_poll
```
**Symbols:**

```
ffffffff81c1c360-ffffffff81c1c4fe: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dcd350)
Location: net/core/dev.c:6016
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cell_poll
  - net/mptcp/protocol.c:mptcp_napi_poll
```
**Symbols:**

```
ffffffff81dcd350-ffffffff81dcd505: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3deb0)
Location: net/core/dev.c:5992
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cell_poll
  - net/mptcp/protocol.c:mptcp_napi_poll
```
**Symbols:**

```
ffffffff81e3deb0-ffffffff81e3e06c: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efc750)
Location: net/core/dev.c:6074
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cell_poll
  - net/mptcp/protocol.c:mptcp_napi_poll
```
**Symbols:**

```
ffffffff81efc750-ffffffff81efc90c: napi_complete_done (STB_GLOBAL)
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
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd4078)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_poll
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffff800010bd4078-ffff800010bd4238: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cef874)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_mq_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
c0cef874-c0cefa38: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb2fd0)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
c000000000cb2fd0-c000000000cb323c: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075e09c)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffe00075e09c-ffffffe00075e19a: napi_complete_done (STB_GLOBAL)
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
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d5ba0)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff818d5ba0-ffffffff818d5cc3: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188fa10)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff8188fa10-ffffffff8188fb20: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81926bd0)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81926bd0-ffffffff81926cf3: napi_complete_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool napi_complete_done(struct napi_struct *n, int work_done);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81948220)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_napi_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:net_rx_action
  - net/core/gro_cells.c:gro_cell_poll
```
**Symbols:**

```
ffffffff81948220-ffffffff81948343: napi_complete_done (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
