# Function: <code>skb_network_header_len</code>

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
In net/ipv4/ip_input.c (ffffffff81758a4c)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8175f162)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/skbuff.h:2088
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c7e86)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff817c8995)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (0)
Location: include/linux/skbuff.h:2088
Inline: True
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2088
Inline: True
```
```
In net/ipv6/reassembly.c (0)
Location: include/linux/skbuff.h:2088
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/skbuff.h:2088
Inline: True
```
```
In net/ipv6/ip6_offload.c (ffffffff81800d2c)
Location: include/linux/skbuff.h:2088
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ipv4/ip_input.c (ffffffff817c4dfc)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff817cb381)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff817dc545)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv6/ip6_output.c (ffffffff81834fc6)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81835a1f)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8185515d)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2223
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff8185d27c)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818619c3)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff818724b9)
Location: include/linux/skbuff.h:2223
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/ipv4/ip_input.c (ffffffff817f491c)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff817fafe1)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8180c613)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv6/ip6_output.c (ffffffff81866afc)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff8186754f)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff81886ecd)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2240
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff8188f1e5)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81895094)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff818a6aa9)
Location: include/linux/skbuff.h:2240
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/filter.c (ffffffff817eb544)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_input.c (ffffffff81814d6c)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8181b3a8)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8182c54f)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv6/ip6_output.c (ffffffff8188b1c5)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff8188bce2)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff818ad378)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2289
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff818b5746)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff818bb3c3)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff818cd528)
Location: include/linux/skbuff.h:2289
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/filter.c (ffffffff81867414)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_input.c (ffffffff81893f35)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8189a2d8)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff818ab422)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv6/ip6_output.c (ffffffff8190c3e5)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff8190cfcd)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/raw.c (ffffffff8192ff88)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (0)
Location: include/linux/skbuff.h:2376
Inline: True
```
```
In net/ipv6/reassembly.c (ffffffff819384bc)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff8193e3d9)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81952318)
Location: include/linux/skbuff.h:2376
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/filter.c (ffffffff818b6424)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_input.c (ffffffff818e81bf)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff818ee7ac)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8190085e)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/udp.c (ffffffff8191b3b0)
Location: include/linux/skbuff.h:2388
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8196385d)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff819642a8)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_input_finish
  - net/ipv6/ip6_input.c:ip6_input_finish
