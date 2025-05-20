# Function: <code>invalidate_inode_pages2_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8119e790)
Location: mm/truncate.c:563
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff8119e790-ffffffff8119ebe7: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811b4280)
Location: mm/truncate.c:584
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff811b4280-ffffffff811b4714: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811c48f0)
Location: mm/truncate.c:614
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:dax_iomap_actor
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff811c48f0-ffffffff811c4d99: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811ccc40)
Location: mm/truncate.c:619
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/dax.c:dax_iomap_actor
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_rw
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff811ccc40-ffffffff811cd0f7: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff811e1ed0)
Location: mm/truncate.c:672
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff811e1ed0-ffffffff811e2425: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81203640)
Location: mm/truncate.c:668
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81203640-ffffffff81203b99: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81215f10)
Location: mm/truncate.c:669
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap.c:iomap_dio_rw
  - fs/iomap.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81215f10-ffffffff8121647a: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/truncate.c (0)
Location: mm/truncate.c:672
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81226d8d-ffffffff81226da0: invalidate_inode_pages2_range.cold (STB_LOCAL)
ffffffff81225920-ffffffff81225e4e: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81233770)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81233770-ffffffff81233cad: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81260ea0)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81260ea0-ffffffff812612de: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8126b2a0)
Location: mm/truncate.c:712
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/block_dev.c:truncate_bdev_range
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff8126b2a0-ffffffff8126b6dc: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81270380)
Location: mm/truncate.c:609
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:truncate_bdev_range
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81270380-ffffffff81270881: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff812ae000)
Location: mm/truncate.c:608
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff812ae000-ffffffff812ae53e: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81307520)
Location: mm/truncate.c:628
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff81307520-ffffffff8130795a: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81371640)
Location: mm/truncate.c:620
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/iomap/direct-io.c:__iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff81371640-ffffffff81371b4f: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813a3750)
Location: mm/truncate.c:620
Inline: False
Direct callers:
  - mm/filemap.c:kiocb_invalidate_pages
  - mm/truncate.c:invalidate_inode_pages2
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff813a3750-ffffffff813a3c59: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff813cd2f0)
Location: mm/truncate.c:609
Inline: False
Direct callers:
  - mm/filemap.c:kiocb_invalidate_pages
  - mm/truncate.c:invalidate_inode_pages2
  - fs/dax.c:dax_iomap_iter
  - fs/dax.c:dax_zero_range
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/inode.c:fuse_reverse_inval_inode
  - block/bdev.c:truncate_bdev_range
```
**Symbols:**

```
ffffffff813cd2f0-ffffffff813cd7d7: invalidate_inode_pages2_range (STB_GLOBAL)
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
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffff8000102c3c48)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffff8000102c3c48-ffff8000102c419c: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c04ee7f0)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
c04ee7f0-c04eebe0: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (c00000000037e030)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
c00000000037e030-c00000000037e76c: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffe0001e48a8)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffe0001e48a8-ffffffe0001e4cac: invalidate_inode_pages2_range (STB_GLOBAL)
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
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8122bdc0)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff8122bdc0-ffffffff8122c2fd: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff8121eea0)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff8121eea0-ffffffff8121f3d7: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81229b60)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81229b60-ffffffff8122a09d: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int invalidate_inode_pages2_range(struct address_space *mapping, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/truncate.c (ffffffff81238f60)
Location: mm/truncate.c:684
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_direct_write
  - mm/filemap.c:generic_file_direct_write
  - mm/truncate.c:invalidate_inode_pages2
  - fs/block_dev.c:blkdev_fallocate
  - fs/direct-io.c:dio_complete
  - fs/dax.c:dax_iomap_actor
  - fs/iomap/direct-io.c:iomap_dio_rw
  - fs/iomap/direct-io.c:iomap_dio_complete
  - fs/fuse/inode.c:fuse_reverse_inval_inode
```
**Symbols:**

```
ffffffff81238f60-ffffffff8123948a: invalidate_inode_pages2_range (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
