# Function: <code>rt_cache_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817530f1)
Location: net/ipv4/route.c:438
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81757590-ffffffff817575a2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817bf271)
Location: net/ipv4/route.c:438
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff817c3830-ffffffff817c3842: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817eebc1)
Location: net/ipv4/route.c:438
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff817f3350-ffffffff817f3362: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8180ec81)
Location: net/ipv4/route.c:442
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81810f90-ffffffff81810fa2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188e241)
Location: net/ipv4/route.c:445
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81890570-ffffffff81890582: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e1f5d)
Location: net/ipv4/route.c:428
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff818e3d00-ffffffff818e3d12: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8190edfd)
Location: net/ipv4/route.c:428
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81910be0-ffffffff81910bf2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81970911)
Location: net/ipv4/route.c:425
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff819732d0-ffffffff819732e2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a7311)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff819a9c50-ffffffff819a9c62: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a90661)
Location: net/ipv4/route.c:427
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81a94350-ffffffff81a94362: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9a4d1)
Location: net/ipv4/route.c:427
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81a9e310-ffffffff81a9e322: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a857c1)
Location: net/ipv4/route.c:404
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81a89270-ffffffff81a89282: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b3ff91)
Location: net/ipv4/route.c:405
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81b43da0-ffffffff81b43db2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccc861)
Location: net/ipv4/route.c:398
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81cd08e0-ffffffff81cd08f8: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8c801)
Location: net/ipv4/route.c:398
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81e90ab0-ffffffff81e90ac8: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eeaf51)
Location: net/ipv4/route.c:398
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81eef260-ffffffff81eef278: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81faef71)
Location: net/ipv4/route.c:398
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:replace_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81fb33c0-ffffffff81fb33d8: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5877c)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffff800010c59d48-ffff800010c59d94: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d66768)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
c0d693c4-c0d693fc: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d57db4)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
c000000000d5b6c0-c000000000d5b6e0: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c0f4e)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffe0007c3438-ffffffe0007c3462: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81947181)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff81949ac0-ffffffff81949ad2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81900c71)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff819035b0-ffffffff819035c2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b1951)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff819b4290-ffffffff819b42a2: rt_cache_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rt_cache_flush(struct net *net);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819baff1)
Location: net/ipv4/route.c:426
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_sysctl_rtcache_flush
  - net/ipv4/route.c:ip_rt_multicast_event
Direct callers:
  - net/ipv4/arp.c:arp_netdev_event
  - net/ipv4/devinet.c:ipv4_doint_and_flush
  - net/ipv4/devinet.c:devinet_sysctl_forward
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/devinet.c:devinet_conf_proc
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_netdev_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_inetaddr_event
  - net/ipv4/fib_frontend.c:fib_disable_ip
  - net/ipv4/fib_frontend.c:fib_flush
  - net/ipv4/fib_trie.c:fib_table_delete
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/fib_trie.c:fib_table_insert
  - net/ipv4/nexthop.c:nh_netdev_event
  - net/ipv4/nexthop.c:rtm_new_nexthop
  - net/ipv4/fib_rules.c:fib4_rule_flush_cache
```
**Symbols:**

```
ffffffff819bd990-ffffffff819bd9a2: rt_cache_flush (STB_GLOBAL)
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
