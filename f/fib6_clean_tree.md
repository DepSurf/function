# Function: <code>fib6_clean_tree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct rt6_info *, void *), bool prune, int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817da2f0)
Location: net/ipv6/ip6_fib.c:1655
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff817da2f0-ffffffff817da358: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct rt6_info *, void *), bool prune, int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81847740)
Location: net/ipv6/ip6_fib.c:1657
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81847740-ffffffff818477a8: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct rt6_info *, void *), bool prune, int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81879580)
Location: net/ipv6/ip6_fib.c:1663
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81879580-ffffffff818795e8: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct rt6_info *, void *), bool prune, int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8189eef0)
Location: net/ipv6/ip6_fib.c:1705
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8189eef0-ffffffff8189ef52: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct rt6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819215d0)
Location: net/ipv6/ip6_fib.c:1949
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff819215d0-ffffffff8192162e: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81979840)
Location: net/ipv6/ip6_fib.c:2004
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81979840-ffffffff8197989e: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819af400)
Location: net/ipv6/ip6_fib.c:2039
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff819af400-ffffffff819af462: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1d620)
Location: net/ipv6/ip6_fib.c:2113
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81a1d620-ffffffff81a1d689: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a54250)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81a54250-ffffffff81a542b9: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4c140)
Location: net/ipv6/ip6_fib.c:2217
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81b4c140-ffffffff81b4c24a: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5ad80)
Location: net/ipv6/ip6_fib.c:2221
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81b5ad80-ffffffff81b5ae8a: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b49000)
Location: net/ipv6/ip6_fib.c:2222
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81b49000-ffffffff81b4910a: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c10310)
Location: net/ipv6/ip6_fib.c:2223
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81c10310-ffffffff81c1041a: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dab530)
Location: net/ipv6/ip6_fib.c:2224
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81dab530-ffffffff81dab651: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7ae80)
Location: net/ipv6/ip6_fib.c:2223
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81f7ae80-ffffffff81f7afa1: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdb080)
Location: net/ipv6/ip6_fib.c:2223
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81fdb080-ffffffff81fdb1a1: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820a8ad0)
Location: net/ipv6/ip6_fib.c:2219
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff820a8ad0-ffffffff820a8bf1: fib6_clean_tree (STB_LOCAL)
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
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d199f8)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffff800010d199f8-ffff800010d19a9c: fib6_clean_tree (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (c0e1e07c)
Location: net/ipv6/ip6_fib.c:2114
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e46240)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
c000000000e46240-c000000000e462d4: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085d256)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffe00085d256-ffffffe00085d2ce: fib6_clean_tree (STB_LOCAL)
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
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f38e0)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff819f38e0-ffffffff819f3949: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b06a0)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff819b06a0-ffffffff819b0709: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5e360)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81a5e360-ffffffff81a5e3c9: fib6_clean_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fib6_clean_tree(struct net *net, struct fib6_node *root, int (*func)(struct fib6_info *, void *), int sernum, void *arg, bool skip_notify);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6a750)
Location: net/ipv6/ip6_fib.c:2114
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:__fib6_clean_all
```
**Symbols:**

```
ffffffff81a6a750-ffffffff81a6a7b9: fib6_clean_tree (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool prune</code>
</li>
<li>
<b>Param reordered. </b>
<code>net, root, func, prune, sernum, arg</code> ➡️ <code>net, root, func, sernum, arg</code>
</li>
</ul>
</details>
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
