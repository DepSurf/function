# Function: <code>file_end_write</code>

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
In kernel/acct.c (ffffffff8110bd34)
Location: include/linux/fs.h:2484
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/read_write.c (ffffffff8120c91e)
Location: include/linux/fs.h:2484
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
```
```
In fs/splice.c (ffffffff8123fc30)
Location: include/linux/fs.h:2484
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff8125c7b1)
Location: include/linux/fs.h:2484
Inline: True
Inline callers:
  - fs/aio.c:aio_run_iocb
```
```
In fs/coredump.c (ffffffff8126f7e3)
Location: include/linux/fs.h:2484
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8156f2df)
Location: include/linux/fs.h:2484
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff81113596)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/read_write.c (ffffffff81233bf2)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
```
In fs/splice.c (ffffffff81267f6d)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff8128586a)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - fs/aio.c:aio_run_iocb
```
```
In fs/coredump.c (ffffffff8129ad3d)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff815c4bdf)
Location: include/linux/fs.h:2599
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff8111aca6)
Location: include/linux/fs.h:2568
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/read_write.c (ffffffff81246782)
Location: include/linux/fs.h:2568
Inline: True
Inline callers:
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
```
In fs/splice.c (ffffffff8127aedd)
Location: include/linux/fs.h:2568
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff812988f0)
Location: include/linux/fs.h:2568
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/coredump.c (ffffffff812af8f7)
Location: include/linux/fs.h:2568
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff815f331f)
Location: include/linux/fs.h:2568
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff8111c861)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff8124cd6e)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8125210b)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/ioctl.c (ffffffff8126708a)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/splice.c (ffffffff81288310)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff812a6a31)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/coredump.c (ffffffff812bd287)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff81607611)
Location: include/linux/fs.h:2680
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff81127f7d)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff8126ecdc)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81273a7c)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/ioctl.c (ffffffff81289916)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/splice.c (ffffffff812aae3c)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff812ca021)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - fs/aio.c:aio_complete
```
```
In fs/coredump.c (ffffffff812e0b92)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8166fad9)
Location: include/linux/fs.h:2741
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff81135d6c)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812948cf)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8129a3b6)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/ioctl.c (ffffffff812afcc1)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/splice.c (ffffffff812d0a94)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff812f424c)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff8130cf21)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816ab671)
Location: include/linux/fs.h:2763
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff811414fc)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812a98ad)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812aceda)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff812e5cb9)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff81308f02)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff813227b3)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816cbde1)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff8114c8f4)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812c6039)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c98c1)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff81304856)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff81329766)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8132d829)
Location: include/linux/fs.h:2853
Inline: True
```
```
In fs/coredump.c (ffffffff81349ec6)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817073e1)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff811585c4)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812d7a49)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812db2d1)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff813178d6)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff8133d696)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8134012b)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffffffff81362166)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8172b631)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff8116965f)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff8130dc69)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81311f51)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff813524fc)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff81377431)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8137c54d)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw_common
```
```
In fs/coredump.c (ffffffff813a815a)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817e7f51)
Location: include/linux/fs.h:2957
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff81165d54)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff81319f50)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813209e3)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff8135ec60)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81366793)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff81385721)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8138a6e6)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw_common
```
```
In fs/coredump.c (ffffffff813b91cd)
Location: include/linux/fs.h:2792
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817fce71)
Location: include/linux/fs.h:2792
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
In kernel/acct.c (ffffffff81166a84)
Location: include/linux/fs.h:3045
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff81320030)
Location: include/linux/fs.h:3045
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81326a75)
Location: include/linux/fs.h:3045
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff81365614)
Location: include/linux/fs.h:3045
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8136d043)
Location: include/linux/fs.h:3045
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8138c991)
Location: include/linux/fs.h:3045
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff813c0433)
Location: include/linux/fs.h:3045
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817e1901)
Location: include/linux/fs.h:3045
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
In kernel/acct.c (ffffffff8118c244)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff8136d5d0)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81374015)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff813b3f04)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813bbd23)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff813d9fe1)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff8141025b)
Location: include/linux/fs.h:3028
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8186d0a1)
Location: include/linux/fs.h:3028
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
In kernel/acct.c (ffffffff811bb63c)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff813ec14c)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813f2fad)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff81439224)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814425d3)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814644cd)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff81485c07)
Location: include/linux/fs.h:2794
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff819b6c4c)
Location: include/linux/fs.h:2794
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
In kernel/acct.c (ffffffff811fd45c)
Location: include/linux/fs.h:2948
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff8147461c)
Location: include/linux/fs.h:2948
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8147bba8)
Location: include/linux/fs.h:2948
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff814c7514)
Location: include/linux/fs.h:2948
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814d12c3)
Location: include/linux/fs.h:2948
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff814f480d)
Location: include/linux/fs.h:2948
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff81519264)
Location: include/linux/fs.h:2948
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff81b2bebc)
Location: include/linux/fs.h:2948
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
In kernel/acct.c (ffffffff812125e9)
Location: include/linux/fs.h:2562
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff814a8fe6)
Location: include/linux/fs.h:2562
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814b0740)
Location: include/linux/fs.h:2562
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff814fd309)
Location: include/linux/fs.h:2562
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff815075b9)
Location: include/linux/fs.h:2562
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/aio.c (ffffffff8152b5e0)
Location: include/linux/fs.h:2562
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/coredump.c (ffffffff81550b6f)
Location: include/linux/fs.h:2562
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff81b7c190)
Location: include/linux/fs.h:2562
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
In kernel/acct.c (ffffffff81229c69)
Location: include/linux/fs.h:2810
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff814da045)
Location: include/linux/fs.h:2810
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814e1e7e)
Location: include/linux/fs.h:2810
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff81531f4c)
Location: include/linux/fs.h:2810
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c74d)
Location: include/linux/fs.h:2810
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/backing-file.c (ffffffff81581afa)
Location: include/linux/fs.h:2810
Inline: True
```
```
In fs/coredump.c (ffffffff81586a00)
Location: include/linux/fs.h:2810
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In kernel/acct.c (ffff8000101c7e7c)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffff80001037ce38)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffff800010380d94)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffff8000103cef70)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffff8000103fd3b8)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffff8000104001b8)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffff800010428774)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffff8000109217d4)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (c040ec84)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (c0567b44)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c056b1c0)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (c05aa240)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (c05cfed0)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (c05d2284)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:kiocb_end_write
```
```
In fs/coredump.c (c05f14a8)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (c0a07038)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (c00000000023006c)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (c000000000472278)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c000000000476b50)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (c0000000004d0900)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (c000000000506208)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (c000000000509704)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (c000000000538a4c)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (c0000000009c6760)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffe000147be8)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffe000253358)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffe0002563e6)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffe00028b0d6)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffe0002aad5a)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffe0002ac874)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffffffe0002c69cc)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffe0005a0580)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff81150be4)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812d0029)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d38b1)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff8130feb6)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff81335c76)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8133870b)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffffffff8135a746)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816f1411)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff81143e8e)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812c0ca9)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c4531)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff81300ac6)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff81326606)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff8132943b)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffffffff8134b3f0)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816cb511)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff8114ea94)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812cde39)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d16c1)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff8130dca6)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff81333746)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813361db)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffffffff81358216)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8171eaf1)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
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
In kernel/acct.c (ffffffff8115b875)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In fs/open.c (ffffffff812dec49)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812e24f1)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff8131f4a6)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/aio.c (ffffffff81347a56)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/aio.c:aio_complete_rw
```
```
In fs/io_uring.c (ffffffff813492ab)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/io_uring.c:io_complete_rw_iopoll
  - fs/io_uring.c:io_complete_rw
```
```
In fs/coredump.c (ffffffff8136b948)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff81739f21)
Location: include/linux/fs.h:2915
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
```
</details>
</li>
</ul>

## Differences
