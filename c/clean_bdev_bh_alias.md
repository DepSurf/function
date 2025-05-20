# Function: <code>clean_bdev_bh_alias</code>

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
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/buffer.c (ffffffff812823c5)
Location: include/linux/buffer_head.h:173
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81289eae)
Location: include/linux/buffer_head.h:173
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff812da5b0)
Location: include/linux/buffer_head.h:173
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff812e4879)
Location: include/linux/buffer_head.h:173
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
In fs/buffer.c (ffffffff8128fabe)
Location: include/linux/buffer_head.h:174
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81296b75)
Location: include/linux/buffer_head.h:174
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff812fe435)
Location: include/linux/buffer_head.h:174
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff8131e5a6)
Location: include/linux/buffer_head.h:174
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
In fs/buffer.c (ffffffff812b27b0)
Location: include/linux/buffer_head.h:175
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812b9de0)
Location: include/linux/buffer_head.h:175
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff81322c11)
Location: include/linux/buffer_head.h:175
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81342bef)
Location: include/linux/buffer_head.h:175
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
In fs/buffer.c (ffffffff812da650)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812e2963)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff813505a5)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81370937)
Location: include/linux/buffer_head.h:177
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
In fs/buffer.c (ffffffff812efb30)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff812f75c4)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
```
In fs/ext4/inode.c (ffffffff81368910)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_block_write_begin
```
```
In fs/ext4/page-io.c (ffffffff81388dbf)
Location: include/linux/buffer_head.h:177
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
In fs/buffer.c (ffffffff813113c4)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81317bfe)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff813243a4)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8132aa79)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8135e3cb)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff813647b2)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8136bebe)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff813717b4)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff813727ee)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81378a85)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff813c184f)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff813c5431)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8144881c)
Location: include/linux/buffer_head.h:201
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff8144c3d6)
Location: include/linux/buffer_head.h:201
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff814d6b71)
Location: include/linux/buffer_head.h:213
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff814da804)
Location: include/linux/buffer_head.h:213
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8150d11a)
Location: include/linux/buffer_head.h:226
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/mpage.c (ffffffff8150ed30)
Location: include/linux/buffer_head.h:226
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff81541d86)
Location: include/linux/buffer_head.h:217
Inline: True
Inline callers:
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_folio
```
```
In fs/mpage.c (ffffffff815435ec)
Location: include/linux/buffer_head.h:217
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffff8000103dd774)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffff8000103e636c)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (c05b6c2c)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (c05bdd5c)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (c0000000004e3120)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (c0000000004ec498)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffe000295720)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffe00029b574)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8131c984)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81323059)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8130d524)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81313bf9)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8131a454)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81320b29)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
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
In fs/buffer.c (ffffffff8132c138)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/buffer.c:nobh_write_begin
  - fs/buffer.c:__block_write_begin_int
  - fs/buffer.c:__block_write_full_page
```
```
In fs/mpage.c (ffffffff81332849)
Location: include/linux/buffer_head.h:177
Inline: True
Inline callers:
  - fs/mpage.c:__mpage_writepage
```
</details>
</li>
</ul>

## Differences
