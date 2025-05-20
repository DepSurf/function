# Function: <code>buffer_async_write</code>

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
In fs/buffer.c (ffffffff81244115)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8129f77e)
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
In fs/buffer.c (ffffffff8126d22d)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff812ce914)
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
In fs/buffer.c (ffffffff81280484)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff812e4709)
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
In fs/buffer.c (ffffffff8128ddeb)
Location: include/linux/buffer_head.h:125
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8131e3eb)
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
In fs/buffer.c (ffffffff812b09ec)
Location: include/linux/buffer_head.h:126
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81342a0b)
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
In fs/buffer.c (ffffffff812d881b)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81370883)
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
In fs/buffer.c (ffffffff812edceb)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81388d0c)
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
In fs/buffer.c (ffffffff8130f47f)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813b2e1d)
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
In fs/buffer.c (ffffffff813223df)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813cbe9f)
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
In fs/buffer.c (ffffffff8135c638)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81418047)
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
In fs/buffer.c (ffffffff8136aad0)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8142ba44)
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
In fs/buffer.c (ffffffff813701e4)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff8143265e)
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
In fs/buffer.c (ffffffff813bed64)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff81485f1e)
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
In fs/buffer.c (ffffffff814474cf)
Location: include/linux/buffer_head.h:128
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815094b4)
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
In fs/buffer.c (ffffffff814d6106)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815a458a)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_page
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
In fs/buffer.c (ffffffff8150b55d)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff815daece)
Location: include/linux/buffer_head.h:132
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffffffff81540374)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:__block_write_full_folio
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff816136f2)
Location: include/linux/buffer_head.h:130
Inline: True
Inline callers:
  - fs/ext4/page-io.c:ext4_bio_write_folio
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
In fs/buffer.c (ffff8000103db1c4)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffff8000104a3f28)
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
In fs/buffer.c (c05b4648)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (c0665e08)
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
In fs/buffer.c (c0000000004e0550)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (c0000000005d1098)
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
In fs/buffer.c (ffffffe000293b62)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffe000325474)
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
In fs/buffer.c (ffffffff8131a9bf)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813c447f)
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
In fs/buffer.c (ffffffff8130b55f)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813b4eff)
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
In fs/buffer.c (ffffffff8131848f)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813c190f)
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
In fs/buffer.c (ffffffff8132a0af)
Location: include/linux/buffer_head.h:129
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:__block_write_full_page
  - fs/buffer.c:end_buffer_async_write
  - fs/buffer.c:end_buffer_async_write
```
```
In fs/ext4/page-io.c (ffffffff813d6a6f)
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
