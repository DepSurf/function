# Function: <code>sb_start_write</code>

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
In fs/open.c (ffffffff81209699)
Location: include/linux/fs.h:1455
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/namespace.c (ffffffff8122d626)
Location: include/linux/fs.h:1455
Inline: True
```
```
In fs/ext4/super.c (ffffffff812ad018)
Location: include/linux/fs.h:1455
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff812d7b06)
Location: include/linux/fs.h:1455
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff8122f489)
Location: include/linux/fs.h:1532
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/namespace.c (ffffffff81255df6)
Location: include/linux/fs.h:1532
Inline: True
```
```
In fs/ext4/super.c (ffffffff812e18ee)
Location: include/linux/fs.h:1532
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff81307876)
Location: include/linux/fs.h:1532
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812419f3)
Location: include/linux/fs.h:1498
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81246a11)
Location: include/linux/fs.h:1498
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
```
```
In fs/ioctl.c (ffffffff8125a693)
Location: include/linux/fs.h:1498
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/namespace.c (ffffffff812691e6)
Location: include/linux/fs.h:1498
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff8131d866)
Location: include/linux/fs.h:1498
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff8124ddf7)
Location: include/linux/fs.h:1514
Inline: True
```
```
In fs/namespace.c (ffffffff81276986)
Location: include/linux/fs.h:1514
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff813144e6)
Location: include/linux/fs.h:1514
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff8126fae7)
Location: include/linux/fs.h:1543
Inline: True
```
```
In fs/namespace.c (ffffffff81299436)
Location: include/linux/fs.h:1543
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write_file_path
```
```
In fs/ext4/mmp.c (ffffffff81338ca6)
Location: include/linux/fs.h:1543
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff81295d5b)
Location: include/linux/fs.h:1554
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff812bf2b5)
Location: include/linux/fs.h:1554
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write_file_path
```
```
In fs/ext4/mmp.c (ffffffff81367245)
Location: include/linux/fs.h:1554
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812aab4b)
Location: include/linux/fs.h:1609
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff812d4435)
Location: include/linux/fs.h:1609
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff8137f6c5)
Location: include/linux/fs.h:1609
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812c7328)
Location: include/linux/fs.h:1625
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff812f1945)
Location: include/linux/fs.h:1625
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff813a8b35)
Location: include/linux/fs.h:1625
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812d8d38)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff813034f5)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff813c1a45)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff8130eb78)
Location: include/linux/fs.h:1675
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff8133d205)
Location: include/linux/fs.h:1675
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff8140dd3d)
Location: include/linux/fs.h:1675
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff81319ff2)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81320af4)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff813490d3)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8135ed63)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813667c0)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81383238)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff81397e72)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/coredump.c (ffffffff813b9483)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/mmp.c (ffffffff81421168)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In drivers/block/loop.c (ffffffff817fceac)
Location: include/linux/fs.h:1662
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In fs/open.c (ffffffff813200d2)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81326bd5)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff8134fad3)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813656ad)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8136d070)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8138a2c0)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff8139d8ce)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/coredump.c (ffffffff813c05f4)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/mmp.c (ffffffff81427918)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In drivers/block/loop.c (ffffffff817e193c)
Location: include/linux/fs.h:1831
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In fs/open.c (ffffffff8136d682)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff81374195)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff8139de33)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff813b3f9d)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813bbd50)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff813d75d0)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff813ec0ef)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In fs/coredump.c (ffffffff8141041c)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/mmp.c (ffffffff8147b5bb)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In drivers/block/loop.c (ffffffff8186d0dc)
Location: include/linux/fs.h:1881
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In fs/open.c (ffffffff813ec249)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff813f30d4)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff81420e33)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814392e1)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81442612)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81461235)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff81485ec4)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/mmp.c (ffffffff814fda4b)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In io_uring/io_uring.c (ffffffff816d7668)
Location: include/linux/fs.h:1772
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff819b6d69)
Location: include/linux/fs.h:1772
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
In fs/open.c (ffffffff81474719)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff8147bdc2)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff814ad453)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814c75d1)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814d1302)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814f11c5)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff81519753)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/mmp.c (ffffffff8159823b)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In io_uring/rw.c (ffffffff817a4ac3)
Location: include/linux/fs.h:1887
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b2bfc5)
Location: include/linux/fs.h:1887
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
In fs/open.c (ffffffff814a90f6)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814b0989)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff814e2233)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff814fd4e7)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff815075f8)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8152853e)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff8155102b)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff81560949)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/mmp.c (ffffffff815cee02)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In io_uring/rw.c (ffffffff817e5ac6)
Location: include/linux/fs.h:1567
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b7c297)
Location: include/linux/fs.h:1567
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
In fs/open.c (ffffffff814da148)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e214a)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/namespace.c (ffffffff81512f13)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff8153213a)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c82a)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8155d5be)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/backing-file.c (ffffffff81581b31)
Location: include/linux/fs.h:1775
Inline: True
```
```
In fs/coredump.c (ffffffff81586ebc)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff81597039)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/mmp.c (ffffffff81607692)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In io_uring/rw.c (ffffffff81829d80)
Location: include/linux/fs.h:1775
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
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
In fs/open.c (ffff80001037e0c8)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffff8000103b6a48)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (ffff800010498ea0)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (c0568a48)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (c05950e0)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (c065abd4)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (c000000000473adc)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (c0000000004b32a4)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (c0000000005c33e8)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffe000253e50)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffe0002795f6)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (ffffffe00031cd26)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812d1318)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff812fbad5)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff813ba025)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812c1f98)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff812ec6f5)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff813aaab5)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812cf128)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff812f98c5)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff813b7885)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
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
In fs/open.c (ffffffff812dff38)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/namespace.c (ffffffff8130abe5)
Location: include/linux/fs.h:1651
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff813cc585)
Location: include/linux/fs.h:1651
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
</details>
</li>
</ul>

## Differences
