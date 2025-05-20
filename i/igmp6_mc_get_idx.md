# Function: <code>igmp6_mc_get_idx</code>

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
In net/ipv6/mcast.c (ffffffff817e95c3)
Location: net/ipv6/mcast.c:2631
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81857e13)
Location: net/ipv6/mcast.c:2630
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81889c00)
Location: net/ipv6/mcast.c:2657
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff818b0420)
Location: net/ipv6/mcast.c:2693
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81933229)
Location: net/ipv6/mcast.c:2695
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff8198bd10)
Location: net/ipv6/mcast.c:2721
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff819c2370)
Location: net/ipv6/mcast.c:2721
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81a3116d)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81a67cbd)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ifmcaddr6 *igmp6_mc_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b60870)
Location: net/ipv6/mcast.c:2718
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
**Symbols:**

```
ffffffff81b60870-ffffffff81b60932: igmp6_mc_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ifmcaddr6 *igmp6_mc_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/mcast.c (ffffffff81b6efe0)
Location: net/ipv6/mcast.c:2718
Inline: False
Direct callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
```
**Symbols:**

```
ffffffff81b6efe0-ffffffff81b6f0a2: igmp6_mc_get_idx (STB_LOCAL)
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
In net/ipv6/mcast.c (ffffffff81b5d550)
Location: net/ipv6/mcast.c:2903
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81c24800)
Location: net/ipv6/mcast.c:2902
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81dc1a4f)
Location: net/ipv6/mcast.c:2904
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81f9237f)
Location: net/ipv6/mcast.c:2904
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81ff2cef)
Location: net/ipv6/mcast.c:2904
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff820c097f)
Location: net/ipv6/mcast.c:2905
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffff800010d2e574)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (c0e315fc)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (c000000000e5f39c)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffe00086d65a)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81a0734d)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff819c410d)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81a71dcd)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
In net/ipv6/mcast.c (ffffffff81a7e3f4)
Location: net/ipv6/mcast.c:2720
Inline: True
Inline callers:
  - net/ipv6/mcast.c:igmp6_mc_seq_start
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
