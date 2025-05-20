# Function: <code>sb_issue_discard</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d17d1)
Location: include/linux/blkdev.h:1127
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_free_data_callback
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_trim_fs
```
```
In fs/fat/fatent.c (ffffffff812f9ae0)
Location: include/linux/blkdev.h:1127
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81305782)
Location: include/linux/blkdev.h:1156
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
```
```
In fs/fat/fatent.c (ffffffff8132d71b)
Location: include/linux/blkdev.h:1156
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8131b740)
Location: include/linux/blkdev.h:1321
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
  - fs/ext4/mballoc.c:ext4_free_data_callback
```
```
In fs/fat/fatent.c (ffffffff8134345b)
Location: include/linux/blkdev.h:1321
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81312b20)
Location: include/linux/blkdev.h:1359
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff81357f05)
Location: include/linux/blkdev.h:1359
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813372db)
Location: include/linux/blkdev.h:1374
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff8137cbc5)
Location: include/linux/blkdev.h:1374
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81365a19)
Location: include/linux/blkdev.h:1409
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff813ab632)
Location: include/linux/blkdev.h:1409
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137ddd9)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_fs
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff813c3dc3)
Location: include/linux/blkdev.h:1190
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a44d1)
Location: include/linux/blkdev.h:1204
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff813ee55f)
Location: include/linux/blkdev.h:1204
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813bd341)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff8140852f)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81409022)
Location: include/linux/blkdev.h:1260
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff814578ed)
Location: include/linux/blkdev.h:1260
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141b53d)
Location: include/linux/blkdev.h:1353
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_extent
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff81473cad)
Location: include/linux/blkdev.h:1353
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81421be4)
Location: include/linux/blkdev.h:1338
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff814796f9)
Location: include/linux/blkdev.h:1338
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81474336)
Location: include/linux/blkdev.h:1310
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_try_to_trim_range
```
```
In fs/fat/fatent.c (ffffffff814d0c5f)
Location: include/linux/blkdev.h:1310
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814f0af0)
Location: include/linux/blkdev.h:1121
Inline: True
```
```
In fs/fat/fatent.c (ffffffff8155d804)
Location: include/linux/blkdev.h:1121
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8158af20)
Location: include/linux/blkdev.h:1069
Inline: True
```
```
In fs/fat/fatent.c (ffffffff815ff854)
Location: include/linux/blkdev.h:1069
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815c1ebc)
Location: include/linux/blkdev.h:1049
Inline: True
```
```
In fs/fat/fatent.c (ffffffff81637834)
Location: include/linux/blkdev.h:1049
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff815fa9ec)
Location: include/linux/blkdev.h:1027
Inline: True
```
```
In fs/fat/fatent.c (ffffffff81670d24)
Location: include/linux/blkdev.h:1027
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_trim_fs
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010494014)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffff8000104e8a3c)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c06556b8)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (c06a68c8)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005bd018)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (c0000000006266bc)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe000318bd8)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffe000359f68)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b5921)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff81400b0f)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a63b1)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff813f158f)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b3181)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff813fde8f)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c7cc8)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_all_free
  - fs/ext4/mballoc.c:ext4_free_blocks
```
```
In fs/fat/fatent.c (ffffffff81413b3f)
Location: include/linux/blkdev.h:1231
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_trim_clusters
  - fs/fat/fatent.c:fat_free_clusters
```
</details>
</li>
</ul>

## Differences
