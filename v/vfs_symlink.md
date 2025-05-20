# Function: <code>vfs_symlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812185f0)
Location: fs/namei.c:3928
Inline: True
Direct callers:
  - fs/namei.c:SyS_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812185f0-ffffffff812186f3: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81240150)
Location: fs/namei.c:4071
Inline: True
Direct callers:
  - fs/namei.c:SyS_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81240150-ffffffff812402b4: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81253a60)
Location: fs/namei.c:4028
Inline: True
Direct callers:
  - fs/namei.c:SyS_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81253a60-ffffffff81253bc4: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125fc70)
Location: fs/namei.c:4093
Inline: True
Direct callers:
  - fs/namei.c:SyS_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff8125fc70-ffffffff8125fde3: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81282350)
Location: fs/namei.c:4089
Inline: True
Direct callers:
  - fs/namei.c:SyS_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81282350-ffffffff812824c9: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9310)
Location: fs/namei.c:4123
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812a9310-ffffffff812a9490: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bee10)
Location: fs/namei.c:4112
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812bee10-ffffffff812bef90: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dba00)
Location: fs/namei.c:4113
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812dba00-ffffffff812dbb81: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ed510)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812ed510-ffffffff812ed691: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81324be0)
Location: fs/namei.c:3939
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81324be0-ffffffff81324dc0: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813303c0)
Location: fs/namei.c:3939
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff813303c0-ffffffff81330580: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81336c60)
Location: fs/namei.c:4157
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81336c60-ffffffff81336e06: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81384650)
Location: fs/namei.c:4235
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81384650-ffffffff8138480a: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81402400)
Location: fs/namei.c:4330
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81402400-ffffffff814024f7: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148c6a0)
Location: fs/namei.c:4386
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff8148c6a0-ffffffff8148c797: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c29b0)
Location: fs/namei.c:4461
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff814c29b0-ffffffff814c2b9f: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f4e70)
Location: fs/namei.c:4468
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/init.c:init_symlink
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff814f4e70-ffffffff814f505f: vfs_symlink (STB_GLOBAL)
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
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010396b40)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffff800010396b40-ffff800010396ccc: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057c164)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
c057c164-c057c31c: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048f2d0)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
c00000000048f2d0-c00000000048f4e4: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000264e7a)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffe000264e7a-ffffffe000264f92: vfs_symlink (STB_GLOBAL)
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
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5af0)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812e5af0-ffffffff812e5c71: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6730)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812d6730-ffffffff812d68b1: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3900)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812e3900-ffffffff812e3a81: vfs_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_symlink(struct inode *dir, struct dentry *dentry, const char *oldname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f39d0)
Location: fs/namei.c:4108
Inline: True
Direct callers:
  - fs/namei.c:do_symlinkat
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff812f39d0-ffffffff812f3b51: vfs_symlink (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
<li>
<b>Param reordered. </b>
<code>dir, dentry, oldname</code> ➡️ <code>mnt_userns, dir, dentry, oldname</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
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
