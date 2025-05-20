# Function: <code>set_init_blocksize</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f0460)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff812f0460-ffffffff812f04d6: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81311e00)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81311e00-ffffffff81311e76: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81324d60)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81324d60-ffffffff81324dd3: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135e910)
Location: fs/block_dev.c:106
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8135e910-ffffffff8135e983: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff8136d210)
Location: fs/block_dev.c:140
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8136d210-ffffffff8136d272: set_init_blocksize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (ffffffff81373a80)
Location: fs/block_dev.c:139
Inline: True
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff81373a80-ffffffff81373ae2: set_init_blocksize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff815c3de0)
Location: block/bdev.c:130
Inline: True
Direct callers:
  - block/bdev.c:blkdev_get_whole
```
**Symbols:**

```
ffffffff815c3de0-ffffffff815c3e42: set_init_blocksize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff8166e760)
Location: block/bdev.c:126
Inline: True
Direct callers:
  - block/bdev.c:blkdev_get_whole
```
**Symbols:**

```
ffffffff8166e760-ffffffff8166e7cc: set_init_blocksize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff81729a40)
Location: block/bdev.c:125
Inline: True
Direct callers:
  - block/bdev.c:blkdev_get_whole
```
**Symbols:**

```
ffffffff81729a40-ffffffff81729ac1: set_init_blocksize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff81765f00)
Location: block/bdev.c:125
Inline: True
Direct callers:
  - block/bdev.c:blkdev_get_whole
```
**Symbols:**

```
ffffffff81765f00-ffffffff81765f97: set_init_blocksize.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/bdev.c (ffffffff817a7b00)
Location: block/bdev.c:128
Inline: True
Direct callers:
  - block/bdev.c:bdev_open_by_dev
  - block/bdev.c:blkdev_get_whole
```
**Symbols:**

```
ffffffff817a7b00-ffffffff817a7b97: set_init_blocksize.isra.0 (STB_LOCAL)
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
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df258)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffff8000103df258-ffff8000103df2f0: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b9de4)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c05b9de4-c05b9ed0: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e3f60)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
c0000000004e3f60-c0000000004e4010: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002960d8)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffe0002960d8-ffffffe000296150: set_init_blocksize (STB_LOCAL)
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
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d340)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8131d340-ffffffff8131d3b3: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130dee0)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8130dee0-ffffffff8130df53: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131ae10)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8131ae10-ffffffff8131ae83: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_init_blocksize(struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132cab0)
Location: fs/block_dev.c:107
Inline: False
Direct callers:
  - fs/block_dev.c:__blkdev_get
  - fs/block_dev.c:__blkdev_get
```
**Symbols:**

```
ffffffff8132cab0-ffffffff8132cb23: set_init_blocksize (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
