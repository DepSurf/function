# Function: <code>__ip6_del_rt_siblings</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8189ac1f)
Location: net/ipv6/route.c:2162
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff8191bc1c)
Location: net/ipv6/route.c:2859
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff81974472)
Location: net/ipv6/route.c:3198
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff819a9d5d)
Location: net/ipv6/route.c:3178
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff81a1861e)
Location: net/ipv6/route.c:3735
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff81a4f27e)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b45660)
Location: net/ipv6/route.c:3780
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b45660-ffffffff81b458cd: __ip6_del_rt_siblings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b54000)
Location: net/ipv6/route.c:3764
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b54000-ffffffff81b5426d: __ip6_del_rt_siblings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b415d0)
Location: net/ipv6/route.c:3778
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81b415d0-ffffffff81b4183d: __ip6_del_rt_siblings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c09330)
Location: net/ipv6/route.c:3908
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81c09330-ffffffff81c0959d: __ip6_del_rt_siblings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81da3e30)
Location: net/ipv6/route.c:3884
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81da3e30-ffffffff81da40b1: __ip6_del_rt_siblings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f73280)
Location: net/ipv6/route.c:3884
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81f73280-ffffffff81f73501: __ip6_del_rt_siblings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd3370)
Location: net/ipv6/route.c:3882
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81fd3370-ffffffff81fd35f1: __ip6_del_rt_siblings (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __ip6_del_rt_siblings(struct fib6_info *rt, struct fib6_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a0c80)
Location: net/ipv6/route.c:3884
Inline: False
Direct callers:
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff820a0c80-ffffffff820a0f01: __ip6_del_rt_siblings (STB_LOCAL)
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
In net/ipv6/route.c (ffff800010d10a68)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (c0e18d44)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (c000000000e3f8c4)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffe000858146)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff819ee90e)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff819ab6ce)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff81a5938e)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
In net/ipv6/route.c (ffffffff81a655d9)
Location: net/ipv6/route.c:3748
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_del
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
