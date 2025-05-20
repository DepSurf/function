# Function: <code>filemap_sample_wb_err</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/open.c (ffffffff8124d6c4)
Location: include/linux/fs.h:2623
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812530cd)
Location: include/linux/fs.h:2623
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff81293064)
Location: include/linux/fs.h:2623
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff8126f724)
Location: include/linux/fs.h:2684
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812751cd)
Location: include/linux/fs.h:2684
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff812b5e65)
Location: include/linux/fs.h:2684
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff812950e5)
Location: include/linux/fs.h:2707
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8129ba63)
Location: include/linux/fs.h:2707
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff812ddac5)
Location: include/linux/fs.h:2707
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff812a9db7)
Location: include/linux/fs.h:2791
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812b0c5f)
Location: include/linux/fs.h:2791
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff812f30a5)
Location: include/linux/fs.h:2791
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff812c6567)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812cd5dd)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff81314b16)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff812d7f77)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812deffd)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff81327c9e)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff8130dffb)
Location: include/linux/fs.h:2852
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff81315b7d)
Location: include/linux/fs.h:2852
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff813616ce)
Location: include/linux/fs.h:2852
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff8131a11b)
Location: include/linux/fs.h:2714
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff813210ad)
Location: include/linux/fs.h:2714
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff8136ebb7)
Location: include/linux/fs.h:2714
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff813201fb)
Location: include/linux/fs.h:2950
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8132749d)
Location: include/linux/fs.h:2950
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff81375527)
Location: include/linux/fs.h:2950
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff8136d7ab)
Location: include/linux/fs.h:2933
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8137476d)
Location: include/linux/fs.h:2933
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In block/fops.c (ffffffff815c5737)
Location: include/linux/fs.h:2933
Inline: True
Inline callers:
  - block/fops.c:blkdev_open
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
In fs/open.c (ffffffff813eb8b7)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff813f3b79)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In block/fops.c (ffffffff81670194)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - block/fops.c:blkdev_open
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
In fs/open.c (ffffffff81473c67)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff8147c9c9)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In block/fops.c (ffffffff8172b724)
Location: include/linux/pagemap.h:107
Inline: True
Inline callers:
  - block/fops.c:blkdev_open
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
In fs/open.c (ffffffff814a845d)
Location: include/linux/pagemap.h:111
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814b1662)
Location: include/linux/pagemap.h:111
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In block/fops.c (ffffffff817689f4)
Location: include/linux/pagemap.h:111
Inline: True
Inline callers:
  - block/fops.c:blkdev_open
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
In fs/open.c (ffffffff814d953d)
Location: include/linux/pagemap.h:111
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff814e2e32)
Location: include/linux/pagemap.h:111
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In block/fops.c (ffffffff817aa8db)
Location: include/linux/pagemap.h:111
Inline: True
Inline callers:
  - block/fops.c:blkdev_open
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
In fs/open.c (ffff80001037daf0)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffff8000103857d4)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffff8000103e2c18)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (c0567570)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (c056e5ec)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (c05badf4)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (c00000000047291c)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (c00000000047b8e4)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (c0000000004e8ad4)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffe000253792)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffe0002584b8)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffe00029908a)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff812d0557)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812d75dd)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff8132027e)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff812c11d7)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812c825d)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff81310e1e)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
```
In drivers/dax/device.c (ffffffff816f15ac)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - drivers/dax/device.c:dax_open
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
In fs/open.c (ffffffff812ce367)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812d53ed)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff8131dd4e)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
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
In fs/open.c (ffffffff812df177)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/open.c:do_dentry_open
```
```
In fs/file_table.c (ffffffff812e623d)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/file_table.c:alloc_file
```
```
In fs/block_dev.c (ffffffff8132fa4e)
Location: include/linux/fs.h:2829
Inline: True
Inline callers:
  - fs/block_dev.c:blkdev_open
```
</details>
</li>
</ul>

## Differences
