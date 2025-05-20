# Function: <code>bio_alloc_clone</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_clone(struct block_device *bdev, struct bio *bio_src, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81673402)
Location: block/bio.c:795
Inline: True
Inline callers:
  - block/bio.c:bio_split
Direct callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - drivers/md/md.c:md_account_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:alloc_tio
```
**Symbols:**

```
ffffffff81673350-ffffffff816733bc: bio_alloc_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_clone(struct block_device *bdev, struct bio *bio_src, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172ef92)
Location: block/bio.c:846
Inline: True
Inline callers:
  - block/bio.c:bio_split
Direct callers:
  - block/blk-mq.c:blk_rq_prep_clone
  - drivers/md/md.c:md_account_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff8172eed0-ffffffff8172ef3c: bio_alloc_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_clone(struct block_device *bdev, struct bio *bio_src, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176b1c2)
Location: block/bio.c:845
Inline: True
Inline callers:
  - block/bio.c:bio_split
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/blk-mq.c:blk_rq_prep_clone
  - drivers/md/md.c:md_account_bio
  - drivers/md/dm.c:dm_split_and_process_bio
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff8176b100-ffffffff8176b16c: bio_alloc_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bio *bio_alloc_clone(struct block_device *bdev, struct bio *bio_src, gfp_t gfp, struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817ad652)
Location: block/bio.c:845
Inline: True
Inline callers:
  - block/bio.c:bio_split
Direct callers:
  - fs/squashfs/block.c:squashfs_bio_read_cached
  - block/blk-mq.c:blk_rq_prep_clone
  - drivers/md/md.c:md_account_bio
  - drivers/md/dm.c:alloc_tio
  - drivers/md/dm.c:alloc_io
  - drivers/md/dm-io-rewind.c:dm_io_rewind
```
**Symbols:**

```
ffffffff817ad590-ffffffff817ad5fc: bio_alloc_clone (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
