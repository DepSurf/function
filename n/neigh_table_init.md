# Function: <code>neigh_table_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817283b0)
Location: net/core/neighbour.c:1497
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff817283b0-ffffffff8172860f: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81791ef0)
Location: net/core/neighbour.c:1492
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81791ef0-ffffffff81792161: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817bf070)
Location: net/core/neighbour.c:1494
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff817bf070-ffffffff817bf2e1: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817dbef0)
Location: net/core/neighbour.c:1536
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff817dbef0-ffffffff817dc140: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81856370)
Location: net/core/neighbour.c:1536
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81856370-ffffffff818565ac: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1552
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff818a5772-ffffffff818a5796: neigh_table_init.cold.61 (STB_LOCAL)
ffffffff818a5130-ffffffff818a534b: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1662
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff818c8ca9-ffffffff818c8ccd: neigh_table_init.cold.65 (STB_LOCAL)
ffffffff818c4920-ffffffff818c4b50: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1676
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81915919-ffffffff81915950: neigh_table_init.cold (STB_LOCAL)
ffffffff81914330-ffffffff81914559: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81947ef0-ffffffff81947f14: neigh_table_init.cold (STB_LOCAL)
ffffffff819469a0-ffffffff81946bcb: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1675
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81a1804e-ffffffff81a18072: neigh_table_init.cold (STB_LOCAL)
ffffffff81a130f0-ffffffff81a13322: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1676
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81c315d3-ffffffff81c315f7: neigh_table_init.cold (STB_LOCAL)
ffffffff81a134d0-ffffffff81a13702: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1680
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81c238bf-ffffffff81c238e3: neigh_table_init.cold (STB_LOCAL)
ffffffff819f95e0-ffffffff819f9812: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1680
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81d36b15-ffffffff81d36b39: neigh_table_init.cold (STB_LOCAL)
ffffffff81aac630-ffffffff81aac879: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1740
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81f03412-ffffffff81f03436: neigh_table_init.cold (STB_LOCAL)
ffffffff81c254f0-ffffffff81c257c7: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd8880)
Location: net/core/neighbour.c:1784
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81dd8880-ffffffff81dd8b85: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e495e0)
Location: net/core/neighbour.c:1763
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81e495e0-ffffffff81e498e5: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f082d0)
Location: net/core/neighbour.c:1774
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81f082d0-ffffffff81f08604: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be2458)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffff800010be2458-ffff800010be2650: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0d00ed4)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
c0d00ed4-c0d01100: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc9fe0)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
c000000000cc9fe0-c000000000cca27c: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe000769b88)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffe000769b88-ffffffe000769d74: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff818e7ec0-ffffffff818e7ee4: neigh_table_init.cold (STB_LOCAL)
ffffffff818e6970-ffffffff818e6b9b: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff818a1d00-ffffffff818a1d24: neigh_table_init.cold (STB_LOCAL)
ffffffff818a07b0-ffffffff818a09db: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff81938ef0-ffffffff81938f14: neigh_table_init.cold (STB_LOCAL)
ffffffff819379a0-ffffffff81937bcb: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void neigh_table_init(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1673
Inline: False
Direct callers:
  - net/ipv4/arp.c:arp_init
  - net/ipv6/ndisc.c:ndisc_init
```
**Symbols:**

```
ffffffff8195a700-ffffffff8195a724: neigh_table_init.cold (STB_LOCAL)
ffffffff81959170-ffffffff8195939b: neigh_table_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
