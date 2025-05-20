# Function: <code>ip6_flowlabel</code>

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
In net/core/flow_dissector.c (ffffffff8171211a)
Location: include/net/ipv6.h:810
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/tcp_ipv6.c (ffffffff817f09f8)
Location: include/net/ipv6.h:810
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
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
In net/core/flow_dissector.c (ffffffff81779ab1)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8185f76c)
Location: include/net/ipv6.h:842
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
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
In net/core/flow_dissector.c (ffffffff817a6bcf)
Location: include/net/ipv6.h:847
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818916b1)
Location: include/net/ipv6.h:847
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818a41fc)
Location: include/net/ipv6.h:847
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/flow_dissector.c (0)
Location: include/net/ipv6.h:848
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff818b7cf3)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff818ca84b)
Location: include/net/ipv6.h:848
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh
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
In net/core/flow_dissector.c (0)
Location: include/net/ipv6.h:889
Inline: True
```
```
In net/ipv6/tcp_ipv6.c (ffffffff8193ab61)
Location: include/net/ipv6.h:889
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff8194df63)
Location: include/net/ipv6.h:889
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81889a0f)
Location: include/net/ipv6.h:888
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff8197601c)
Location: include/net/ipv6.h:888
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819941e3)
Location: include/net/ipv6.h:888
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819a761f)
Location: include/net/ipv6.h:888
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff818a9c2e)
Location: include/net/ipv6.h:887
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff819abc5e)
Location: include/net/ipv6.h:887
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_multipath_hash
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cab05)
Location: include/net/ipv6.h:887
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819de192)
Location: include/net/ipv6.h:887
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff818f5794)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81a1480b)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffffffff81a2faaa)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a39752)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a4cd01)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81927697)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81a4b3fb)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffffffff81a665fa)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a702e2)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a838d1)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff819fb91d)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81b4127c)
Location: include/net/ipv6.h:949
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5efa4)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b69ef2)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7e6d0)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff819fb5e2)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81b4fd3c)
Location: include/net/ipv6.h:949
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b6d734)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b789d2)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b8d6f1)
Location: include/net/ipv6.h:949
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff819e1a7e)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81b3db64)
Location: include/net/ipv6.h:950
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81b5bacc)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b66cdc)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81b7c59c)
Location: include/net/ipv6.h:950
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81a91fcd)
Location: include/net/ipv6.h:961
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81c043c4)
Location: include/net/ipv6.h:961
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81c231fd)
Location: include/net/ipv6.h:961
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2e899)
Location: include/net/ipv6.h:961
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81c474a7)
Location: include/net/ipv6.h:961
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81c08284)
Location: include/net/ipv6.h:1015
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81d9e788)
Location: include/net/ipv6.h:1015
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81dc0108)
Location: include/net/ipv6.h:1015
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dcb4ec)
Location: include/net/ipv6.h:1015
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81de6857)
Location: include/net/ipv6.h:1015
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81db7c43)
Location: include/net/ipv6.h:1048
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81f6d678)
Location: include/net/ipv6.h:1048
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81f90878)
Location: include/net/ipv6.h:1048
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9c57c)
Location: include/net/ipv6.h:1048
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81fb9590)
Location: include/net/ipv6.h:1048
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81e27f0e)
Location: include/net/ipv6.h:1045
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81fcd798)
Location: include/net/ipv6.h:1045
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff81ff10f7)
Location: include/net/ipv6.h:1045
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffcfcc)
Location: include/net/ipv6.h:1045
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff82019ce7)
Location: include/net/ipv6.h:1045
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81ee5f91)
Location: include/net/ipv6.h:1046
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv4/tcp_input.c (ffffffff81fdbd5a)
Location: include/net/ipv6.h:1046
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_data_queue_ofo
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_input.c:tcp_rcv_spurious_retrans
  - net/ipv4/tcp_input.c:tcp_event_data_recv
```
```
In net/ipv6/route.c (ffffffff8209afe8)
Location: include/net/ipv6.h:1046
Inline: True
```
```
In net/ipv6/icmp.c (ffffffff820becd7)
Location: include/net/ipv6.h:1046
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cc0e1)
Location: include/net/ipv6.h:1046
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff820e8cb7)
Location: include/net/ipv6.h:1046
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap_red
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffff800010bc3c2c)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffff800010d0e448)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffff800010d2c4ec)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d38c20)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffff800010d4f638)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (c0cdef88)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (c0e14cf0)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (c0e30444)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (c0e3afcc)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (c0e503c0)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (c000000000c9df14)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (c000000000e3a5c0)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (c000000000e5de24)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6b604)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (c000000000e86890)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffe000750666)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffe000855f4a)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffffffe00086c7be)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffe000875e54)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffe000887bb8)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff818c7697)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff819eaa8b)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffffffff81a05c8a)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a0f972)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a22f61)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff818815d7)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv4/udp_tunnel.c (ffffffff8197202f)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv4/udp_tunnel.c:udp_tun_rx_dst
```
```
In net/ipv6/route.c (ffffffff819a784b)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffffffff819c2a4a)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cc732)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff819dfd21)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff81918697)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81a5550b)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffffffff81a7070a)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7a3f2)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d9e1)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
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
In net/core/flow_dissector.c (ffffffff819399f0)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
```
```
In net/ipv6/route.c (ffffffff81a6150b)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_multipath_l3_keys
```
```
In net/ipv6/icmp.c (ffffffff81a7cd2a)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_echo_reply
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a86c32)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_do_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_syn_recv_sock
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_reset
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_synack
```
```
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a6e6)
Location: include/net/ipv6.h:945
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_do_srh_encap
```
</details>
</li>
</ul>

## Differences
