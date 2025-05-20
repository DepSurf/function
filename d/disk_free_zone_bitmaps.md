# Function: <code>disk_free_zone_bitmaps</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void disk_free_zone_bitmaps(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81778b0b)
Location: block/blk-zoned.c:448
Inline: True
Inline callers:
  - block/blk-zoned.c:disk_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff81778a90-ffffffff81778ad7: disk_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void disk_free_zone_bitmaps(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817b86bb)
Location: block/blk-zoned.c:432
Inline: True
Inline callers:
  - block/blk-zoned.c:disk_clear_zone_settings
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff817b8640-ffffffff817b8687: disk_free_zone_bitmaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void disk_free_zone_bitmaps(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817fc6db)
Location: block/blk-zoned.c:432
Inline: True
Inline callers:
  - block/blk-zoned.c:blk_revalidate_disk_zones
Direct callers:
  - block/genhd.c:disk_release
```
**Symbols:**

```
ffffffff817fd140-ffffffff817fd187: disk_free_zone_bitmaps (STB_GLOBAL)
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
