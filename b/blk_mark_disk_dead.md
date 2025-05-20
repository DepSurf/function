# Function: <code>blk_mark_disk_dead</code>

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
void blk_mark_disk_dead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3950)
Location: block/genhd.c:555
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff815e3950-ffffffff815e3969: blk_mark_disk_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mark_disk_dead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81691af0)
Location: block/genhd.c:570
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81691af0-ffffffff81691b0f: blk_mark_disk_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mark_disk_dead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81751b10)
Location: block/genhd.c:559
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff81751b10-ffffffff81751b48: blk_mark_disk_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mark_disk_dead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178ca90)
Location: block/genhd.c:586
Inline: False
Direct callers:
  - block/genhd.c:del_gendisk
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8178ca90-ffffffff8178cbde: blk_mark_disk_dead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mark_disk_dead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817cf3e0)
Location: block/genhd.c:615
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkback_changed
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff817cf3e0-ffffffff817cf40d: blk_mark_disk_dead (STB_GLOBAL)
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
