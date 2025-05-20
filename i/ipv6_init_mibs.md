# Function: <code>ipv6_init_mibs</code>

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
In net/ipv6/af_inet6.c (ffffffff817c3736)
Location: net/ipv6/af_inet6.c:722
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff818307e6)
Location: net/ipv6/af_inet6.c:736
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff81862276)
Location: net/ipv6/af_inet6.c:748
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff81886a10)
Location: net/ipv6/af_inet6.c:749
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff81907c00)
Location: net/ipv6/af_inet6.c:754
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff8195e814)
Location: net/ipv6/af_inet6.c:780
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff8199337f)
Location: net/ipv6/af_inet6.c:793
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff819fee21)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff81a35a21)
Location: net/ipv6/af_inet6.c:819
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ipv6_init_mibs(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b2a850)
Location: net/ipv6/af_inet6.c:883
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
**Symbols:**

```
ffffffff81b2a850-ffffffff81b2a954: ipv6_init_mibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ipv6_init_mibs(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81b391e0)
Location: net/ipv6/af_inet6.c:880
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
**Symbols:**

```
ffffffff81b391e0-ffffffff81b392e4: ipv6_init_mibs (STB_LOCAL)
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
In net/ipv6/af_inet6.c (ffffffff81b26f82)
Location: net/ipv6/af_inet6.c:884
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In net/ipv6/af_inet6.c (ffffffff81bec9ff)
Location: net/ipv6/af_inet6.c:886
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/af_inet6.c (ffffffff81d84eb8)
Location: net/ipv6/af_inet6.c:897
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_net_init
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
In net/ipv6/af_inet6.c (ffffffff81f52820)
Location: net/ipv6/af_inet6.c:906
Inline: True
Direct callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
**Symbols:**

```
ffffffff81f52820-ffffffff81f5296a: ipv6_init_mibs.constprop.0 (STB_LOCAL)
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
In net/ipv6/af_inet6.c (ffffffff81fb2220)
Location: net/ipv6/af_inet6.c:894
Inline: True
Direct callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
**Symbols:**

```
ffffffff81fb2220-ffffffff81fb236a: ipv6_init_mibs.constprop.0 (STB_LOCAL)
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
In net/ipv6/af_inet6.c (ffffffff8207f970)
Location: net/ipv6/af_inet6.c:903
Inline: True
Direct callers:
  - net/ipv6/af_inet6.c:inet6_net_init
```
**Symbols:**

```
ffffffff8207f970-ffffffff8207faf1: ipv6_init_mibs.constprop.0 (STB_LOCAL)
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
In net/ipv6/af_inet6.c (ffff800010cf5cec)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (c0dfc810)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (c000000000e1c9e4)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (ffffffe000841c6e)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff819d50b1)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff81991e71)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff81a3fb31)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
In net/ipv6/af_inet6.c (ffffffff81a4b671)
Location: net/ipv6/af_inet6.c:819
Inline: True
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
</ul>