```
```
In net/ipv6/udp.c (ffffffff8198335f)
Location: include/linux/skbuff.h:2388
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81988c21)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff8198f710)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81991395)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81997189)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff819ab89a)
Location: include/linux/skbuff.h:2388
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/filter.c (ffffffff818db4c1)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_adjust_room
```
```
In net/ipv4/ip_input.c (ffffffff819158a7)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8191bf5c)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8192ed24)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/udp.c (ffffffff8194992d)
Location: include/linux/skbuff.h:2466
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8199881d)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81999b63)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819b986c)
Location: include/linux/skbuff.h:2466
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819bf5bb)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff819c5fca)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c7ad6)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff819cda77)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff819e23ab)
Location: include/linux/skbuff.h:2466
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
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
In net/core/skbuff.c (ffffffff818eed67)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffff81977e15)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff8197e27a)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8198deeb)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff819adfad)
Location: include/linux/skbuff.h:2552
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819c2392)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81a04675)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a05a9f)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a28499)
Location: include/linux/skbuff.h:2552
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a2e224)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81a34e2f)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a366cd)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c09d)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a51070)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a528e4)
Location: include/linux/skbuff.h:2552
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffff819ae785)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819b4c2a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819c4abb)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff819e4cbd)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff819f8f32)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81a3b265)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a3c613)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a5ef3f)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a64d94)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81a6b97f)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a6d232)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a72d1d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a87c90)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a894c4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffff81a98625)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a9ee15)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81aaff66)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81ad1dee)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff81ae6cf4)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81b3082e)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b31ca7)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b57879)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b5d7a1)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81b648cd)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b66588)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d8a5)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b83143)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b84954)
Location: include/linux/skbuff.h:2589
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
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
In net/core/skbuff.c (ffffffff81c30604)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81a2c735)
Location: include/linux/skbuff.h:2615
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81aa2575)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81aa8d55)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81abafa8)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81addf2e)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff81af3bc4)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81b3f45e)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b408a7)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b65d89)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b6bf91)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81b7306d)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81b74d61)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81b7c35d)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b927f0)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b942b4)
Location: include/linux/skbuff.h:2615
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_query
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
In net/core/skbuff.c (ffffffff81c228e2)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81a13cdf)
Location: include/linux/skbuff.h:2631
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81a8d275)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81a93e75)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81aa5f68)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81ac8f41)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff81adf36d)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81b2d2fe)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81b2e137)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81b53e2d)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81b5a2b2)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81b604d8)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81b6389e)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81b6ae4a)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81b81945)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81b833c0)
Location: include/linux/skbuff.h:2631
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/skbuff.c (ffffffff81d34d6a)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81ac579f)
Location: include/linux/skbuff.h:2660
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81b48445)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81b4f2b5)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81b62348)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81b877d1)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff81b9e84d)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81bf34b7)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81bf4424)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81c1d2dd)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81c2192d)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81c27dcb)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81c2b35e)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81c32caa)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81c4d986)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81c4f490)
Location: include/linux/skbuff.h:2660
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/skbuff.c (ffffffff81bfcd4b)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81c412d4)
Location: include/linux/skbuff.h:3029
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81cd57c0)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81cdcc3c)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81cf15d8)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81d18641)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff81d30bb2)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81d8c0bf)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81d8d14a)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81db993e)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81dbe7e7)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81dc51ab)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81dc8603)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81dd0497)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81dee059)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81defebb)
Location: include/linux/skbuff.h:3029
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/skbuff.c (ffffffff81dac79c)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81df6a34)
Location: include/linux/skbuff.h:2923
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81e95c20)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81e9d6ac)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81eb5dd8)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81edefa1)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff81ef8cc2)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81f5a07f)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81f5b241)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81f899ce)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81f8ecce)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81f95d3b)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81f99393)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1827)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81fc261c)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81fc3fdb)
Location: include/linux/skbuff.h:2923
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/skbuff.c (ffffffff81e1c597)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81e686e4)
Location: include/linux/skbuff.h:2977
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81ef4460)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81efbdfd)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81f141f8)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81f3e3e1)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff81f58732)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81fb9d30)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81fbafcd)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81fe927e)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff81fef488)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81ff670b)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff81ff9d63)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff82002099)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/seg6_local.c (ffffffff8201d10d)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff8202359a)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff82024ffb)
Location: include/linux/skbuff.h:2977
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/skbuff.c (ffffffff81ed9c97)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_dump
```
```
In net/core/filter.c (ffffffff81f278b4)
Location: include/linux/skbuff.h:2984
Inline: True
```
```
In net/ipv4/ip_input.c (ffffffff81fb83e0)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffff81fbfd3d)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81fd86d8)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff82004681)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (ffffffff8201ebf2)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff820871fd)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff820883dd)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff820b5d8e)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (ffffffff820bcfcf)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff820c434b)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/mcast.c:__mld_query_work
```
```
In net/ipv6/reassembly.c (ffffffff820c79d3)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
```
```
In net/ipv6/exthdrs.c (ffffffff820d0e99)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/seg6_local.c (ffffffff820ec0ed)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:seg6_pop_srh
```
```
In net/ipv6/ip6_offload.c (ffffffff820f2698)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff820f42db)
Location: include/linux/skbuff.h:2984
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_mld_msg
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
In net/core/skbuff.c (ffff800010bb43bc)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffff800010c5eccc)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffff800010c653c4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffff800010c7abb4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/udp.c (ffff800010c9cce4)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (ffff800010cae6e8)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffff800010cfc3b4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffff800010cfd948)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffff800010d24da8)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (ffff800010d2ac68)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffff800010d332b8)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffff800010d35bec)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffff800010d3b854)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffff800010d54850)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffff800010d562e0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (c0cd00d0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (c0d6e408)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (c0d74ff0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (c0d88230)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/udp.c (c0da70b8)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_send_skb
```
```
In net/ipv4/igmp.c (c0dbca08)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (c0e03798)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (c0e05100)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c0e282f8)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
```
In net/ipv6/raw.c (c0e2ec94)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (c0e35fcc)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c0e380ec)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (c0e3ecfc)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_destopt_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (c0e54e30)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c0e568dc)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (c000000000d6178c)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (c000000000d69924)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (c000000000d7f930)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (c000000000daf794)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (c000000000dc6ae4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (c000000000e23e84)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (c000000000e25a08)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (c000000000e54524)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (c000000000e5bf1c)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (c000000000e658e4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (c000000000e67d6c)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (c000000000e6f0cc)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (c000000000e8d37c)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (c000000000e8f498)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (ffffffe000742172)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffe0007c72a4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_input.c:ip_local_deliver_finish
```
```
In net/ipv4/ip_output.c (ffffffe0007ccbec)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffe0007de5b2)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
```
```
In net/ipv4/udp.c (ffffffe0007f7918)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (ffffffe000809a82)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffe000846c7e)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffe000847e14)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffe000865612)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (ffffffe00086b2b6)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffe00087164c)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffe000873054)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffe000878162)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffe00088c1d0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffe00088db98)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffff8194e5f5)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81954a9a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8196492b)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff81984b2d)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81998cd2)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff819da8f5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff819dbca3)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819fe5cf)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a04424)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81a0b00f)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a0c8c2)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a123ad)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a27320)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a28b54)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffff819080e5)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff8190e58a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8191e41b)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff8193e5ed)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81952792)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff819976b5)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81998a63)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff819bb38f)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (ffffffff819c11e4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff819c7dcf)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff819c9682)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff819cf16d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff819e40e0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff819e5d44)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffff819b8dc5)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819bf26a)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819cf0fb)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff819ef2fd)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a03572)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81a45375)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a46723)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a6904f)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a6eea4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81a75a8f)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a77342)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a7ce2d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/netfilter/nf_conntrack_reasm.c (ffffffff81a90fc8)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
```
In net/ipv6/ip6_offload.c (ffffffff81a92ed0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81a94704)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
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
In net/core/skbuff.c (0)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_dump
```
```
In net/ipv4/ip_input.c (ffffffff819c2645)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff819c8bea)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:__ip_make_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819d8c8b)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_reqsk_record_syn
```
```
In net/ipv4/udp.c (ffffffff819f9aed)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv4/igmp.c (ffffffff81a0dac2)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
  - net/ipv4/igmp.c:ip_mc_check_igmp
```
```
In net/ipv6/ip6_output.c (ffffffff81a51045)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_make_skb
  - net/ipv6/ip6_output.c:__ip6_make_skb
```
```
In net/ipv6/ip6_input.c (ffffffff81a52453)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
  - net/ipv6/ip6_input.c:ip6_protocol_deliver_rcu
```
```
In net/ipv6/udp.c (ffffffff81a7562f)
Location: include/linux/skbuff.h:2566
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81a7b4d4)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/raw.c:rawv6_rcv
```
```
In net/ipv6/mcast.c (ffffffff81a821bf)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_event_query
```
```
In net/ipv6/reassembly.c (ffffffff81a83960)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/reassembly.c:ipv6_frag_rcv
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
```
In net/ipv6/exthdrs.c (ffffffff81a8967d)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
```
In net/ipv6/ip6_offload.c (ffffffff81a9f024)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
```
In net/ipv6/mcast_snoop.c (ffffffff81aa0864)
Location: include/linux/skbuff.h:2566
Inline: True
Inline callers:
  - net/ipv6/mcast_snoop.c:ipv6_mc_check_icmpv6
```
</details>
</li>
</ul>

## Differences
