# Function: <code>ipmr_fill_table</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff8186a9e3)
Location: net/ipv4/ipmr.c:2657
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff818eb16b)
Location: net/ipv4/ipmr.c:2822
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff81941930)
Location: net/ipv4/ipmr.c:2651
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff819711e1)
Location: net/ipv4/ipmr.c:2690
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff819da969)
Location: net/ipv4/ipmr.c:2753
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff81a1184e)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ipmr_fill_table(struct mr_table *mrt, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b00130)
Location: net/ipv4/ipmr.c:2722
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81b00130-ffffffff81b0025e: ipmr_fill_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ipmr_fill_table(struct mr_table *mrt, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b0e170)
Location: net/ipv4/ipmr.c:2731
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81b0e170-ffffffff81b0e29e: ipmr_fill_table (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffffffff81b0097e)
Location: net/ipv4/ipmr.c:2731
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ipmr_fill_table(struct mr_table *mrt, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:2733
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81bbd930-ffffffff81bbda8a: ipmr_fill_table (STB_LOCAL)
ffffffff81d3e975-ffffffff81d3e9b3: ipmr_fill_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ipmr_fill_table(struct mr_table *mrt, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:2727
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81d521f0-ffffffff81d52356: ipmr_fill_table (STB_LOCAL)
ffffffff81f0b29e-ffffffff81f0b2dc: ipmr_fill_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool ipmr_fill_table(struct mr_table *mrt, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:2734
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81f1c250-ffffffff81f1c3b6: ipmr_fill_table (STB_LOCAL)
ffffffff820b2b48-ffffffff820b2b86: ipmr_fill_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool ipmr_fill_table(struct mr_table *mrt, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:2749
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff81f7bd30-ffffffff81f7be96: ipmr_fill_table (STB_LOCAL)
ffffffff82133d00-ffffffff82133d3e: ipmr_fill_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool ipmr_fill_table(struct mr_table *mrt, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:2747
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
```
**Symbols:**

```
ffffffff82042420-ffffffff82042586: ipmr_fill_table (STB_LOCAL)
ffffffff8221570c-ffffffff8221574a: ipmr_fill_table.cold (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffff800010cc9f3c)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (c0dd5ed4)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (c000000000de939c)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffe00081f41c)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff819b1171)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff8196d7a1)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff81a1ba11)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
In net/ipv4/ipmr.c (ffffffff81a2695e)
Location: net/ipv4/ipmr.c:2754
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_dumplink
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
