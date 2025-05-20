# Function: <code>neigh_table_clear</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81727bc0)
Location: net/core/neighbour.c:1548
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81727bc0-ffffffff81727c87: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817916d0)
Location: net/core/neighbour.c:1543
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff817916d0-ffffffff81791797: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817befa0)
Location: net/core/neighbour.c:1545
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff817befa0-ffffffff817bf067: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff817dcfb0)
Location: net/core/neighbour.c:1587
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff817dcfb0-ffffffff817dd077: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81858850)
Location: net/core/neighbour.c:1587
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81858850-ffffffff81858917: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1603
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff818a574c-ffffffff818a575d: neigh_table_clear.cold.59 (STB_LOCAL)
ffffffff818a3cd0-ffffffff818a3d8d: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1714
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff818c8d03-ffffffff818c8d14: neigh_table_clear.cold.68 (STB_LOCAL)
ffffffff818c70e0-ffffffff818c719f: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1728
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81915908-ffffffff81915919: neigh_table_clear.cold (STB_LOCAL)
ffffffff81913260-ffffffff8191331f: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81947edf-ffffffff81947ef0: neigh_table_clear.cold (STB_LOCAL)
ffffffff819458c0-ffffffff8194597f: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1727
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81a180b4-ffffffff81a180c5: neigh_table_clear.cold (STB_LOCAL)
ffffffff81a15820-ffffffff81a15903: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1728
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81c3161c-ffffffff81c3162d: neigh_table_clear.cold (STB_LOCAL)
ffffffff81a15b10-ffffffff81a15bf3: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1732
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81c23925-ffffffff81c23936: neigh_table_clear.cold (STB_LOCAL)
ffffffff819fc680-ffffffff819fc763: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1732
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81d36c20-ffffffff81d36c31: neigh_table_clear.cold (STB_LOCAL)
ffffffff81aae6a0-ffffffff81aae7a6: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1798
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81f03521-ffffffff81f03532: neigh_table_clear.cold (STB_LOCAL)
ffffffff81c273e0-ffffffff81c274d9: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81dd9f40)
Location: net/core/neighbour.c:1843
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81dd9f40-ffffffff81dda045: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81e4aca0)
Location: net/core/neighbour.c:1822
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81e4aca0-ffffffff81e4ada5: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffff81f099c0)
Location: net/core/neighbour.c:1833
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81f099c0-ffffffff81f09ac5: neigh_table_clear (STB_GLOBAL)
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
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffff800010be4878)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffff800010be4878-ffff800010be4934: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c0cff50c)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
c0cff50c-c0cff5cc: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (c000000000cc8990)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
c000000000cc8990-c000000000cc8a94: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/neighbour.c (ffffffe00076b800)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffe00076b800-ffffffe00076b8d2: neigh_table_clear (STB_GLOBAL)
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
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff818e7eaf-ffffffff818e7ec0: neigh_table_clear.cold (STB_LOCAL)
ffffffff818e5890-ffffffff818e594f: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff818a1cef-ffffffff818a1d00: neigh_table_clear.cold (STB_LOCAL)
ffffffff8189f6d0-ffffffff8189f78f: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff81938edf-ffffffff81938ef0: neigh_table_clear.cold (STB_LOCAL)
ffffffff819368c0-ffffffff8193697f: neigh_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int neigh_table_clear(int index, struct neigh_table *tbl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/neighbour.c (0)
Location: net/core/neighbour.c:1725
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_cleanup
```
**Symbols:**

```
ffffffff8195a6ef-ffffffff8195a700: neigh_table_clear.cold (STB_LOCAL)
ffffffff81958050-ffffffff8195810f: neigh_table_clear (STB_GLOBAL)
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
