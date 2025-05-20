# Function: <code>ext4_clear_io_unwritten_flag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8129f620)
Location: fs/ext4/page-io.c:143
Inline: True
Direct callers:
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
  - fs/ext4/page-io.c:ext4_put_io_end
```
**Symbols:**

```
ffffffff8129f620-ffffffff8129f671: ext4_clear_io_unwritten_flag.isra.3 (STB_LOCAL)
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
In fs/ext4/inode.c (ffffffff812c3d43)
Location: fs/ext4/ext4.h:3266
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff812ce5f9)
Location: fs/ext4/ext4.h:3266
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff812d93f3)
Location: fs/ext4/ext4.h:3244
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff812e43e9)
Location: fs/ext4/ext4.h:3244
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff812fd326)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff8131e0b9)
Location: fs/ext4/ext4.h:3260
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff81321c06)
Location: fs/ext4/ext4.h:3221
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813426c9)
Location: fs/ext4/ext4.h:3221
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff8134fc73)
Location: fs/ext4/ext4.h:3212
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff81370551)
Location: fs/ext4/ext4.h:3212
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff81367e63)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813889e1)
Location: fs/ext4/ext4.h:3236
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff81391145)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813b2ac4)
Location: fs/ext4/ext4.h:3323
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff813a9b75)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813cbb24)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81417c8b)
Location: fs/ext4/ext4.h:3503
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff8142b78b)
Location: fs/ext4/ext4.h:3702
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff814323ab)
Location: fs/ext4/ext4.h:3767
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81485c43)
Location: fs/ext4/ext4.h:3849
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81509195)
Location: fs/ext4/ext4.h:3814
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815a3d35)
Location: fs/ext4/ext4.h:3825
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff815da7b5)
Location: fs/ext4/ext4.h:3797
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/page-io.c (ffffffff81612f75)
Location: fs/ext4/ext4.h:3813
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffff80001047eea8)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffff8000104a3c34)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (c063ea20)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (c0665b28)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (c0000000005a2040)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (c0000000005d0d08)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffe0003074b0)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffe00032520e)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff813a2155)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813c4104)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff81392be5)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813b4b84)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff8139f9b5)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813c1594)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
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
In fs/ext4/inode.c (ffffffff813b4595)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_end_io_dio
```
```
In fs/ext4/page-io.c (ffffffff813d66f4)
Location: fs/ext4/ext4.h:3393
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_put_io_end
  - fs/ext4/page-io.c:ext4_end_io_rsv_work
```
</details>
</li>
</ul>

## Differences
