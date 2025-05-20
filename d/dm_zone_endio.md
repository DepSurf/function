# Function: <code>dm_zone_endio</code>

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
void dm_zone_endio(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:599
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81d29e63-ffffffff81d29e85: dm_zone_endio.cold (STB_LOCAL)
ffffffff81a06160-ffffffff81a062ca: dm_zone_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dm_zone_endio(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:592
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff81ef616b-ffffffff81ef618d: dm_zone_endio.cold (STB_LOCAL)
ffffffff81b6ddc0-ffffffff81b6df66: dm_zone_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dm_zone_endio(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:586
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff820a85ac-ffffffff820a85ce: dm_zone_endio.cold (STB_LOCAL)
ffffffff81d0a2c0-ffffffff81d0a469: dm_zone_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dm_zone_endio(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:585
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff821297c1-ffffffff821297e3: dm_zone_endio.cold (STB_LOCAL)
ffffffff81d73400-ffffffff81d735a3: dm_zone_endio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dm_zone_endio(struct dm_io *io, struct bio *clone);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:585
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
```
**Symbols:**

```
ffffffff8220b28c-ffffffff8220b300: dm_zone_endio.cold (STB_LOCAL)
ffffffff81e2a4f0-ffffffff81e2a6b4: dm_zone_endio (STB_GLOBAL)
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
