# Function: <code>rt_dst_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81753550)
Location: net/ipv4/route.c:1441
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff81753550-ffffffff8175363b: rt_dst_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817bf4c0)
Location: net/ipv4/route.c:1447
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff817bf4c0-ffffffff817bf5ab: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817eee10)
Location: net/ipv4/route.c:1457
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff817eee10-ffffffff817eeefb: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8180ef00)
Location: net/ipv4/route.c:1490
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff8180ef00-ffffffff8180efd2: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188e4c0)
Location: net/ipv4/route.c:1497
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff8188e4c0-ffffffff8188e592: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e21e0)
Location: net/ipv4/route.c:1570
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff818e21e0-ffffffff818e22a2: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8190f080)
Location: net/ipv4/route.c:1567
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff8190f080-ffffffff8190f142: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81970b50)
Location: net/ipv4/route.c:1618
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81970b50-ffffffff81970c15: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a7550)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819a7550-ffffffff819a7622: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a90800)
Location: net/ipv4/route.c:1625
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a90800-ffffffff81a908c6: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9a650)
Location: net/ipv4/route.c:1631
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a9a650-ffffffff81a9a716: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a859e0)
Location: net/ipv4/route.c:1619
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81a859e0-ffffffff81a85aa1: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b401e0)
Location: net/ipv4/route.c:1615
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81b401e0-ffffffff81b402a1: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81cccbd0)
Location: net/ipv4/route.c:1628
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81cccbd0-ffffffff81ccccaf: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8cbd0)
Location: net/ipv4/route.c:1627
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81e8cbd0-ffffffff81e8cca3: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eeb300)
Location: net/ipv4/route.c:1627
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81eeb300-ffffffff81eeb3cd: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool noxfrm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81faf320)
Location: net/ipv4/route.c:1629
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__mkroute_input
```
**Symbols:**

```
ffffffff81faf320-ffffffff81faf3df: rt_dst_alloc (STB_GLOBAL)
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
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c570f8)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffff800010c570f8-ffff800010c571d8: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6684c)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c0d6684c-c0d66914: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d58070)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
c000000000d58070-c000000000d58188: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c1120)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffe0007c1120-ffffffe0007c11d6: rt_dst_alloc (STB_GLOBAL)
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
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819473c0)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819473c0-ffffffff81947492: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81900eb0)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff81900eb0-ffffffff81900f82: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b1b90)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819b1b90-ffffffff819b1c62: rt_dst_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rtable *rt_dst_alloc(struct net_device *dev, unsigned int flags, u16 type, bool nopolicy, bool noxfrm, bool will_cache);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bb230)
Location: net/ipv4/route.c:1621
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
```
**Symbols:**

```
ffffffff819bb230-ffffffff819bb302: rt_dst_alloc (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool will_cache</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool nopolicy</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, flags, type, nopolicy, noxfrm</code> ➡️ <code>dev, flags, type, noxfrm</code>
</li>
</ul>
</details>
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
