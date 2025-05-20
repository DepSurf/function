# Function: <code>map_bh</code>

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
In fs/ext4/inode.c (ffffffff81297139)
Location: include/linux/buffer_head.h:332
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff812fb68a)
Location: include/linux/buffer_head.h:332
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff812c4762)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff8132f2fd)
Location: include/linux/buffer_head.h:336
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff812d9e12)
Location: include/linux/buffer_head.h:339
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff8134505d)
Location: include/linux/buffer_head.h:339
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff812fdabb)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff81359aa5)
Location: include/linux/buffer_head.h:340
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff8132229b)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff8137e7b5)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff81351559)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff813ad081)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff8136a385)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff813c6432)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff813939d5)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff813f366f)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff813ac375)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff8140d54f)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff813f86a5)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff81459fa8)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffffffff8140a345)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff814762f8)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffffffff81410515)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff8147bd68)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffffffff81465b85)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff814d34e5)
Location: include/linux/buffer_head.h:344
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffffffff814e552d)
Location: include/linux/buffer_head.h:366
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff815608e9)
Location: include/linux/buffer_head.h:366
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffffffff8157ebfd)
Location: include/linux/buffer_head.h:373
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff81603b09)
Location: include/linux/buffer_head.h:373
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffffffff815b298d)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff8163ba29)
Location: include/linux/buffer_head.h:386
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffffffff815eb78d)
Location: include/linux/buffer_head.h:377
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff81674f89)
Location: include/linux/buffer_head.h:377
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:__fat_get_block
  - fs/fat/inode.c:__fat_get_block
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
In fs/ext4/inode.c (ffff800010480780)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffff8000104ecffc)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (c063fe8c)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (c06a9564)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (c0000000005a28ac)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (c000000000629980)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block_bmap
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffe000309866)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffe00035e62a)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff813a4955)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff81405b2f)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff813953e5)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff813f65af)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff813a21b5)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff81402eaf)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
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
In fs/ext4/inode.c (ffffffff813b5635)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
  - fs/ext4/inode.c:_ext4_get_block
```
```
In fs/fat/inode.c (ffffffff81418b0f)
Location: include/linux/buffer_head.h:342
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_get_block
  - fs/fat/inode.c:fat_get_block
```
</details>
</li>
</ul>

## Differences
