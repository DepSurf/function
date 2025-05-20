# Function: <code>eth_type_trans</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81740180)
Location: net/ethernet/eth.c:154
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:__dev_forward_skb
  - net/core/dev.c:napi_gro_frags
```
**Symbols:**

```
ffffffff81740180-ffffffff817402c2: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817acf20)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:virtnet_receive
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_forward_skb
```
**Symbols:**

```
ffffffff817acf20-ffffffff817ad079: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817dc570)
Location: net/ethernet/eth.c:156
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_forward_skb
```
**Symbols:**

```
ffffffff817dc570-ffffffff817dc6c9: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff817fbc30)
Location: net/ethernet/eth.c:156
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff817fbc30-ffffffff817fbd94: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818795f0)
Location: net/ethernet/eth.c:156
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818795f0-ffffffff81879754: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818cafd0)
Location: net/ethernet/eth.c:156
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818cafd0-ffffffff818cb12a: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818f6180)
Location: net/ethernet/eth.c:157
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818f6180-ffffffff818f62c9: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff819557c0)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819557c0-ffffffff81955928: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8198bc60)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8198bc60-ffffffff8198bdc8: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a63910)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a63910-ffffffff81a63a7a: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a6ba70)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a6ba70-ffffffff81a6bbda: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81a54200)
Location: net/ethernet/eth.c:156
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a54200-ffffffff81a54365: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81b0cf10)
Location: net/ethernet/eth.c:154
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81b0cf10-ffffffff81b0d058: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81c93840)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/gro.c:napi_gro_frags
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81c93840-ffffffff81c939a2: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81e4ef70)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/gro.c:napi_gro_frags
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81e4ef70-ffffffff81e4f0d2: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81eaa610)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/gro.c:napi_gro_frags
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81eaa610-ffffffff81eaa775: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81f6d0c0)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/netkit.c:netkit_xmit
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/virtio_net.c:receive_buf
  - drivers/net/xen-netfront.c:handle_incoming_queue
  - net/core/dev.c:bpf_prog_run_generic_xdp
  - net/core/dev.c:__dev_forward_skb2
  - net/core/xdp.c:__xdp_build_skb_from_frame
  - net/core/gro.c:napi_gro_frags
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81f6d0c0-ffffffff81f6d225: eth_type_trans (STB_GLOBAL)
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
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffff800010c36cd8)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/broadcom/bgmac.c:bgmac_dma_rx_read
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/smsc/smc91x.c:smc_rcv
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffff800010c36cd8-ffff800010c36e70: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c0d49624)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_xdp_one
  - drivers/net/tun.c:tun_get_user
  - drivers/net/ethernet/freescale/fec_main.c:fec_enet_rx_queue
  - drivers/net/ethernet/ti/cpsw.c:cpsw_rx_handler
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c0d49624-c0d497dc: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (c000000000d2ecd0)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c000000000d2ecd0-c000000000d2eef4: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffe0007a8692)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffe0007a8692-ffffffe0007a87e8: eth_type_trans (STB_GLOBAL)
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
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8192bad0)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8192bad0-ffffffff8192bc38: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff818e5880)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/vxlan.c:vxlan_rcv
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/ipv4/ip_tunnel.c:ip_tunnel_rcv
```
**Symbols:**

```
ffffffff818e5880-ffffffff818e59e8: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8197cc60)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8197cc60-ffffffff8197cdc8: eth_type_trans (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__be16 eth_type_trans(struct sk_buff *skb, struct net_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff8199f1d0)
Location: net/ethernet/eth.c:155
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
  - drivers/net/loopback.c:loopback_xmit
  - drivers/net/tun.c:tun_sendmsg
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_poll
  - net/core/dev.c:napi_gro_frags
  - net/core/dev.c:netif_receive_generic_xdp
  - net/core/dev.c:__dev_forward_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8199f1d0-ffffffff8199f338: eth_type_trans (STB_GLOBAL)
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
