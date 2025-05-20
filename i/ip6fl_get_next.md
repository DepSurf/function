# Function: <code>ip6fl_get_next</code>

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
In net/ipv6/ip6_flowlabel.c (ffffffff817f5cd9)
Location: net/ipv6/ip6_flowlabel.c:719
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
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
In net/ipv6/ip6_flowlabel.c (ffffffff81864e4f)
Location: net/ipv6/ip6_flowlabel.c:720
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff8189752f)
Location: net/ipv6/ip6_flowlabel.c:720
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff818bd946)
Location: net/ipv6/ip6_flowlabel.c:720
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff819409e6)
Location: net/ipv6/ip6_flowlabel.c:721
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff819998d6)
Location: net/ipv6/ip6_flowlabel.c:721
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff819d0226)
Location: net/ipv6/ip6_flowlabel.c:720
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a3ef26)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a75b96)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff81b700b0)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff81b700b0-ffffffff81b7010b: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff81b7ebe0)
Location: net/ipv6/ip6_flowlabel.c:770
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff81b7ebe0-ffffffff81b7ec3b: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff81b6d7e0)
Location: net/ipv6/ip6_flowlabel.c:770
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff81b6d7e0-ffffffff81b6d83b: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff81c35620)
Location: net/ipv6/ip6_flowlabel.c:772
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff81c35620-ffffffff81c356b8: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff81dd3040)
Location: net/ipv6/ip6_flowlabel.c:772
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff81dd3040-ffffffff81dd30e8: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff81fa45c0)
Location: net/ipv6/ip6_flowlabel.c:772
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff81fa45c0-ffffffff81fa4668: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff82004e70)
Location: net/ipv6/ip6_flowlabel.c:775
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff82004e70-ffffffff82004f18: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff820d3c40)
Location: net/ipv6/ip6_flowlabel.c:775
Inline: True
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffff820d3c40-ffffffff820d3ce8: ip6fl_get_next.isra.0 (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffff800010d3e5ac)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ip6_flowlabel *ip6fl_get_next(struct seq_file *seq, struct ip6_flowlabel *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (c0e41758)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: False
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
c0e41758-c0e417f0: ip6fl_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ip6_flowlabel *ip6fl_get_next(struct seq_file *seq, struct ip6_flowlabel *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (c000000000e72bc0)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: False
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
c000000000e72bc0-c000000000e72c74: ip6fl_get_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ip6_flowlabel *ip6fl_get_next(struct seq_file *seq, struct ip6_flowlabel *fl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ip6_flowlabel.c (ffffffe00087a9ec)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: False
Direct callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
**Symbols:**

```
ffffffe00087a9ec-ffffffe00087aa6c: ip6fl_get_next (STB_LOCAL)
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a15226)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff819d1fe6)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a7fca6)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
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
In net/ipv6/ip6_flowlabel.c (ffffffff81a8c566)
Location: net/ipv6/ip6_flowlabel.c:744
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_next
  - net/ipv6/ip6_flowlabel.c:ip6fl_seq_start
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
