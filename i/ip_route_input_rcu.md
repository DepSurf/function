# Function: <code>ip_route_input_rcu</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818114f0)
Location: net/ipv4/route.c:2084
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff818114f0-ffffffff818122c7: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81890b70)
Location: net/ipv4/route.c:2099
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81890b70-ffffffff818918ec: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e5590)
Location: net/ipv4/route.c:2131
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff818e5590-ffffffff818e5867: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819124d0)
Location: net/ipv4/route.c:2132
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff819124d0-ffffffff8191277c: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81974c10)
Location: net/ipv4/route.c:2259
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81974c10-ffffffff81974ea0: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ab630)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff819ab630-ffffffff819ab8c0: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a95870)
Location: net/ipv4/route.c:2305
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81a95870-ffffffff81a95aff: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9f900)
Location: net/ipv4/route.c:2311
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81a9f900-ffffffff81a9fb66: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8a840)
Location: net/ipv4/route.c:2312
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81a8a840-ffffffff81a8aaa6: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b45730)
Location: net/ipv4/route.c:2431
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81b45730-ffffffff81b4599e: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cd2470)
Location: net/ipv4/route.c:2459
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81cd2470-ffffffff81cd2736: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81e9372a)
Location: net/ipv4/route.c:2436
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81e91470-ffffffff81e916f8: ip_route_input_rcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81ef1ecf)
Location: net/ipv4/route.c:2434
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81eefbf0-ffffffff81eefe7b: ip_route_input_rcu.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb601f)
Location: net/ipv4/route.c:2437
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81fb3d40-ffffffff81fb3fcb: ip_route_input_rcu.part.0 (STB_LOCAL)
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
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5b7a8)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffff800010c5b7a8-ffff800010c5ba3c: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6adb8)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
c0d6adb8-c0d6b050: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5d7e0)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
c000000000d5d7e0-c000000000d5db14: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c4a64)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffe0007c4a64-ffffffe0007c4c60: ip_route_input_rcu (STB_GLOBAL)
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
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194b4a0)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff8194b4a0-ffffffff8194b730: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81904f90)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff81904f90-ffffffff81905220: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b5c70)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff819b5c70-ffffffff819b5f00: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ip_route_input_rcu(struct sk_buff *skb, __be32 daddr, __be32 saddr, u8 tos, struct net_device *dev, struct fib_result *res);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bf430)
Location: net/ipv4/route.c:2263
Inline: True
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff819bf430-ffffffff819bf6c0: ip_route_input_rcu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
