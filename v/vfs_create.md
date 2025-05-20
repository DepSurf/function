# Function: <code>vfs_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218380)
Location: fs/namei.c:2650
Inline: True
Direct callers:
  - fs/namei.c:path_openat
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_create
  - ipc/mqueue.c:do_create
```
**Symbols:**

```
ffffffff81218380-ffffffff8121849f: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123ffb0)
Location: fs/namei.c:2871
Inline: True
Direct callers:
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_create
  - ipc/mqueue.c:do_create
```
**Symbols:**

```
ffffffff8123ffb0-ffffffff81240144: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812538c0)
Location: fs/namei.c:2835
Inline: True
Direct callers:
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_create
  - ipc/mqueue.c:do_create
```
**Symbols:**

```
ffffffff812538c0-ffffffff81253a54: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125fad0)
Location: fs/namei.c:2880
Inline: True
Direct callers:
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_create
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff8125fad0-ffffffff8125fc6b: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812821a0)
Location: fs/namei.c:2878
Inline: True
Direct callers:
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_create
  - ipc/mqueue.c:do_mq_open
```
**Symbols:**

```
ffffffff812821a0-ffffffff81282341: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9490)
Location: fs/namei.c:2879
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812a9490-ffffffff812a9634: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bec60)
Location: fs/namei.c:2898
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812bec60-ffffffff812bee04: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812db870)
Location: fs/namei.c:2896
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812db870-ffffffff812db9f7: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ed380)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812ed380-ffffffff812ed507: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81324dc0)
Location: fs/namei.c:2791
Inline: True
```
**Symbols:**

```
ffffffff81324dc0-ffffffff81324fb4: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81330580)
Location: fs/namei.c:2789
Inline: True
```
**Symbols:**

```
ffffffff81330580-ffffffff81330759: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81336e10)
Location: fs/namei.c:2898
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81336e10-ffffffff81336fce: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81384810)
Location: fs/namei.c:2967
Inline: True
Direct callers:
  - fs/namei.c:do_mknodat
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81384810-ffffffff813849e2: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81402010)
Location: fs/namei.c:3063
Inline: True
Direct callers:
  - fs/open.c:dentry_create
  - fs/namei.c:do_mknodat
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff81402010-ffffffff81402121: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148c1c0)
Location: fs/namei.c:3101
Inline: True
Direct callers:
  - fs/open.c:dentry_create
  - fs/namei.c:do_mknodat
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff8148c1c0-ffffffff8148c2f5: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c2bb0)
Location: fs/namei.c:3178
Inline: True
Direct callers:
  - fs/open.c:dentry_create
  - fs/namei.c:do_mknodat
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff814c2bb0-ffffffff814c2de2: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f5070)
Location: fs/namei.c:3186
Inline: True
Direct callers:
  - fs/open.c:dentry_create
  - fs/namei.c:do_mknodat
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff814f5070-ffffffff814f52a8: vfs_create (STB_GLOBAL)
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
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103969a8)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffff8000103969a8-ffff800010396b3c: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057bf9c)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
c057bf9c-c057c164: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048f090)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
c00000000048f090-c00000000048f2c4: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000264d4e)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffe000264d4e-ffffffe000264e7a: vfs_create (STB_GLOBAL)
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
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5960)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812e5960-ffffffff812e5ae7: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d65a0)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812d65a0-ffffffff812d6727: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3770)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812e3770-ffffffff812e38f7: vfs_create (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_create(struct inode *dir, struct dentry *dentry, umode_t mode, bool want_excl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f3840)
Location: fs/namei.c:2889
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_create
```
**Symbols:**

```
ffffffff812f3840-ffffffff812f39c7: vfs_create (STB_GLOBAL)
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
<code>dir, dentry, mode, want_excl</code> ➡️ <code>mnt_userns, dir, dentry, mode, want_excl</code>
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
