# Function: <code>clear_buffer_async_write</code>

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
In fs/buffer.c (ffffffff81244169)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8129f756)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_finish_bio
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8126be4d)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff812ceb81)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff8127f1bd)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff812e4983)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff8128cb5d)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8131e643)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff812af5fd)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81342c8c)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff812d6d44)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81370ae4)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff812ec4c4)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81388f78)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff8130dc44)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813b3094)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff81320c24)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813cc10e)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff8135af95)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81418219)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff81368f55)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8142bccc)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff8136f495)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81432998)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff813be095)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81486260)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff814450fd)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815098e6)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff814d4334)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815a4591)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8150aa68)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815daed5)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffffffff8153f8d8)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff816136f9)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffff8000103da604)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffff8000104a4318)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (c05b2cf8)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (c0666114)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (c0000000004de278)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (c0000000005d1190)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffe000291fce)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffe00032572e)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff81319204)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813c46ee)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff81309d67)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813b516e)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff81316cd4)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813c1b7e)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
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
In fs/buffer.c (ffffffff81328d0b)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813d6cf7)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
  - fs/ext4/page-io.c:ext4_finish_bio
```
</details>
</li>
</ul>

## Differences
