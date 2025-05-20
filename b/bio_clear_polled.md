# Function: <code>bio_clear_polled</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81679423)
Location: include/linux/bio.h:785
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff8167f8ee)
Location: include/linux/bio.h:785
Inline: True
Inline callers:
  - block/blk-merge.c:blk_bio_segment_split
```
```
In drivers/md/dm.c (ffffffff81b720df)
Location: include/linux/bio.h:785
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_io_complete
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
In block/blk-core.c (ffffffff81735b35)
Location: include/linux/bio.h:785
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff8173cbf3)
Location: include/linux/bio.h:785
Inline: True
Inline callers:
  - block/blk-merge.c:bio_split_rw
```
```
In drivers/md/dm.c (ffffffff81d0cb67)
Location: include/linux/bio.h:785
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_handle_requeue
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
In block/blk-core.c (ffffffff81771e50)
Location: include/linux/bio.h:798
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff8177922e)
Location: include/linux/bio.h:798
Inline: True
Inline callers:
  - block/blk-merge.c:bio_split_rw
```
```
In drivers/md/dm.c (ffffffff81d76e52)
Location: include/linux/bio.h:798
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
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
In block/blk-core.c (ffffffff817b4291)
Location: include/linux/bio.h:820
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-merge.c (ffffffff817bb5fe)
Location: include/linux/bio.h:820
Inline: True
Inline callers:
  - block/blk-merge.c:bio_split_rw
```
```
In drivers/md/dm.c (ffffffff81e2e082)
Location: include/linux/bio.h:820
Inline: True
Inline callers:
  - drivers/md/dm.c:__dm_io_complete
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
