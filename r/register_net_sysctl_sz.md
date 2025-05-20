# Function: <code>register_net_sysctl_sz</code>

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
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl_sz(struct net *net, const char *path, struct ctl_table *table, size_t table_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff82130640)
Location: net/sysctl_net.c:164
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_static_sysctl_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/mptcp/ctrl.c:mptcp_net_init
  - net/mptcp/ctrl.c:mptcp_net_init
```
**Symbols:**

```
ffffffff82130640-ffffffff821306ba: register_net_sysctl_sz (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
