# Function: <code>nf_sockopt_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nf_sockopt_ops *nf_sockopt_find(struct sock *sk, u_int8_t pf, int val, int get);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/nf_sockopt.c (ffffffff81752be0)
Location: net/netfilter/nf_sockopt.c:61
Inline: False
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
```
**Symbols:**

```
ffffffff81752be0-ffffffff81752c89: nf_sockopt_find (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netfilter/nf_sockopt.c (ffffffff817becf0)
Location: net/netfilter/nf_sockopt.c:61
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff817becf0-ffffffff817bed99: nf_sockopt_find.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netfilter/nf_sockopt.c (ffffffff817ee5e0)
Location: net/netfilter/nf_sockopt.c:61
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff817ee5e0-ffffffff817ee689: nf_sockopt_find.constprop.2 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff8180e6d0)
Location: net/netfilter/nf_sockopt.c:61
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff8180e6d0-ffffffff8180e779: nf_sockopt_find.constprop.2 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff8188dc90)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff8188dc90-ffffffff8188dd39: nf_sockopt_find.constprop.2 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff818e1980)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff818e1980-ffffffff818e1a29: nf_sockopt_find.constprop.3 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff8190e510)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff8190e510-ffffffff8190e5b9: nf_sockopt_find.constprop.3 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81970080)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81970080-ffffffff81970131: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff819a6a70)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff819a6a70-ffffffff819a6b21: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81a8fdc0)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81a8fdc0-ffffffff81a8fe71: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81a99db0)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81a99db0-ffffffff81a99e61: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81a850c0)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81a850c0-ffffffff81a85171: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81b3f7b0)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81b3f7b0-ffffffff81b3f861: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81ccbf40)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81ccbf40-ffffffff81ccbff3: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81e8bde0)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81e8bde0-ffffffff81e8be93: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81ee9e60)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81ee9e60-ffffffff81ee9f13: nf_sockopt_find.isra.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81fadc10)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81fadc10-ffffffff81fadcc3: nf_sockopt_find.isra.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffff800010c56380)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffff800010c56380-ffff800010c56468: nf_sockopt_find.isra.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (c0d65d84)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
c0d65d84-c0d65e58: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (c000000000d56d30)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
c000000000d56d30-c000000000d56e7c: nf_sockopt_find.isra.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffe0007c05da)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffe0007c05da-ffffffe0007c068e: nf_sockopt_find.isra.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff819468e0)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff819468e0-ffffffff81946991: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff819003d0)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff819003d0-ffffffff81900481: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff81997a70)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff81997a70-ffffffff81997b21: nf_sockopt_find.constprop.0 (STB_LOCAL)
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
In net/netfilter/nf_sockopt.c (ffffffff819ba750)
Location: net/netfilter/nf_sockopt.c:62
Inline: True
Direct callers:
  - net/netfilter/nf_sockopt.c:compat_nf_getsockopt
  - net/netfilter/nf_sockopt.c:compat_nf_setsockopt
  - net/netfilter/nf_sockopt.c:nf_getsockopt
  - net/netfilter/nf_sockopt.c:nf_setsockopt
```
**Symbols:**

```
ffffffff819ba750-ffffffff819ba801: nf_sockopt_find.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
