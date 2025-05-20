# Function: <code>fib6_purge_rt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct rt6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817da1f0)
Location: net/ipv6/ip6_fib.c:705
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_del
```
**Symbols:**

```
ffffffff817da1f0-ffffffff817da26e: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct rt6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81848620)
Location: net/ipv6/ip6_fib.c:707
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81848620-ffffffff8184869e: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct rt6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187a470)
Location: net/ipv6/ip6_fib.c:707
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8187a470-ffffffff8187a4ee: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct rt6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8189fb70)
Location: net/ipv6/ip6_fib.c:736
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8189fb70-ffffffff8189fbf7: fib6_purge_rt (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (ffffffff81923f14)
Location: net/ipv6/ip6_fib.c:845
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81922990-ffffffff81922a27: fib6_purge_rt.part.21 (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (ffffffff8197c29a)
Location: net/ipv6/ip6_fib.c:898
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8197ad10-ffffffff8197ae1d: fib6_purge_rt.part.27 (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (ffffffff819b1f7a)
Location: net/ipv6/ip6_fib.c:932
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819b09e0-ffffffff819b0aed: fib6_purge_rt.part.29 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a1e980)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a1e980-ffffffff81a1eade: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a555e0)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a555e0-ffffffff81a5573e: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b4cee0)
Location: net/ipv6/ip6_fib.c:1022
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b4cee0-ffffffff81b4d0cf: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b5bb60)
Location: net/ipv6/ip6_fib.c:1023
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b5bb60-ffffffff81b5bd57: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81b49d20)
Location: net/ipv6/ip6_fib.c:1024
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81b49d20-ffffffff81b49f13: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81c11080)
Location: net/ipv6/ip6_fib.c:1026
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81c11080-ffffffff81c11273: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81dac4a0)
Location: net/ipv6/ip6_fib.c:1027
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81dac4a0-ffffffff81dac699: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81f7bea0)
Location: net/ipv6/ip6_fib.c:1026
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81f7bea0-ffffffff81f7c099: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81fdc0c0)
Location: net/ipv6/ip6_fib.c:1026
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81fdc0c0-ffffffff81fdc2b9: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff820a9c20)
Location: net/ipv6/ip6_fib.c:1026
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff820a9c20-ffffffff820a9e19: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d19020)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffff800010d19020-ffff800010d19194: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1f654)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c0e1f654-c0e1f7ec: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e47c50)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
c000000000e47c50-c000000000e47e68: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085e3ee)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffe00085e3ee-ffffffe00085e51a: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819f4c70)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819f4c70-ffffffff819f4dce: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff819b1a30)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff819b1a30-ffffffff819b1b8e: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a5f6f0)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a5f6f0-ffffffff81a5f84e: fib6_purge_rt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fib6_purge_rt(struct fib6_info *rt, struct fib6_node *fn, struct net *net);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff81a6bba0)
Location: net/ipv6/ip6_fib.c:971
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_del
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
  - net/ipv6/ip6_fib.c:fib6_add_rt2node
```
**Symbols:**

```
ffffffff81a6bba0-ffffffff81a6bcfe: fib6_purge_rt (STB_LOCAL)
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
