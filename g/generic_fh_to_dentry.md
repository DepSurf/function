# Function: <code>generic_fh_to_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812345e0)
Location: fs/libfs.c:868
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff812345e0-ffffffff8123461a: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125ca60)
Location: fs/libfs.c:896
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff8125ca60-ffffffff8125ca9a: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126ffb0)
Location: fs/libfs.c:904
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff8126ffb0-ffffffff8126ffea: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d6b0)
Location: fs/libfs.c:905
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff8127d6b0-ffffffff8127d6e4: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a0150)
Location: fs/libfs.c:905
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff812a0150-ffffffff812a0186: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6900)
Location: fs/libfs.c:905
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff812c6900-ffffffff812c692f: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dbb00)
Location: fs/libfs.c:905
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff812dbb00-ffffffff812dbb2f: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa160)
Location: fs/libfs.c:924
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff812fa160-ffffffff812fa195: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130bf60)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff8130bf60-ffffffff8130bf95: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345440)
Location: fs/libfs.c:1000
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff81345440-ffffffff81345475: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351790)
Location: fs/libfs.c:1004
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff81351790-ffffffff813517c5: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813584b0)
Location: fs/libfs.c:1007
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff813584b0-ffffffff813584e5: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6af0)
Location: fs/libfs.c:1016
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff813a6af0-ffffffff813a6b25: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b730)
Location: fs/libfs.c:1043
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff8142b730-ffffffff8142b784: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b87e0)
Location: fs/libfs.c:1060
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff814b87e0-ffffffff814b8834: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ed9f0)
Location: fs/libfs.c:1055
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff814ed9f0-ffffffff814eda44: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521750)
Location: fs/libfs.c:1366
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff81521750-ffffffff815217a4: generic_fh_to_dentry (STB_GLOBAL)
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
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c04d0)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffff8000103c04d0-ffff8000103c0558: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d8f8)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
c059d8f8-c059d950: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004bfa90)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
c0000000004bfa90-c0000000004bfb08: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000280c90)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffe000280c90-ffffffe000280cf0: generic_fh_to_dentry (STB_GLOBAL)
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
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81304540)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff81304540-ffffffff81304575: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f5160)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff812f5160-ffffffff812f5195: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81302330)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff81302330-ffffffff81302365: generic_fh_to_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *generic_fh_to_dentry(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313950)
Location: fs/libfs.c:964
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/super.c:ext4_fh_to_dentry
  - fs/fat/nfs.c:fat_fh_to_dentry
```
**Symbols:**

```
ffffffff81313950-ffffffff81313985: generic_fh_to_dentry (STB_GLOBAL)
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
