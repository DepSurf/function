# Function: <code>call_read_iter</code>

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
In fs/read_write.c (ffffffff8124f9bd)
Location: include/linux/fs.h:1737
Inline: True
```
```
In fs/splice.c (ffffffff812865fb)
Location: include/linux/fs.h:1737
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812a6ef6)
Location: include/linux/fs.h:1737
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In drivers/block/loop.c (ffffffff816088ee)
Location: include/linux/fs.h:1737
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff81271907)
Location: include/linux/fs.h:1767
Inline: True
```
```
In fs/splice.c (ffffffff812a90fb)
Location: include/linux/fs.h:1767
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812ca4f6)
Location: include/linux/fs.h:1767
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In drivers/block/loop.c (ffffffff81670703)
Location: include/linux/fs.h:1767
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff81297772)
Location: include/linux/fs.h:1787
Inline: True
```
```
In fs/splice.c (ffffffff812cfc65)
Location: include/linux/fs.h:1787
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff812f4555)
Location: include/linux/fs.h:1787
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In drivers/block/loop.c (ffffffff816acb62)
Location: include/linux/fs.h:1787
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff812ac446)
Location: include/linux/fs.h:1863
Inline: True
```
```
In fs/splice.c (ffffffff812e5058)
Location: include/linux/fs.h:1863
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81307313)
Location: include/linux/fs.h:1863
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In drivers/block/loop.c (ffffffff816ccebf)
Location: include/linux/fs.h:1863
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff812c8b56)
Location: include/linux/fs.h:1864
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff81303858)
Location: include/linux/fs.h:1864
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813288b3)
Location: include/linux/fs.h:1864
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff8132db23)
Location: include/linux/fs.h:1864
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff8170860d)
Location: include/linux/fs.h:1864
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff812da566)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff813168d8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8133b663)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff81340c68)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff8172c85d)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff813129db)
Location: include/linux/fs.h:1912
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff81350534)
Location: include/linux/fs.h:1912
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81375561)
Location: include/linux/fs.h:1912
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff81382f2c)
Location: include/linux/fs.h:1912
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff817e8e20)
Location: include/linux/fs.h:1912
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
In fs/read_write.c (ffffffff8131e030)
Location: include/linux/fs.h:1895
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff8135d3d7)
Location: include/linux/fs.h:1895
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8138340d)
Location: include/linux/fs.h:1895
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff8138a349)
Location: include/linux/fs.h:1895
Inline: True
```
```
In drivers/block/loop.c (ffffffff817fdd39)
Location: include/linux/fs.h:1895
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
In fs/read_write.c (ffffffff81323a70)
Location: include/linux/fs.h:2105
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff81363e37)
Location: include/linux/fs.h:2105
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8138a4ac)
Location: include/linux/fs.h:2105
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff81390ee9)
Location: include/linux/fs.h:2105
Inline: True
```
```
In drivers/block/loop.c (ffffffff817e2499)
Location: include/linux/fs.h:2105
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
In fs/read_write.c (ffffffff81371670)
Location: include/linux/fs.h:2156
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff813b266a)
Location: include/linux/fs.h:2156
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813d77bc)
Location: include/linux/fs.h:2156
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff813ebac5)
Location: include/linux/fs.h:2156
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff8186e881)
Location: include/linux/fs.h:2156
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
In fs/read_write.c (ffffffff813ef662)
Location: include/linux/fs.h:2049
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (ffffffff81437691)
Location: include/linux/fs.h:2049
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff8146147e)
Location: include/linux/fs.h:2049
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In io_uring/io_uring.c (ffffffff816d782b)
Location: include/linux/fs.h:2049
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_read
  - io_uring/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff819b717e)
Location: include/linux/fs.h:2049
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
In fs/read_write.c (ffffffff81477c02)
Location: include/linux/fs.h:2180
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_read
```
```
In fs/splice.c (ffffffff814c5747)
Location: include/linux/fs.h:2180
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff814f142e)
Location: include/linux/fs.h:2180
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In io_uring/rw.c (ffffffff817a437d)
Location: include/linux/fs.h:2180
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
```
```
In drivers/block/loop.c (ffffffff81b2c3d5)
Location: include/linux/fs.h:2180
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
In fs/read_write.c (ffffffff814ac127)
Location: include/linux/fs.h:1868
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_read
```
```
In fs/splice.c (ffffffff814fa87f)
Location: include/linux/fs.h:1868
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff815289c1)
Location: include/linux/fs.h:1868
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In io_uring/rw.c (ffffffff817e5380)
Location: include/linux/fs.h:1868
Inline: True
Inline callers:
  - io_uring/rw.c:io_read
  - io_uring/rw.c:io_read
```
```
In drivers/block/loop.c (ffffffff81b7c66b)
Location: include/linux/fs.h:1868
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
In fs/read_write.c (ffffffff814ddaf5)
Location: include/linux/fs.h:2078
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_read
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_read
```
```
In fs/splice.c (ffffffff8152f288)
Location: include/linux/fs.h:2078
Inline: True
Inline callers:
  - fs/splice.c:copy_splice_read
```
```
In fs/aio.c (ffffffff8155dad1)
Location: include/linux/fs.h:2078
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In io_uring/rw.c (ffffffff818289bd)
Location: include/linux/fs.h:2078
Inline: True
Inline callers:
  - io_uring/rw.c:__io_read
  - io_uring/rw.c:__io_read
```
```
In drivers/block/loop.c (ffffffff81bd059b)
Location: include/linux/fs.h:2078
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
In fs/read_write.c (ffff80001037f8b0)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffff8000103cd22c)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffff8000103fa3f8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffff800010400c64)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffff8000109226d0)
Location: include/linux/fs.h:1897
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
In fs/read_write.c (c0569eb4)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (c05a8de4)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c05cefcc)
Location: include/linux/fs.h:1897
Inline: True
```
```
In fs/io_uring.c (c05d2b30)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (c0a08874)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (c00000000047597c)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_read
```
```
In fs/splice.c (c0000000004cefd8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (c000000000503ad0)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (c00000000050a6d4)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (c0000000009c7fec)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffe000255566)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffe00028a60c)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffe0002a9e96)
Location: include/linux/fs.h:1897
Inline: True
```
```
In fs/io_uring.c (ffffffe0002ad24c)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffe0005a14ae)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff812d2b46)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130eeb8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81333c43)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff81339248)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff816f263d)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff812c37c6)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff812ffac8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff813248b3)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff81329f78)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff816cc73d)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff812d0956)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8130cca8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81331713)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff81336d18)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff8171fd1d)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
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
In fs/read_write.c (ffffffff812e1786)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/splice.c (ffffffff8131e4b8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/splice.c:generic_file_splice_read
```
```
In fs/aio.c (ffffffff81344303)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/aio.c:aio_read
```
```
In fs/io_uring.c (ffffffff81349dd8)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - fs/io_uring.c:io_read
```
```
In drivers/block/loop.c (ffffffff8173b0dd)
Location: include/linux/fs.h:1897
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
```
</details>
</li>
</ul>

## Differences
