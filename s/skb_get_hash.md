# Function: <code>skb_get_hash</code>

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
In drivers/net/tun.c (ffffffff815ede93)
Location: include/linux/skbuff.h:1034
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_select_queue
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_get_user
```
```
In drivers/net/xen-netfront.c (ffffffff815fa419)
Location: include/linux/skbuff.h:1034
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff81715213)
Location: include/linux/skbuff.h:1034
Inline: True
Inline callers:
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__skb_tx_hash
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:enqueue_to_backlog
```
```
In net/packet/af_packet.c (ffffffff818048e5)
Location: include/linux/skbuff.h:1034
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:packet_rcv_fanout
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
In drivers/net/tun.c (ffffffff8164dcac)
Location: include/linux/skbuff.h:1132
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/xen-netfront.c (ffffffff8165a2d9)
Location: include/linux/skbuff.h:1132
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff817818c0)
Location: include/linux/skbuff.h:1132
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/filter.c (ffffffff8179cb05)
Location: include/linux/skbuff.h:1132
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/packet/af_packet.c (ffffffff818754ae)
Location: include/linux/skbuff.h:1132
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/tun.c (ffffffff8167f99d)
Location: include/linux/skbuff.h:1147
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_get_user
  - drivers/net/tun.c:tun_net_xmit
  - drivers/net/tun.c:tun_select_queue
