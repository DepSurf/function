# Function: <code>ipv6_push_rthdr0</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818941e5)
Location: net/ipv6/exthdrs.c:842
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff818bb6a7)
Location: net/ipv6/exthdrs.c:842
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff8193e728)
Location: net/ipv6/exthdrs.c:883
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff8199766c)
Location: net/ipv6/exthdrs.c:870
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff819cdf3c)
Location: net/ipv6/exthdrs.c:870
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a3cb4f)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a737cf)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81b6c120)
Location: net/ipv6/exthdrs.c:1063
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b6c120-ffffffff81b6c1d5: ipv6_push_rthdr0.constprop.0 (STB_LOCAL)
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
In net/ipv6/exthdrs.c (ffffffff81b7ab90)
Location: net/ipv6/exthdrs.c:1058
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81b7ab90-ffffffff81b7ac45: ipv6_push_rthdr0.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81b6b0e9)
Location: net/ipv6/exthdrs.c:1058
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c32f49)
Location: net/ipv6/exthdrs.c:1106
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81dcedb0)
Location: net/ipv6/exthdrs.c:1107
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81dcedb0-ffffffff81dcee7c: ipv6_push_rthdr0.constprop.0 (STB_LOCAL)
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
In net/ipv6/exthdrs.c (ffffffff81fa0100)
Location: net/ipv6/exthdrs.c:1107
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff81fa0100-ffffffff81fa01cc: ipv6_push_rthdr0.constprop.0 (STB_LOCAL)
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
In net/ipv6/exthdrs.c (ffffffff82000be0)
Location: net/ipv6/exthdrs.c:1074
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff82000be0-ffffffff82000c87: ipv6_push_rthdr0.isra.0 (STB_LOCAL)
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
In net/ipv6/exthdrs.c (ffffffff820cfa20)
Location: net/ipv6/exthdrs.c:1079
Inline: True
Direct callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
**Symbols:**

```
ffffffff820cfa20-ffffffff820cfac7: ipv6_push_rthdr0.isra.0 (STB_LOCAL)
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
In net/ipv6/exthdrs.c (ffff800010d3c280)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (c0e3f488)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (c000000000e6feb0)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffe000878c98)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a12e5f)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff819cfc1f)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a7d8df)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
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
In net/ipv6/exthdrs.c (ffffffff81a8a12f)
Location: net/ipv6/exthdrs.c:866
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ipv6_push_nfrag_opts
```
</details>
</li>
</ul>

## Differences
