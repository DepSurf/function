# Function: <code>vfs_link</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218700)
Location: fs/namei.c:4004
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81218700-ffffffff81218987: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81241070)
Location: fs/namei.c:4147
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81241070-ffffffff8124139e: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81253f20)
Location: fs/namei.c:4104
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81253f20-ffffffff8125424e: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81260900)
Location: fs/namei.c:4169
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81260900-ffffffff81260c3a: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81282ff0)
Location: fs/namei.c:4165
Inline: False
Direct callers:
  - fs/namei.c:SyS_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81282ff0-ffffffff81283333: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a9a60)
Location: fs/namei.c:4205
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812a9a60-ffffffff812a9db3: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bf2f0)
Location: fs/namei.c:4194
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812bf2f0-ffffffff812bf643: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dbef0)
Location: fs/namei.c:4195
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812dbef0-ffffffff812dc288: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812eda00)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812eda00-ffffffff812edd98: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81325490)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81325490-ffffffff8132585f: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81330c00)
Location: fs/namei.c:4021
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81330c00-ffffffff81330fb6: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct user_namespace *mnt_userns, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81337430)
Location: fs/namei.c:4252
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81337430-ffffffff8133778e: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct user_namespace *mnt_userns, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81384e90)
Location: fs/namei.c:4330
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff81384e90-ffffffff81385213: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct user_namespace *mnt_userns, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814030c0)
Location: fs/namei.c:4425
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff814030c0-ffffffff814033fa: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct user_namespace *mnt_userns, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148d4e0)
Location: fs/namei.c:4481
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff8148d4e0-ffffffff8148d81a: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct mnt_idmap *idmap, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c3370)
Location: fs/namei.c:4553
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff814c3370-ffffffff814c3767: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct mnt_idmap *idmap, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f5840)
Location: fs/namei.c:4560
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/init.c:init_link
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff814f5840-ffffffff814f5c37: vfs_link (STB_GLOBAL)
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
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010397248)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffff800010397248-ffff80001039758c: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057d780)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
c057d780-c057db30: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000490fb0)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
c000000000490fb0-c000000000491404: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe00026538e)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffe00026538e-ffffffe00026563a: vfs_link (STB_GLOBAL)
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
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5fe0)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812e5fe0-ffffffff812e6378: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d6c20)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812d6c20-ffffffff812d6fb8: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e3df0)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812e3df0-ffffffff812e4188: vfs_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_link(struct dentry *old_dentry, struct inode *dir, struct dentry *new_dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f3ec0)
Location: fs/namei.c:4190
Inline: False
Direct callers:
  - fs/namei.c:do_linkat
  - fs/ecryptfs/inode.c:ecryptfs_link
```
**Symbols:**

```
ffffffff812f3ec0-ffffffff812f4256: vfs_link (STB_GLOBAL)
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
<code>old_dentry, dir, new_dentry, delegated_inode</code> ➡️ <code>old_dentry, mnt_userns, dir, new_dentry, delegated_inode</code>
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
