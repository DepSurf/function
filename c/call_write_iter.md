# Function: <code>call_write_iter</code>

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
In fs/read_write.c (ffffffff8124f989)
Location: include/linux/fs.h:1743
Inline: True
```
```
In fs/aio.c (ffffffff812a6db1)
Location: include/linux/fs.h:1743
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In drivers/block/loop.c (ffffffff81608890)
Location: include/linux/fs.h:1743
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
In fs/read_write.c (ffffffff812718cd)
Location: include/linux/fs.h:1773
Inline: True
```
```
In fs/aio.c (ffffffff812ca3b1)
Location: include/linux/fs.h:1773
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In drivers/block/loop.c (ffffffff816705cc)
Location: include/linux/fs.h:1773
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
In fs/read_write.c (ffffffff81297740)
Location: include/linux/fs.h:1793
Inline: True
```
```
In fs/aio.c (ffffffff812f43aa)
Location: include/linux/fs.h:1793
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In drivers/block/loop.c (ffffffff816acc53)
Location: include/linux/fs.h:1793
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
In fs/read_write.c (ffffffff812ac3ff)
Location: include/linux/fs.h:1869
Inline: True
```
```
In fs/aio.c (ffffffff81307494)
Location: include/linux/fs.h:1869
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In drivers/block/loop.c (ffffffff816ccfb0)
Location: include/linux/fs.h:1869
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
In fs/read_write.c (ffffffff812c8b02)
Location: include/linux/fs.h:1870
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81328a37)
Location: include/linux/fs.h:1870
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff8132dd1a)
Location: include/linux/fs.h:1870
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff817084e2)
Location: include/linux/fs.h:1870
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
In fs/read_write.c (ffffffff812da512)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff8133b7e7)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff81340ed0)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff8172c732)
Location: include/linux/fs.h:1903
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
In fs/read_write.c (ffffffff81313163)
Location: include/linux/fs.h:1918
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/aio.c (ffffffff81375315)
Location: include/linux/fs.h:1918
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff81383167)
Location: include/linux/fs.h:1918
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff817e8d8b)
Location: include/linux/fs.h:1918
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
In fs/read_write.c (ffffffff8131ea73)
Location: include/linux/fs.h:1901
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/aio.c (ffffffff81383174)
Location: include/linux/fs.h:1901
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff81397d60)
Location: include/linux/fs.h:1901
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff817fdcdb)
Location: include/linux/fs.h:1901
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
In fs/read_write.c (ffffffff813244b3)
Location: include/linux/fs.h:2111
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/aio.c (ffffffff8138a1f3)
Location: include/linux/fs.h:2111
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff8139d742)
Location: include/linux/fs.h:2111
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff817e243b)
Location: include/linux/fs.h:2111
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
In fs/read_write.c (ffffffff813720d3)
Location: include/linux/fs.h:2162
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/aio.c (ffffffff813d7503)
Location: include/linux/fs.h:2162
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff813ebf4c)
Location: include/linux/fs.h:2162
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff8186e82a)
Location: include/linux/fs.h:2162
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
In fs/read_write.c (ffffffff813f0168)
Location: include/linux/fs.h:2055
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/aio.c (ffffffff81461146)
Location: include/linux/fs.h:2055
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In io_uring/io_uring.c (ffffffff816d7526)
Location: include/linux/fs.h:2055
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff819b70ff)
Location: include/linux/fs.h:2055
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
In fs/read_write.c (ffffffff814784d8)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
```
```
In fs/aio.c (ffffffff814f10d6)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In io_uring/rw.c (ffffffff817a48d1)
Location: include/linux/fs.h:2186
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b2c439)
Location: include/linux/fs.h:2186
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
In fs/read_write.c (ffffffff814acecb)
Location: include/linux/fs.h:1874
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
```
```
In fs/aio.c (ffffffff8152843c)
Location: include/linux/fs.h:1874
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In io_uring/rw.c (ffffffff817e58c4)
Location: include/linux/fs.h:1874
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81b7c6e2)
Location: include/linux/fs.h:1874
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
In fs/read_write.c (ffffffff814df5dd)
Location: include/linux/fs.h:2084
Inline: True
Inline callers:
  - fs/read_write.c:vfs_iocb_iter_write
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:vfs_write
```
```
In fs/splice.c (ffffffff8153083f)
Location: include/linux/fs.h:2084
Inline: True
Inline callers:
  - fs/splice.c:iter_file_splice_write
```
```
In fs/aio.c (ffffffff8155d4bc)
Location: include/linux/fs.h:2084
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In io_uring/rw.c (ffffffff81829ba6)
Location: include/linux/fs.h:2084
Inline: True
Inline callers:
  - io_uring/rw.c:io_write
```
```
In drivers/block/loop.c (ffffffff81bd0612)
Location: include/linux/fs.h:2084
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
In fs/read_write.c (ffff80001037f844)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffff8000103fa57c)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffff800010400e7c)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffff8000109225bc)
Location: include/linux/fs.h:1903
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
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/aio.c (c05cebf8)
Location: include/linux/fs.h:1903
Inline: True
```
```
In fs/io_uring.c (c05d2d5c)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (c0a08868)
Location: include/linux/fs.h:1903
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
In fs/read_write.c (c000000000475a40)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
  - fs/read_write.c:new_sync_write
```
```
In fs/aio.c (c000000000503cd4)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (c00000000050a970)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (c0000000009c7edc)
Location: include/linux/fs.h:1903
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
In fs/read_write.c (ffffffe000255520)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffe0002a9cd6)
Location: include/linux/fs.h:1903
Inline: True
```
```
In fs/io_uring.c (ffffffe0002ad3e0)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffe0005a142c)
Location: include/linux/fs.h:1903
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
In fs/read_write.c (ffffffff812d2af2)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81333dc7)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff813394b0)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff816f2512)
Location: include/linux/fs.h:1903
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
In fs/read_write.c (ffffffff812c3772)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81324a37)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff8132a1e0)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff816cc612)
Location: include/linux/fs.h:1903
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
In fs/read_write.c (ffffffff812d0902)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81331897)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff81336f80)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff8171fbf2)
Location: include/linux/fs.h:1903
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
In fs/read_write.c (ffffffff812e1732)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/read_write.c:do_iter_readv_writev
```
```
In fs/aio.c (ffffffff81344487)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/aio.c:aio_write
```
```
In fs/io_uring.c (ffffffff8134a040)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - fs/io_uring.c:io_write
```
```
In drivers/block/loop.c (ffffffff8173afb2)
Location: include/linux/fs.h:1903
Inline: True
Inline callers:
  - drivers/block/loop.c:lo_rw_aio
```
</details>
</li>
</ul>

## Differences
