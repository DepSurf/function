# Function: <code>drop_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120f170)
Location: fs/super.c:539
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:__invalidate_device
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff8120f170-ffffffff8120f191: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235ba0)
Location: fs/super.c:553
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff81235ba0-ffffffff81235bc1: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812487b0)
Location: fs/super.c:559
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812487b0-ffffffff812487d1: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812540c0)
Location: fs/super.c:562
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812540c0-ffffffff812540e1: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812761d0)
Location: fs/super.c:562
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:SyS_quotactl
  - fs/quota/quota.c:SyS_quotactl
```
**Symbols:**

```
ffffffff812761d0-ffffffff812761f1: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c7f0)
Location: fs/super.c:572
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff8129c7f0-ffffffff8129c811: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1930)
Location: fs/super.c:576
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812b1930-ffffffff812b1951: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ce680)
Location: fs/super.c:630
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812ce680-ffffffff812ce6a3: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0130)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812e0130-ffffffff812e0153: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81316ee0)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/block_dev.c:check_disk_change
  - fs/block_dev.c:check_disk_size_change
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff81316ee0-ffffffff81316f2a: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81322440)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff81322440-ffffffff8132248a: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813284b0)
Location: fs/super.c:637
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff813284b0-ffffffff813284fa: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81375a80)
Location: fs/super.c:637
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - block/bdev.c:__invalidate_device
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff81375a80-ffffffff81375aca: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f4ce0)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - block/bdev.c:__invalidate_device
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff813f4ce0-ffffffff813f4d2d: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147ddc0)
Location: fs/super.c:679
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - block/bdev.c:__invalidate_device
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff8147ddc0-ffffffff8147de0d: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b435f)
Location: fs/super.c:686
Inline: True
Inline callers:
  - fs/super.c:fs_mark_dead
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
  - block/bdev.c:__invalidate_device
  - block/bdev.c:fsync_bdev
```
**Symbols:**

```
ffffffff814b2b50-ffffffff814b2b9d: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e42d0)
Location: fs/super.c:863
Inline: False
Direct callers:
  - fs/statfs.c:__do_compat_sys_ustat
  - fs/statfs.c:__do_sys_ustat
  - fs/quota/quota.c:__ia32_sys_quotactl
  - fs/quota/quota.c:__x64_sys_quotactl
```
**Symbols:**

```
ffffffff814e42d0-ffffffff814e431d: drop_super (STB_GLOBAL)
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
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010387990)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffff800010387990-ffff8000103879c4: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056f7a4)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c056f7a4-c056f7d0: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047d0e0)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
c00000000047d0e0-c00000000047d128: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259698)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:__do_sys_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffe000259698-ffffffe0002596ce: drop_super (STB_GLOBAL)
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
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d8710)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812d8710-ffffffff812d8733: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9390)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812c9390-ffffffff812c93b3: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6520)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812d6520-ffffffff812d6543: drop_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void drop_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7110)
Location: fs/super.c:636
Inline: False
Direct callers:
  - fs/statfs.c:vfs_ustat
  - fs/block_dev.c:__invalidate_device
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:fsync_bdev
  - fs/quota/quota.c:kernel_quotactl
```
**Symbols:**

```
ffffffff812e7110-ffffffff812e7133: drop_super (STB_GLOBAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
