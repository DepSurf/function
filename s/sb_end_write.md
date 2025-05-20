# Function: <code>sb_end_write</code>

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
In fs/open.c (ffffffff812096c5)
Location: include/linux/fs.h:1407
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/pipe.c (ffffffff812150ba)
Location: include/linux/fs.h:1407
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812291d0)
Location: include/linux/fs.h:1407
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8122b851)
Location: include/linux/fs.h:1407
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
```
```
In fs/ext4/super.c (ffffffff812ad061)
Location: include/linux/fs.h:1407
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff812d7be5)
Location: include/linux/fs.h:1407
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
In fs/open.c (ffffffff8122f4b5)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/pipe.c (ffffffff8123bf3f)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812518e0)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81253ff5)
Location: include/linux/fs.h:1484
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
```
```
In fs/ext4/super.c (ffffffff812e1937)
Location: include/linux/fs.h:1484
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff8130795a)
Location: include/linux/fs.h:1484
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
In fs/open.c (ffffffff81241a1f)
Location: include/linux/fs.h:1450
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81246b79)
Location: include/linux/fs.h:1450
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
```
```
In fs/pipe.c (ffffffff8124ecc0)
Location: include/linux/fs.h:1450
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/ioctl.c (ffffffff8125a6ca)
Location: include/linux/fs.h:1450
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/inode.c (ffffffff81264ab1)
Location: include/linux/fs.h:1450
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81267335)
Location: include/linux/fs.h:1450
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
```
```
In fs/ext4/super.c (ffffffff812f75aa)
Location: include/linux/fs.h:1450
Inline: True
```
```
In fs/ext4/mmp.c (ffffffff8131d94a)
Location: include/linux/fs.h:1450
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
In fs/open.c (ffffffff8124de39)
Location: include/linux/fs.h:1466
Inline: True
```
```
In fs/pipe.c (ffffffff8125abc6)
Location: include/linux/fs.h:1466
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812722e3)
Location: include/linux/fs.h:1466
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81274b95)
Location: include/linux/fs.h:1466
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
```
```
In fs/ext4/mmp.c (ffffffff813145c2)
Location: include/linux/fs.h:1466
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8132bf7c)
Location: include/linux/fs.h:1466
Inline: True
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
In fs/open.c (ffffffff8126fb29)
Location: include/linux/fs.h:1495
Inline: True
```
```
In fs/pipe.c (ffffffff8127cf63)
Location: include/linux/fs.h:1495
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81294bfa)
Location: include/linux/fs.h:1495
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff812974c9)
Location: include/linux/fs.h:1495
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write_file_path
  - fs/namespace.c:mnt_want_write_file_path
```
```
In fs/ext4/mmp.c (ffffffff81338d82)
Location: include/linux/fs.h:1495
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8135043d)
Location: include/linux/fs.h:1495
Inline: True
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
In fs/open.c (ffffffff81295dbc)
Location: include/linux/fs.h:1506
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812a3ee2)
Location: include/linux/fs.h:1506
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812bad56)
Location: include/linux/fs.h:1506
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff812bd6b5)
Location: include/linux/fs.h:1506
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write_file_path
```
```
In fs/ext4/mmp.c (ffffffff813672e3)
Location: include/linux/fs.h:1506
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8137e5c0)
Location: include/linux/fs.h:1506
Inline: True
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
In fs/open.c (ffffffff812aabac)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812b9030)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812cff44)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff812d29a5)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff8137f763)
Location: include/linux/fs.h:1561
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81396e70)
Location: include/linux/fs.h:1561
Inline: True
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
In fs/open.c (ffffffff812c738a)
Location: include/linux/fs.h:1577
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812d5d7c)
Location: include/linux/fs.h:1577
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812ece84)
Location: include/linux/fs.h:1577
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff812efb75)
Location: include/linux/fs.h:1577
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff813a8bcc)
Location: include/linux/fs.h:1577
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff813c0efb)
Location: include/linux/fs.h:1577
Inline: True
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
In fs/open.c (ffffffff812d8d9a)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812e78ec)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812fea14)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81301645)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff813c1adc)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff813da24b)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (ffffffff8130ebda)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff8131f7bf)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81337ab4)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8133a725)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff8140dda9)
Location: include/linux/fs.h:1627
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81427121)
Location: include/linux/fs.h:1627
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
In fs/open.c (ffffffff8131aec4)
Location: include/linux/fs.h:1614
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff8132acdd)
Location: include/linux/fs.h:1614
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813433fc)
Location: include/linux/fs.h:1614
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81346a79)
Location: include/linux/fs.h:1614
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/ext4/mmp.c (ffffffff814211f2)
Location: include/linux/fs.h:1614
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff8143ef15)
Location: include/linux/fs.h:1614
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
In fs/open.c (ffffffff8132102f)
Location: include/linux/fs.h:1783
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff81330990)
Location: include/linux/fs.h:1783
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff813496ec)
Location: include/linux/fs.h:1783
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8134cd5f)
Location: include/linux/fs.h:1783
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/io_uring.c (ffffffff8139a8f3)
Location: include/linux/fs.h:1783
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
```
```
In fs/ext4/mmp.c (ffffffff814279a2)
Location: include/linux/fs.h:1783
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81444d55)
Location: include/linux/fs.h:1783
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
In fs/open.c (ffffffff8136e50f)
Location: include/linux/fs.h:1833
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff8137e110)
Location: include/linux/fs.h:1833
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8139743c)
Location: include/linux/fs.h:1833
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8139accf)
Location: include/linux/fs.h:1833
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/io_uring.c (ffffffff813eb91a)
Location: include/linux/fs.h:1833
Inline: True
Inline callers:
  - fs/io_uring.c:kiocb_done
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/ext4/mmp.c (ffffffff8147b66d)
Location: include/linux/fs.h:1833
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81498be5)
Location: include/linux/fs.h:1833
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
In fs/open.c (ffffffff813ecc6a)
Location: include/linux/fs.h:1724
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff813fdd4d)
Location: include/linux/fs.h:1724
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81419613)
Location: include/linux/fs.h:1724
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff8141e6fe)
Location: include/linux/fs.h:1724
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/ext4/mmp.c (ffffffff814fdb25)
Location: include/linux/fs.h:1724
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81523abb)
Location: include/linux/fs.h:1724
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816ca791)
Location: include/linux/fs.h:1724
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
In fs/open.c (ffffffff814751f5)
Location: include/linux/fs.h:1839
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff8148796d)
Location: include/linux/fs.h:1839
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814a5053)
Location: include/linux/fs.h:1839
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff814aae0e)
Location: include/linux/fs.h:1839
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/ext4/mmp.c (ffffffff81598310)
Location: include/linux/fs.h:1839
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff815c0ca2)
Location: include/linux/fs.h:1839
Inline: True
```
```
In io_uring/rw.c (ffffffff817a38d5)
Location: include/linux/fs.h:1839
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
In fs/open.c (ffffffff814a9b8f)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff814bc7dd)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff814da2d3)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff814dfcc1)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/quota/quota.c (ffffffff8156097a)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/mmp.c (ffffffff815cee39)
Location: include/linux/fs.h:1519
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff815f8422)
Location: include/linux/fs.h:1519
Inline: True
```
```
In io_uring/rw.c (ffffffff817e4908)
Location: include/linux/fs.h:1519
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
In kernel/acct.c (ffffffff81229c7e)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff814da0a7)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
  - fs/open.c:do_sys_ftruncate
