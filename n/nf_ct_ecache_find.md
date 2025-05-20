# Function: <code>nf_ct_ecache_find</code>

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
In net/netfilter/nf_conntrack_core.c (ffffffff8199fcab)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
  - net/netfilter/nf_conntrack_core.c:__nf_conntrack_confirm
```
```
In net/netfilter/nf_conntrack_proto_tcp.c (ffffffff819a6457)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
```
```
In net/netfilter/nf_conntrack_proto_udp.c (ffffffff819a72ea)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
```
```
In net/netfilter/nf_conntrack_ecache.c (ffffffff819a944e)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_expect_event_report
  - net/netfilter/nf_conntrack_ecache.c:nf_ct_deliver_cached_events
  - net/netfilter/nf_conntrack_ecache.c:nf_conntrack_eventmask_report
  - net/netfilter/nf_conntrack_ecache.c:ecache_work_evict_list
```
```
In net/netfilter/nf_conntrack_labels.c (ffffffff819a9683)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_labels.c:nf_connlabels_replace
```
```
In net/netfilter/nf_conntrack_proto_dccp.c (ffffffff819aa013)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
```
```
In net/netfilter/nf_conntrack_proto_sctp.c (ffffffff819aafb8)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
```
```
In net/netfilter/nf_conntrack_proto_gre.c (ffffffff819abbe7)
Location: include/net/netfilter/nf_conntrack_ecache.h:32
Inline: True
Inline callers:
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
