# Function: <code>ip_route_output_tunnel</code>

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
struct rtable *ip_route_output_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, __be32 *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a96cd0)
Location: net/ipv4/route.c:2776
Inline: False
```
**Symbols:**

```
ffffffff81a96cd0-ffffffff81a96e45: ip_route_output_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rtable *ip_route_output_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, __be32 *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81aa0dc0)
Location: net/ipv4/route.c:2755
Inline: False
```
**Symbols:**

```
ffffffff81aa0dc0-ffffffff81aa0f38: ip_route_output_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rtable *ip_route_output_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, __be32 *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8bd40)
Location: net/ipv4/route.c:2756
Inline: False
```
**Symbols:**

```
ffffffff81a8bd40-ffffffff81a8bebe: ip_route_output_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rtable *ip_route_output_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, __be32 *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b46cd0)
Location: net/ipv4/route.c:2874
Inline: False
```
**Symbols:**

```
ffffffff81b46cd0-ffffffff81b46e48: ip_route_output_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rtable *ip_route_output_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, __be32 *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd3d60)
Location: net/ipv4/route.c:2898
Inline: False
```
**Symbols:**

```
ffffffff81cd3d60-ffffffff81cd3efa: ip_route_output_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rtable *ip_route_output_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, __be32 *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e93fa0)
Location: net/ipv4/route.c:2889
Inline: False
```
**Symbols:**

```
ffffffff81e93fa0-ffffffff81e9413a: ip_route_output_tunnel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rtable *ip_route_output_tunnel(struct sk_buff *skb, struct net_device *dev, struct net *net, __be32 *saddr, const struct ip_tunnel_info *info, u8 protocol, bool use_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef2750)
Location: net/ipv4/route.c:2885
Inline: False
```
**Symbols:**

```
ffffffff81ef2750-ffffffff81ef28ea: ip_route_output_tunnel (STB_GLOBAL)
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
