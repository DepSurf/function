# Function: <code>inet_select_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8178f4c0)
Location: net/ipv4/devinet.c:1192
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff8178f4c0-ffffffff8178f582: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff817fcd90)
Location: net/ipv4/devinet.c:1196
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff817fcd90-ffffffff817fced3: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8182dcf0)
Location: net/ipv4/devinet.c:1196
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8182dcf0-ffffffff8182de33: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8184f790)
Location: net/ipv4/devinet.c:1231
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8184f790-ffffffff8184f8f2: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818cf3c0)
Location: net/ipv4/devinet.c:1239
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff818cf3c0-ffffffff818cf522: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81925240)
Location: net/ipv4/devinet.c:1246
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81925240-ffffffff819253a1: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81954050)
Location: net/ipv4/devinet.c:1258
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_select_path
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81954050-ffffffff819541b1: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819b8f80)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff819b8f80-ffffffff819b9118: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819efc80)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff819efc80-ffffffff819efe18: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ade0c0)
Location: net/ipv4/devinet.c:1301
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81ade0c0-ffffffff81ade244: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81aeaef0)
Location: net/ipv4/devinet.c:1300
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81aeaef0-ffffffff81aeb07d: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81ad6660)
Location: net/ipv4/devinet.c:1300
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81ad6660-ffffffff81ad67ed: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81b953a0)
Location: net/ipv4/devinet.c:1300
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81b953a0-ffffffff81b9552d: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d27050)
Location: net/ipv4/devinet.c:1304
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81d27050-ffffffff81d271fe: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81eee990)
Location: net/ipv4/devinet.c:1305
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81eee990-ffffffff81eeeb3e: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f4e350)
Location: net/ipv4/devinet.c:1308
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff81f4e350-ffffffff81f4e4fe: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82014480)
Location: net/ipv4/devinet.c:1325
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
  - net/ipv4/fib_semantics.c:fib_result_prefsrc
```
**Symbols:**

```
ffffffff82014480-ffffffff8201463f: inet_select_addr (STB_GLOBAL)
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
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca5aa0)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffff800010ca5aa0-ffff800010ca5c48: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db2474)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
c0db2474-c0db2658: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000db9ae0)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
c000000000db9ae0-c000000000db9d40: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe00080132e)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffe00080132e-ffffffe000801468: inet_select_addr (STB_GLOBAL)
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
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8198fa20)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff8198fa20-ffffffff8198fbb8: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819494e0)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff819494e0-ffffffff81949678: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fa2c0)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff819fa2c0-ffffffff819fa458: inet_select_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
__be32 inet_select_addr(const struct net_device *dev, __be32 dst, int scope);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a045e0)
Location: net/ipv4/devinet.c:1295
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_rt_get_source
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/icmp.c:__icmp_send
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
```
**Symbols:**

```
ffffffff81a045e0-ffffffff81a04787: inet_select_addr (STB_GLOBAL)
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
