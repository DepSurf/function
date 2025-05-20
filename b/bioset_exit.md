# Function: <code>bioset_exit</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814796d0)
Location: block/bio.c:1950
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff814796d0-ffffffff814797c9: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81497730)
Location: block/bio.c:1882
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff81497730-ffffffff81497829: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/bio.c (0)
Location: block/bio.c:1916
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff814c7f38-ffffffff814c7f50: bioset_exit.cold (STB_LOCAL)
ffffffff814c50f0-ffffffff814c51ce: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ddff0)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff814ddff0-ffffffff814de0d4: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8153ec15)
Location: block/bio.c:1537
Inline: True
Inline callers:
  - block/bio.c:bioset_init
Direct callers:
  - block/blk-core.c:__blk_alloc_queue
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff8153d600-ffffffff8153d65e: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8155b425)
Location: block/bio.c:1540
Inline: True
Inline callers:
  - block/bio.c:bioset_init
Direct callers:
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:__bind_mempools
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff8155a1f0-ffffffff8155a24e: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81562a70)
Location: block/bio.c:1503
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff81562a70-ffffffff81562b68: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff815c7b30)
Location: block/bio.c:1587
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:acct_bioset_exit
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff815c7b30-ffffffff815c7cdf: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81672860)
Location: block/bio.c:1645
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:acct_bioset_exit
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff81672860-ffffffff81672a0e: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8172e320)
Location: block/bio.c:1708
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:acct_bioset_exit
  - drivers/md/md.c:md_free_disk
  - drivers/md/md.c:md_free_disk
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff8172e320-ffffffff8172e4bb: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8176a5f0)
Location: block/bio.c:1693
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:acct_bioset_exit
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff8176a5f0-ffffffff8176a78b: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff817aca50)
Location: block/bio.c:1700
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_release
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:__md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:__bind
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff817aca50-ffffffff817acbeb: bioset_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105da688)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffff8000105da688-ffff8000105da788: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0787960)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
c0787960-c0787a84: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076a950)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
c00000000076a950-c00000000076aae8: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041dc84)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffe00041dc84-ffffffe00041dd7e: bioset_exit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d65d0)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff814d65d0-ffffffff814d66b4: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6f90)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff814c6f90-ffffffff814c7074: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d2660)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff814d2660-ffffffff814d2744: bioset_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bioset_exit(struct bio_set *bs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814eb180)
Location: block/bio.c:1958
Inline: False
Direct callers:
  - block/bio.c:bioset_init
  - block/blk-core.c:blk_alloc_queue_node
  - block/blk-sysfs.c:__blk_release_queue
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_stop
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_run
  - drivers/md/md.c:md_free
  - drivers/md/md.c:md_free
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_alloc_md_mempools
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-io.c:dm_io_client_destroy
```
**Symbols:**

```
ffffffff814eb180-ffffffff814eb264: bioset_exit (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
