# Function: <code>file_start_write</code>

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
In fs/read_write.c (ffffffff8120c8a7)
Location: include/linux/fs.h:2470
Inline: True
Inline callers:
  - fs/read_write.c:vfs_write
  - fs/read_write.c:do_readv_writev
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_sendfile
```
```
In fs/splice.c (ffffffff8123fbe1)
Location: include/linux/fs.h:2470
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff8125c792)
Location: include/linux/fs.h:2470
Inline: True
Inline callers:
  - fs/aio.c:aio_run_iocb
```
```
In fs/coredump.c (ffffffff8126f7b9)
Location: include/linux/fs.h:2470
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8156f2bb)
Location: include/linux/fs.h:2470
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
In fs/read_write.c (ffffffff81233bbd)
Location: include/linux/fs.h:2585
Inline: True
Inline callers:
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
```
In fs/splice.c (ffffffff81267f1d)
Location: include/linux/fs.h:2585
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff8128584d)
Location: include/linux/fs.h:2585
Inline: True
Inline callers:
  - fs/aio.c:aio_run_iocb
```
```
In fs/coredump.c (ffffffff8129ad12)
Location: include/linux/fs.h:2585
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff815c4bbb)
Location: include/linux/fs.h:2585
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
In fs/read_write.c (ffffffff8124674d)
Location: include/linux/fs.h:2554
Inline: True
Inline callers:
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_do_readv_writev
  - fs/read_write.c:do_readv_writev
```
```
In fs/splice.c (ffffffff8127ae8d)
Location: include/linux/fs.h:2554
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff81298ca8)
Location: include/linux/fs.h:2554
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff812af8cc)
Location: include/linux/fs.h:2554
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff815f32fb)
Location: include/linux/fs.h:2554
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
In fs/open.c (ffffffff8124cd43)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81252073)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/ioctl.c (ffffffff81267061)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/splice.c (ffffffff812882c5)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff812a6da4)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff812bd25f)
Location: include/linux/fs.h:2666
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816075eb)
Location: include/linux/fs.h:2666
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
In fs/open.c (ffffffff8126ecaf)
Location: include/linux/fs.h:2727
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812739de)
Location: include/linux/fs.h:2727
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/ioctl.c (ffffffff812898ed)
Location: include/linux/fs.h:2727
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/splice.c (ffffffff812aadf1)
Location: include/linux/fs.h:2727
Inline: True
Inline callers:
  - fs/splice.c:SyS_splice
```
```
In fs/aio.c (ffffffff812ca39f)
Location: include/linux/fs.h:2727
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/coredump.c (ffffffff812e0b65)
Location: include/linux/fs.h:2727
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8166fab6)
Location: include/linux/fs.h:2727
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
In fs/open.c (ffffffff812948a1)
Location: include/linux/fs.h:2749
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8129a322)
Location: include/linux/fs.h:2749
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/ioctl.c (ffffffff812afc8c)
Location: include/linux/fs.h:2749
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_file_clone
```
```
In fs/splice.c (ffffffff812d0a46)
Location: include/linux/fs.h:2749
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff8130cef0)
Location: include/linux/fs.h:2749
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816ab646)
Location: include/linux/fs.h:2749
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
In fs/open.c (ffffffff812a9871)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812acea5)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff812e5c6b)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff81322782)
Location: include/linux/fs.h:2833
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816cbdb6)
Location: include/linux/fs.h:2833
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
In fs/open.c (ffffffff812c5ffe)
Location: include/linux/fs.h:2839
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c9885)
Location: include/linux/fs.h:2839
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff81304810)
Location: include/linux/fs.h:2839
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff81349e96)
Location: include/linux/fs.h:2839
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817073b6)
Location: include/linux/fs.h:2839
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
In fs/open.c (ffffffff812d7a0e)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812db295)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff81317890)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff81362136)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8172b606)
Location: include/linux/fs.h:2901
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
In fs/open.c (ffffffff8130dc32)
Location: include/linux/fs.h:2943
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81311f2f)
Location: include/linux/fs.h:2943
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
In fs/splice.c (ffffffff813524cf)
Location: include/linux/fs.h:2943
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff813a812e)
Location: include/linux/fs.h:2943
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817e7f2b)
Location: include/linux/fs.h:2943
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
In fs/open.c (ffffffff81319f22)
Location: include/linux/fs.h:2778
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81320922)
Location: include/linux/fs.h:2778
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff8135ec1f)
Location: include/linux/fs.h:2778
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81366771)
Location: include/linux/fs.h:2778
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/coredump.c (ffffffff813b91a1)
Location: include/linux/fs.h:2778
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817fce4b)
Location: include/linux/fs.h:2778
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
In fs/open.c (ffffffff81320002)
Location: include/linux/fs.h:3031
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813269bb)
Location: include/linux/fs.h:3031
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff813655d3)
Location: include/linux/fs.h:3031
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff8136d021)
Location: include/linux/fs.h:3031
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/coredump.c (ffffffff813c03fa)
Location: include/linux/fs.h:3031
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff817e18db)
Location: include/linux/fs.h:3031
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
In fs/open.c (ffffffff8136d5a2)
Location: include/linux/fs.h:3014
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff81373f5b)
Location: include/linux/fs.h:3014
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff813b3ec3)
Location: include/linux/fs.h:3014
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff813bbd01)
Location: include/linux/fs.h:3014
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/coredump.c (ffffffff81410222)
Location: include/linux/fs.h:3014
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8186d07b)
Location: include/linux/fs.h:3014
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
In fs/open.c (ffffffff813ec119)
Location: include/linux/fs.h:2780
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff813f2e6b)
Location: include/linux/fs.h:2780
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff814391e2)
Location: include/linux/fs.h:2780
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814425b1)
Location: include/linux/fs.h:2780
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/coredump.c (ffffffff81485bce)
Location: include/linux/fs.h:2780
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff819b6d4d)
Location: include/linux/fs.h:2780
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
In fs/open.c (ffffffff814745e9)
Location: include/linux/fs.h:2934
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff8147bb05)
Location: include/linux/fs.h:2934
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff814c74d2)
Location: include/linux/fs.h:2934
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff814d12a1)
Location: include/linux/fs.h:2934
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/coredump.c (ffffffff81519228)
Location: include/linux/fs.h:2934
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff81b2bfa9)
Location: include/linux/fs.h:2934
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
In fs/open.c (ffffffff814a8fb0)
Location: include/linux/fs.h:2548
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814b068e)
Location: include/linux/fs.h:2548
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff814fd2c1)
Location: include/linux/fs.h:2548
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/remap_range.c (ffffffff81507594)
Location: include/linux/fs.h:2548
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/coredump.c (ffffffff81550b30)
Location: include/linux/fs.h:2548
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff81b7c27b)
Location: include/linux/fs.h:2548
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
In fs/open.c (ffffffff814da00f)
Location: include/linux/fs.h:2790
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff814e1e5b)
Location: include/linux/fs.h:2790
Inline: True
Inline callers:
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:vfs_writev
  - fs/read_write.c:vfs_iter_write
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff81531f08)
Location: include/linux/fs.h:2790
Inline: True
Inline callers:
  - fs/splice.c:do_splice
  - fs/splice.c:direct_splice_actor
```
```
In fs/remap_range.c (ffffffff8153c70c)
Location: include/linux/fs.h:2790
Inline: True
Inline callers:
  - fs/remap_range.c:vfs_clone_file_range
```
```
In fs/backing-file.c (ffffffff81581acd)
Location: include/linux/fs.h:2790
Inline: True
```
```
In fs/coredump.c (ffffffff815869c1)
Location: include/linux/fs.h:2790
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
In fs/open.c (ffff80001037cdfc)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffff800010380d5c)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffff8000103cef34)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffff800010428748)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffff8000109217a4)
Location: include/linux/fs.h:2901
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
In fs/open.c (c0567b00)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c056b158)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (c05aa1dc)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (c05f1474)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (c0a06ffc)
Location: include/linux/fs.h:2901
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
In fs/open.c (c00000000047222c)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (c000000000476b08)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (c0000000004d08a4)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (c000000000538a00)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (c0000000009c671c)
Location: include/linux/fs.h:2901
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
In fs/open.c (ffffffe00025332e)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffe0002563c2)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffe00028b0b0)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffe0002c69ac)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffe0005a055c)
Location: include/linux/fs.h:2901
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
In fs/open.c (ffffffff812cffee)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d3875)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff8130fe70)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff8135a716)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816f13e6)
Location: include/linux/fs.h:2901
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
In fs/open.c (ffffffff812c0c6e)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812c44f5)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff81300a80)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff8134b3c0)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff816cb4e6)
Location: include/linux/fs.h:2901
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
In fs/open.c (ffffffff812cddfe)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812d1685)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff8130dc60)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff813581e6)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff8171eac6)
Location: include/linux/fs.h:2901
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
In fs/open.c (ffffffff812dec0e)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/open.c:vfs_fallocate
```
```
In fs/read_write.c (ffffffff812e24b5)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_clone_file_range
  - fs/read_write.c:vfs_copy_file_range
  - fs/read_write.c:do_sendfile
  - fs/read_write.c:compat_writev
  - fs/read_write.c:vfs_writev
```
```
In fs/splice.c (ffffffff8131f460)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/splice.c:do_splice
```
```
In fs/coredump.c (ffffffff8136b918)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In drivers/block/loop.c (ffffffff81739ef6)
Location: include/linux/fs.h:2901
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_write_bvec
```
</details>
</li>
</ul>

## Differences
