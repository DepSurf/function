# Function: <code>blkdev_reread_part</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff813c8900)
Location: block/ioctl.c:185
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff813c8900-ffffffff813c8936: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8140cb60)
Location: block/ioctl.c:185
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff8140cb60-ffffffff8140cb96: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81427e40)
Location: block/ioctl.c:188
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff81427e40-ffffffff81427e76: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81436190)
Location: block/ioctl.c:188
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff81436190-ffffffff814361c6: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81461ec0)
Location: block/ioctl.c:188
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff81461ec0-ffffffff81461ef6: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814957e0)
Location: block/ioctl.c:188
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff814957e0-ffffffff81495816: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814af690)
Location: block/ioctl.c:188
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff814af690-ffffffff814af6c6: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814dda40)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff814dda40-ffffffff814dda78: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814f6ea0)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff814f6ea0-ffffffff814f6ed8: blkdev_reread_part (STB_GLOBAL)
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
In block/ioctl.c (ffffffff81557eed)
Location: block/ioctl.c:93
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff81574773)
Location: block/ioctl.c:84
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff8157c7f6)
Location: block/ioctl.c:84
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
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
In block/ioctl.c (ffffffff815e1c4e)
Location: block/ioctl.c:85
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_common_ioctl
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffff8000105f7700)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffff8000105f7700-ffff8000105f7748: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c07a2de8)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
c07a2de8-c07a2e28: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c00000000078fd90)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
c00000000078fd90-c00000000078fdfc: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffe000434c08)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffe000434c08-ffffffe000434c52: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814ef480)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff814ef480-ffffffff814ef4b8: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814df9c0)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff814df9c0-ffffffff814df9f8: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814eb510)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff814eb510-ffffffff814eb548: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_reread_part(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81504520)
Location: block/ioctl.c:189
Inline: False
Direct callers:
  - block/ioctl.c:blkdev_ioctl
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:loop_reread_partitions
```
**Symbols:**

```
ffffffff81504520-ffffffff81504558: blkdev_reread_part (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
