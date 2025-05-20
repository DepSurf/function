# Function: <code>nf_ct_l4proto_log_invalid</code>

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
void nf_ct_l4proto_log_invalid(const struct sk_buff *skb, const struct nf_conn *ct, const char *fmt, void (anon));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_conntrack_proto.c (ffffffff819a4c89)
Location: net/netfilter/nf_conntrack_proto.c:74
Inline: False
Direct callers:
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:nf_conntrack_tcp_packet
  - net/netfilter/nf_conntrack_proto_tcp.c:tcp_in_window
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
  - net/netfilter/nf_conntrack_proto_dccp.c:nf_conntrack_dccp_packet
  - net/netfilter/nf_conntrack_proto_dccp.c:dccp_new
```
**Symbols:**

```
ffffffff819a4c89-ffffffff819a4d20: nf_ct_l4proto_log_invalid (STB_GLOBAL)
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
