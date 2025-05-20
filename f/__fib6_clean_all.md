# Function: <code>__fib6_clean_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817da360)
Location: net/ipv6/ip6_fib.c:1674
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_run_gc
```
**Symbols:**

```
ffffffff817da360-ffffffff817da3f2: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818477b0)
Location: net/ipv6/ip6_fib.c:1676
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
```
**Symbols:**

```
ffffffff818477b0-ffffffff81847842: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818795f0)
Location: net/ipv6/ip6_fib.c:1682
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
```
**Symbols:**

```
ffffffff818795f0-ffffffff81879682: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8189ef60)
Location: net/ipv6/ip6_fib.c:1724
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
```
**Symbols:**

```
ffffffff8189ef60-ffffffff8189eff5: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct rt6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81921630)
Location: net/ipv6/ip6_fib.c:1967
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
```
**Symbols:**

```
ffffffff81921630-ffffffff819216c3: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819798a0)
Location: net/ipv6/ip6_fib.c:2022
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
```
**Symbols:**

```
ffffffff819798a0-ffffffff81979933: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819af470)
Location: net/ipv6/ip6_fib.c:2058
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff819af470-ffffffff819af50e: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1d690)
Location: net/ipv6/ip6_fib.c:2133
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81a1d690-ffffffff81a1d72a: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a542c0)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81a542c0-ffffffff81a54358: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4c250)
Location: net/ipv6/ip6_fib.c:2237
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81b4c250-ffffffff81b4c2e8: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5ae90)
Location: net/ipv6/ip6_fib.c:2241
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81b5ae90-ffffffff81b5af2d: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b49110)
Location: net/ipv6/ip6_fib.c:2242
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81b49110-ffffffff81b491ad: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c10420)
Location: net/ipv6/ip6_fib.c:2243
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81c10420-ffffffff81c104bd: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dab660)
Location: net/ipv6/ip6_fib.c:2244
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81dab660-ffffffff81dab716: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7afc0)
Location: net/ipv6/ip6_fib.c:2243
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81f7afc0-ffffffff81f7b076: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdb1c0)
Location: net/ipv6/ip6_fib.c:2243
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81fdb1c0-ffffffff81fdb276: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820a8c10)
Location: net/ipv6/ip6_fib.c:2239
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff820a8c10-ffffffff820a8cc6: __fib6_clean_all (STB_LOCAL)
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
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d19aa0)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffff800010d19aa0-ffff800010d19bb8: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1e004)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
c0e1e004-c0e1e108: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e462e0)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
c000000000e462e0-c000000000e463d0: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085d2ce)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffe00085d2ce-ffffffe00085d358: __fib6_clean_all (STB_LOCAL)
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
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f3950)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff819f3950-ffffffff819f39e8: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b0710)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff819b0710-ffffffff819b07a8: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5e3d0)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81a5e3d0-ffffffff81a5e468: __fib6_clean_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __fib6_clean_all(struct net *net, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6a970)
Location: net/ipv6/ip6_fib.c:2134
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_run_gc
  - net/ipv6/ip6_fib.c:fib6_flush_trees
  - net/ipv6/ip6_fib.c:fib6_clean_all_skip_notify
```
**Symbols:**

```
ffffffff81a6a970-ffffffff81a6aa12: __fib6_clean_all (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int (*func)(struct rt6_info *, void *)</code> ➡️ <code>int (*func)(struct fib6_info *, void *)</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool skip_notify</code>
</li>
</ul>
</details>
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
