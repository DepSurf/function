# Function: <code>__dev_kfree_skb_any</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81718f30)
Location: net/core/dev.c:2333
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/netpoll.c:netpoll_start_xmit
  - net/core/netpoll.c:zap_completion_queue
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81718f30-ffffffff81718f61: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81781660)
Location: net/core/dev.c:2355
Inline: False
Direct callers:
  - drivers/net/virtio_net.c:start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81781660-ffffffff81781691: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aef70)
Location: net/core/dev.c:2487
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff817aef70-ffffffff817aefa1: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817cd8b0)
Location: net/core/dev.c:2502
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff817cd8b0-ffffffff817cd8e1: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81847260)
Location: net/core/dev.c:2529
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81847260-ffffffff81847291: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81890770)
Location: net/core/dev.c:2573
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81890770-ffffffff818907a1: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b10c0)
Location: net/core/dev.c:2808
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818b10c0-ffffffff818b10f1: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818fe0d0)
Location: net/core/dev.c:2818
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818fe0d0-ffffffff818fe101: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81930400)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81930400-ffffffff81930431: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a04970)
Location: net/core/dev.c:3096
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_vlan
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a04970-ffffffff81a049a1: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a056f0)
Location: net/core/dev.c:3121
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_vlan
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a056f0-ffffffff81a05721: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ee1f7)
Location: net/core/dev.c:3189
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819edf10-ffffffff819edf41: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a9f497)
Location: net/core/dev.c:3110
Inline: True
Inline callers:
  - net/core/dev.c:validate_xmit_vlan
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a9f1b0-ffffffff81a9f1e1: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0f420)
Location: net/core/dev.c:3145
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81c0f420-ffffffff81c0f464: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbf1c0)
Location: net/core/dev.c:3130
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81dbf1c0-ffffffff81dbf250: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bce110)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/smsc/smc91x.c:smc_hard_start_xmit
  - drivers/net/ethernet/smsc/smc91x.c:smc_hardware_send_pkt
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffff800010bce110-ffff800010bce174: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce46a0)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_napi
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_restart
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_tso
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_txq_submit_skb
  - drivers/net/ethernet/ti/cpts.c:cpts_overflow_check
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
  - drivers/net/ethernet/ti/cpts.c:cpts_fifo_read
  - drivers/net/ethernet/ti/cpsw.c:cpsw_tx_handler
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c0ce46a0-c0ce46f0: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca4e30)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c000000000ca4e30-c000000000ca4e94: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754fdc)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffe000754fdc-ffffffe000755038: __dev_kfree_skb_any (STB_GLOBAL)
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
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d0400)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818d0400-ffffffff818d0431: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81886280)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81886280-ffffffff818862ac: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81921400)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81921400-ffffffff81921431: __dev_kfree_skb_any (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __dev_kfree_skb_any(struct sk_buff *skb, enum skb_free_reason reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81943270)
Location: net/core/dev.c:2736
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - drivers/net/xen-netfront.c:xennet_start_xmit
  - net/core/dev.c:validate_xmit_skb
  - net/core/netpoll.c:zap_completion_queue
  - net/core/netpoll.c:netpoll_start_xmit
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81943270-ffffffff819432a1: __dev_kfree_skb_any (STB_GLOBAL)
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
