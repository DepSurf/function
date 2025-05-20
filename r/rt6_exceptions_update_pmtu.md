# Function: <code>rt6_exceptions_update_pmtu</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/route.c (ffffffff8191a4fe)
Location: net/ipv6/route.c:1538
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
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
In net/ipv6/route.c (ffffffff81972b2d)
Location: net/ipv6/route.c:1677
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
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
In net/ipv6/route.c (ffffffff819a84cd)
Location: net/ipv6/route.c:1668
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_mtu_change_route
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
In net/ipv6/route.c (ffffffff81a148b1)
Location: net/ipv6/route.c:1986
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (ffffffff81a4b4a1)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (ffffffff81b41490)
Location: net/ipv6/route.c:2014
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff81b41490-ffffffff81b4157c: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81b4ff50)
Location: net/ipv6/route.c:1997
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff81b4ff50-ffffffff81b5003c: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81b3ddf0)
Location: net/ipv6/route.c:2007
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff81b3ddf0-ffffffff81b3df34: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81c04440)
Location: net/ipv6/route.c:2010
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff81c04440-ffffffff81c0460b: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81d9ebe0)
Location: net/ipv6/route.c:2010
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff81d9ebe0-ffffffff81d9edd1: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81f6dbb0)
Location: net/ipv6/route.c:2010
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff81f6dbb0-ffffffff81f6dda1: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff81fcdc60)
Location: net/ipv6/route.c:2009
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff81fcdc60-ffffffff81fcde5f: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffffffff8209b4b0)
Location: net/ipv6/route.c:2011
Inline: True
Direct callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
**Symbols:**

```
ffffffff8209b4b0-ffffffff8209b6af: rt6_exceptions_update_pmtu.isra.0 (STB_LOCAL)
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
In net/ipv6/route.c (ffff800010d11a10)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (c0e14e34)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (c000000000e3b51c)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (ffffffe0008563fa)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (ffffffff819eab31)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (ffffffff819a78f1)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (ffffffff81a555b1)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
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
In net/ipv6/route.c (ffffffff81a615b1)
Location: net/ipv6/route.c:1992
Inline: True
Inline callers:
  - net/ipv6/route.c:fib6_nh_mtu_change
```
</details>
</li>
</ul>

## Differences
