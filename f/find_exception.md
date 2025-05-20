# Function: <code>find_exception</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh *nh, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81754e90)
Location: net/ipv4/route.c:1252
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff81754e90-ffffffff81754f83: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh *nh, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817c1010)
Location: net/ipv4/route.c:1258
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
**Symbols:**

```
ffffffff817c1010-ffffffff817c1103: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh *nh, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff817f0610)
Location: net/ipv4/route.c:1268
Inline: False
Direct callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
```
**Symbols:**

```
ffffffff817f0610-ffffffff817f0703: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh *nh, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81810a50)
Location: net/ipv4/route.c:1282
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff81810a50-ffffffff81810b58: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh *nh, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8188fed0)
Location: net/ipv4/route.c:1289
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
**Symbols:**

```
ffffffff8188fed0-ffffffff8188ffd4: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh *nh, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff818e2e10)
Location: net/ipv4/route.c:1319
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff818e2e10-ffffffff818e305f: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh *nh, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff8190fcb0)
Location: net/ipv4/route.c:1322
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff8190fcb0-ffffffff8190ff07: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819722b0)
Location: net/ipv4/route.c:1359
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff819722b0-ffffffff819724e2: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819a8c20)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff819a8c20-ffffffff819a8e52: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a934e0)
Location: net/ipv4/route.c:1365
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81a934e0-ffffffff81a93758: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a9d390)
Location: net/ipv4/route.c:1371
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81a9d390-ffffffff81a9d608: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81a88150)
Location: net/ipv4/route.c:1359
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81a88150-ffffffff81a88257: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81b42bf0)
Location: net/ipv4/route.c:1355
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81b42bf0-ffffffff81b42cf7: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81ccf630)
Location: net/ipv4/route.c:1362
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81ccf630-ffffffff81ccf757: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81e8f830)
Location: net/ipv4/route.c:1362
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81e8f830-ffffffff81e8f957: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81eedf30)
Location: net/ipv4/route.c:1362
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81eedf30-ffffffff81eee055: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81fb2090)
Location: net/ipv4/route.c:1364
Inline: False
Direct callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:__mkroute_input
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81fb2090-ffffffff81fb21b5: find_exception (STB_LOCAL)
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
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffff800010c59828)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffff800010c59828-ffff800010c59b48: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c0d6811c)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
c0d6811c-c0d683ac: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (c000000000d5a120)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
c000000000d5a120-c000000000d5a488: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffe0007c24a4)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffe0007c24a4-ffffffe0007c2738: find_exception (STB_LOCAL)
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
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81948a90)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81948a90-ffffffff81948cc2: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff81902580)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff81902580-ffffffff819027b2: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819b3260)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff819b3260-ffffffff819b3492: find_exception (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fib_nh_exception *find_exception(struct fib_nh_common *nhc, __be32 daddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/route.c (ffffffff819bc930)
Location: net/ipv4/route.c:1361
Inline: False
Direct callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mtu_from_fib_result
```
**Symbols:**

```
ffffffff819bc930-ffffffff819bcb62: find_exception (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fib_nh_common *nhc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct fib_nh *nh</code>
</li>
</ul>
</details>
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
