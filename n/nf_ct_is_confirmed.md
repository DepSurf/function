# Function: <code>nf_ct_is_confirmed</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_conntrack_core.c (ffffffff8199f5b1)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_update
  - net/netfilter/nf_conntrack_core.c:__nf_ct_refresh_acct
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_alter_reply
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:gc_worker
  - net/netfilter/nf_conntrack_core.c:early_drop
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_tuple_taken
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_hash_check_insert
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_find_get
```
```
In net/netfilter/nf_conntrack_standalone.c (ffffffff819a1823)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_standalone.c:ct_seq_show
```
```
In net/netfilter/nf_conntrack_expect.c (ffffffff819a2e07)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_expect.c:nf_ct_find_expectation
```
```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a49dc)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto.c:ipv4_confirm
  - net/netfilter/nf_conntrack_proto.c:nf_confirm
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a626a)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a7060)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
```
In net/netfilter/nf_conntrack_extend.c (ffffffff819a7cc5)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_extend.c:nf_ct_ext_add
```
```
In net/netfilter/nf_conntrack_proto_icmpv6.c (ffffffff819a8862)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_packet
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a8fda)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_deliver_cached_events
  - net/netfilter/nf_conntrack_ecache.c:nf_conntrack_eventmask_report
  - net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819a9c7c)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aac4d)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819abb2b)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
```
```
In net/netfilter/nf_conntrack_netlink.c (ffffffff819b0a7c)
Location: include/net/netfilter/nf_conntrack.h:244
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
  - net/netfilter/nf_conntrack_netlink.c:ctnetlink_dump_table
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
