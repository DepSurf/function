# Function: <code>dm_zone_map_bio</code>

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
int dm_zone_map_bio(struct dm_target_io *tio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:520
Inline: False
```
**Symbols:**

```
ffffffff81d29e07-ffffffff81d29e63: dm_zone_map_bio.cold (STB_LOCAL)
ffffffff81a05e10-ffffffff81a0615f: dm_zone_map_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dm_zone_map_bio(struct dm_target_io *tio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:518
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff81ef611f-ffffffff81ef616b: dm_zone_map_bio.cold (STB_LOCAL)
ffffffff81b6db20-ffffffff81b6ddbf: dm_zone_map_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dm_zone_map_bio(struct dm_target_io *tio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:513
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff820a8560-ffffffff820a85ac: dm_zone_map_bio.cold (STB_LOCAL)
ffffffff81d0a010-ffffffff81d0a2a8: dm_zone_map_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dm_zone_map_bio(struct dm_target_io *tio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:512
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff82129775-ffffffff821297c1: dm_zone_map_bio.cold (STB_LOCAL)
ffffffff81d73150-ffffffff81d733e1: dm_zone_map_bio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dm_zone_map_bio(struct dm_target_io *tio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:512
Inline: False
Direct callers:
  - drivers/md/dm.c:__map_bio
```
**Symbols:**

```
ffffffff8220b1c1-ffffffff8220b28c: dm_zone_map_bio.cold (STB_LOCAL)
ffffffff81e2a250-ffffffff81e2a4dd: dm_zone_map_bio (STB_GLOBAL)
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
