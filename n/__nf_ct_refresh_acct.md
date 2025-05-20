# Function: <code>__nf_ct_refresh_acct</code>

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
<summary>In <code>gcp</code>: ✅</summary>

```c
void __nf_ct_refresh_acct(struct nf_conn *ct, enum ip_conntrack_info ctinfo, const struct sk_buff *skb, u32 extra_jiffies, bool do_acct);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_conntrack_core.c (ffffffff8199d450)
Location: net/netfilter/nf_conntrack_core.c:1781
Inline: False
Direct callers:
  - net/netfilter/nf_conntrack_core.c:nf_conntrack_in
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udplite_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
  - net/netfilter/nf_conntrack_proto_udp.c:nf_conntrack_udp_packet
  - net/netfilter/nf_conntrack_proto_icmp.c:nf_conntrack_icmp_packet
  - net/netfilter/nf_conntrack_proto_icmpv6.c:nf_conntrack_icmpv6_packet
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
  - net/netfilter/nf_conntrack_proto_sctp.c:nf_conntrack_sctp_packet
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
  - net/netfilter/nf_conntrack_proto_gre.c:nf_conntrack_gre_packet
```
**Symbols:**

```
ffffffff8199d450-ffffffff8199d4c0: __nf_ct_refresh_acct (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Flavor</b>
<ul>
</ul>
