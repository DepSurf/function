# Function: <code>ip6_list_rcv_finish</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_input.c (ffffffff819995f6)
Location: net/ipv6/ip6_input.c:87
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff81a0553b)
Location: net/ipv6/ip6_input.c:87
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff81a3c10f)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff81b315b0)
Location: net/ipv6/ip6_input.c:105
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81b315b0-ffffffff81b317c6: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
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
In net/ipv6/ip6_input.c (ffffffff81b401a0)
Location: net/ipv6/ip6_input.c:105
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81b401a0-ffffffff81b403b6: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
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
In net/ipv6/ip6_input.c (ffffffff81b2e7b0)
Location: net/ipv6/ip6_input.c:105
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81b2e7b0-ffffffff81b2e9c4: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
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
In net/ipv6/ip6_input.c (0)
Location: net/ipv6/ip6_input.c:105
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81bf4ac0-ffffffff81bf4cff: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
ffffffff81d3f685-ffffffff81d3f6a1: ip6_list_rcv_finish.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_input.c (0)
Location: net/ipv6/ip6_input.c:108
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81d8d8b0-ffffffff81d8db08: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
ffffffff81f0c033-ffffffff81f0c050: ip6_list_rcv_finish.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_input.c (0)
Location: net/ipv6/ip6_input.c:108
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81f5b9e0-ffffffff81f5bc38: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
ffffffff820b3868-ffffffff820b3885: ip6_list_rcv_finish.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_input.c (0)
Location: net/ipv6/ip6_input.c:108
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff81fbb7a0-ffffffff81fbb9f3: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
ffffffff82134961-ffffffff8213497e: ip6_list_rcv_finish.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_input.c (0)
Location: net/ipv6/ip6_input.c:109
Inline: True
Direct callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
**Symbols:**

```
ffffffff82088bd0-ffffffff82088e2a: ip6_list_rcv_finish.constprop.0 (STB_LOCAL)
ffffffff8221641e-ffffffff8221643b: ip6_list_rcv_finish.constprop.0.cold (STB_LOCAL)
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
In net/ipv6/ip6_input.c (ffff800010cfcf14)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (c0e04c60)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (c000000000e253a8)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffe000847a6e)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff819db79f)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff8199855f)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff81a4621f)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
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
In net/ipv6/ip6_input.c (ffffffff81a51f1d)
Location: net/ipv6/ip6_input.c:89
Inline: True
Inline callers:
  - net/ipv6/ip6_input.c:ip6_sublist_rcv
```
</details>
</li>
</ul>

## Differences
