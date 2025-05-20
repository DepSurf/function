# Function: <code>inode_dio_begin</code>

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
In fs/direct-io.c (ffffffff8124a38e)
Location: include/linux/fs.h:2735
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff8125e4b5)
Location: include/linux/fs.h:2735
Inline: True
Inline callers:
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/inode.c (ffffffff81298310)
Location: include/linux/fs.h:2735
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/indirect.c (ffffffff812d9ce2)
Location: include/linux/fs.h:2735
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_direct_IO
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
In fs/direct-io.c (ffffffff81272d71)
Location: include/linux/fs.h:2881
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/dax.c (ffffffff81286bf0)
Location: include/linux/fs.h:2881
Inline: True
Inline callers:
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/inode.c (ffffffff812cbdea)
Location: include/linux/fs.h:2881
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff81286873)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812b205b)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff812e1a25)
Location: include/linux/fs.h:2847
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff81293f20)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812bf563)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff81305e93)
Location: include/linux/fs.h:2975
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff812b6e80)
Location: include/linux/fs.h:3037
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff812e300c)
Location: include/linux/fs.h:3037
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff8132a9e9)
Location: include/linux/fs.h:3037
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff812df831)
Location: include/linux/fs.h:3058
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff8130f9cf)
Location: include/linux/fs.h:3058
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff81358ca9)
Location: include/linux/fs.h:3058
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff812f4367)
Location: include/linux/fs.h:3133
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap.c (ffffffff81326945)
Location: include/linux/fs.h:3133
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff81370fd8)
Location: include/linux/fs.h:3133
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff81316a50)
Location: include/linux/fs.h:3144
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134d32d)
Location: include/linux/fs.h:3144
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff8139a3f1)
Location: include/linux/fs.h:3144
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (ffffffff813298ce)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813655d4)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813b2eb1)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (ffffffff813636d5)
Location: include/linux/fs.h:3262
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813ad664)
Location: include/linux/fs.h:3262
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
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
In fs/direct-io.c (ffffffff8137093f)
Location: include/linux/fs.h:3062
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813beb54)
Location: include/linux/fs.h:3062
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
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
In fs/direct-io.c (ffffffff813771cc)
Location: include/linux/fs.h:3315
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff813c57bb)
Location: include/linux/fs.h:3315
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
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
In fs/direct-io.c (ffffffff813c3799)
Location: include/linux/fs.h:3296
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81415c7a)
Location: include/linux/fs.h:3296
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
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
In fs/direct-io.c (ffffffff8144a57e)
Location: include/linux/fs.h:3076
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8148d472)
Location: include/linux/fs.h:3076
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
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
In fs/direct-io.c (ffffffff814d8c7f)
Location: include/linux/fs.h:3230
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff81520a59)
Location: include/linux/fs.h:3230
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
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
In fs/direct-io.c (ffffffff81511b6b)
Location: include/linux/fs.h:2850
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff815588ca)
Location: include/linux/fs.h:2850
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
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
In fs/direct-io.c (ffffffff81546012)
Location: include/linux/fs.h:3131
Inline: True
Inline callers:
  - fs/direct-io.c:__blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8158eff7)
Location: include/linux/fs.h:3131
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
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
In fs/direct-io.c (ffff8000103e4d24)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffff80001042d278)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffff8000104876d4)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (c05bcc04)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c05f6340)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (c064980c)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (c0000000004eb08c)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (c00000000053d8f0)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (c0000000005adbb0)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (ffffffe00029a8e4)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffe0002c98f8)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffe00030f692)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff81321eae)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8135dbb4)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813ab491)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (ffffffff81312a4e)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8134e854)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff8139bf21)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (ffffffff8131f97e)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8135b684)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813a8cf1)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
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
In fs/direct-io.c (ffffffff8133169e)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/direct-io.c:do_blockdev_direct_IO
```
```
In fs/iomap/direct-io.c (ffffffff8136edd4)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_rw
```
```
In fs/ext4/inode.c (ffffffff813bd5a1)
Location: include/linux/fs.h:3206
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
```
</details>
</li>
</ul>

## Differences
