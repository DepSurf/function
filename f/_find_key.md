# Function: <code>_find_key</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dev_pm_opp *_find_key(struct device *dev, long unsigned int *key, int index, bool available, long unsigned int (*read)(struct dev_pm_opp *, int), bool (*compare)(struct dev_pm_opp **, struct dev_pm_opp *, long unsigned int, long unsigned int), bool (*assert)(struct opp_table *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d28010)
Location: drivers/opp/core.c:529
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81d28010-ffffffff81d28125: _find_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dev_pm_opp *_find_key(struct device *dev, long unsigned int *key, int index, bool available, long unsigned int (*read)(struct dev_pm_opp *, int), bool (*compare)(struct dev_pm_opp **, struct dev_pm_opp *, long unsigned int, long unsigned int), bool (*assert)(struct opp_table *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81d911b0)
Location: drivers/opp/core.c:532
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81d911b0-ffffffff81d912c5: _find_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dev_pm_opp *_find_key(struct device *dev, long unsigned int *key, int index, bool available, long unsigned int (*read)(struct dev_pm_opp *, int), bool (*compare)(struct dev_pm_opp **, struct dev_pm_opp *, long unsigned int, long unsigned int), bool (*assert)(struct opp_table *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/opp/core.c (ffffffff81e48880)
Location: drivers/opp/core.c:531
Inline: False
Direct callers:
  - drivers/opp/core.c:dev_pm_opp_find_bw_floor
  - drivers/opp/core.c:dev_pm_opp_find_bw_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_floor
  - drivers/opp/core.c:dev_pm_opp_find_level_ceil
  - drivers/opp/core.c:dev_pm_opp_find_level_exact
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor_indexed
  - drivers/opp/core.c:dev_pm_opp_find_freq_floor
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil_indexed
  - drivers/opp/core.c:dev_pm_opp_find_freq_ceil
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact_indexed
  - drivers/opp/core.c:dev_pm_opp_find_freq_exact
```
**Symbols:**

```
ffffffff81e48880-ffffffff81e48995: _find_key (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
