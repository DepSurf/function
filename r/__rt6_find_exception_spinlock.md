# Function: <code>__rt6_find_exception_spinlock</code>

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
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191bfd0)
Location: net/ipv6/route.c:1207
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff8191bfd0-ffffffff8191c08f: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819737b0)
Location: net/ipv6/route.c:1329
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff819737b0-ffffffff8197386c: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a9400)
Location: net/ipv6/route.c:1343
Inline: False
Direct callers:
  - net/ipv6/route.c:rt6_remove_exception_rt
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff819a9400-ffffffff819a94bc: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a16350)
Location: net/ipv6/route.c:1493
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a16350-ffffffff81a16408: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a4cf90)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a4cf90-ffffffff81a4d04c: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b43260)
Location: net/ipv6/route.c:1521
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
```
**Symbols:**

```
ffffffff81b43260-ffffffff81b434d2: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b51950)
Location: net/ipv6/route.c:1504
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
```
**Symbols:**

```
ffffffff81b51950-ffffffff81b51bc2: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3d8b0)
Location: net/ipv6/route.c:1514
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81b3d8b0-ffffffff81b3d967: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c04110)
Location: net/ipv6/route.c:1514
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81c04110-ffffffff81c041c7: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9e3c0)
Location: net/ipv6/route.c:1514
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81d9e3c0-ffffffff81d9e4ad: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6d280)
Location: net/ipv6/route.c:1514
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81f6d280-ffffffff81f6d36d: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcd3a0)
Location: net/ipv6/route.c:1513
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81fcd3a0-ffffffff81fcd490: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209abf0)
Location: net/ipv6/route.c:1515
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff8209abf0-ffffffff8209ace0: __rt6_find_exception_spinlock (STB_LOCAL)
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
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0ff78)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffff800010d0ff78-ffff800010d10048: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e17914)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
c0e17914-c0e17a28: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e3dc40)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
c000000000e3dc40-c000000000e3dd58: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000857cb4)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffe000857cb4-ffffffe000857d90: __rt6_find_exception_spinlock (STB_LOCAL)
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
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819ec620)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff819ec620-ffffffff819ec6dc: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a93e0)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff819a93e0-ffffffff819a949c: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a570a0)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a570a0-ffffffff81a5715c: __rt6_find_exception_spinlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rt6_exception *__rt6_find_exception_spinlock(struct rt6_exception_bucket **bucket, const struct in6_addr *daddr, const struct in6_addr *saddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a63150)
Location: net/ipv6/route.c:1499
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_nh_remove_exception
  - net/ipv6/route.c:rt6_insert_exception
```
**Symbols:**

```
ffffffff81a63150-ffffffff81a6320c: __rt6_find_exception_spinlock (STB_LOCAL)
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
