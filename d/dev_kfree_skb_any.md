# Function: <code>dev_kfree_skb_any</code>

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
In drivers/net/virtio_net.c (ffffffff815f19e9)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff815faf58)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8171c62b)
Location: include/linux/netdevice.h:3043
Inline: True
```
```
In net/core/netpoll.c (ffffffff81738c6b)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/netpoll.c:zap_completion_queue
```
```
In net/8021q/vlan_core.c (ffffffff81809672)
Location: include/linux/netdevice.h:3043
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/virtio_net.c (ffffffff81652112)
Location: include/linux/netdevice.h:3266
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff8165ae2f)
Location: include/linux/netdevice.h:3266
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81785176)
Location: include/linux/netdevice.h:3266
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817a5126)
Location: include/linux/netdevice.h:3266
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8187b187)
Location: include/linux/netdevice.h:3266
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/xen-netfront.c (ffffffff81688ba2)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817b2786)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817d3b96)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff818afa47)
Location: include/linux/netdevice.h:3205
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff8169e102)
Location: include/linux/netdevice.h:3244
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff817cff80)
Location: include/linux/netdevice.h:3244
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff817f2f37)
Location: include/linux/netdevice.h:3244
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff818d63d1)
Location: include/linux/netdevice.h:3244
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff817092a2)
Location: include/linux/netdevice.h:3269
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818498d0)
Location: include/linux/netdevice.h:3269
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8186e333)
Location: include/linux/netdevice.h:3269
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8195bf9a)
Location: include/linux/netdevice.h:3269
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff81748017)
Location: include/linux/netdevice.h:3371
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff8189391d)
Location: include/linux/netdevice.h:3371
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818bf4c3)
Location: include/linux/netdevice.h:3371
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff819b57ea)
Location: include/linux/netdevice.h:3371
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff8176c0e4)
Location: include/linux/netdevice.h:3587
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818b433f)
Location: include/linux/netdevice.h:3587
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818e82e2)
Location: include/linux/netdevice.h:3587
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff819ecaac)
Location: include/linux/netdevice.h:3587
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff817a9ef7)
Location: include/linux/netdevice.h:3604
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81900c3f)
Location: include/linux/netdevice.h:3604
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81937ad4)
Location: include/linux/netdevice.h:3604
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a5bc7a)
Location: include/linux/netdevice.h:3604
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff817cd95f)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81932f6f)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8196a994)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a928a2)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff81899503)
Location: include/linux/netdevice.h:3731
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a04ae7)
Location: include/linux/netdevice.h:3731
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a3e594)
Location: include/linux/netdevice.h:3731
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81b8dd56)
Location: include/linux/netdevice.h:3731
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff818a7a26)
Location: include/linux/netdevice.h:3892
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a0586e)
Location: include/linux/netdevice.h:3892
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a41334)
Location: include/linux/netdevice.h:3892
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81b9da25)
Location: include/linux/netdevice.h:3892
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff8188b2bb)
Location: include/linux/netdevice.h:3977
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819ee1f7)
Location: include/linux/netdevice.h:3977
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81a25f92)
Location: include/linux/netdevice.h:3977
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81b8c8e1)
Location: include/linux/netdevice.h:3977
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff8191db3c)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81a9f497)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
```
```
In net/core/netpoll.c (ffffffff81adad02)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81c58ca1)
Location: include/linux/netdevice.h:3991
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff81a75200)
Location: include/linux/netdevice.h:3781
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81c19103)
Location: include/linux/netdevice.h:3781
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81c5b4d3)
Location: include/linux/netdevice.h:3781
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81dfa58d)
Location: include/linux/netdevice.h:3781
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff81c06b8f)
Location: include/linux/netdevice.h:3826
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81dca0e2)
Location: include/linux/netdevice.h:3826
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e11797)
Location: include/linux/netdevice.h:3826
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81fcecae)
Location: include/linux/netdevice.h:3826
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/virtio_net.c (ffffffff81c50fba)
Location: include/linux/netdevice.h:3885
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81c6c296)
Location: include/linux/netdevice.h:3885
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/net/net_failover.c (ffffffff81c6f2da)
Location: include/linux/netdevice.h:3885
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
```
```
In net/core/dev.c (ffffffff81e3ac59)
Location: include/linux/netdevice.h:3885
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81e850a7)
Location: include/linux/netdevice.h:3885
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8204a5fe)
Location: include/linux/netdevice.h:3885
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/virtio_net.c (ffffffff81d06ff7)
Location: include/linux/netdevice.h:3956
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:start_xmit
```
```
In drivers/net/xen-netfront.c (ffffffff81d20c46)
Location: include/linux/netdevice.h:3956
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In drivers/net/net_failover.c (ffffffff81d23ba6)
Location: include/linux/netdevice.h:3956
Inline: True
Inline callers:
  - drivers/net/net_failover.c:net_failover_start_xmit
```
```
In net/core/dev.c (ffffffff81ef900c)
Location: include/linux/netdevice.h:3956
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff81f47097)
Location: include/linux/netdevice.h:3956
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff8211ca6a)
Location: include/linux/netdevice.h:3956
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/ethernet/freescale/fec_main.c (ffff8000109e7344)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/smsc/smc91x.c (ffff8000109fce5c)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
```
```
In drivers/net/xen-netfront.c (ffff800010a094b0)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffff800010bd0f28)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffff800010c10cfc)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffff800010d605c4)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/ethernet/freescale/fec_main.c (c0acc144)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
```
```
In drivers/net/ethernet/ti/cpsw.c (c0ad1a00)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_handler
```
```
In net/core/dev.c (c0cebbc0)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c0d27fb8)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (c0e6010c)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (c000000000caf064)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (c000000000cfc5e4)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (c000000000e9b720)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffe00075b51e)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffe00078c6ba)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffe0008959ec)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff8179257f)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff818d2f6f)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8190a964)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a31f32)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/core/dev.c (ffffffff8188cdff)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff818c3d8d)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff819ef122)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff817c27df)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff81923f6f)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8195b994)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81a9dae2)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In drivers/net/xen-netfront.c (ffffffff817dca9f)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
```
```
In net/core/dev.c (ffffffff819453df)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_skb
```
```
In net/core/netpoll.c (ffffffff8197dd77)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
```
```
In net/8021q/vlan_core.c (ffffffff81aa9ce2)
Location: include/linux/netdevice.h:3618
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
</details>
</li>
</ul>

## Differences
