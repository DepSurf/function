# Function: <code>attach_page_buffers</code>

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
In fs/buffer.c (ffffffff812438fe)
Location: include/linux/buffer_head.h:263
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In drivers/md/bitmap.c (ffffffff8169b92f)
Location: include/linux/buffer_head.h:263
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In fs/buffer.c (ffffffff8126ba22)
Location: include/linux/buffer_head.h:267
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
```
```
In drivers/md/bitmap.c (ffffffff816fca57)
Location: include/linux/buffer_head.h:267
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In fs/buffer.c (ffffffff8127eb62)
Location: include/linux/buffer_head.h:270
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/bitmap.c (ffffffff8172e627)
Location: include/linux/buffer_head.h:270
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In fs/buffer.c (ffffffff8128ca4e)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/bitmap.c (ffffffff81747597)
Location: include/linux/buffer_head.h:271
Inline: True
Inline callers:
  - drivers/md/bitmap.c:read_page
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
In fs/buffer.c (ffffffff812aefa1)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff817b9827)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff812d7473)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff818019d7)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff812ec983)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff8182dbe8)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff8130e12e)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff81870238)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff8132114e)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff818a2038)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
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
In fs/buffer.c (ffff8000103d9474)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffff800010af6fbc)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (c05b219c)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_slow
```
```
In drivers/md/md-bitmap.c (c0bd78e4)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (c0000000004dbb54)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:attach_nobh_buffers
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (c000000000be3040)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffe0002928d6)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffe0006e8ccc)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff8131972e)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff81847eb8)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff8130a2ee)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff8180f518)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff813171fe)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff818974e8)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
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
In fs/buffer.c (ffffffff813285ae)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - fs/buffer.c:create_empty_buffers
  - fs/buffer.c:__getblk_gfp
```
```
In drivers/md/md-bitmap.c (ffffffff818b35c8)
Location: include/linux/buffer_head.h:273
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:read_page
```
</details>
</li>
</ul>

## Differences
