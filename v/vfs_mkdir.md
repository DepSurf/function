# Function: <code>vfs_mkdir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812184a0)
Location: fs/namei.c:3591
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812184a0-ffffffff812185e9: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812402c0)
Location: fs/namei.c:3759
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812402c0-ffffffff8124046a: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81253bd0)
Location: fs/namei.c:3716
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff81253bd0-ffffffff81253d7a: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125fdf0)
Location: fs/namei.c:3781
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff8125fdf0-ffffffff8125ffa7: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812824d0)
Location: fs/namei.c:3779
Inline: False
Direct callers:
  - fs/namei.c:SyS_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812824d0-ffffffff8128268d: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9640)
Location: fs/namei.c:3808
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812a9640-ffffffff812a97fb: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bf130)
Location: fs/namei.c:3797
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812bf130-ffffffff812bf2eb: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dbd30)
Location: fs/namei.c:3796
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812dbd30-ffffffff812dbeef: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ed840)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffff812ed840-ffffffff812ed9ff: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81324fc0)
Location: fs/namei.c:3622
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffff81324fc0-ffffffff813251d3: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81330760)
Location: fs/namei.c:3624
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffff81330760-ffffffff81330953: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_mkdir(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81336fd0)
Location: fs/namei.c:3793
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
```
**Symbols:**

```
ffffffff81336fd0-ffffffff813371b0: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_mkdir(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813849f0)
Location: fs/namei.c:3865
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
```
**Symbols:**

```
ffffffff813849f0-ffffffff81384be4: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_mkdir(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814022d0)
Location: fs/namei.c:3959
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
```
**Symbols:**

```
ffffffff814022d0-ffffffff814023f9: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_mkdir(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148c530)
Location: fs/namei.c:4016
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
```
**Symbols:**

```
ffffffff8148c530-ffffffff8148c686: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_mkdir(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c2e00)
Location: fs/namei.c:4096
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
```
**Symbols:**

```
ffffffff814c2e00-ffffffff814c304e: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_mkdir(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f52c0)
Location: fs/namei.c:4105
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/init.c:init_mkdir
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
```
**Symbols:**

```
ffffffff814f52c0-ffffffff814f5514: vfs_mkdir (STB_GLOBAL)
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
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010397098)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffff800010397098-ffff800010397248: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057c724)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
c057c724-c057c90c: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048f9f0)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
c00000000048f9f0-c00000000048fc40: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000265262)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffe000265262-ffffffe00026538e: vfs_mkdir (STB_GLOBAL)
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
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5e20)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffff812e5e20-ffffffff812e5fdf: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6a60)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffff812d6a60-ffffffff812d6c1f: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3c30)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffff812e3c30-ffffffff812e3def: vfs_mkdir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_mkdir(struct inode *dir, struct dentry *dentry, umode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f3d00)
Location: fs/namei.c:3791
Inline: False
Direct callers:
  - fs/namei.c:do_mkdirat
  - fs/ecryptfs/inode.c:ecryptfs_mkdir
```
**Symbols:**

```
ffffffff812f3d00-ffffffff812f3ebf: vfs_mkdir (STB_GLOBAL)
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
<code>dir, dentry, mode</code> ➡️ <code>mnt_userns, dir, dentry, mode</code>
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
