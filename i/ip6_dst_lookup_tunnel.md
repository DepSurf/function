# Function: <code>ip6_dst_lookup_tunnel</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, struct socket *sock, struct in6_addr *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b2cb80)
Location: net/ipv6/ip6_output.c:1216
Inline: False
```
**Symbols:**

```
ffffffff81b2cb80-ffffffff81b2cd57: ip6_dst_lookup_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, struct socket *sock, struct in6_addr *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b3b590)
Location: net/ipv6/ip6_output.c:1255
Inline: False
```
**Symbols:**

```
ffffffff81b3b590-ffffffff81b3b767: ip6_dst_lookup_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, struct socket *sock, struct in6_addr *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81b28d10)
Location: net/ipv6/ip6_output.c:1286
Inline: False
```
**Symbols:**

```
ffffffff81b28d10-ffffffff81b28ee7: ip6_dst_lookup_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, struct socket *sock, struct in6_addr *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81beebc0)
Location: net/ipv6/ip6_output.c:1265
Inline: False
```
**Symbols:**

```
ffffffff81beebc0-ffffffff81beed91: ip6_dst_lookup_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, struct socket *sock, struct in6_addr *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81d87260)
Location: net/ipv6/ip6_output.c:1287
Inline: False
```
**Symbols:**

```
ffffffff81d87260-ffffffff81d8745e: ip6_dst_lookup_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, struct socket *sock, struct in6_addr *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81f54d90)
Location: net/ipv6/ip6_output.c:1305
Inline: False
```
**Symbols:**

```
ffffffff81f54d90-ffffffff81f54f8e: ip6_dst_lookup_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dst_entry *ip6_dst_lookup_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, struct socket *sock, struct in6_addr *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_output.c (ffffffff81fb47a0)
Location: net/ipv6/ip6_output.c:1306
Inline: False
```
**Symbols:**

```
ffffffff81fb47a0-ffffffff81fb499e: ip6_dst_lookup_tunnel (STB_GLOBAL)
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
