# Function: <code>napi_schedule</code>

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
In drivers/net/virtio_net.c (ffffffff815f0e5d)
Location: include/linux/netdevice.h:422
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_netpoll
```
```
In drivers/net/xen-netfront.c (ffffffff815fbe7c)
Location: include/linux/netdevice.h:422
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_open
```
```
In net/core/dev.c (ffffffff81718e9c)
Location: include/linux/netdevice.h:422
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
Location: include/linux/netdevice.h:427
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_netpoll
```
```
In drivers/net/xen-netfront.c (ffffffff8165d287)
Location: include/linux/netdevice.h:427
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff817815bc)
Location: include/linux/netdevice.h:427
Inline: True
Inline callers:
  - net/core/dev.c:napi_watchdog
  - net/core/dev.c:sk_busy_loop
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff8168b090)
Location: include/linux/netdevice.h:427
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff816a02e0)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff817f992e)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff816ff818)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8170b4a0)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff8187724e)
Location: include/linux/netdevice.h:428
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8173f3ca)
Location: include/linux/netdevice.h:430
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8174a190)
Location: include/linux/netdevice.h:430
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff818c897f)
Location: include/linux/netdevice.h:430
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81763376)
Location: include/linux/netdevice.h:441
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8176e320)
Location: include/linux/netdevice.h:441
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff818f38bd)
Location: include/linux/netdevice.h:441
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817a1072)
Location: include/linux/netdevice.h:438
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817ab311)
Location: include/linux/netdevice.h:438
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff81952761)
Location: include/linux/netdevice.h:438
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817c6044)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817ced51)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff81988ab1)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8188e1b7)
Location: include/linux/netdevice.h:447
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81898ed1)
Location: include/linux/netdevice.h:447
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff81a60725)
Location: include/linux/netdevice.h:447
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8189c712)
Location: include/linux/netdevice.h:456
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff818a73d1)
Location: include/linux/netdevice.h:456
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff81a0be14)
Location: include/linux/netdevice.h:456
Inline: True
Inline callers:
  - net/core/dev.c:napi_poll
```
```
In net/core/gro_cells.c (ffffffff81a68fbe)
Location: include/linux/netdevice.h:456
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8187ec75)
Location: include/linux/netdevice.h:460
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8188abb1)
Location: include/linux/netdevice.h:460
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff819f2df3)
Location: include/linux/netdevice.h:460
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
```
```
In net/core/gro_cells.c (ffffffff81a4c37e)
Location: include/linux/netdevice.h:460
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/mptcp/protocol.c (ffffffff81bb0942)
Location: include/linux/netdevice.h:460
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8191046f)
Location: include/linux/netdevice.h:453
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff8191e205)
Location: include/linux/netdevice.h:453
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff81aa3c63)
Location: include/linux/netdevice.h:453
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
```
```
In net/core/gro_cells.c (ffffffff81b0482e)
Location: include/linux/netdevice.h:453
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/mptcp/protocol.c (ffffffff81c7e962)
Location: include/linux/netdevice.h:453
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/options.c (ffffffff81c83dfa)
Location: include/linux/netdevice.h:453
Inline: True
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
In drivers/net/tun.c (ffffffff81a67914)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81a726e8)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff81c1c648)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
```
```
In net/core/gro_cells.c (ffffffff81c8a0e1)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/mptcp/protocol.c (ffffffff81e240f0)
Location: include/linux/netdevice.h:465
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_check_push
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/options.c (ffffffff81e29f88)
Location: include/linux/netdevice.h:465
Inline: True
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
In drivers/net/tun.c (ffffffff81bf33b4)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81c06118)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff81dcd695)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
```
```
In net/core/gro_cells.c (ffffffff81e44cc1)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/mptcp/protocol.c (ffffffff81ff8fbe)
Location: include/linux/netdevice.h:479
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/options.c (ffffffff82002098)
Location: include/linux/netdevice.h:479
Inline: True
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
In drivers/net/tun.c (ffffffff81c4ba77)
Location: include/linux/netdevice.h:488
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81c6b808)
Location: include/linux/netdevice.h:488
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff81e3e1fa)
Location: include/linux/netdevice.h:488
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
```
```
In net/core/gro_cells.c (ffffffff81e9fac1)
Location: include/linux/netdevice.h:488
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/mptcp/protocol.c (ffffffff820754a9)
Location: include/linux/netdevice.h:488
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/options.c (ffffffff8207dca8)
Location: include/linux/netdevice.h:488
Inline: True
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
In drivers/net/tun.c (ffffffff81d01107)
Location: include/linux/netdevice.h:519
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81d201db)
Location: include/linux/netdevice.h:519
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_handle_rx
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/dev.c (ffffffff81efca9d)
Location: include/linux/netdevice.h:519
Inline: True
Inline callers:
  - net/core/dev.c:__napi_poll
```
```
In net/core/gro_cells.c (ffffffff81f6232b)
Location: include/linux/netdevice.h:519
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
```
In net/mptcp/protocol.c (ffffffff8214d8a2)
Location: include/linux/netdevice.h:519
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
```
```
In net/mptcp/subflow.c (ffffffff8214e4f1)
Location: include/linux/netdevice.h:519
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_write_space
```
```
In net/mptcp/options.c (ffffffff82152f81)
Location: include/linux/netdevice.h:519
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffff8000109e1118)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/broadcom/bgmac.c (ffff8000109e25e4)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_interrupt
```
```
In drivers/net/xen-netfront.c (ffff800010a07270)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:xennet_open
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffff800010c30c88)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac5554)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad3d48)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_interrupt
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_interrupt
```
```
In net/core/gro_cells.c (c0d47a88)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000aa1ef4)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/gro_cells.c (c000000000d29a1c)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe00062a856)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/gro_cells.c (ffffffe0007a6b82)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8178ab24)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff81793971)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff81928921)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff8176a474)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In net/core/gro_cells.c (ffffffff818e26d1)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817baec4)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817c3bd1)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff81979ab1)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff817d33ce)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff817dde81)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_rx_interrupt
  - drivers/net/xen-netfront.c:xennet_poll
  - drivers/net/xen-netfront.c:rx_refill_timeout
```
```
In net/core/gro_cells.c (ffffffff8199bfe2)
Location: include/linux/netdevice.h:442
Inline: True
Inline callers:
  - net/core/gro_cells.c:gro_cells_receive
```
</details>
</li>
</ul>

## Differences
