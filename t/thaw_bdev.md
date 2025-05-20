# Function: <code>thaw_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812476b0)
Location: fs/block_dev.c:267
Inline: False
Direct callers:
  - fs/buffer.c:do_thaw_one
```
**Symbols:**

```
ffffffff812476b0-ffffffff8124773c: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8126fe50)
Location: fs/block_dev.c:286
Inline: False
Direct callers:
  - fs/buffer.c:do_thaw_one
```
**Symbols:**

```
ffffffff8126fe50-ffffffff8126fedc: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81283050)
Location: fs/block_dev.c:541
Inline: False
Direct callers:
  - fs/buffer.c:do_thaw_one
```
**Symbols:**

```
ffffffff81283050-ffffffff812830d9: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81290810)
Location: fs/block_dev.c:549
Inline: False
Direct callers:
  - fs/buffer.c:do_thaw_one
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81290810-ffffffff81290899: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b34d0)
Location: fs/block_dev.c:537
Inline: False
Direct callers:
  - fs/buffer.c:do_thaw_one
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff812b34d0-ffffffff812b355c: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db3a0)
Location: fs/block_dev.c:538
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff812db3a0-ffffffff812db42c: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f08f0)
Location: fs/block_dev.c:575
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff812f08f0-ffffffff812f097c: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81312270)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff81312270-ffffffff813122fd: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813251c0)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff813251c0-ffffffff8132524d: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135eb90)
Location: fs/block_dev.c:579
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:free_dev
```
**Symbols:**

```
ffffffff8135eb90-ffffffff8135ec1d: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136c350)
Location: fs/block_dev.c:602
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:__dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:free_dev
```
**Symbols:**

```
ffffffff8136c350-ffffffff8136c3e8: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81372c90)
Location: fs/block_dev.c:606
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:free_dev
```
**Symbols:**

```
ffffffff81372c90-ffffffff81372d28: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff815c3be0)
Location: block/bdev.c:273
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff815c3be0-ffffffff815c3c78: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff8166e550)
Location: block/bdev.c:277
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:dm_internal_resume
  - drivers/md/dm.c:dm_resume
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff8166e550-ffffffff8166e5ee: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81729780)
Location: block/bdev.c:276
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_shutdown
  - drivers/md/dm.c:unlock_fs
```
**Symbols:**

```
ffffffff81729780-ffffffff8172981e: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bdev.c (ffffffff81765af0)
Location: block/bdev.c:276
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_force_shutdown
  - drivers/md/dm.c:unlock_fs
```
**Symbols:**

```
ffffffff81765af0-ffffffff81765b8e: thaw_bdev (STB_GLOBAL)
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
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103df798)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffff8000103df798-ffff8000103df858: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b7a7c)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c05b7a7c-c05b7b2c: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4660)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
c0000000004e4660-c0000000004e4758: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe0002965ac)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffe0002965ac-ffffffe000296638: thaw_bdev (STB_GLOBAL)
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
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d7a0)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8131d7a0-ffffffff8131d82d: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e340)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8130e340-ffffffff8130e3cd: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b270)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8131b270-ffffffff8131b2fd: thaw_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int thaw_bdev(struct block_device *bdev, struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132cf10)
Location: fs/block_dev.c:580
Inline: False
Direct callers:
  - fs/buffer.c:emergency_thaw_bdev
  - fs/ext4/ioctl.c:ext4_ioctl
```
**Symbols:**

```
ffffffff8132cf10-ffffffff8132cf9d: thaw_bdev (STB_GLOBAL)
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
<b>Param removed. </b>
<code>struct super_block *sb</code>
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
