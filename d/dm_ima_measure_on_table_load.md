# Function: <code>dm_ima_measure_on_table_load</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dm_ima_measure_on_table_load(struct dm_table *table, unsigned int status_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:178
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81d29e85-ffffffff81d29e91: dm_ima_measure_on_table_load.cold (STB_LOCAL)
ffffffff81a066a0-ffffffff81a06ce0: dm_ima_measure_on_table_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_ima_measure_on_table_load(struct dm_table *table, unsigned int status_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:179
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81ef618d-ffffffff81ef6199: dm_ima_measure_on_table_load.cold (STB_LOCAL)
ffffffff81b6e3b0-ffffffff81b6ea10: dm_ima_measure_on_table_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_ima_measure_on_table_load(struct dm_table *table, unsigned int status_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d0a920)
Location: drivers/md/dm-ima.c:179
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81d0a920-ffffffff81d0af92: dm_ima_measure_on_table_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_ima_measure_on_table_load(struct dm_table *table, unsigned int status_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d73a60)
Location: drivers/md/dm-ima.c:178
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81d73a60-ffffffff81d740c8: dm_ima_measure_on_table_load (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_ima_measure_on_table_load(struct dm_table *table, unsigned int status_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81e2ab70)
Location: drivers/md/dm-ima.c:178
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81e2ab70-ffffffff81e2b1d8: dm_ima_measure_on_table_load (STB_GLOBAL)
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
