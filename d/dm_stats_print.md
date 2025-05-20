# Function: <code>dm_stats_print</code>

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
In drivers/md/dm-stats.c (ffffffff816acca4)
Location: drivers/md/dm-stats.c:802
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff8170d210)
Location: drivers/md/dm-stats.c:801
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff8173f270)
Location: drivers/md/dm-stats.c:802
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff81759073)
Location: drivers/md/dm-stats.c:797
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff817cb2d3)
Location: drivers/md/dm-stats.c:798
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff818140e6)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff818400e6)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff81882fb3)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff818b4e53)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81985ae0)
Location: drivers/md/dm-stats.c:799
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff81985ae0-ffffffff81985e14: dm_stats_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81989b60)
Location: drivers/md/dm-stats.c:799
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff81989b60-ffffffff81989e94: dm_stats_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8196e120)
Location: drivers/md/dm-stats.c:799
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff8196e120-ffffffff8196e45d: dm_stats_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81a16990)
Location: drivers/md/dm-stats.c:799
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff81a16990-ffffffff81a16ccd: dm_stats_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81b7ef10)
Location: drivers/md/dm-stats.c:832
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff81b7ef10-ffffffff81b7f261: dm_stats_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d1e240)
Location: drivers/md/dm-stats.c:832
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff81d1e240-ffffffff81d1e591: dm_stats_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81d87430)
Location: drivers/md/dm-stats.c:844
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff81d87430-ffffffff81d8777d: dm_stats_print (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_stats_print(struct dm_stats *stats, int id, size_t idx_start, size_t idx_len, bool clear, char *result, unsigned int maxlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81e3eb40)
Location: drivers/md/dm-stats.c:853
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:message_stats_print
```
**Symbols:**

```
ffffffff81e3eb40-ffffffff81e3ee8d: dm_stats_print (STB_LOCAL)
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
In drivers/md/dm-stats.c (ffff800010b0c9d0)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (c0beacf0)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (c000000000bff0bc)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffe0006fa36a)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff8185acd3)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff81822163)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff818aa303)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
In drivers/md/dm-stats.c (ffffffff818c6e73)
Location: drivers/md/dm-stats.c:799
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:message_stats_print
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
