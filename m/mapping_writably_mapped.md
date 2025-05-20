# Function: <code>mapping_writably_mapped</code>

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
In mm/filemap.c (ffffffff8118d4e6)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811aaffe)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff81262da0)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/fuse/file.c (ffffffff81319358)
Location: include/linux/fs.h:534
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff811a00c5)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811c337a)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff8128ef4f)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap.c (ffffffff8129c523)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff8134de09)
Location: include/linux/fs.h:537
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff811af960)
Location: include/linux/fs.h:488
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811d33f3)
Location: include/linux/fs.h:488
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff812a3f03)
Location: include/linux/fs.h:488
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap.c (ffffffff812b1243)
Location: include/linux/fs.h:488
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff81363709)
Location: include/linux/fs.h:488
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff811b6842)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811dbbea)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff812b2b2b)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap.c (ffffffff812be76d)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff81377fdb)
Location: include/linux/fs.h:499
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff811cab7c)
Location: include/linux/fs.h:503
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_read_iter
```
```
In mm/shmem.c (ffffffff811f19fa)
Location: include/linux/fs.h:503
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff812d65c5)
Location: include/linux/fs.h:503
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap.c (ffffffff812e213d)
Location: include/linux/fs.h:503
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff8139cdab)
Location: include/linux/fs.h:503
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff811ebc6b)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81211eed)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff813012ff)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap.c (ffffffff8130efce)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff813cc1b5)
Location: include/linux/fs.h:505
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff811fc81b)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8122609d)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff81316dee)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap.c (ffffffff813257fe)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - fs/iomap.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff813e54e2)
Location: include/linux/fs.h:542
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
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
In mm/filemap.c (ffffffff812140bb)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81235a5e)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff8133e68f)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff8134c677)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff81411389)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffffffff8149c3cc)
Location: include/linux/fs.h:554
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (ffffffff812218eb)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff81243c9e)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff81356c7f)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff81364947)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff8142afb0)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffffffff814b6548)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (ffffffff8124e4db)
Location: include/linux/fs.h:579
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8126f42e)
Location: include/linux/fs.h:579
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff8139de7f)
Location: include/linux/fs.h:579
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff813ac431)
Location: include/linux/fs.h:579
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff81476bcc)
Location: include/linux/fs.h:579
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff8151532a)
Location: include/linux/fs.h:579
Inline: True
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
In mm/filemap.c (ffffffff81258acb)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8127a79e)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff813af820)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff813bda0f)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff814919df)
Location: include/linux/fs.h:543
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff8153237a)
Location: include/linux/fs.h:543
Inline: True
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
In mm/filemap.c (ffffffff8125cfcf)
Location: include/linux/fs.h:544
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff8127f8da)
Location: include/linux/fs.h:544
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (0)
Location: include/linux/fs.h:544
Inline: True
```
```
In fs/iomap/buffered-io.c (ffffffff813c4be3)
Location: include/linux/fs.h:544
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff81496b64)
Location: include/linux/fs.h:544
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff8153a7fa)
Location: include/linux/fs.h:544
Inline: True
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
In mm/filemap.c (ffffffff81298edd)
Location: include/linux/fs.h:551
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff812bdc0b)
Location: include/linux/fs.h:551
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/iomap/buffered-io.c (ffffffff8141442c)
Location: include/linux/fs.h:551
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_file_buffered_write
```
```
In fs/fuse/file.c (ffffffff814ee46e)
Location: include/linux/fs.h:551
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff8159919a)
Location: include/linux/fs.h:551
Inline: True
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
In mm/filemap.c (ffffffff812ef79c)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff8131b452)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/iomap/buffered-io.c (ffffffff8148b5fe)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/fuse/file.c (ffffffff8157e1ac)
Location: include/linux/fs.h:506
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff8163dd8c)
Location: include/linux/fs.h:506
Inline: True
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
In mm/filemap.c (ffffffff8135a4fc)
Location: include/linux/fs.h:521
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff8138f21e)
Location: include/linux/fs.h:521
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/iomap/buffered-io.c (ffffffff8151f64e)
Location: include/linux/fs.h:521
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/fuse/file.c (ffffffff81623f1c)
Location: include/linux/fs.h:521
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff816f598c)
Location: include/linux/fs.h:521
Inline: True
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
In mm/filemap.c (ffffffff8138be10)
Location: include/linux/fs.h:536
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff813c0803)
Location: include/linux/fs.h:536
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/iomap/buffered-io.c (ffffffff815576f7)
Location: include/linux/fs.h:536
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/fuse/file.c (ffffffff8165c2fc)
Location: include/linux/fs.h:536
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff8172fbaf)
Location: include/linux/fs.h:536
Inline: True
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
In mm/filemap.c (ffffffff813b5980)
Location: include/linux/fs.h:569
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:filemap_splice_read
  - mm/filemap.c:filemap_read
```
```
In mm/shmem.c (ffffffff813eb490)
Location: include/linux/fs.h:569
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_splice_read
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/iomap/buffered-io.c (ffffffff8158dc42)
Location: include/linux/fs.h:569
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_iter
```
```
In fs/fuse/file.c (ffffffff8169605c)
Location: include/linux/fs.h:569
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_fill_write_pages
```
```
In security/integrity/ima/ima_main.c (ffffffff8177053f)
Location: include/linux/fs.h:569
Inline: True
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
In mm/filemap.c (ffff8000102ae334)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffff8000102d5f8c)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffff8000104197c8)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffff80001042bd90)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffff80001050ee68)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffff8000105ae7a4)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (c04db8b0)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c04fe180)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (c05e5af8)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk64
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (c05f47c4)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (c06ca6e8)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (c075deb0)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (c0000000003637cc)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (c0000000003960a4)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (c000000000529310)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (c00000000053d1f4)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (c0000000006561f4)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (c00000000072d770)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (ffffffe0001d4f36)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffe0001f18f0)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffe0002bfefe)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffe0002c94ea)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffe000379906)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffffffe0003f6952)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (ffffffff81219f3b)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123c2ee)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff8134f25f)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff8135cf27)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff81423590)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffffffff814aeb28)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (ffffffff8120d14b)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8122f2ee)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff8133ff3f)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff8134dbc7)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff81414010)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffffffff8149f548)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (ffffffff81217cdb)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8123a08e)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff8134cd2f)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff8135a9f7)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff8141f730)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffffffff814aabc8)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
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
In mm/filemap.c (ffffffff81226d92)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/filemap.c:generic_perform_write
  - mm/filemap.c:generic_file_buffered_read
```
```
In mm/shmem.c (ffffffff8124977e)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - mm/shmem.c:shmem_file_read_iter
```
```
In fs/locks.c (ffffffff81360289)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/locks.c:fcntl_setlk
```
```
In fs/iomap/buffered-io.c (ffffffff8136e15e)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_write_actor
```
```
In fs/fuse/file.c (ffffffff814364b0)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_perform_write
```
```
In security/integrity/ima/ima_main.c (ffffffff814c3608)
Location: include/linux/fs.h:561
Inline: True
Inline callers:
  - security/integrity/ima/ima_main.c:process_measurement
  - security/integrity/ima/ima_main.c:process_measurement
```
</details>
</li>
</ul>

## Differences
