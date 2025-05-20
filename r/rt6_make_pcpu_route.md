# Function: <code>rt6_make_pcpu_route</code>

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
In net/ipv6/route.c (ffffffff817d5c7b)
Location: net/ipv6/route.c:1002
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
In net/ipv6/route.c (ffffffff818441db)
Location: net/ipv6/route.c:1007
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81875f4b)
Location: net/ipv6/route.c:1010
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff8189b526)
Location: net/ipv6/route.c:1032
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff8191e0b8)
Location: net/ipv6/route.c:1122
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81976664)
Location: net/ipv6/route.c:1247
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff819ac244)
Location: net/ipv6/route.c:1250
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81a19cdf)
Location: net/ipv6/route.c:1398
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81a5094f)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b47d91)
Location: net/ipv6/route.c:1426
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81b56953)
Location: net/ipv6/route.c:1409
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81b42f70)
Location: net/ipv6/route.c:1412
Inline: True
Direct callers:
  - net/ipv6/route.c:ip6_pol_route
```
**Symbols:**

```
ffffffff81b42f70-ffffffff81b43120: rt6_make_pcpu_route.constprop.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81c0b48f)
Location: net/ipv6/route.c:1412
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81da62e9)
Location: net/ipv6/route.c:1412
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81f75859)
Location: net/ipv6/route.c:1412
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff81fd5902)
Location: net/ipv6/route.c:1411
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff820a3262)
Location: net/ipv6/route.c:1413
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffff800010d14890)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (c0e1a4f0)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (c000000000e415d0)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffe00085a090)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff819effdf)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff819acd9f)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81a5aa5f)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
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
In net/ipv6/route.c (ffffffff81a66cfe)
Location: net/ipv6/route.c:1404
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_pol_route
```
</details>
</li>
</ul>

## Differences
