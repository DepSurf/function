# Function: <code>freeze_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120ee60)
Location: fs/super.c:1337
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff8120ee60-ffffffff8120efe5: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235890)
Location: fs/super.c:1357
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81235890-ffffffff81235a15: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81248440)
Location: fs/super.c:1412
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81248440-ffffffff812485dd: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81253d40)
Location: fs/super.c:1454
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81253d40-ffffffff81253edd: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275e50)
Location: fs/super.c:1454
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81275e50-ffffffff81275ff0: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1517
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff8129e3a8-ffffffff8129e407: freeze_super.cold.22 (STB_LOCAL)
ffffffff8129c670-ffffffff8129c7ba: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1503
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff812b337b-ffffffff812b33da: freeze_super.cold.23 (STB_LOCAL)
ffffffff812b17b0-ffffffff812b18fa: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1659
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff812cffef-ffffffff812d0050: freeze_super.cold (STB_LOCAL)
ffffffff812ce4f0-ffffffff812ce64d: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff812e1ba0-ffffffff812e1c01: freeze_super.cold (STB_LOCAL)
ffffffff812dffa0-ffffffff812e00fd: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1758
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81318ea4-ffffffff81318eed: freeze_super.cold (STB_LOCAL)
ffffffff813178b0-ffffffff813179e6: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1658
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81bea570-ffffffff81bea5b9: freeze_super.cold (STB_LOCAL)
ffffffff81322b10-ffffffff81322c46: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1660
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81bdc5ac-ffffffff81bdc5f5: freeze_super.cold (STB_LOCAL)
ffffffff81328bd0-ffffffff81328d06: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1658
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81cc38a4-ffffffff81cc38f2: freeze_super.cold (STB_LOCAL)
ffffffff813761a0-ffffffff8137633e: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1658
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81e75fef-ffffffff81e76038: freeze_super.cold (STB_LOCAL)
ffffffff813f5180-ffffffff813f52ff: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147e380)
Location: fs/super.c:1663
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff8147e380-ffffffff8147e541: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b3310)
Location: fs/super.c:1680
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff814b3310-ffffffff814b349a: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb, enum freeze_holder who);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff814e59b7)
Location: fs/super.c:2021
Inline: True
Inline callers:
  - fs/super.c:fs_bdev_freeze
Direct callers:
  - fs/super.c:fs_bdev_freeze
  - fs/ioctl.c:do_vfs_ioctl
```
**Symbols:**

```
ffffffff814e5470-ffffffff814e58d6: freeze_super.part.0 (STB_LOCAL)
ffffffff814e58f0-ffffffff814e5938: freeze_super (STB_GLOBAL)
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
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386d20)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffff800010386d20-ffff800010386ec4: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056f524)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
c056f524-c056f6b8: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047cd30)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
c00000000047cd30-c00000000047cf8c: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259524)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffe000259524-ffffffe000259662: freeze_super (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff812da180-ffffffff812da1e1: freeze_super.cold (STB_LOCAL)
ffffffff812d8580-ffffffff812d86dd: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff812cae00-ffffffff812cae61: freeze_super.cold (STB_LOCAL)
ffffffff812c9200-ffffffff812c935d: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff812d7f90-ffffffff812d7ff1: freeze_super.cold (STB_LOCAL)
ffffffff812d6390-ffffffff812d64ed: freeze_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int freeze_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/super.c (0)
Location: fs/super.c:1760
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/block_dev.c:freeze_bdev
```
**Symbols:**

```
ffffffff812e8de8-ffffffff812e8e49: freeze_super.cold (STB_LOCAL)
ffffffff812e6f00-ffffffff812e705d: freeze_super (STB_GLOBAL)
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
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum freeze_holder who</code>
</li>
</ul>
</details>
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
