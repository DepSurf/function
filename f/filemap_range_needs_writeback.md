# Function: <code>filemap_range_needs_writeback</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool filemap_range_needs_writeback(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125db80)
Location: mm/filemap.c:638
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff8125db80-ffffffff8125dd5b: filemap_range_needs_writeback (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool filemap_range_needs_writeback(struct address_space *mapping, loff_t start_byte, loff_t end_byte);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299e10)
Location: mm/filemap.c:656
Inline: False
Direct callers:
  - mm/filemap.c:generic_file_read_iter
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
**Symbols:**

```
ffffffff81299e10-ffffffff81299ff7: filemap_range_needs_writeback (STB_GLOBAL)
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
In mm/filemap.c (ffffffff812f5799)
Location: include/linux/pagemap.h:1159
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/iomap/direct-io.c (ffffffff8148d518)
Location: include/linux/pagemap.h:1159
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In block/fops.c (ffffffff81670da3)
Location: include/linux/pagemap.h:1159
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
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
In mm/filemap.c (ffffffff8135f70d)
Location: include/linux/pagemap.h:1133
Inline: True
Inline callers:
  - mm/filemap.c:generic_file_read_iter
```
```
In fs/iomap/direct-io.c (ffffffff81520996)
Location: include/linux/pagemap.h:1133
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In block/fops.c (ffffffff8172c4d3)
Location: include/linux/pagemap.h:1133
Inline: True
Inline callers:
  - block/fops.c:blkdev_read_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8139213e)
Location: include/linux/pagemap.h:1136
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_write_and_wait
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba1ce)
Location: include/linux/pagemap.h:1223
Inline: True
Inline callers:
  - mm/filemap.c:kiocb_write_and_wait
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
