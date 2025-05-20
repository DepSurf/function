# Function: <code>freeze_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812475c0)
Location: fs/block_dev.c:221
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff812475c0-ffffffff812476a3: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126fd80)
Location: fs/block_dev.c:239
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8126fd80-ffffffff8126fe48: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81282f80)
Location: fs/block_dev.c:494
Inline: False
Direct callers:
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81282f80-ffffffff81283048: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291c80)
Location: fs/block_dev.c:502
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81291c80-ffffffff81291d4d: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4a00)
Location: fs/block_dev.c:490
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff812b4a00-ffffffff812b4ad0: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db2c0)
Location: fs/block_dev.c:491
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff812db2c0-ffffffff812db395: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f0810)
Location: fs/block_dev.c:528
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff812f0810-ffffffff812f08e5: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81312190)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81312190-ffffffff81312269: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813250e0)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff813250e0-ffffffff813251b9: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81360430)
Location: fs/block_dev.c:532
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81360430-ffffffff8136051c: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136d9c0)
Location: fs/block_dev.c:564
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8136d9c0-ffffffff8136da7c: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813743a0)
Location: fs/block_dev.c:568
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff813743a0-ffffffff8137445c: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c4130)
Location: block/bdev.c:235
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff815c4130-ffffffff815c41ec: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166f1b0)
Location: block/bdev.c:239
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8166f1b0-ffffffff8166f279: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8172a510)
Location: block/bdev.c:238
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8172a510-ffffffff8172a5d9: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81766850)
Location: block/bdev.c:238
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff81766850-ffffffff81766919: freeze_bdev (STB_GLOBAL)
```
</details>
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
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df6b0)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffff8000103df6b0-ffff8000103df798: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b79a4)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
c05b79a4-c05b7a7c: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4500)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
c0000000004e4500-c0000000004e4660: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002964de)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffe0002964de-ffffffe0002965ac: freeze_bdev (STB_GLOBAL)
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
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d6c0)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8131d6c0-ffffffff8131d799: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e260)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8130e260-ffffffff8130e339: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b190)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8131b190-ffffffff8131b269: freeze_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct super_block *freeze_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ce30)
Location: fs/block_dev.c:533
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl
  - drivers/md/dm.c:__dm_suspend
```
**Symbols:**

```
ffffffff8132ce30-ffffffff8132cf09: freeze_bdev (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct super_block *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
