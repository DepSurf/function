# Function: <code>vfs_mknod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218da0)
Location: fs/namei.c:3499
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81218da0-ffffffff81218eea: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123fdd0)
Location: fs/namei.c:3665
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8123fdd0-ffffffff8123ffa7: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812536e0)
Location: fs/namei.c:3622
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812536e0-ffffffff812538b7: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125f8f0)
Location: fs/namei.c:3687
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8125f8f0-ffffffff8125fac8: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81281f50)
Location: fs/namei.c:3685
Inline: True
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_pin_user
  - fs/namei.c:SyS_mknod
  - fs/namei.c:SyS_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81281f50-ffffffff81282196: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9800)
Location: fs/namei.c:3707
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812a9800-ffffffff812a9a51: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bea10)
Location: fs/namei.c:3697
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812bea10-ffffffff812bec52: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812db640)
Location: fs/namei.c:3696
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812db640-ffffffff812db86b: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ed150)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812ed150-ffffffff812ed37b: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813251e0)
Location: fs/namei.c:3520
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff813251e0-ffffffff8132548e: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81330960)
Location: fs/namei.c:3522
Inline: False
Direct callers:
  - fs/init.c:init_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:handle_create
  - net/unix/af_unix.c:unix_mknod
```
**Symbols:**

```
ffffffff81330960-ffffffff81330bf3: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_mknod(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813371b0)
Location: fs/namei.c:3670
Inline: False
Direct callers:
  - fs/init.c:init_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff813371b0-ffffffff8133742b: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_mknod(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81384bf0)
Location: fs/namei.c:3739
Inline: False
Direct callers:
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81384bf0-ffffffff81384e87: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_mknod(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81402130)
Location: fs/namei.c:3833
Inline: False
Direct callers:
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81402130-ffffffff814022cd: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_mknod(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148c310)
Location: fs/namei.c:3890
Inline: False
Direct callers:
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8148c310-ffffffff8148c518: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_mknod(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c3060)
Location: fs/namei.c:3970
Inline: False
Direct callers:
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814c3060-ffffffff814c335a: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_mknod(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f5530)
Location: fs/namei.c:3979
Inline: False
Direct callers:
  - fs/namei.c:do_mknodat
  - fs/namei.c:do_mknodat
  - fs/init.c:init_mknod
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814f5530-ffffffff814f5830: vfs_mknod (STB_GLOBAL)
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
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010396e60)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff800010396e60-ffff800010397098: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057c4d0)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c057c4d0-c057c724: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048f730)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c00000000048f730-c00000000048f9e8: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002650b6)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe0002650b6-ffffffe000265262: vfs_mknod (STB_GLOBAL)
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
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5730)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812e5730-ffffffff812e595b: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6370)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812d6370-ffffffff812d659b: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3540)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812e3540-ffffffff812e376b: vfs_mknod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_mknod(struct inode *dir, struct dentry *dentry, umode_t mode, dev_t dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f3610)
Location: fs/namei.c:3691
Inline: True
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_mknod
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff812f3610-ffffffff812f383b: vfs_mknod (STB_GLOBAL)
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
<code>dir, dentry, mode, dev</code> ➡️ <code>mnt_userns, dir, dentry, mode, dev</code>
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
