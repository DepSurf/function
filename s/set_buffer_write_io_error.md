# Function: <code>set_buffer_write_io_error</code>

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
In fs/buffer.c (ffffffff812431d0)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_write_sync
  - fs/buffer.c:end_buffer_async_write
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
In fs/buffer.c (ffffffff8126bed4)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_write_sync
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
In fs/buffer.c (ffffffff8127f244)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_write_sync
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
In fs/buffer.c (ffffffff8128c5df)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812af1ef)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812d6aa5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812ec0e5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff8130d735)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81320705)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
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
In fs/buffer.c (ffffffff8135a3d5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
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
In fs/buffer.c (ffffffff81368575)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
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
In fs/buffer.c (ffffffff8136e865)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
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
In fs/buffer.c (ffffffff813bd5d5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
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
In fs/buffer.c (ffffffff81443655)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/ext4/page-io.c (ffffffff81508896)
Location: include/linux/buffer_head.h:131
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff814d2d45)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/ext4/page-io.c (ffffffff815a3396)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff815095b5)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/ext4/page-io.c (ffffffff815d9c99)
Location: include/linux/buffer_head.h:135
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff8153dec5)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
```
In fs/ext4/page-io.c (ffffffff81612373)
Location: include/linux/buffer_head.h:133
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffff8000103d8e40)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c05b22f8)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (c0000000004ddab8)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffe000291e9c)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81318ce5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813098d5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff813167b5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff81328705)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_write_io_error
```
</details>
</li>
</ul>

## Differences
