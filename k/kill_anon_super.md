# Function: <code>kill_anon_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8120ec50)
Location: fs/super.c:925
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff8120ec50-ffffffff8120ec6c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812356bd)
Location: fs/super.c:939
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81235680-ffffffff8123569c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8124825d)
Location: fs/super.c:985
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81248220-ffffffff8124823c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81253a7d)
Location: fs/super.c:988
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81253a40-ffffffff81253a5c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81275afd)
Location: fs/super.c:988
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81275ac0-ffffffff81275adc: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8129cb8d)
Location: fs/super.c:1043
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff8129cb50-ffffffff8129cb6c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812b1d10)
Location: fs/super.c:1030
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff812b1d10-ffffffff812b1d39: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812ceaa0)
Location: fs/super.c:1099
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff812ceaa0-ffffffff812ceac9: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e0520)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff812e0520-ffffffff812e0549: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8131727d)
Location: fs/super.c:1105
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff813171e0-ffffffff8131720c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8132278d)
Location: fs/super.c:1052
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff813226f0-ffffffff8132271c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813286fd)
Location: fs/super.c:1054
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81328660-ffffffff8132868c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81375ccd)
Location: fs/super.c:1054
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff81375c30-ffffffff81375c5c: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f461d)
Location: fs/super.c:1053
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff813f4180-ffffffff813f41b4: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147d6dd)
Location: fs/super.c:1096
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff8147d200-ffffffff8147d234: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b248d)
Location: fs/super.c:1107
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff814b1fd0-ffffffff814b2004: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e400d)
Location: fs/super.c:1222
Inline: True
Inline callers:
  - fs/super.c:kill_litter_super
Direct callers:
  - fs/proc/root.c:proc_kill_sb
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff814e3bd0-ffffffff814e3c18: kill_anon_super (STB_GLOBAL)
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
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff8000103881a0)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffff8000103881a0-ffff8000103881e0: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c056ee08)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
c056ee08-c056ee38: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047c3c0)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
c00000000047c3c0-c00000000047c410: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe000259c52)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffe000259c52-ffffffe000259c9a: kill_anon_super (STB_GLOBAL)
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
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d8b00)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff812d8b00-ffffffff812d8b29: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812c9780)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff812c9780-ffffffff812c97a9: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d6910)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff812d6910-ffffffff812d6939: kill_anon_super (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kill_anon_super(struct super_block *sb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e6980)
Location: fs/super.c:1105
Inline: False
Direct callers:
  - fs/super.c:kill_litter_super
  - fs/proc/root.c:proc_kill_sb
  - fs/kernfs/mount.c:kernfs_kill_sb
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_kill_sb_anon
```
**Symbols:**

```
ffffffff812e6980-ffffffff812e69a9: kill_anon_super (STB_GLOBAL)
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
