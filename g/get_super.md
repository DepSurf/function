# Function: <code>get_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff8120f310)
Location: fs/super.c:625
Inline: True
Inline callers:
  - fs/super.c:get_super_thawed
Direct callers:
  - fs/super.c:get_super_thawed
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:__invalidate_device
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff8120f310-ffffffff8120f3d5: get_super.part.7 (STB_LOCAL)
ffffffff8120f3e0-ffffffff8120f40c: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/super.c (ffffffff81235e63)
Location: fs/super.c:639
Inline: True
Inline callers:
  - fs/super.c:get_super_thawed
Direct callers:
  - fs/super.c:get_super_thawed
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81235d40-ffffffff81235e10: get_super.part.7 (STB_LOCAL)
ffffffff81235e10-ffffffff81235e3c: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81248a50)
Location: fs/super.c:687
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81248a50-ffffffff81248a7e: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254360)
Location: fs/super.c:690
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81254360-ffffffff8125438e: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81276470)
Location: fs/super.c:690
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81276470-ffffffff8127649e: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129cd20)
Location: fs/super.c:722
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff8129cd20-ffffffff8129cd4e: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1ee0)
Location: fs/super.c:726
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812b1ee0-ffffffff812b1f0e: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cec90)
Location: fs/super.c:780
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812cec90-ffffffff812cecc0: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e06c0)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812e06c0-ffffffff812e06f0: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813174c0)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff813174c0-ffffffff813174f2: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323ba0)
Location: fs/super.c:750
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
```
**Symbols:**

```
ffffffff81323ba0-ffffffff81323c89: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329c60)
Location: fs/super.c:751
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
```
**Symbols:**

```
ffffffff81329c60-ffffffff81329d49: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81377290)
Location: fs/super.c:751
Inline: False
Direct callers:
  - block/bdev.c:__invalidate_device
```
**Symbols:**

```
ffffffff81377290-ffffffff81377379: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6510)
Location: fs/super.c:750
Inline: False
Direct callers:
  - block/bdev.c:__invalidate_device
```
**Symbols:**

```
ffffffff813f6510-ffffffff813f65d9: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147f600)
Location: fs/super.c:793
Inline: False
Direct callers:
  - block/bdev.c:__invalidate_device
```
**Symbols:**

```
ffffffff8147f600-ffffffff8147f6c9: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4250)
Location: fs/super.c:800
Inline: False
Direct callers:
  - fs/super.c:fs_mark_dead
  - block/bdev.c:__invalidate_device
```
**Symbols:**

```
ffffffff814b4250-ffffffff814b4319: get_super (STB_GLOBAL)
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
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010387bb0)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffff800010387bb0-ffff800010387c4c: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056fb44)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c056fb44-c056fb84: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047d800)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c00000000047d800-c00000000047d86c: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259ea0)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffe000259ea0-ffffffe000259eea: get_super (STB_GLOBAL)
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
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d8ca0)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812d8ca0-ffffffff812d8cd0: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9920)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812c9920-ffffffff812c9950: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6ab0)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812d6ab0-ffffffff812d6ae0: get_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct super_block *get_super(struct block_device *bdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7480)
Location: fs/super.c:786
Inline: False
Direct callers:
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812e7480-ffffffff812e74b0: get_super (STB_GLOBAL)
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