```
```
In fs/read_write.c (ffffffff814e1f9f)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/pipe.c (ffffffff814eed18)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff8150c8be)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81512bc1)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
  - fs/namespace.c:mnt_want_write
```
```
In fs/splice.c (ffffffff81532100)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c7ec)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81560541)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/backing-file.c (ffffffff81581c7c)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/backing-file.c:backing_aio_rw_complete
```
```
In fs/coredump.c (ffffffff81586e5d)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/quota/quota.c (ffffffff8159706a)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/quota/quota.c:quotactl_block
```
```
In fs/ext4/mmp.c (ffffffff816076c9)
Location: include/linux/fs.h:1727
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff81630fd2)
Location: include/linux/fs.h:1727
Inline: True
```
```
In io_uring/rw.c (ffffffff8182885e)
Location: include/linux/fs.h:1727
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
In fs/open.c (ffff80001037e110)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffff8000103905e0)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffff8000103af93c)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffff8000103b4aa0)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffff800010498f20)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffff8000104ad8a0)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (c0568ae4)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (c0577044)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (c058f724)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (c0592c44)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (c065ac84)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (c0676620)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (c000000000473b64)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (c000000000488278)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (c0000000004ab530)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (c0000000004b0ed4)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (c0000000005c34c4)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (c0000000005e6670)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (ffffffe000253eb4)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffe00025ff5e)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffe000274358)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffe0002775b2)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffe00031cdc4)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffe000330c2c)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (ffffffff812d137a)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812dfecc)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812f6ff4)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff812f9c25)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff813ba0bc)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff813d282b)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (ffffffff812c1ffa)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812d0b0c)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812e7c14)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff812ea845)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff813aab4c)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff813c32ab)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (ffffffff812cf18a)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812ddcdc)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff812f4e04)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff812f7a15)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff813b791c)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff813cfcbb)
Location: include/linux/fs.h:1603
Inline: True
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
In fs/open.c (ffffffff812dff9a)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/open.c:do_sys_ftruncate
```
```
In fs/pipe.c (ffffffff812eec5c)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/pipe.c:pipe_write
```
```
In fs/inode.c (ffffffff81305f94)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/inode.c:touch_atime
```
```
In fs/namespace.c (ffffffff81308d55)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/namespace.c:mnt_drop_write_file
  - fs/namespace.c:mnt_drop_write
```
```
In fs/ext4/mmp.c (ffffffff813cc612)
Location: include/linux/fs.h:1603
Inline: True
Inline callers:
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/super.c (ffffffff813e52b6)
Location: include/linux/fs.h:1603
Inline: True
```
</details>
</li>
</ul>

## Differences
