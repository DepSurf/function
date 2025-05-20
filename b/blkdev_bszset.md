# Function: <code>blkdev_bszset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff813c8fa9)
Location: block/ioctl.c:469
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8140d20b)
Location: block/ioctl.c:469
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814288dc)
Location: block/ioctl.c:478
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81436b83)
Location: block/ioctl.c:478
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8146291c)
Location: block/ioctl.c:485
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8149655f)
Location: block/ioctl.c:485
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814b0011)
Location: block/ioctl.c:485
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814de70a)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814f7b49)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, fmode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff81557bb0)
Location: block/ioctl.c:465
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff81557bb0-ffffffff81557c6c: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, fmode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff815741a0)
Location: block/ioctl.c:425
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff815741a0-ffffffff8157426c: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, fmode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8157c230)
Location: block/ioctl.c:427
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8157c230-ffffffff8157c2fc: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, fmode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff815e1790)
Location: block/ioctl.c:440
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff815e1790-ffffffff815e185c: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, fmode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff816903e0)
Location: block/ioctl.c:442
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff816903e0-ffffffff816904b0: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, fmode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8174ef90)
Location: block/ioctl.c:442
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8174ef90-ffffffff8174f060: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, blk_mode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff8178b120)
Location: block/ioctl.c:459
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff8178b120-ffffffff8178b1f3: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkdev_bszset(struct block_device *bdev, blk_mode_t mode, int *argp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff817cd880)
Location: block/ioctl.c:468
Inline: False
Direct callers:
  - block/ioctl.c:compat_blkdev_ioctl
  - block/ioctl.c:blkdev_ioctl
```
**Symbols:**

```
ffffffff817cd880-ffffffff817cd951: blkdev_bszset (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffff8000105f87c8)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c07a3b34)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (c00000000079127c)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffe00043544e)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814f0129)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814e0669)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff814ec1b9)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/ioctl.c (ffffffff815051c9)
Location: block/ioctl.c:486
Inline: True
Inline callers:
  - block/ioctl.c:blkdev_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
