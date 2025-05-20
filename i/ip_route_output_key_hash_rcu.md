# Function: <code>ip_route_output_key_hash_rcu</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81812310)
Location: net/ipv4/route.c:2296
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff81812310-ffffffff81812cc6: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81891930)
Location: net/ipv4/route.c:2311
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff81891930-ffffffff81892306: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e58b0)
Location: net/ipv4/route.c:2334
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff818e58b0-ffffffff818e62dc: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819127c0)
Location: net/ipv4/route.c:2336
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff819127c0-ffffffff819131f5: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81974ee0)
Location: net/ipv4/route.c:2463
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff81974ee0-ffffffff81975781: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ab900)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff819ab900-ffffffff819ac19d: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a95b40)
Location: net/ipv4/route.c:2508
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff81a95b40-ffffffff81a95fa0: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9fbc0)
Location: net/ipv4/route.c:2514
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff81a9fbc0-ffffffff81aa0025: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a8ab00)
Location: net/ipv4/route.c:2515
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff81a8ab00-ffffffff81a8af65: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2634
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff81d39fb4-ffffffff81d39fd0: ip_route_output_key_hash_rcu.cold (STB_LOCAL)
ffffffff81b459f0-ffffffff81b45ea7: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2659
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff81f0670b-ffffffff81f06726: ip_route_output_key_hash_rcu.cold (STB_LOCAL)
ffffffff81cd27e0-ffffffff81cd2c48: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2650
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff820ae232-ffffffff820ae24d: ip_route_output_key_hash_rcu.cold (STB_LOCAL)
ffffffff81e92ab0-ffffffff81e92f18: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2648
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff8212f730-ffffffff8212f74b: ip_route_output_key_hash_rcu.cold (STB_LOCAL)
ffffffff81ef1250-ffffffff81ef16b8: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/route.c (0)
Location: net/ipv4/route.c:2651
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_flow
```
**Symbols:**

```
ffffffff822114ed-ffffffff82211508: ip_route_output_key_hash_rcu.cold (STB_LOCAL)
ffffffff81fb53a0-ffffffff81fb5804: ip_route_output_key_hash_rcu (STB_GLOBAL)
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
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5bac8)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffff800010c5bac8-ffff800010c5c234: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6b0b8)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
c0d6b0b8-c0d6b95c: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5db80)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
c000000000d5db80-c000000000d5e5e4: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c4cb0)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffe0007c4cb0-ffffffe0007c52ac: ip_route_output_key_hash_rcu (STB_GLOBAL)
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
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194b770)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff8194b770-ffffffff8194c00d: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81905260)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff81905260-ffffffff81905afd: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b5f40)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff819b5f40-ffffffff819b67dd: ip_route_output_key_hash_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rtable *ip_route_output_key_hash_rcu(struct net *net, struct flowi4 *fl4, struct fib_result *res, const struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bf740)
Location: net/ipv4/route.c:2467
Inline: False
Direct callers:
  - net/ipv4/route.c:inet_rtm_getroute
  - net/ipv4/route.c:ip_route_output_key_hash
```
**Symbols:**

```
ffffffff819bf740-ffffffff819c0019: ip_route_output_key_hash_rcu (STB_GLOBAL)
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
