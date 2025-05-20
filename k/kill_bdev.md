# Function: <code>kill_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247340)
Location: fs/block_dev.c:74
Inline: False
Direct callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:__blkdev_put
  - drivers/block/brd.c:brd_ioctl
```
**Symbols:**

```
ffffffff81247340-ffffffff81247372: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126fc00)
Location: fs/block_dev.c:87
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/brd.c:brd_ioctl
```
**Symbols:**

```
ffffffff8126fc00-ffffffff8126fc32: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81282e00)
Location: fs/block_dev.c:89
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff81282e00-ffffffff81282e32: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81290770)
Location: fs/block_dev.c:90
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff81290770-ffffffff812907a2: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b3430)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff812b3430-ffffffff812b3462: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db130)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff812db130-ffffffff812db162: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f0680)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff812f0680-ffffffff812f06b2: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81312000)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff81312000-ffffffff81312036: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81324f60)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff81324f60-ffffffff81324f96: kill_bdev (STB_GLOBAL)
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
In fs/block_dev.c (ffffffff813606b4)
Location: fs/block_dev.c:78
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
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
In fs/block_dev.c (ffffffff8136dc1f)
Location: fs/block_dev.c:78
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
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
In fs/block_dev.c (ffffffff81374558)
Location: fs/block_dev.c:78
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
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
In block/bdev.c (ffffffff815c42a6)
Location: block/bdev.c:69
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
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
In block/bdev.c (ffffffff8166ebd6)
Location: block/bdev.c:69
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
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
In block/bdev.c (ffffffff81729ec3)
Location: block/bdev.c:68
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
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
In block/bdev.c (ffffffff81766233)
Location: block/bdev.c:68
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
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
In block/bdev.c (ffffffff817a7cf3)
Location: block/bdev.c:71
Inline: True
Inline callers:
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:set_blocksize
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df4e0)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffff8000103df4e0-ffff8000103df52c: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b780c)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
c05b780c-c05b7858: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4280)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
c0000000004e4280-c0000000004e42ec: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296356)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffe000296356-ffffffe000296396: kill_bdev (STB_GLOBAL)
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
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d540)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff8131d540-ffffffff8131d576: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e0e0)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff8130e0e0-ffffffff8130e116: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b010)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff8131b010-ffffffff8131b046: kill_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kill_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ccb0)
Location: fs/block_dev.c:78
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:set_blocksize
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
```
**Symbols:**

```
ffffffff8132ccb0-ffffffff8132cce6: kill_bdev (STB_GLOBAL)
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
