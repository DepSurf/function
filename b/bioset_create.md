# Function: <code>bioset_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct bio_set *bioset_create(unsigned int pool_size, unsigned int front_pad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0f00)
Location: block/bio.c:1925
Inline: True
Inline callers:
  - block/bio.c:init_bio
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff813b0f00-ffffffff813b0f15: bioset_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct bio_set *bioset_create(unsigned int pool_size, unsigned int front_pad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81fc5a7e)
Location: block/bio.c:1920
Inline: True
Inline callers:
  - block/bio.c:init_bio
Direct callers:
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff813f48f0-ffffffff813f4905: bioset_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct bio_set *bioset_create(unsigned int pool_size, unsigned int front_pad);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8200248e)
Location: block/bio.c:1967
Inline: True
Inline callers:
  - block/bio.c:init_bio
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff8140e2e0-ffffffff8140e2f5: bioset_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bio_set *bioset_create(unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141bc90)
Location: block/bio.c:1960
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff8141bc90-ffffffff8141bf20: bioset_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bio_set *bioset_create(unsigned int pool_size, unsigned int front_pad, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446940)
Location: block/bio.c:1921
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_init
  - block/bio.c:init_bio
  - block/blk-core.c:blk_alloc_queue_node
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm-io.c:dm_io_client_create
```
**Symbols:**

```
ffffffff81446940-ffffffff81446bd0: bioset_create (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
