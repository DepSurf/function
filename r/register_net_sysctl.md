# Function: <code>register_net_sysctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff818163d0)
Location: net/sysctl_net.c:107
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/route.c:ip_static_sysctl_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff818163d0-ffffffff818163e7: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff818892a0)
Location: net/sysctl_net.c:107
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
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff818892a0-ffffffff818892b7: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff818bdb20)
Location: net/sysctl_net.c:118
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:ip_static_sysctl_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/route.c:sysctl_route_net_init
  - net/ipv4/ip_fragment.c:ipfrag_init
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff818bdb20-ffffffff818bdb37: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff818e4470)
Location: net/sysctl_net.c:117
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
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff818e4470-ffffffff818e4487: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff8196a2b0)
Location: net/sysctl_net.c:117
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
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff8196a2b0-ffffffff8196a2c7: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff819c3c90)
Location: net/sysctl_net.c:117
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
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff819c3c90-ffffffff819c3ca7: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff819fb040)
Location: net/sysctl_net.c:117
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
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/ip_fragment.c:ipv4_frags_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:__devinet_sysctl_register
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/ipv4/xfrm4_policy.c:xfrm4_net_init
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_init
  - net/unix/sysctl_net_unix.c:unix_sysctl_register
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/reassembly.c:ipv6_frags_init_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff819fb040-ffffffff819fb057: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81a6a6d0)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81a6a6d0-ffffffff81a6a6e7: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81aa10c0)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81aa10c0-ffffffff81aa10d7: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81b9ca30)
Location: net/sysctl_net.c:118
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
ffffffff81b9ca30-ffffffff81b9ca47: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81bac740)
Location: net/sysctl_net.c:118
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
ffffffff81bac740-ffffffff81bac757: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81b9b9c0)
Location: net/sysctl_net.c:163
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
ffffffff81b9b9c0-ffffffff81b9b9fe: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81c68900)
Location: net/sysctl_net.c:163
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
ffffffff81c68900-ffffffff81c6893e: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81e0bab0)
Location: net/sysctl_net.c:163
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
ffffffff81e0bab0-ffffffff81e0baf8: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81fe1760)
Location: net/sysctl_net.c:163
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
ffffffff81fe1760-ffffffff81fe17a8: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff8205d9e0)
Location: net/sysctl_net.c:163
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
ffffffff8205d9e0-ffffffff8205da28: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffff800010d725c8)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffff800010d725c8-ffff800010d7260c: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (c0e6f544)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
c0e6f544-c0e6f564: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (c000000000eb1510)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
c000000000eb1510-c000000000eb1548: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffe0008a2bea)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffe0008a2bea-ffffffe0008a2c26: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81a40450)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81a40450-ffffffff81a40467: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff819fd040)
Location: net/sysctl_net.c:118
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_init_module
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff819fd040-ffffffff819fd057: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81aac300)
Location: net/sysctl_net.c:118
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/sysctl_net_core.c:sysctl_core_net_init
  - net/core/neighbour.c:neigh_sysctl_register
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_init
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81aac300-ffffffff81aac317: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ctl_table_header *register_net_sysctl(struct net *net, const char *path, struct ctl_table *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81ab8670)
Location: net/sysctl_net.c:118
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
  - net/ipv6/addrconf.c:__addrconf_sysctl_register
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_init
```
**Symbols:**

```
ffffffff81ab8670-ffffffff81ab8687: register_net_sysctl (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
