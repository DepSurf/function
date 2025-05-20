# Function: <code>__mkroute_output</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8175638e)
Location: net/ipv4/route.c:2001
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c259b)
Location: net/ipv4/route.c:2008
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f0c4b)
Location: net/ipv4/route.c:2047
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818123ed)
Location: net/ipv4/route.c:2134
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81891a0d)
Location: net/ipv4/route.c:2149
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e5966)
Location: net/ipv4/route.c:2181
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81912876)
Location: net/ipv4/route.c:2183
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81974f8c)
Location: net/ipv4/route.c:2310
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819ab9ac)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a93b70)
Location: net/ipv4/route.c:2356
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81a93b70-ffffffff81a9403a: __mkroute_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9da20)
Location: net/ipv4/route.c:2362
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81a9da20-ffffffff81a9df8d: __mkroute_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a889b0)
Location: net/ipv4/route.c:2363
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81a889b0-ffffffff81a88ed7: __mkroute_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b43120)
Location: net/ipv4/route.c:2482
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81b43120-ffffffff81b43647: __mkroute_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccfbb0)
Location: net/ipv4/route.c:2510
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81ccfbb0-ffffffff81cd0131: __mkroute_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8fdd0)
Location: net/ipv4/route.c:2502
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81e8fdd0-ffffffff81e902c6: __mkroute_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eee4e0)
Location: net/ipv4/route.c:2500
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81eee4e0-ffffffff81eeea40: __mkroute_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rtable *__mkroute_output(const struct fib_result *res, const struct flowi4 *fl4, int orig_oif, struct net_device *dev_out, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb2640)
Location: net/ipv4/route.c:2503
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81fb2640-ffffffff81fb2ba0: __mkroute_output (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c5bb64)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6b194)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5dd04)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c4d34)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8194b81c)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8190530c)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b5fec)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bf7ec)
Location: net/ipv4/route.c:2314
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
