# Function: <code>inode_dio_end</code>

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
In fs/direct-io.c (ffffffff81249a29)
Location: include/linux/fs.h:2747
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/dax.c (ffffffff8125e8b7)
Location: include/linux/fs.h:2747
Inline: True
Inline callers:
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/inode.c (ffffffff81298650)
Location: include/linux/fs.h:2747
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
```
```
In fs/ext4/indirect.c (ffffffff812d9b7e)
Location: include/linux/fs.h:2747
Inline: True
Inline callers:
  - fs/ext4/indirect.c:ext4_ind_direct_IO
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
In fs/direct-io.c (ffffffff812723da)
Location: include/linux/fs.h:2893
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/dax.c (ffffffff812870a7)
Location: include/linux/fs.h:2893
Inline: True
Inline callers:
  - fs/dax.c:dax_do_io
```
```
In fs/ext4/inode.c (ffffffff812cbe16)
Location: include/linux/fs.h:2893
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO
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
In fs/direct-io.c (ffffffff81285f50)
Location: include/linux/fs.h:2859
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff812b1036)
Location: include/linux/fs.h:2859
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff812e1ada)
Location: include/linux/fs.h:2859
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
In fs/direct-io.c (ffffffff812935b0)
Location: include/linux/fs.h:2987
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff812be3fb)
Location: include/linux/fs.h:2987
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff81305f23)
Location: include/linux/fs.h:2987
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
In fs/direct-io.c (ffffffff812b6494)
Location: include/linux/fs.h:3049
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff812e1d6a)
Location: include/linux/fs.h:3049
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff8132aa79)
Location: include/linux/fs.h:3049
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
In fs/direct-io.c (ffffffff812df328)
Location: include/linux/fs.h:3070
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff8130e4fc)
Location: include/linux/fs.h:3070
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff81358fe9)
Location: include/linux/fs.h:3070
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
In fs/direct-io.c (ffffffff812f3e0a)
Location: include/linux/fs.h:3145
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap.c (ffffffff81323d2c)
Location: include/linux/fs.h:3145
Inline: True
Inline callers:
  - fs/iomap.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff8137106e)
Location: include/linux/fs.h:3145
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
In fs/direct-io.c (ffffffff8131578f)
Location: include/linux/fs.h:3156
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8134d017)
Location: include/linux/fs.h:3156
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff8139a473)
Location: include/linux/fs.h:3156
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
In fs/direct-io.c (ffffffff8132860f)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff813652ce)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff813b2f33)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (ffffffff81361dbf)
Location: include/linux/fs.h:3274
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff813ad35e)
Location: include/linux/fs.h:3274
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffffffff8136f0af)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff813be343)
Location: include/linux/fs.h:3074
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffffffff8137595f)
Location: include/linux/fs.h:3327
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff813c5383)
Location: include/linux/fs.h:3327
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffffffff813c1caf)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81415123)
Location: include/linux/fs.h:3308
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffffffff81448b20)
Location: include/linux/fs.h:3088
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8148c760)
Location: include/linux/fs.h:3088
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffffffff814d74bc)
Location: include/linux/fs.h:3242
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81520ec0)
Location: include/linux/fs.h:3242
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffffffff81510496)
Location: include/linux/fs.h:2862
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff81558ecd)
Location: include/linux/fs.h:2862
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffffffff81544936)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8158f60d)
Location: include/linux/fs.h:3143
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
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
In fs/direct-io.c (ffff8000103e3a88)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffff80001042cfac)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffff8000104877a8)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (c05bb828)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (c05f5e44)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (c06499e8)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (c0000000004e9970)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (c00000000053d4f8)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (c0000000005adc30)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (ffffffe0002999b6)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffe0002c96b6)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffe00030f720)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (ffffffff81320bef)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8135d8ae)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff813ab513)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (ffffffff8131178f)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8134e54e)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff8139bfa3)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (ffffffff8131e6bf)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8135b37e)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff813a8d73)
Location: include/linux/fs.h:3218
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
In fs/direct-io.c (ffffffff813303bf)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/direct-io.c:dio_complete
```
```
In fs/iomap/direct-io.c (ffffffff8136eace)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:iomap_dio_complete
```
```
In fs/ext4/inode.c (ffffffff813bd623)
Location: include/linux/fs.h:3218
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_direct_IO_write
```
</details>
</li>
</ul>

## Differences
