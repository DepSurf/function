# Function: <code>csum_shift</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff816194b4)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81a80958)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/dev.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/core/filter.c (ffffffff81acaa3a)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81b4b96f)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81b5a234)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv4/raw.c (ffffffff81b853d9)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81b9236a)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/ip6_input.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv6/raw.c (ffffffff81c1f6c9)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81c2200f)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/checksum.h:83
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81c77917)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81c8098c)
Location: include/net/checksum.h:83
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff816e685e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81bf5405)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81c483ca)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81cd902f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81ce8586)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81d1611f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81d23c7a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv6/raw.c (ffffffff81dbc2bf)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81dbecef)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81e1cb87)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81e25bae)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff817d639b)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81da3935)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81dfd35a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81e9963f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_append_page
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81eabed6)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81edc64f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81eeb20a)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff81f0bae6)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (ffffffff81f8c79f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81f8f27f)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/checksum.h:84
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff81ff4017)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81ffd83e)
Location: include/net/checksum.h:84
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In lib/iov_iter.c (ffffffff81813a8b)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_to_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
  - lib/iov_iter.c:csum_and_copy_from_iter
```
```
In net/core/skbuff.c (ffffffff81e14cd1)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/filter.c (ffffffff81e7326b)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81ef7f3f)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81f0a696)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff81f3b7a6)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff81f4ab2a)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff81f6b6b6)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (ffffffff81fed026)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff81fefa7f)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82070627)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff82079b0e)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
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
In net/core/skbuff.c (ffffffff81ece361)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:csum_and_copy_from_iter_full
  - net/core/skbuff.c:skb_splice_from_iter
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:skb_copy_and_csum_bits
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:__skb_checksum
  - net/core/skbuff.c:pskb_trim_rcsum_slow
```
```
In net/core/datagram.c (ffffffff81edd67e)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
  - net/core/datagram.c:csum_and_copy_to_iter
```
```
In net/core/filter.c (ffffffff81f329eb)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:__bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
  - net/core/filter.c:bpf_skb_store_bytes
```
```
In net/core/lwt_bpf.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/sched/sch_frag.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbbf8f)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_reply_glue_bits
  - net/ipv4/ip_output.c:ip_generic_getfrag
```
```
In net/ipv4/tcp.c (ffffffff81fce695)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/tcp.c:skb_do_copy_data_nocache
```
```
In net/ipv4/raw.c (ffffffff820018c6)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_getfrag
```
```
In net/ipv4/icmp.c (ffffffff82010c3a)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_glue_bits
```
```
In net/ipv4/ping.c (ffffffff8203171a)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_getfrag
```
```
In net/ipv6/raw.c (ffffffff820bac26)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv6/raw.c:raw6_getfrag
```
```
In net/ipv6/icmp.c (ffffffff820bd64f)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/ipv6/icmp.c:icmpv6_getfrag
```
```
In net/ipv6/reassembly.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/xfrm6_input.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/seg6_iptunnel.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/seg6_local.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/ipv6/ioam6_iptunnel.c (0)
Location: include/net/checksum.h:86
Inline: True
```
```
In net/mptcp/protocol.c (ffffffff82144587)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8214ef6e)
Location: include/net/checksum.h:86
Inline: True
Inline callers:
  - net/mptcp/subflow.c:validate_data_csum
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
