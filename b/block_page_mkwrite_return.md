# Function: <code>block_page_mkwrite_return</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129f3f1)
Location: include/linux/buffer_head.h:233
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812cda0c)
Location: include/linux/buffer_head.h:237
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e37dc)
Location: include/linux/buffer_head.h:242
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813078d2)
Location: include/linux/buffer_head.h:243
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap.c (ffffffff812e2a7c)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8132c522)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap.c (ffffffff8130f41e)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8135ae46)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap.c (ffffffff8132638e)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81373106)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8134b3dd)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8139c529)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8136368d)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff813b5039)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff813aa50f)
Location: include/linux/buffer_head.h:247
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff814003b1)
Location: include/linux/buffer_head.h:247
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff813bbb5f)
Location: include/linux/buffer_head.h:247
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81412dc4)
Location: include/linux/buffer_head.h:247
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff813c2c4f)
Location: include/linux/buffer_head.h:249
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81419224)
Location: include/linux/buffer_head.h:249
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff81412ed6)
Location: include/linux/buffer_head.h:249
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8146c46a)
Location: include/linux/buffer_head.h:249
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8148aa14)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff814ec1b4)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8151e28a)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff81585f1e)
Location: include/linux/buffer_head.h:282
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff815563f0)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff815bc7eb)
Location: include/linux/buffer_head.h:295
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In fs/iomap/buffered-io.c (ffff80001042a3f0)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffff8000104897f0)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (c05f3244)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (c064bd4c)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (c00000000053ad24)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (c0000000005b0b18)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffe0002c7f2e)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffe000310eb2)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8135bc6d)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff813ad619)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8134c90d)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff8139e0a9)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8135973d)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff813aae79)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
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
In fs/iomap/buffered-io.c (ffffffff8136ce38)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/iomap/buffered-io.c:iomap_page_mkwrite
```
```
In fs/ext4/inode.c (ffffffff813bf7c4)
Location: include/linux/buffer_head.h:245
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_page_mkwrite
```
</details>
</li>
</ul>

## Differences
