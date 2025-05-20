# Function: <code>__napi_schedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718e30)
Location: net/core/dev.c:4605
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_open
  - net/core/dev.c:napi_watchdog
```
**Symbols:**

```
ffffffff81718e30-ffffffff81718e83: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781550)
Location: net/core/dev.c:4886
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:virtnet_netpoll
  - drivers/net/virtio_net.c:virtnet_busy_poll
  - drivers/net/virtio_net.c:skb_recv_done
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:sk_busy_loop
```
**Symbols:**

```
ffffffff81781550-ffffffff817815a3: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aeb40)
Location: net/core/dev.c:4905
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
```
**Symbols:**

```
ffffffff817aeb40-ffffffff817aeb93: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd4b0)
Location: net/core/dev.c:5141
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff817cd4b0-ffffffff817cd503: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81846be0)
Location: net/core/dev.c:5282
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff81846be0-ffffffff81846c33: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890250)
Location: net/core/dev.c:5412
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff81890250-ffffffff818902a3: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b0b00)
Location: net/core/dev.c:5962
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818b0b00-ffffffff818b0b53: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fd8a0)
Location: net/core/dev.c:5972
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818fd8a0-ffffffff818fd8f3: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192fef0)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff8192fef0-ffffffff8192ff43: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a03fd0)
Location: net/core/dev.c:6278
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff81a03fd0-ffffffff81a04026: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04d30)
Location: net/core/dev.c:6379
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:napi_poll
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff81a04d30-ffffffff81a04d86: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819eddd0)
Location: net/core/dev.c:6492
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff819eddd0-ffffffff819ede69: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9f070)
Location: net/core/dev.c:6478
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff81a9f070-ffffffff81a9f108: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c15c30)
Location: net/core/dev.c:5964
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff81c15c30-ffffffff81c15cbb: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc7b00)
Location: net/core/dev.c:5955
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:__napi_poll
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff81dc7b00-ffffffff81dc7b93: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:5931
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
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
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
**Symbols:**

```
ffffffff8212cbbe-ffffffff8212cbd2: __napi_schedule.cold (STB_LOCAL)
ffffffff81e36c50-ffffffff81e36d05: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:6013
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_sendmsg
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
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/subflow.c:subflow_write_space
```
**Symbols:**

```
ffffffff8220e8fc-ffffffff8220e910: __napi_schedule.cold (STB_LOCAL)
ffffffff81ef4ca0-ffffffff81ef4d55: __napi_schedule (STB_GLOBAL)
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
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcd8f0)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_interrupt
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffff800010bcd8f0-ffff800010bcd95c: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce430c)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_interrupt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
c0ce430c-c0ce4360: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca4960)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
c000000000ca4960-c000000000ca49e0: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754c76)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffe000754c76-ffffffe000754cd8: __napi_schedule (STB_GLOBAL)
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
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cfef0)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff818cfef0-ffffffff818cff43: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886050)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff81886050-ffffffff8188608d: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81920ef0)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff81920ef0-ffffffff81920f43: __napi_schedule (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __napi_schedule(struct napi_struct *n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81942c80)
Location: net/core/dev.c:5895
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:busy_poll_stop
  - net/core/dev.c:napi_complete_done
  - net/core/gro_cells.c:gro_cells_receive
```
**Symbols:**

```
ffffffff81942c80-ffffffff81942cd3: __napi_schedule (STB_GLOBAL)
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
