# Function: <code>inet_addr_type_dev_table</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8179a460)
Location: net/ipv4/fib_frontend.c:267
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8179a460-ffffffff8179a536: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81808330)
Location: net/ipv4/fib_frontend.c:268
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81808330-ffffffff81808403: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81839410)
Location: net/ipv4/fib_frontend.c:260
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/icmp.c:icmp_route_lookup
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81839410-ffffffff818394e3: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8185a950)
Location: net/ipv4/fib_frontend.c:260
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff8185a950-ffffffff8185aa3b: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff818da880)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff818da880-ffffffff818da96b: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81931800)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/netfilter.c:ip_route_me_harder
```
**Symbols:**

```
ffffffff81931800-ffffffff819318ef: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81961060)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81961060-ffffffff8196114f: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819c4d80)
Location: net/ipv4/fib_frontend.c:269
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff819c4d80-ffffffff819c4dbc: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff819fb920)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff819fb920-ffffffff819fb95c: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81aec623)
Location: net/ipv4/fib_frontend.c:260
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81aeb080-ffffffff81aeb0ba: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81af9530)
Location: net/ipv4/fib_frontend.c:260
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81af7f60-ffffffff81af7fa9: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ae4cf0)
Location: net/ipv4/fib_frontend.c:260
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81ae3670-ffffffff81ae36b9: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81ba4620)
Location: net/ipv4/fib_frontend.c:260
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81ba2f70-ffffffff81ba2fb9: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81d36f7f)
Location: net/ipv4/fib_frontend.c:261
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81d35740-ffffffff81d35797: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81eff642)
Location: net/ipv4/fib_frontend.c:261
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81efdce0-ffffffff81efdd37: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81f5f0d9)
Location: net/ipv4/fib_frontend.c:261
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81f5d770-ffffffff81f5d7c7: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff820256a9)
Location: net/ipv4/fib_frontend.c:261
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff82023d30-ffffffff82023d87: inet_addr_type_dev_table (STB_GLOBAL)
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
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffff800010cb3850)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffff800010cb3850-ffff800010cb38ac: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c0dc0054)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
c0dc0054-c0dc01a4: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (c000000000dca4d0)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
c000000000dca4d0-c000000000dca534: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffe00080b4ce)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffe00080b4ce-ffffffe00080b51e: inet_addr_type_dev_table (STB_GLOBAL)
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
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff8199b6c0)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff8199b6c0-ffffffff8199b6fc: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81955180)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81955180-ffffffff819551bc: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a05f60)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81a05f60-ffffffff81a05f9c: inet_addr_type_dev_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int inet_addr_type_dev_table(struct net *net, const struct net_device *dev, __be32 addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_frontend.c (ffffffff81a10580)
Location: net/ipv4/fib_frontend.c:270
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_process
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_solicit
  - net/ipv4/arp.c:arp_constructor
  - net/ipv4/icmp.c:icmp_unreach
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_semantics.c:fib_check_nh_v4_gw
  - net/ipv4/netfilter.c:ip_route_me_harder
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81a10580-ffffffff81a105d3: inet_addr_type_dev_table (STB_GLOBAL)
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
