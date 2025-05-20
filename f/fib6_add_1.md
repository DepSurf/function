# Function: <code>fib6_add_1</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fib6_node *fib6_add_1(struct fib6_node *root, struct in6_addr *addr, int plen, int offset, int allow_create, int replace_required, int sernum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff817da900)
Location: net/ipv6/ip6_fib.c:461
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff817da900-ffffffff817dacc9: fib6_add_1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fib6_node *fib6_add_1(struct fib6_node *root, struct in6_addr *addr, int plen, int offset, int allow_create, int replace_required, int sernum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff818486a0)
Location: net/ipv6/ip6_fib.c:463
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff818486a0-ffffffff81848a90: fib6_add_1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fib6_node *fib6_add_1(struct fib6_node *root, struct in6_addr *addr, int plen, int offset, int allow_create, int replace_required, int sernum);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8187a4f0)
Location: net/ipv6/ip6_fib.c:463
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8187a4f0-ffffffff8187a8e0: fib6_add_1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fib6_node *fib6_add_1(struct fib6_node *root, struct in6_addr *addr, int plen, int offset, int allow_create, int replace_required, int sernum, struct netlink_ext_ack *extack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffff8189fc00)
Location: net/ipv6/ip6_fib.c:487
Inline: False
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8189fc00-ffffffff818a000c: fib6_add_1 (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (ffffffff81922a30)
Location: net/ipv6/ip6_fib.c:592
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81922a30-ffffffff81922e4a: fib6_add_1.isra.20 (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:658
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff8197ae20-ffffffff8197b1ba: fib6_add_1.isra.25 (STB_LOCAL)
ffffffff8197c643-ffffffff8197c6b7: fib6_add_1.isra.25.cold.36 (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:692
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819b0af0-ffffffff819b0e8a: fib6_add_1.isra.27 (STB_LOCAL)
ffffffff819b2363-ffffffff819b23d7: fib6_add_1.isra.27.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a1ed60-ffffffff81a1f144: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff81a20942-ffffffff81a209ae: fib6_add_1.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a559e0-ffffffff81a55dc4: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff81a57453-ffffffff81a574bf: fib6_add_1.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:736
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b4d770-ffffffff81b4dc36: fib6_add_1.constprop.0 (STB_LOCAL)
ffffffff81b4f5b3-ffffffff81b4f627: fib6_add_1.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:737
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b5c3e0-ffffffff81b5c8a6: fib6_add_1.constprop.0 (STB_LOCAL)
ffffffff81c32d2a-ffffffff81c32d9e: fib6_add_1.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:738
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81b4a5b0-ffffffff81b4aab0: fib6_add_1.constprop.0 (STB_LOCAL)
ffffffff81c2503f-ffffffff81c25099: fib6_add_1.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:740
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81c11910-ffffffff81c11dec: fib6_add_1.constprop.0 (STB_LOCAL)
ffffffff81d40285-ffffffff81d40324: fib6_add_1.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:741
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81dacd90-ffffffff81dad2b2: fib6_add_1.constprop.0 (STB_LOCAL)
ffffffff81f0cc06-ffffffff81f0cca3: fib6_add_1.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:740
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81f7c7c0-ffffffff81f7cd12: fib6_add_1.constprop.0 (STB_LOCAL)
ffffffff820b4235-ffffffff820b4277: fib6_add_1.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:740
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81fdc9e0-ffffffff81fdcf2f: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff82135359-ffffffff8213539b: fib6_add_1.isra.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:740
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff820aa540-ffffffff820aaa8f: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff82216e2a-ffffffff82216e6c: fib6_add_1.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffff800010d19ff0)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffff800010d19ff0-ffff800010d1a444: fib6_add_1.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (c0e1f910)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
c0e1f910-c0e1fd20: fib6_add_1.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (c000000000e47e70)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
c000000000e47e70-c000000000e4848c: fib6_add_1.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (ffffffe00085e816)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffe00085e816-ffffffe00085ec34: fib6_add_1.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819f5070-ffffffff819f5454: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff819f6ae3-ffffffff819f6b4f: fib6_add_1.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff819b1e30-ffffffff819b2214: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff819b38a3-ffffffff819b390f: fib6_add_1.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a5faf0-ffffffff81a5fed4: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff81a61563-ffffffff81a615cf: fib6_add_1.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/ip6_fib.c (0)
Location: net/ipv6/ip6_fib.c:685
Inline: True
Direct callers:
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
  - net/ipv6/ip6_fib.c:fib6_add
```
**Symbols:**

```
ffffffff81a6bfa0-ffffffff81a6c384: fib6_add_1.isra.0 (STB_LOCAL)
ffffffff81a6da23-ffffffff81a6da8f: fib6_add_1.isra.0.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct netlink_ext_ack *extack</code>
</li>
</ul>
</details>
</li>
</ul>
