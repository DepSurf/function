# Function: <code>_opp_table_find_key</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *_opp_table_find_key(struct opp_table *opp_table, long unsigned int *key, int index, bool available, long unsigned int (*read)(struct dev_pm_opp *, int), bool (*compare)(struct dev_pm_opp **, struct dev_pm_opp *, long unsigned int, long unsigned int), bool (*assert)(struct opp_table *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:495
Inline: False
Direct callers:
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:_find_key
```
**Symbols:**

```
ffffffff81d27aa0-ffffffff81d27c0b: _opp_table_find_key (STB_LOCAL)
ffffffff820a8a85-ffffffff820a8aa0: _opp_table_find_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *_opp_table_find_key(struct opp_table *opp_table, long unsigned int *key, int index, bool available, long unsigned int (*read)(struct dev_pm_opp *, int), bool (*compare)(struct dev_pm_opp **, struct dev_pm_opp *, long unsigned int, long unsigned int), bool (*assert)(struct opp_table *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:498
Inline: False
Direct callers:
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:_find_key
```
**Symbols:**

```
ffffffff81d90c40-ffffffff81d90dab: _opp_table_find_key (STB_LOCAL)
ffffffff82129c5b-ffffffff82129c76: _opp_table_find_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct dev_pm_opp *_opp_table_find_key(struct opp_table *opp_table, long unsigned int *key, int index, bool available, long unsigned int (*read)(struct dev_pm_opp *, int), bool (*compare)(struct dev_pm_opp **, struct dev_pm_opp *, long unsigned int, long unsigned int), bool (*assert)(struct opp_table *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/opp/core.c (0)
Location: drivers/opp/core.c:497
Inline: False
Direct callers:
  - drivers/opp/core.c:_find_freq_ceil
  - drivers/opp/core.c:_find_key
```
**Symbols:**

```
ffffffff81e48310-ffffffff81e4847b: _opp_table_find_key (STB_LOCAL)
ffffffff8220b9a4-ffffffff8220b9bf: _opp_table_find_key.cold (STB_LOCAL)
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
