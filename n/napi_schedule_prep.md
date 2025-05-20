# Function: <code>napi_schedule_prep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff815f0e05)
Location: include/linux/netdevice.h:409
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
```
```
In drivers/net/xen-netfront.c (ffffffff815fbe7c)
Location: include/linux/netdevice.h:409
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81718e9c)
Location: include/linux/netdevice.h:409
Inline: True
Inline callers:
  - net/core/dev.c:napi_watchdog
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/virtio_net.c (ffffffff8165081d)
Location: include/linux/netdevice.h:414
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:skb_recv_done
```
```
In drivers/net/xen-netfront.c (ffffffff8165d287)
Location: include/linux/netdevice.h:414
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff817815bc)
Location: include/linux/netdevice.h:414
Inline: True
Inline callers:
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:sk_busy_loop
  - net/core/dev.c:sk_busy_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817a9630)
Location: net/core/dev.c:4924
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
**Symbols:**

```
ffffffff817a9630-ffffffff817a9671: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c7c70)
Location: net/core/dev.c:5160
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff817c7c70-ffffffff817c7cb1: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818417b0)
Location: net/core/dev.c:5301
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818417b0-ffffffff818417fb: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188b4e0)
Location: net/core/dev.c:5431
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff8188b4e0-ffffffff8188b52b: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ac660)
Location: net/core/dev.c:5981
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818ac660-ffffffff818ac6a8: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f86c0)
Location: net/core/dev.c:5991
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818f86c0-ffffffff818f86fe: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192a860)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff8192a860-ffffffff8192a89e: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe590)
Location: net/core/dev.c:6297
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff819fe590-ffffffff819fe5ce: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fe180)
Location: net/core/dev.c:6398
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:napi_poll
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff819fe180-ffffffff819fe1be: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e4a40)
Location: net/core/dev.c:6511
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff819e4a40-ffffffff819e4a7e: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a953d0)
Location: net/core/dev.c:6497
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff81a953d0-ffffffff81a9540e: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0bae0)
Location: net/core/dev.c:5983
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff81c0bae0-ffffffff81c0bb36: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbbbd0)
Location: net/core/dev.c:5974
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff81dbbbd0-ffffffff81dbbc25: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2c360)
Location: net/core/dev.c:5950
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:skb_xmit_done
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff81e2c360-ffffffff81e2c3b5: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eea3c0)
Location: net/core/dev.c:6032
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_xdp_set
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_set_ringparam
  - drivers/net/virtio_net.c:virtnet_poll_tx
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_open
  - drivers/net/virtio_net.c:virtnet_poll
  - drivers/net/virtio_net.c:refill_work
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:skb_xmit_done
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff81eea3c0-ffffffff81eea415: napi_schedule_prep (STB_GLOBAL)
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
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcad00)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffff800010bcad00-ffff800010bcad84: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce7cf8)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
c0ce7cf8-c0ce7d64: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca1f80)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
c000000000ca1f80-c000000000ca1fe8: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe0007536aa)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffe0007536aa-ffffffe00075370c: napi_schedule_prep (STB_GLOBAL)
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
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ca860)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818ca860-ffffffff818ca89e: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818847a0)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818847a0-ffffffff818847de: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191b860)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff8191b860-ffffffff8191b89e: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool napi_schedule_prep(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193cbb0)
Location: net/core/dev.c:5914
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff8193cbb0-ffffffff8193cbee: napi_schedule_prep (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
