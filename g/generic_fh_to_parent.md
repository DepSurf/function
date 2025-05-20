# Function: <code>generic_fh_to_parent</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234620)
Location: fs/libfs.c:901
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff81234620-ffffffff8123465b: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125caa0)
Location: fs/libfs.c:929
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff8125caa0-ffffffff8125cadb: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126fff0)
Location: fs/libfs.c:937
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff8126fff0-ffffffff8127002b: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d6f0)
Location: fs/libfs.c:938
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff8127d6f0-ffffffff8127d72b: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a0190)
Location: fs/libfs.c:938
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff812a0190-ffffffff812a01cd: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6930)
Location: fs/libfs.c:938
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff812c6930-ffffffff812c696e: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dbb30)
Location: fs/libfs.c:938
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff812dbb30-ffffffff812dbb6e: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa1a0)
Location: fs/libfs.c:957
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff812fa1a0-ffffffff812fa1e6: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130bfa0)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff8130bfa0-ffffffff8130bfe6: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345480)
Location: fs/libfs.c:1033
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff81345480-ffffffff813454c6: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813517d0)
Location: fs/libfs.c:1037
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff813517d0-ffffffff81351816: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813584f0)
Location: fs/libfs.c:1040
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff813584f0-ffffffff81358536: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6b30)
Location: fs/libfs.c:1049
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff813a6b30-ffffffff813a6b76: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b790)
Location: fs/libfs.c:1076
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff8142b790-ffffffff8142b801: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8850)
Location: fs/libfs.c:1093
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff814b8850-ffffffff814b88c1: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814eda60)
Location: fs/libfs.c:1088
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff814eda60-ffffffff814edad1: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff815217c0)
Location: fs/libfs.c:1399
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff815217c0-ffffffff81521831: generic_fh_to_parent (STB_GLOBAL)
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
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c0558)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffff8000103c0558-ffff8000103c05ec: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d950)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
c059d950-c059d9ac: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004bfb10)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
c0000000004bfb10-c0000000004bfbb8: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000280cf0)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffe000280cf0-ffffffe000280d52: generic_fh_to_parent (STB_GLOBAL)
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
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81304580)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff81304580-ffffffff813045c6: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f51a0)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff812f51a0-ffffffff812f51e6: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81302370)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff81302370-ffffffff813023b6: generic_fh_to_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *generic_fh_to_parent(struct super_block *sb, struct fid *fid, int fh_len, int fh_type, struct inode * (*get_inode)(struct super_block *, u64, u32));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313990)
Location: fs/libfs.c:997
Inline: False
Direct callers:
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/ext4/super.c:ext4_fh_to_parent
  - fs/fat/nfs.c:fat_fh_to_parent
```
**Symbols:**

```
ffffffff81313990-ffffffff813139d6: generic_fh_to_parent (STB_GLOBAL)
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
