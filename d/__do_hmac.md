# Function: <code>__do_hmac</code>

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
In net/ipv6/seg6_hmac.c (ffffffff818a4aa7)
Location: net/ipv6/seg6_hmac.c:123
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff818cb272)
Location: net/ipv6/seg6_hmac.c:123
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff81950012)
Location: net/ipv6/seg6_hmac.c:124
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff819a9754)
Location: net/ipv6/seg6_hmac.c:124
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff819e0254)
Location: net/ipv6/seg6_hmac.c:125
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff81a4eeb4)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff81a85b44)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff81b80ab0)
Location: net/ipv6/seg6_hmac.c:119
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff81b80ab0-ffffffff81b80c04: __do_hmac.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_hmac.c (ffffffff81b90320)
Location: net/ipv6/seg6_hmac.c:118
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff81b90320-ffffffff81b90474: __do_hmac.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_hmac.c (ffffffff81b7f560)
Location: net/ipv6/seg6_hmac.c:118
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff81b7f560-ffffffff81b7f6b5: __do_hmac.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_hmac.c (ffffffff81c4ae10)
Location: net/ipv6/seg6_hmac.c:118
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff81c4ae10-ffffffff81c4af5c: __do_hmac.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_hmac.c (ffffffff81dea670)
Location: net/ipv6/seg6_hmac.c:118
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff81dea670-ffffffff81dea7b4: __do_hmac.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_hmac.c (ffffffff81fbdeb0)
Location: net/ipv6/seg6_hmac.c:118
Inline: True
Direct callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
**Symbols:**

```
ffffffff81fbdeb0-ffffffff81fbdff4: __do_hmac.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_hmac.c (ffffffff8201ee0d)
Location: net/ipv6/seg6_hmac.c:118
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff820edf3b)
Location: net/ipv6/seg6_hmac.c:118
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffff800010d52130)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (c0e5285c)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (c000000000e8a0b0)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffe00088a162)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff81a251d4)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff819e1f94)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff81a8fc54)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
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
In net/ipv6/seg6_hmac.c (ffffffff81a9ca34)
Location: net/ipv6/seg6_hmac.c:120
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_compute
```
</details>
</li>
</ul>

## Differences
