# Function: <code>udp_get_first</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81787420)
Location: net/ipv4/udp.c:2300
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_next
  - net/ipv4/udp.c:udp_get_idx
```
**Symbols:**

```
ffffffff81787420-ffffffff817874c7: udp_get_first.isra.26 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff817f4600)
Location: net/ipv4/udp.c:2231
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff817f4600-ffffffff817f469e: udp_get_first.isra.27 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff818256d0)
Location: net/ipv4/udp.c:2401
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff818256d0-ffffffff8182576e: udp_get_first.isra.27 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff818476f0)
Location: net/ipv4/udp.c:2565
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff818476f0-ffffffff81847795: udp_get_first.isra.44 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff818c7150)
Location: net/ipv4/udp.c:2580
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff818c7150-ffffffff818c71f5: udp_get_first.isra.44 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff8191c590)
Location: net/ipv4/udp.c:2675
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff8191c590-ffffffff8191c64d: udp_get_first.isra.56 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff8194ab30)
Location: net/ipv4/udp.c:2791
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff8194ab30-ffffffff8194abed: udp_get_first.isra.67 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff819af170)
Location: net/ipv4/udp.c:2776
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff819af170-ffffffff819af227: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff819e5e80)
Location: net/ipv4/udp.c:2812
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff819e5e80-ffffffff819e5f37: udp_get_first.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sock *udp_get_first(struct seq_file *seq, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad2500)
Location: net/ipv4/udp.c:2829
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff81ad2500-ffffffff81ad25bc: udp_get_first (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81adecb0)
Location: net/ipv4/udp.c:2860
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
```
**Symbols:**

```
ffffffff81adecb0-ffffffff81aded79: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81ac9ca0)
Location: net/ipv4/udp.c:2931
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff81ac9ca0-ffffffff81ac9d69: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81b88530)
Location: net/ipv4/udp.c:2946
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff81b88530-ffffffff81b885f9: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81d19970)
Location: net/ipv4/udp.c:2961
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff81d19970-ffffffff81d19a40: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81ee0330)
Location: net/ipv4/udp.c:2992
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff81ee0330-ffffffff81ee041e: udp_get_first.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock *udp_get_first(struct seq_file *seq, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3fec0)
Location: net/ipv4/udp.c:2987
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff81f3fec0-ffffffff81f3ffd4: udp_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock *udp_get_first(struct seq_file *seq, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82005e40)
Location: net/ipv4/udp.c:2978
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_seq_next
  - net/ipv4/udp.c:udp_seq_start
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff82005e40-ffffffff82005f54: udp_get_first (STB_LOCAL)
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
In net/ipv4/udp.c (ffff800010c9ab70)
Location: net/ipv4/udp.c:2812
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffff800010c9ab70-ffff800010c9ad08: udp_get_first.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *udp_get_first(struct seq_file *seq, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da7d48)
Location: net/ipv4/udp.c:2812
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
c0da7d48-c0da7e34: udp_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *udp_get_first(struct seq_file *seq, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dab8a0)
Location: net/ipv4/udp.c:2812
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
c000000000dab8a0-c000000000daba34: udp_get_first (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *udp_get_first(struct seq_file *seq, int start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f742e)
Location: net/ipv4/udp.c:2812
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffe0007f742e-ffffffe0007f74f8: udp_get_first (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff81985cf0)
Location: net/ipv4/udp.c:2812
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff81985cf0-ffffffff81985da7: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff8193f7b0)
Location: net/ipv4/udp.c:2812
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff8193f7b0-ffffffff8193f867: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff819f04c0)
Location: net/ipv4/udp.c:2812
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff819f04c0-ffffffff819f0577: udp_get_first.isra.0 (STB_LOCAL)
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
In net/ipv4/udp.c (ffffffff819fb540)
Location: net/ipv4/udp.c:2812
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_get_idx
  - net/ipv4/udp.c:udp_get_next
```
**Symbols:**

```
ffffffff819fb540-ffffffff819fb5f7: udp_get_first.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
