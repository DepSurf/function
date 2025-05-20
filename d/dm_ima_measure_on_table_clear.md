# Function: <code>dm_ima_measure_on_table_clear</code>

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
void dm_ima_measure_on_table_clear(struct mapped_device *md, bool new_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:608
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_clear
```
**Symbols:**

```
ffffffff81d29ea9-ffffffff81d29eb5: dm_ima_measure_on_table_clear.cold (STB_LOCAL)
ffffffff81a07530-ffffffff81a07837: dm_ima_measure_on_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_ima_measure_on_table_clear(struct mapped_device *md, bool new_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-ima.c (0)
Location: drivers/md/dm-ima.c:609
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_clear
```
**Symbols:**

```
ffffffff81ef61b1-ffffffff81ef61bd: dm_ima_measure_on_table_clear.cold (STB_LOCAL)
ffffffff81b6f250-ffffffff81b6f5ac: dm_ima_measure_on_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dm_ima_measure_on_table_clear(struct mapped_device *md, bool new_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d0b820)
Location: drivers/md/dm-ima.c:606
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_clear
```
**Symbols:**

```
ffffffff81d0b820-ffffffff81d0bb72: dm_ima_measure_on_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dm_ima_measure_on_table_clear(struct mapped_device *md, bool new_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81d74950)
Location: drivers/md/dm-ima.c:605
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_clear
```
**Symbols:**

```
ffffffff81d74950-ffffffff81d74ca2: dm_ima_measure_on_table_clear (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dm_ima_measure_on_table_clear(struct mapped_device *md, bool new_map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-ima.c (ffffffff81e2ba60)
Location: drivers/md/dm-ima.c:605
Inline: False
Direct callers:
  - drivers/md/dm-ioctl.c:table_clear
```
**Symbols:**

```
ffffffff81e2ba60-ffffffff81e2bdb2: dm_ima_measure_on_table_clear (STB_GLOBAL)
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
