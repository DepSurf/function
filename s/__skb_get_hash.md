# Function: <code>__skb_get_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817126a0)
Location: net/core/flow_dissector.c:674
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_get_user
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__skb_tx_hash
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:enqueue_to_backlog
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_rcv_fanout
```
**Symbols:**

```
ffffffff817126a0-ffffffff8171299b: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8177a030)
Location: net/core/flow_dissector.c:680
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
  - net/core/filter.c:bpf_get_hash_recalc
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8177a030-ffffffff8177a321: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817a75d0)
Location: net/core/flow_dissector.c:785
Inline: False
Direct callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
  - net/core/filter.c:bpf_get_hash_recalc
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff817a75d0-ffffffff817a78d1: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c5c10)
Location: net/core/flow_dissector.c:980
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
  - net/core/filter.c:bpf_get_hash_recalc
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff817c5c10-ffffffff817c5f0f: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183f800)
Location: net/core/flow_dissector.c:1179
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
  - net/core/filter.c:bpf_get_hash_recalc
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8183f800-ffffffff8183fb06: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8188a050)
Location: net/core/flow_dissector.c:1234
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__netdev_pick_tx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8188a050-ffffffff8188a330: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818aaf80)
Location: net/core/flow_dissector.c:1410
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff818aaf80-ffffffff818ab248: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f6900)
Location: net/core/flow_dissector.c:1523
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff818f6900-ffffffff818f6ba9: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81928820)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81928820-ffffffff81928a02: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fc970)
Location: net/core/flow_dissector.c:1579
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:skb_flow_limit
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
ffffffff819fc970-ffffffff819fca65: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fc5b0)
Location: net/core/flow_dissector.c:1602
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:skb_flow_limit
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
```
**Symbols:**

```
ffffffff819fc5b0-ffffffff819fc6a5: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e2e30)
Location: net/core/flow_dissector.c:1628
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
ffffffff819e2e30-ffffffff819e2f27: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a933b0)
Location: net/core/flow_dissector.c:1633
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
ffffffff81a933b0-ffffffff81a935d3: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c09570)
Location: net/core/flow_dissector.c:1687
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
ffffffff81c09570-ffffffff81c097d6: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db92f0)
Location: net/core/flow_dissector.c:1759
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
ffffffff81db92f0-ffffffff81db9539: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e29940)
Location: net/core/flow_dissector.c:1799
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
ffffffff81e29940-ffffffff81e29bc0: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee79b0)
Location: net/core/flow_dissector.c:1849
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
ffffffff81ee79b0-ffffffff81ee7c30: __skb_get_hash (STB_GLOBAL)
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
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc4ab8)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffff800010bc4ab8-ffff800010bc4cd8: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c0ce00e0)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
**Symbols:**

```
c0ce00e0-c0ce02f0: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9f1b0)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
c000000000c9f1b0-c000000000c9f4bc: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe0007515e2)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_run_all_ft_ops
```
**Symbols:**

```
ffffffe0007515e2-ffffffe0007517a6: __skb_get_hash (STB_GLOBAL)
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
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c8820)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff818c8820-ffffffff818c8a02: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81882760)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit_one
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81882760-ffffffff81882942: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81919820)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff81919820-ffffffff81919a02: __skb_get_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __skb_get_hash(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8193aa60)
Location: net/core/flow_dissector.c:1560
Inline: False
Direct callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
  - net/core/filter.c:bpf_get_hash_recalc
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
  - net/packet/af_packet.c:fanout_demux_rollover
```
**Symbols:**

```
ffffffff8193aa60-ffffffff8193ac42: __skb_get_hash (STB_GLOBAL)
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
