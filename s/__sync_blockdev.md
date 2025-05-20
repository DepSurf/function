# Function: <code>__sync_blockdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812473e5)
Location: fs/block_dev.c:173
Inline: True
Inline callers:
  - fs/block_dev.c:set_blocksize
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:__blkdev_put
```
**Symbols:**

```
ffffffff81249560-ffffffff8124958b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8127106a)
Location: fs/block_dev.c:191
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff81271610-ffffffff8127163b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812849d7)
Location: fs/block_dev.c:446
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81285a40-ffffffff81285a6b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291daf)
Location: fs/block_dev.c:454
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81292db0-ffffffff81292ddc: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4b2f)
Location: fs/block_dev.c:442
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff812b5ba0-ffffffff812b5bcc: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dccc0)
Location: fs/block_dev.c:443
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff812dd800-ffffffff812dd82b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2120)
Location: fs/block_dev.c:480
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff812f2de0-ffffffff812f2e0b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313b60)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81314840-ffffffff8131486b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326a70)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff81327020-ffffffff8132704b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360656)
Location: fs/block_dev.c:484
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff81361780-ffffffff813617b7: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136dbc6)
Location: fs/block_dev.c:516
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff8136e520-ffffffff8136e557: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813744fb)
Location: fs/block_dev.c:520
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:bdev_disk_changed
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
```
**Symbols:**

```
ffffffff81374e30-ffffffff81374e67: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4623)
Location: block/bdev.c:187
Inline: True
Inline callers:
  - block/bdev.c:blkdev_put
  - block/bdev.c:blkdev_flush_mapping
  - block/bdev.c:freeze_bdev
  - block/bdev.c:set_blocksize
Direct callers:
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__ia32_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
  - fs/sync.c:__x64_sys_syncfs
```
**Symbols:**

```
ffffffff815c4810-ffffffff815c4847: __sync_blockdev (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1890)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffff8000103e1d80-ffff8000103e1ddc: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b8ae8)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
c05ba08c-c05ba0c8: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e5638)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
c0000000004e7860-c0000000004e78d8: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000297dd6)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffe000298458-ffffffe0002984b2: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f050)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff8131f600-ffffffff8131f62b: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130fbf0)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff813101a0-ffffffff813101cb: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131cb20)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff8131d0d0-ffffffff8131d0fb: __sync_blockdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __sync_blockdev(struct block_device *bdev, int wait);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132dd23)
Location: fs/block_dev.c:485
Inline: True
Inline callers:
  - fs/block_dev.c:__blkdev_put
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:set_blocksize
Direct callers:
  - fs/sync.c:__sync_filesystem
```
**Symbols:**

```
ffffffff8132edb0-ffffffff8132eddb: __sync_blockdev (STB_GLOBAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
