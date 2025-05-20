# Function: <code>rt6_nlmsg_size</code>

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
In net/ipv6/route.c (ffffffff817d9212)
Location: net/ipv6/route.c:3027
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
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
In net/ipv6/route.c (ffffffff81847162)
Location: net/ipv6/route.c:3091
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
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
In net/ipv6/route.c (ffffffff81878fa2)
Location: net/ipv6/route.c:3160
Inline: True
Inline callers:
  - net/ipv6/route.c:inet6_rt_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81898ac0)
Location: net/ipv6/route.c:3296
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81898ac0-ffffffff81898b10: rt6_nlmsg_size.isra.48 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81919d10)
Location: net/ipv6/route.c:3983
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81919d10-ffffffff81919d60: rt6_nlmsg_size.isra.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff81971a00)
Location: net/ipv6/route.c:4568
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81971a00-ffffffff81971a4d: rt6_nlmsg_size.isra.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/route.c (ffffffff819a7200)
Location: net/ipv6/route.c:4541
Inline: True
Direct callers:
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819a7200-ffffffff819a724d: rt6_nlmsg_size.isra.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a13020)
Location: net/ipv6/route.c:5287
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a13020-ffffffff81a130c0: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a49c10)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a49c10-ffffffff81a49cb0: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b40700)
Location: net/ipv6/route.c:5381
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b40700-ffffffff81b4079f: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b4f1c0)
Location: net/ipv6/route.c:5366
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b4f1c0-ffffffff81b4f25f: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b3cee0)
Location: net/ipv6/route.c:5383
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81b3cee0-ffffffff81b3cf7f: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81c03770)
Location: net/ipv6/route.c:5541
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81c03770-ffffffff81c0380f: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81d9d790)
Location: net/ipv6/route.c:5534
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81d9d790-ffffffff81d9d839: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f6ed70)
Location: net/ipv6/route.c:5534
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81f6ed70-ffffffff81f6ee77: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fcee80)
Location: net/ipv6/route.c:5532
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff81fcee80-ffffffff81fcef87: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8209c6e0)
Location: net/ipv6/route.c:5525
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_info_hw_flags_set
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:__ip6_del_rt_siblings
```
**Symbols:**

```
ffffffff8209c6e0-ffffffff8209c7e7: rt6_nlmsg_size (STB_LOCAL)
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
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffff800010d0cd88)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffff800010d0cd88-ffff800010d0ce48: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c0e13584)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c0e13584-c0e13644: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (c000000000e385a0)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
c000000000e385a0-c000000000e3868c: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffe000854746)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffe000854746-ffffffe0008547cc: rt6_nlmsg_size (STB_LOCAL)
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
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819e92a0)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819e92a0-ffffffff819e9340: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff819a6060)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff819a6060-ffffffff819a6100: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a53d20)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a53d20-ffffffff81a53dc0: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t rt6_nlmsg_size(struct fib6_info *f6i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81a5fd10)
Location: net/ipv6/route.c:5301
Inline: False
Direct callers:
  - net/ipv6/route.c:fib6_rt_update
  - net/ipv6/route.c:inet6_rt_notify
  - net/ipv6/route.c:ip6_route_del
```
**Symbols:**

```
ffffffff81a5fd10-ffffffff81a5fdb0: rt6_nlmsg_size (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
