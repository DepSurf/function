# Function: <code>dm_is_zone_write</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dm_is_zone_write(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81a05b20)
Location: drivers/md/dm-zone.c:124
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_io_dec_pending
```
**Symbols:**

```
ffffffff81a05b20-ffffffff81a05b6f: dm_is_zone_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dm_is_zone_write(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81b6d820)
Location: drivers/md/dm-zone.c:124
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_io_complete
```
**Symbols:**

```
ffffffff81b6d820-ffffffff81b6d880: dm_is_zone_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dm_is_zone_write(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d09bf0)
Location: drivers/md/dm-zone.c:124
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:dm_handle_requeue
```
**Symbols:**

```
ffffffff81d09bf0-ffffffff81d09c50: dm_is_zone_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dm_is_zone_write(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-zone.c (ffffffff81d72d40)
Location: drivers/md/dm-zone.c:125
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:__dm_io_complete
```
**Symbols:**

```
ffffffff81d72d40-ffffffff81d72da0: dm_is_zone_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool dm_is_zone_write(struct mapped_device *md, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-zone.c (0)
Location: drivers/md/dm-zone.c:125
Inline: False
Direct callers:
  - drivers/md/dm.c:clone_endio
  - drivers/md/dm.c:__dm_io_complete
```
**Symbols:**

```
ffffffff8220b1a6-ffffffff8220b1c1: dm_is_zone_write.cold (STB_LOCAL)
ffffffff81e29e20-ffffffff81e29e93: dm_is_zone_write (STB_GLOBAL)
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
