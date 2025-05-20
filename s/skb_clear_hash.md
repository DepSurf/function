# Function: <code>skb_clear_hash</code>

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
In net/ipv4/ip_fragment.c (ffffffff8175a57f)
Location: include/linux/skbuff.h:950
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff817a47c5)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
  - net/ipv4/ip_tunnel_core.c:iptunnel_pull_header
```
```
In net/ipv4/ipmr.c (ffffffff817a83c1)
Location: include/linux/skbuff.h:950
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff817f8e86)
Location: include/linux/skbuff.h:950
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff8179d7e3)
Location: include/linux/skbuff.h:1047
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_fragment.c (ffffffff817c69cf)
Location: include/linux/skbuff.h:1047
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81812889)
Location: include/linux/skbuff.h:1047
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81815aa1)
Location: include/linux/skbuff.h:1047
Inline: True
```
```
In net/ipv6/ip6mr.c (ffffffff81868676)
Location: include/linux/skbuff.h:1047
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff817cc243)
Location: include/linux/skbuff.h:1062
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_fragment.c (ffffffff817f64cf)
Location: include/linux/skbuff.h:1062
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81843d89)
Location: include/linux/skbuff.h:1062
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81847251)
Location: include/linux/skbuff.h:1062
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81894fa7)
Location: include/linux/skbuff.h:1062
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8189b4c6)
Location: include/linux/skbuff.h:1062
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff817eb23f)
Location: include/linux/skbuff.h:1055
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_fragment.c (ffffffff818168f9)
Location: include/linux/skbuff.h:1055
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81865619)
Location: include/linux/skbuff.h:1055
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81868c4d)
Location: include/linux/skbuff.h:1055
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff818bb2fd)
Location: include/linux/skbuff.h:1055
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff818c126e)
Location: include/linux/skbuff.h:1055
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff818670a0)
Location: include/linux/skbuff.h:1129
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_fragment.c (ffffffff81895a96)
Location: include/linux/skbuff.h:1129
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff818e5769)
Location: include/linux/skbuff.h:1129
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff818e9181)
Location: include/linux/skbuff.h:1129
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8193e313)
Location: include/linux/skbuff.h:1129
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819444a7)
Location: include/linux/skbuff.h:1129
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff818b617e)
Location: include/linux/skbuff.h:1134
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_fragment.c (ffffffff818e9ca9)
Location: include/linux/skbuff.h:1134
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8193c00c)
Location: include/linux/skbuff.h:1134
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8193f6d1)
Location: include/linux/skbuff.h:1134
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff8199724a)
Location: include/linux/skbuff.h:1134
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8199cf68)
Location: include/linux/skbuff.h:1134
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff818db280)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/ipv4/ip_fragment.c (ffffffff81916ebc)
Location: include/linux/skbuff.h:1154
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff8196bd21)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196f46b)
Location: include/linux/skbuff.h:1154
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cdb2f)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rthdr_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d335f)
Location: include/linux/skbuff.h:1154
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff8192861d)
Location: include/linux/skbuff.h:1206
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81943714)
Location: include/linux/skbuff.h:1206
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81978e9f)
Location: include/linux/skbuff.h:1206
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a71)
Location: include/linux/skbuff.h:1206
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819d8b69)
Location: include/linux/skbuff.h:1206
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a3c154)
Location: include/linux/skbuff.h:1206
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a423a2)
Location: include/linux/skbuff.h:1206
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff8195a3ad)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8197870c)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff819af80f)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a095e1)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a0f9c9)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a72dd4)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a79002)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81a2dba4)
Location: include/linux/skbuff.h:1234
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a4d6b5)
Location: include/linux/skbuff.h:1234
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81a99699)
Location: include/linux/skbuff.h:1234
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af8f01)
Location: include/linux/skbuff.h:1234
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b03289)
Location: include/linux/skbuff.h:1234
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6d2c1)
Location: include/linux/skbuff.h:1234
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b76bf2)
Location: include/linux/skbuff.h:1234
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81a2f634)
Location: include/linux/skbuff.h:1251
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_proto_6_to_4
  - net/core/filter.c:bpf_skb_proto_4_to_6
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a5337c)
Location: include/linux/skbuff.h:1251
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81aa3609)
Location: include/linux/skbuff.h:1251
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06ef1)
Location: include/linux/skbuff.h:1251
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81b113e9)
Location: include/linux/skbuff.h:1251
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b7bd69)
Location: include/linux/skbuff.h:1251
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b859c2)
Location: include/linux/skbuff.h:1251
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81a19d27)
Location: include/linux/skbuff.h:1259
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81a38ba9)
Location: include/linux/skbuff.h:1259
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81a8e777)
Location: include/linux/skbuff.h:1259
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af264d)
Location: include/linux/skbuff.h:1259
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81aff018)
Location: include/linux/skbuff.h:1259
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81b6a839)
Location: include/linux/skbuff.h:1259
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81b74672)
Location: include/linux/skbuff.h:1259
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81acae55)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81aeea85)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81b49967)
Location: include/linux/skbuff.h:1272
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2b5d)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81bc21e5)
Location: include/linux/skbuff.h:1272
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81c32699)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81c3ef5c)
Location: include/linux/skbuff.h:1272
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81c47ea5)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81c7193c)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81cd6f8b)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d4632c)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81d5279f)
Location: include/linux/skbuff.h:1579
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81dcfe8e)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81dd9ce5)
Location: include/linux/skbuff.h:1579
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81dfc7b2)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81e29a2c)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81e9752b)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f71f)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f1ca84)
Location: include/linux/skbuff.h:1423
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81fa1211)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81fab947)
Location: include/linux/skbuff.h:1423
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81e6d9a2)
Location: include/linux/skbuff.h:1442
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81e9f06d)
Location: include/linux/skbuff.h:1442
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81ef5d5b)
Location: include/linux/skbuff.h:1442
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f40f)
Location: include/linux/skbuff.h:1442
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81f7c564)
Location: include/linux/skbuff.h:1442
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff82001ab9)
Location: include/linux/skbuff.h:1442
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff8200c0e7)
Location: include/linux/skbuff.h:1442
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff81f2d1e2)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff81f617dd)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff81fb9d0b)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/ip_fragment.c:ip_check_defrag
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035b3f)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff82042c54)
Location: include/linux/skbuff.h:1449
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff820d08bc)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_rpl_srh_rcv
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff820db0b1)
Location: include/linux/skbuff.h:1449
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffff800010bfc2ac)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffff800010c1f350)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffff800010c60044)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffff800010cc2994)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffff800010ccc988)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (ffff800010d3b8d8)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffff800010d45f40)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (c0d16a30)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (c0d36f00)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (c0d6f848)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c0dce18c)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c0dd6fd0)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (c0e3dfcc)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c0e47d78)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (c000000000ce6ec8)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (c000000000d11218)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (c000000000d62e38)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (c000000000dde260)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (c000000000de7480)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (c000000000e6f158)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (c000000000e7b9e0)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffe00077e4d2)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffe000798aa8)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffe0007c80fc)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffe000817e24)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffe00081dd7c)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffe0008781d0)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffe00087ddd8)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff818fa37d)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8191857c)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff8194f67f)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff819a9381)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff819af3f9)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a12464)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a18692)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff818b41ad)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff818d232c)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff8190916f)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81962e41)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff8196ba29)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff819cf224)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff819d5452)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff8194b3ad)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8196970c)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff819b9e4f)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a13c21)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a19c99)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a7cee4)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a83112)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
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
In net/core/filter.c (ffffffff8196ccbd)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_skb_change_proto
  - net/core/filter.c:bpf_set_hash_invalid
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (ffffffff8198baec)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/core/lwt_bpf.c:bpf_lwt_push_ip_encap
```
```
In net/ipv4/ip_fragment.c (ffffffff819c388f)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e601)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
  - net/ipv4/ip_tunnel_core.c:iptunnel_xmit
```
```
In net/ipv4/ipmr.c (ffffffff81a24aa5)
Location: include/linux/skbuff.h:1202
Inline: True
```
```
In net/ipv6/exthdrs.c (ffffffff81a89734)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_srh_rcv
```
```
In net/ipv6/ip6mr.c (ffffffff81a8f9df)
Location: include/linux/skbuff.h:1202
Inline: True
Inline callers:
  - net/ipv6/ip6mr.c:pim6_rcv
```
</details>
</li>
</ul>

## Differences
