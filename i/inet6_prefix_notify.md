# Function: <code>inet6_prefix_notify</code>

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
In net/ipv6/addrconf.c (ffffffff817d0c76)
Location: net/ipv6/addrconf.c:5103
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff8183e421)
Location: net/ipv6/addrconf.c:5361
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff81870031)
Location: net/ipv6/addrconf.c:5413
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff81894e5a)
Location: net/ipv6/addrconf.c:5517
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff819162e1)
Location: net/ipv6/addrconf.c:5523
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff8196d91e)
Location: net/ipv6/addrconf.c:5642
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff819a3480)
Location: net/ipv6/addrconf.c:5836
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff81a0f773)
Location: net/ipv6/addrconf.c:5930
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff81a464b3)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff81b35450)
Location: net/ipv6/addrconf.c:5979
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81b35450-ffffffff81b354fc: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81b43f40)
Location: net/ipv6/addrconf.c:6010
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81b43f40-ffffffff81b43fec: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81b321f0)
Location: net/ipv6/addrconf.c:6038
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81b321f0-ffffffff81b323a9: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81bf8530)
Location: net/ipv6/addrconf.c:6085
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81bf8530-ffffffff81bf86e9: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81d91a00)
Location: net/ipv6/addrconf.c:6104
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81d91a00-ffffffff81d91bec: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81f600e0)
Location: net/ipv6/addrconf.c:6117
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81f600e0-ffffffff81f602cc: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff81fbff10)
Location: net/ipv6/addrconf.c:6123
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff81fbff10-ffffffff81fc00f7: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffffffff8208d3d0)
Location: net/ipv6/addrconf.c:6176
Inline: True
Direct callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
**Symbols:**

```
ffffffff8208d3d0-ffffffff8208d5a3: inet6_prefix_notify.constprop.0 (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffff800010d090e8)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (c0e0f6c4)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (c000000000e336e0)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffe000850ef6)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff819e5b43)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff819a2903)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff81a505c3)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
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
In net/ipv6/addrconf.c (ffffffff81a5c639)
Location: net/ipv6/addrconf.c:5962
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_rcv
```
</details>
</li>
</ul>

## Differences