```
```
In drivers/net/xen-netfront.c (ffffffff81688029)
Location: include/linux/skbuff.h:1147
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff817af1d0)
Location: include/linux/skbuff.h:1147
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/filter.c (ffffffff817ca3c5)
Location: include/linux/skbuff.h:1147
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/packet/af_packet.c (ffffffff818a997e)
Location: include/linux/skbuff.h:1147
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff8169d3cb)
Location: include/linux/skbuff.h:1140
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff817cdae0)
Location: include/linux/skbuff.h:1140
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/filter.c (ffffffff817e9365)
Location: include/linux/skbuff.h:1140
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/packet/af_packet.c (ffffffff818d069a)
Location: include/linux/skbuff.h:1140
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff817086db)
Location: include/linux/skbuff.h:1214
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff818475e0)
Location: include/linux/skbuff.h:1214
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__skb_tx_hash
```
```
In net/core/filter.c (ffffffff81864765)
Location: include/linux/skbuff.h:1214
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/packet/af_packet.c (ffffffff819555ba)
Location: include/linux/skbuff.h:1214
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff8174741e)
Location: include/linux/skbuff.h:1225
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff81891e2f)
Location: include/linux/skbuff.h:1225
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__netdev_pick_tx
```
```
In net/core/filter.c (ffffffff818b18b5)
Location: include/linux/skbuff.h:1225
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a742e)
Location: include/linux/skbuff.h:1225
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff819ae22a)
Location: include/linux/skbuff.h:1225
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff8176b52e)
Location: include/linux/skbuff.h:1263
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff818b278f)
Location: include/linux/skbuff.h:1263
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:__netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff818d62e5)
Location: include/linux/skbuff.h:1263
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819ddf88)
Location: include/linux/skbuff.h:1263
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff819e4bba)
Location: include/linux/skbuff.h:1263
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff817a932e)
Location: include/linux/skbuff.h:1343
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff818fef3f)
Location: include/linux/skbuff.h:1343
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81923ab5)
Location: include/linux/skbuff.h:1343
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4caf7)
Location: include/linux/skbuff.h:1343
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81a53cb4)
Location: include/linux/skbuff.h:1343
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff817ccd9e)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff819312af)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81955ce5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a836c7)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81a8a8b9)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff81897d3e)
Location: include/linux/skbuff.h:1345
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff819ff379)
Location: include/linux/skbuff.h:1345
Inline: True
Inline callers:
  - net/core/dev.c:skb_flow_limit
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81a29815)
Location: include/linux/skbuff.h:1345
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e4bd)
Location: include/linux/skbuff.h:1345
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81b86457)
Location: include/linux/skbuff.h:1345
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In drivers/net/xen-netfront.c (ffffffff818a60fe)
Location: include/linux/skbuff.h:1366
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff819ff0ca)
Location: include/linux/skbuff.h:1366
Inline: True
Inline callers:
  - net/core/dev.c:skb_flow_limit
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81a2a175)
Location: include/linux/skbuff.h:1366
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d4d3)
Location: include/linux/skbuff.h:1366
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81b95d7c)
Location: include/linux/skbuff.h:1366
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
```
```
In net/mptcp/syncookies.c (ffffffff81bc94f4)
Location: include/linux/skbuff.h:1366
Inline: True
Inline callers:
  - net/mptcp/syncookies.c:mptcp_token_join_cookie_init_state
  - net/mptcp/syncookies.c:subflow_init_req_cookie_join_save
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
In drivers/net/xen-netfront.c (ffffffff818894be)
Location: include/linux/skbuff.h:1373
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff819ee706)
Location: include/linux/skbuff.h:1373
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81a113d5)
Location: include/linux/skbuff.h:1373
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c383)
Location: include/linux/skbuff.h:1373
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81b84c4e)
Location: include/linux/skbuff.h:1373
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In drivers/net/xen-netfront.c (ffffffff8191c0ee)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff81a9f9a7)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81ac2835)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c47283)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81c510f0)
Location: include/linux/skbuff.h:1386
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In drivers/net/xen-netfront.c (ffffffff81a712ce)
Location: include/linux/skbuff.h:1693
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff81c111c9)
Location: include/linux/skbuff.h:1693
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81c3d405)
Location: include/linux/skbuff.h:1693
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de65f2)
Location: include/linux/skbuff.h:1693
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81df25b4)
Location: include/linux/skbuff.h:1693
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In drivers/net/xen-netfront.c (ffffffff81c03d8e)
Location: include/linux/skbuff.h:1537
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff81dc0e39)
Location: include/linux/skbuff.h:1537
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81df16d5)
Location: include/linux/skbuff.h:1537
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb92f2)
Location: include/linux/skbuff.h:1537
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81fc66c4)
Location: include/linux/skbuff.h:1537
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In drivers/net/xen-netfront.c (ffffffff81c6948e)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff81e30a4d)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81e63415)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019a52)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff820273b0)
Location: include/linux/skbuff.h:1556
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In drivers/net/xen-netfront.c (ffffffff81d1de4b)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff81eecfd3)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81f22855)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8a22)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff820f6c10)
Location: include/linux/skbuff.h:1563
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In drivers/net/xen-netfront.c (ffff800010a0681c)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffff800010bcfa54)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffff800010bf7ac8)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f488)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffff800010d582b4)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In net/core/dev.c (c0ce41b4)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (c0d112ec)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (c0e501dc)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (c0e5a10c)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_fill_curr_block
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
In net/core/dev.c (c000000000cac600)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (c000000000cdda78)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86670)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (c000000000e93364)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In net/core/dev.c (ffffffe000759c0e)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffe0007794c6)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887a16)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffe00088f4ca)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
  - net/packet/af_packet.c:prb_run_all_ft_ops
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
In drivers/net/xen-netfront.c (ffffffff817915ee)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff818d12af)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff818f5cb5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22d57)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81a29f49)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/vxlan.c (ffffffff817703e5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_fill_metadata_dst
  - drivers/net/vxlan.c:vxlan_xmit_one
```
```
In net/core/dev.c (ffffffff8188b14b)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff818afae5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv4/ip_tunnel.c (ffffffff8196742d)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel.c:ip_tunnel_xmit
  - net/ipv4/ip_tunnel.c:ip_md_tunnel_xmit
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfb17)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff819e7139)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff817c1c1e)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff819222af)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff81946ce5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d7d7)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81a95af9)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
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
In drivers/net/xen-netfront.c (ffffffff817dbede)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - drivers/net/xen-netfront.c:xennet_select_queue
```
```
In net/core/dev.c (ffffffff819433e9)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/dev.c:enqueue_to_backlog
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:get_rps_cpu
  - net/core/dev.c:netdev_pick_tx
  - net/core/dev.c:__get_xps_queue_idx
```
```
In net/core/filter.c (ffffffff819685f5)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/core/filter.c:bpf_get_hash_recalc
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a4d0)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
```
In net/packet/af_packet.c (ffffffff81aa2739)
Location: include/linux/skbuff.h:1339
Inline: True
Inline callers:
  - net/packet/af_packet.c:fanout_demux_rollover
```
</details>
</li>
</ul>

## Differences
