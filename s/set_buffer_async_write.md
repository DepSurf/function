# Function: <code>set_buffer_async_write</code>

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
In fs/buffer.c (ffffffff81242571)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8129fefa)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
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
In fs/buffer.c (ffffffff8126d198)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff812ce7f6)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812803f0)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff812e45d6)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8128dd53)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8131e293)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812b0946)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813428b3)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812d8764)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81370733)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff812edc34)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81388bbf)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8130d67d)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813b2caf)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8132068d)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813cbd1d)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8135c5c1)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81417e66)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8136aa3c)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8142b96b)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81370150)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8143258a)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff813becd8)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81485e4a)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81447454)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81509432)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff814d3001)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815a3ff0)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81509c21)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815daa43)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffffffff8153ea51)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81613250)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffff8000103db2c4)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffff8000104a3eb8)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c05b4590)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (c0665d48)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (c0000000004e0434)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (c0000000005d0fdc)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffe000293a40)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:mark_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffe000325416)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff81318c6d)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813c42fd)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8130985d)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813b4d7d)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8131673d)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813c178d)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8132866d)
Location: include/linux/buffer_head.h:129
Inline: True
```
```
In fs/ext4/page-io.c (ffffffff813d68ed)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
```
</details>
</li>
</ul>

## Differences
