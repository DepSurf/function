# Function: <code>deactivate_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120f2b0)
Location: fs/super.c:333
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/devpts/inode.c:devpts_del_ref
```
**Symbols:**

```
ffffffff8120f2b0-ffffffff8120f30f: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81235ce0)
Location: fs/super.c:337
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - fs/namespace.c:cleanup_mnt
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff81235ce0-ffffffff81235d3d: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812488f0)
Location: fs/super.c:336
Inline: True
Direct callers:
  - kernel/cgroup.c:cgroup_mount
  - kernel/cgroup.c:cgroup_mount
  - fs/namespace.c:cleanup_mnt
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812488f0-ffffffff8124894d: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81254200)
Location: fs/super.c:335
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - fs/namespace.c:cleanup_mnt
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff81254200-ffffffff81254252: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81276310)
Location: fs/super.c:339
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - fs/namespace.c:cleanup_mnt
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff81276310-ffffffff81276363: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129c4a0)
Location: fs/super.c:353
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - fs/namespace.c:cleanup_mnt
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff8129c4a0-ffffffff8129c4f3: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b15e0)
Location: fs/super.c:357
Inline: True
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - kernel/cgroup/cgroup-v1.c:cgroup1_mount
  - fs/namespace.c:cleanup_mnt
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812b15e0-ffffffff812b1633: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ce330)
Location: fs/super.c:358
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812ce330-ffffffff812ce372: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812dfde0)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812dfde0-ffffffff812dfe22: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81317720)
Location: fs/super.c:362
Inline: False
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff81317720-ffffffff81317766: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81322980)
Location: fs/super.c:362
Inline: False
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff81322980-ffffffff813229c6: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81328a40)
Location: fs/super.c:362
Inline: False
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff81328a40-ffffffff81328a86: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81376010)
Location: fs/super.c:362
Inline: False
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff81376010-ffffffff81376056: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f4fc0)
Location: fs/super.c:359
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff813f4fc0-ffffffff813f5016: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147e160)
Location: fs/super.c:359
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff8147e160-ffffffff8147e1b6: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b3110)
Location: fs/super.c:357
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
  - block/bdev.c:freeze_bdev
```
**Symbols:**

```
ffffffff814b3110-ffffffff814b3166: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e4b80)
Location: fs/super.c:501
Inline: True
Direct callers:
  - fs/super.c:fs_bdev_thaw
  - fs/super.c:fs_bdev_freeze
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff814e4b80-ffffffff814e4bd6: deactivate_super (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010386ae8)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffff800010386ae8-ffff800010386b74: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c056fe10)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
c056fe10-c056fe7c: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047d590)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
c00000000047d590-c00000000047d610: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259360)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffe000259360-ffffffe0002593c6: deactivate_super (STB_GLOBAL)
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
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d83c0)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812d83c0-ffffffff812d8402: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9040)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812c9040-ffffffff812c9082: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d61d0)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812d61d0-ffffffff812d6212: deactivate_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void deactivate_super(struct super_block *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e7350)
Location: fs/super.c:362
Inline: True
Direct callers:
  - fs/namespace.c:cleanup_mnt
  - fs/fs_context.c:put_fs_context
  - fs/block_dev.c:freeze_bdev
  - fs/block_dev.c:freeze_bdev
  - fs/proc/proc_sysctl.c:drop_sysctl_table
  - fs/devpts/inode.c:devpts_release
```
**Symbols:**

```
ffffffff812e7350-ffffffff812e7392: deactivate_super (STB_GLOBAL)
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
