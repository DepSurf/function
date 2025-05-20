# Function: <code>unregister_net_sysctl_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81816370)
Location: net/sysctl_net.c:114
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff81816370-ffffffff81816380: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81889240)
Location: net/sysctl_net.c:114
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff81889240-ffffffff81889250: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff818bda70)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff818bda70-ffffffff818bda80: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff818e43c0)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff818e43c0-ffffffff818e43d0: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff8196a200)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff8196a200-ffffffff8196a210: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff819c3be0)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff819c3be0-ffffffff819c3bf0: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff819faf90)
Location: net/sysctl_net.c:124
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff819faf90-ffffffff819fafa0: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81a6a620)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff81a6a620-ffffffff81a6a630: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81aa1010)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff81aa1010-ffffffff81aa1020: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81b9c980)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff81b9c980-ffffffff81b9c990: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81bac690)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff81bac690-ffffffff81bac6a0: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81b9b820)
Location: net/sysctl_net.c:173
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff81b9b820-ffffffff81b9b830: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81c68770)
Location: net/sysctl_net.c:173
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_net_exit
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff81c68770-ffffffff81c68780: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81e0b8b0)
Location: net/sysctl_net.c:173
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_net_exit
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff81e0b8b0-ffffffff81e0b8c6: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81fe1510)
Location: net/sysctl_net.c:173
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_net_exit
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff81fe1510-ffffffff81fe1526: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff8205d790)
Location: net/sysctl_net.c:173
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_net_exit
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff8205d790-ffffffff8205d7a6: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff821303c0)
Location: net/sysctl_net.c:183
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_net_exit
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:devinet_init_net
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_exit_net
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/mptcp/ctrl.c:mptcp_net_exit
```
**Symbols:**

```
ffffffff821303c0-ffffffff821303d6: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffff800010d724c0)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffff800010d724c0-ffff800010d724ec: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (c0e6f488)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/devinet.c:__devinet_sysctl_unregister
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/addrconf.c:__addrconf_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
c0e6f488-c0e6f4a4: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (c000000000eb13b0)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/sysctl_net_core.c:sysctl_core_net_exit
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/route.c:sysctl_route_net_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
c000000000eb13b0-c000000000eb13e4: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffe0008a2af0)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffe0008a2af0-ffffffe0008a2b1a: unregister_net_sysctl_table (STB_GLOBAL)
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
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81a403a0)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff81a403a0-ffffffff81a403b0: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff819fcf90)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - drivers/net/vxlan.c:vxlan_cleanup_module
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff819fcf90-ffffffff819fcfa0: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81aac250)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_fini
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_standalone_init
  - net/netfilter/nf_conntrack_standalone.c:nf_conntrack_pernet_exit
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_net_exit
```
**Symbols:**

```
ffffffff81aac250-ffffffff81aac260: unregister_net_sysctl_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_net_sysctl_table(struct ctl_table_header *header);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/sysctl_net.c (ffffffff81ab85c0)
Location: net/sysctl_net.c:125
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_sysctl_unregister
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_exit
  - net/netfilter/nf_log.c:nf_log_net_init
  - net/ipv4/ip_fragment.c:ipv4_frags_exit_net
  - net/ipv4/devinet.c:devinet_exit_net
  - net/ipv4/sysctl_net_ipv4.c:sysctl_ipv4_init
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_exit_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/xfrm4_policy.c:xfrm4_net_exit
  - net/xfrm/xfrm_sysctl.c:xfrm_sysctl_fini
  - net/unix/sysctl_net_unix.c:unix_sysctl_unregister
  - net/ipv6/reassembly.c:ipv6_frag_exit
  - net/ipv6/reassembly.c:ipv6_frag_init
  - net/ipv6/reassembly.c:ipv6_frags_exit_net
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_unregister
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_register
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_exit
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/sysctl_net_ipv6.c:ipv6_sysctl_net_init
  - net/ipv6/xfrm6_policy.c:xfrm6_net_exit
```
**Symbols:**

```
ffffffff81ab85c0-ffffffff81ab85d0: unregister_net_sysctl_table (STB_GLOBAL)
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
