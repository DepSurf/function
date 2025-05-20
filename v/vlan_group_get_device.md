# Function: <code>vlan_group_get_device</code>

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
In net/8021q/vlan_core.c (ffffffff818094b1)
Location: net/8021q/vlan.h:62
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff8187b064)
Location: net/8021q/vlan.h:62
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff818af924)
Location: net/8021q/vlan.h:62
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff818d6115)
Location: net/8021q/vlan.h:62
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff818d63f3-ffffffff818d63f9: vlan_group_get_device.part.12 (STB_LOCAL)
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
In net/8021q/vlan_core.c (ffffffff8195bcbb)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff819b54b4)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff819ec658)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff81a5b7f8)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff81a9242a)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a91c60-ffffffff81a91c62: vlan_group_get_device.part.0 (STB_LOCAL)
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
In net/8021q/vlan_core.c (ffffffff81b8d8da)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff81b9d54a)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff81b8c657)
Location: net/8021q/vlan.h:67
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff81c5897b)
Location: net/8021q/vlan.h:67
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff81dfa063)
Location: net/8021q/vlan.h:67
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff81fce763)
Location: net/8021q/vlan.h:67
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff8204a0b3)
Location: net/8021q/vlan.h:67
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffffffff8211bf73)
Location: net/8021q/vlan.h:67
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (ffff800010d6017c)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
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
In net/8021q/vlan_core.c (c0e5fcb0)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c0e5f66c-c0e5f67c: vlan_group_get_device.part.0 (STB_LOCAL)
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
In net/8021q/vlan_core.c (c000000000e9b100)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:__vlan_find_dev_deep_rcu
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:__vlan_find_dev_deep_rcu
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
c000000000e9a550-c000000000e9a554: vlan_group_get_device.part.0 (STB_LOCAL)
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
In net/8021q/vlan_core.c (ffffffe0008955e2)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffe000894efe-ffffffe000894f06: vlan_group_get_device.part.0 (STB_LOCAL)
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
In net/8021q/vlan_core.c (ffffffff81a31aba)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a312f0-ffffffff81a312f2: vlan_group_get_device.part.0 (STB_LOCAL)
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
In net/8021q/vlan_core.c (ffffffff819eecaa)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff819ee4e0-ffffffff819ee4e2: vlan_group_get_device.part.0 (STB_LOCAL)
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
In net/8021q/vlan_core.c (ffffffff81a9d66a)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81a9cea0-ffffffff81a9cea2: vlan_group_get_device.part.0 (STB_LOCAL)
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
In net/8021q/vlan_core.c (ffffffff81aa986a)
Location: net/8021q/vlan.h:63
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_for_each
  - net/8021q/vlan_core.c:vlan_do_receive
Direct callers:
  - net/8021q/vlan_core.c:vlan_do_receive
```
**Symbols:**

```
ffffffff81aa9090-ffffffff81aa9092: vlan_group_get_device.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
