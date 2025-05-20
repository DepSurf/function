# Function: <code>vfs_rename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81219750)
Location: fs/namei.c:4186
Inline: False
Direct callers:
  - fs/namei.c:SyS_renameat
  - fs/namei.c:SyS_rename
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff81219750-ffffffff81219f86: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812413a0)
Location: fs/namei.c:4336
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812413a0-ffffffff81241cf7: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81254250)
Location: fs/namei.c:4293
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff81254250-ffffffff81254bdc: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125ffb0)
Location: fs/namei.c:4359
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff8125ffb0-ffffffff812608fb: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81282690)
Location: fs/namei.c:4355
Inline: False
Direct callers:
  - fs/namei.c:SyS_rename
  - fs/namei.c:SyS_renameat
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff81282690-ffffffff81282fe7: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ab2c0)
Location: fs/namei.c:4401
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812ab2c0-ffffffff812abc15: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bded0)
Location: fs/namei.c:4390
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812bded0-ffffffff812be821: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812daab0)
Location: fs/namei.c:4391
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812daab0-ffffffff812db45f: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ec5c0)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812ec5c0-ffffffff812ecf6f: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813264e0)
Location: fs/namei.c:4217
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff813264e0-ffffffff81326fb1: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81331980)
Location: fs/namei.c:4217
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff81331980-ffffffff813323cc: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_rename(struct renamedata *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813359c0)
Location: fs/namei.c:4448
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff813359c0-ffffffff81336568: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_rename(struct renamedata *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81383500)
Location: fs/namei.c:4531
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff81383500-ffffffff81383f49: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_rename(struct renamedata *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81403f90)
Location: fs/namei.c:4626
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff81403f90-ffffffff81404994: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_rename(struct renamedata *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148e410)
Location: fs/namei.c:4682
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff8148e410-ffffffff8148ee14: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_rename(struct renamedata *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c3b60)
Location: fs/namei.c:4754
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff814c3b60-ffffffff814c4604: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_rename(struct renamedata *rd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f6030)
Location: fs/namei.c:4762
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff814f6030-ffffffff814f6def: vfs_rename (STB_GLOBAL)
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
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010395e28)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffff800010395e28-ffff800010396778: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057b2a4)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
c057b2a4-c057bc04: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048e100)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
c00000000048e100-c00000000048eba0: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000264490)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffe000264490-ffffffe000264b9c: vfs_rename (STB_GLOBAL)
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
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e4ba0)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812e4ba0-ffffffff812e554f: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d57e0)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812d57e0-ffffffff812d618f: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e29b0)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812e29b0-ffffffff812e335f: vfs_rename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_rename(struct inode *old_dir, struct dentry *old_dentry, struct inode *new_dir, struct dentry *new_dentry, struct inode **delegated_inode, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f28f0)
Location: fs/namei.c:4386
Inline: False
Direct callers:
  - fs/namei.c:do_renameat2
  - fs/ecryptfs/inode.c:ecryptfs_rename
```
**Symbols:**

```
ffffffff812f28f0-ffffffff812f329d: vfs_rename (STB_GLOBAL)
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
<code>struct renamedata *rd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *old_dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *old_dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode *new_dir</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry *new_dentry</code>
</li>
<li>
<b>Param removed. </b>
<code>struct inode **delegated_inode</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
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
