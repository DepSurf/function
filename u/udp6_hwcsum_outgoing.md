# Function: <code>udp6_hwcsum_outgoing</code>

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
In net/ipv6/udp.c (ffffffff817e1d38)
Location: net/ipv6/udp.c:989
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff818501a8)
Location: net/ipv6/udp.c:895
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff81881fa8)
Location: net/ipv6/udp.c:881
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff818a87b6)
Location: net/ipv6/udp.c:992
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff8192b266)
Location: net/ipv6/udp.c:996
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff81983419)
Location: net/ipv6/udp.c:992
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
In net/ipv6/udp.c (ffffffff819b991f)
Location: net/ipv6/udp.c:1072
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
In net/ipv6/udp.c (ffffffff81a2855a)
Location: net/ipv6/udp.c:1061
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
In net/ipv6/udp.c (ffffffff81a5efcd)
Location: net/ipv6/udp.c:1061
Inline: True
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
In net/ipv6/udp.c (ffffffff81b57700)
Location: net/ipv6/udp.c:1066
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
**Symbols:**

```
ffffffff81b57700-ffffffff81b577f8: udp6_hwcsum_outgoing.constprop.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81b65c10)
Location: net/ipv6/udp.c:1123
Inline: True
Direct callers:
  - net/ipv6/udp.c:udp_v6_send_skb
```
**Symbols:**

```
ffffffff81b65c10-ffffffff81b65d08: udp6_hwcsum_outgoing.constprop.0 (STB_LOCAL)
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
In net/ipv6/udp.c (ffffffff81b53f20)
Location: net/ipv6/udp.c:1136
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff81c1d3cf)
Location: net/ipv6/udp.c:1138
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff81db9a20)
Location: net/ipv6/udp.c:1147
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff81f89ab0)
Location: net/ipv6/udp.c:1182
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff81fe935e)
Location: net/ipv6/udp.c:1199
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffffffff820b5e70)
Location: net/ipv6/udp.c:1173
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (ffff800010d24e28)
Location: net/ipv6/udp.c:1061
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
In net/ipv6/udp.c (c0e28390)
Location: net/ipv6/udp.c:1061
Inline: True
Inline callers:
  - net/ipv6/udp.c:udp_v6_send_skb
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
In net/ipv6/udp.c (c000000000e545b8)
Location: net/ipv6/udp.c:1061
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
In net/ipv6/udp.c (ffffffe0008656b4)
Location: net/ipv6/udp.c:1061
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
In net/ipv6/udp.c (ffffffff819fe65d)
Location: net/ipv6/udp.c:1061
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
In net/ipv6/udp.c (ffffffff819bb41d)
Location: net/ipv6/udp.c:1061
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
In net/ipv6/udp.c (ffffffff81a690dd)
Location: net/ipv6/udp.c:1061
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
In net/ipv6/udp.c (ffffffff81a756bd)
Location: net/ipv6/udp.c:1061
Inline: True
```
</details>
</li>
</ul>

## Differences
