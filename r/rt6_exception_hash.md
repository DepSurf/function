# Function: <code>rt6_exception_hash</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191b720)
Location: net/ipv6/route.c:1185
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff8191b720-ffffffff8191b94a: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81973440)
Location: net/ipv6/route.c:1307
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81973440-ffffffff81973664: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9090)
Location: net/ipv6/route.c:1321
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff819a9090-ffffffff819a92b4: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a15ec0)
Location: net/ipv6/route.c:1471
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81a15ec0-ffffffff81a160e4: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4cb00)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81a4cb00-ffffffff81a4cd24: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4329f)
Location: net/ipv6/route.c:1499
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b5198f)
Location: net/ipv6/route.c:1482
Inline: True
Inline callers:
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3d7e0)
Location: net/ipv6/route.c:1485
Inline: True
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81b3d7e0-ffffffff81b3d8ae: rt6_exception_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04020)
Location: net/ipv6/route.c:1485
Inline: True
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81c04020-ffffffff81c04101: rt6_exception_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9e2c0)
Location: net/ipv6/route.c:1485
Inline: True
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81d9e2c0-ffffffff81d9e3b6: rt6_exception_hash.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81f6d170)
Location: net/ipv6/route.c:1485
Inline: True
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81f6d170-ffffffff81f6d266: rt6_exception_hash.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81fcd290)
Location: net/ipv6/route.c:1484
Inline: True
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81fcd290-ffffffff81fcd386: rt6_exception_hash.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff8209aae0)
Location: net/ipv6/route.c:1486
Inline: True
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff8209aae0-ffffffff8209abd6: rt6_exception_hash.isra.0 (STB_LOCAL)
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
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0fa20)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffff800010d0fa20-ffff800010d0fc9c: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e1708c)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
c0e1708c-c0e172d8: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3d230)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
c000000000e3d230-c000000000e3d540: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000857452)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffe000857452-ffffffe0008577f0: rt6_exception_hash (STB_LOCAL)
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
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ec190)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff819ec190-ffffffff819ec3b4: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a8f50)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff819a8f50-ffffffff819a9174: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a56c10)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81a56c10-ffffffff81a56e34: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 rt6_exception_hash(const struct in6_addr *dst, const struct in6_addr *src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a62cc0)
Location: net/ipv6/route.c:1477
Inline: False
Direct callers:
  - net/ipv6/route.c:__rt6_find_exception_rcu
  - net/ipv6/route.c:__rt6_find_exception_spinlock
```
**Symbols:**

```
ffffffff81a62cc0-ffffffff81a62ee4: rt6_exception_hash (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
