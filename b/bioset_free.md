# Function: <code>bioset_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bioset_free(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b0b70)
Location: block/bio.c:1851
Inline: False
Direct callers:
  - block/bio.c:__bioset_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff813b0b70-ffffffff813b0c6b: bioset_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bioset_free(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f4560)
Location: block/bio.c:1846
Inline: False
Direct callers:
  - block/bio.c:__bioset_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff813f4560-ffffffff813f465b: bioset_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bioset_free(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140df50)
Location: block/bio.c:1893
Inline: False
Direct callers:
  - block/bio.c:__bioset_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/dm.c:dm_free_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff8140df50-ffffffff8140e04b: bioset_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bioset_free(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141bba0)
Location: block/bio.c:1922
Inline: False
Direct callers:
  - block/bio.c:bioset_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff8141bba0-ffffffff8141bc85: bioset_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bioset_free(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81446860)
Location: block/bio.c:1886
Inline: False
Direct callers:
  - block/bio.c:bioset_create
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff81446860-ffffffff8144693b: bioset_free (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
