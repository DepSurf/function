# Function: <code>folio_zero_segments</code>

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
In fs/buffer.c (ffffffff81447fde)
Location: include/linux/highmem.h:411
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/iomap/buffered-io.c (ffffffff8148af61)
Location: include/linux/highmem.h:411
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
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
In fs/buffer.c (ffffffff814d6b97)
Location: include/linux/highmem.h:426
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/iomap/buffered-io.c (ffffffff8151f03a)
Location: include/linux/highmem.h:426
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
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
In mm/shmem.c (ffffffff813be672)
Location: include/linux/highmem.h:480
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In fs/buffer.c (ffffffff8150d1a8)
Location: include/linux/highmem.h:480
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/iomap/buffered-io.c (ffffffff8155718a)
Location: include/linux/highmem.h:480
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/ext4/inode.c (ffffffff815b0fc6)
Location: include/linux/highmem.h:480
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
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
In mm/shmem.c (ffffffff813e9344)
Location: include/linux/highmem.h:600
Inline: True
Inline callers:
  - mm/shmem.c:shmem_write_end
```
```
In fs/libfs.c (ffffffff81523122)
Location: include/linux/highmem.h:600
Inline: True
Inline callers:
  - fs/libfs.c:simple_write_begin
```
```
In fs/buffer.c (ffffffff81541e15)
Location: include/linux/highmem.h:600
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
```
```
In fs/iomap/buffered-io.c (ffffffff8158d5ea)
Location: include/linux/highmem.h:600
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:__iomap_write_begin
```
```
In fs/ext4/inode.c (ffffffff815e9e96)
Location: include/linux/highmem.h:600
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
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
