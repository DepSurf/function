# Function: <code>dm_stat_for_entry</code>

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
In drivers/md/dm-stats.c (ffffffff816ad32d)
Location: drivers/md/dm-stats.c:516
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff8170d9a5)
Location: drivers/md/dm-stats.c:516
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff8173fe65)
Location: drivers/md/dm-stats.c:517
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff81759bee)
Location: drivers/md/dm-stats.c:512
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff817cbe2e)
Location: drivers/md/dm-stats.c:513
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff81814bfd)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff81840c5b)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff81883e87)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff818b5da7)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81985080)
Location: drivers/md/dm-stats.c:514
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff81985080-ffffffff819851a6: dm_stat_for_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff81989120)
Location: drivers/md/dm-stats.c:514
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff81989120-ffffffff81989246: dm_stat_for_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-stats.c (ffffffff8196d800)
Location: drivers/md/dm-stats.c:514
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff8196d800-ffffffff8196d925: dm_stat_for_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:514
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff81a16070-ffffffff81a16316: dm_stat_for_entry (STB_LOCAL)
ffffffff81d2a73d-ffffffff81d2a762: dm_stat_for_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:545
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff81b7f3d0-ffffffff81b7f6c4: dm_stat_for_entry (STB_LOCAL)
ffffffff81ef6949-ffffffff81ef696e: dm_stat_for_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:545
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff81d1cca0-ffffffff81d1cf94: dm_stat_for_entry (STB_LOCAL)
ffffffff820a87c3-ffffffff820a87e8: dm_stat_for_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:553
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff81d85ec0-ffffffff81d86184: dm_stat_for_entry (STB_LOCAL)
ffffffff821299d5-ffffffff821299fa: dm_stat_for_entry.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dm_stat_for_entry(struct dm_stat *s, size_t entry, int idx, sector_t len, struct dm_stats_aux *stats_aux, bool end, long unsigned int duration_jiffies);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-stats.c (0)
Location: drivers/md/dm-stats.c:562
Inline: False
Direct callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
```
**Symbols:**

```
ffffffff81e3d600-ffffffff81e3d8c4: dm_stat_for_entry (STB_LOCAL)
ffffffff8220b729-ffffffff8220b74e: dm_stat_for_entry.cold (STB_LOCAL)
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
In drivers/md/dm-stats.c (ffff800010b0dce8)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (c0bebf90)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (c000000000c008a4)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffe0006fadf0)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff8185bc27)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff818231f7)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff818ab257)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
In drivers/md/dm-stats.c (ffffffff818c7482)
Location: drivers/md/dm-stats.c:514
Inline: True
Inline callers:
  - drivers/md/dm-stats.c:dm_stats_account_io
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
