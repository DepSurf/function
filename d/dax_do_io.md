# Function: <code>dax_do_io</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t dax_do_io(struct kiocb *iocb, struct inode *inode, struct iov_iter *iter, loff_t pos, get_block_t *get_block, dio_iodone_t *end_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff8125e420)
Location: fs/dax.c:209
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
  - fs/ext4/indirect.c:ext4_ind_direct_IO
```
**Symbols:**

```
ffffffff8125e420-ffffffff8125eabb: dax_do_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t dax_do_io(struct kiocb *iocb, struct inode *inode, struct iov_iter *iter, get_block_t *get_block, dio_iodone_t *end_io, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dax.c (ffffffff81286b50)
Location: fs/dax.c:258
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
```
**Symbols:**

```
ffffffff81286b50-ffffffff8128715e: dax_do_io (STB_GLOBAL)
```
</details>
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
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>loff_t pos</code>
</li>
<li>
<b>Param reordered. </b>
<code>iocb, inode, iter, pos, get_block, end_io, flags</code> ➡️ <code>iocb, inode, iter, get_block, end_io, flags</code>
</li>
</ul>
</details>
</li>
</ul>
