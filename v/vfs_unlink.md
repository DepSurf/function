# Function: <code>vfs_unlink</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812195b0)
Location: fs/namei.c:3793
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - fs/ecryptfs/inode.c:ecryptfs_create
  - ipc/mqueue.c:SyS_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812195b0-ffffffff81219745: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81240470)
Location: fs/namei.c:3936
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81240470-ffffffff81240607: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81253d80)
Location: fs/namei.c:3893
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81253d80-ffffffff81253f17: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125e5d0)
Location: fs/namei.c:3958
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8125e5d0-ffffffff8125e787: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81281ca0)
Location: fs/namei.c:3956
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:SyS_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81281ca0-ffffffff81281e60: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a8dc0)
Location: fs/namei.c:3990
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812a8dc0-ffffffff812a8f81: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bdd00)
Location: fs/namei.c:3979
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812bdd00-ffffffff812bdec1: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da7a0)
Location: fs/namei.c:3979
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812da7a0-ffffffff812da991: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ec2b0)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812ec2b0-ffffffff812ec4a1: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81325900)
Location: fs/namei.c:3805
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81325900-ffffffff81325b1c: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f940)
Location: fs/namei.c:3806
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8132f940-ffffffff8132fb39: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_unlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813356a0)
Location: fs/namei.c:4004
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff813356a0-ffffffff81335899: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_unlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81385e80)
Location: fs/namei.c:4078
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81385e80-ffffffff81386108: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_unlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81403900)
Location: fs/namei.c:4173
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81403900-ffffffff81403bd5: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_unlink(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148dd50)
Location: fs/namei.c:4229
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff8148dd50-ffffffff8148e025: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_unlink(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c23b0)
Location: fs/namei.c:4306
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814c23b0-ffffffff814c2685: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_unlink(struct mnt_idmap *idmap, struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f4870)
Location: fs/namei.c:4315
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__do_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff814f4870-ffffffff814f4b45: vfs_unlink (STB_GLOBAL)
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
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010395a68)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__arm64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffff800010395a68-ffff800010395cc4: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057ae70)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c057ae70-c057b0b8: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048ddd0)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c00000000048ddd0-c00000000048e0fc: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002641a0)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__se_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffe0002641a0-ffffffe00026438a: vfs_unlink (STB_GLOBAL)
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
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e4890)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812e4890-ffffffff812e4a81: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d54d0)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812d54d0-ffffffff812d56c1: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e26a0)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812e26a0-ffffffff812e2891: vfs_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_unlink(struct inode *dir, struct dentry *dentry, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f2230)
Location: fs/namei.c:3974
Inline: False
Direct callers:
  - fs/namei.c:do_unlinkat
  - fs/ecryptfs/inode.c:ecryptfs_create
  - fs/ecryptfs/inode.c:ecryptfs_do_unlink
  - ipc/mqueue.c:__ia32_sys_mq_unlink
  - ipc/mqueue.c:__x64_sys_mq_unlink
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812f2230-ffffffff812f241f: vfs_unlink (STB_GLOBAL)
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
<code>dir, dentry, delegated_inode</code> ➡️ <code>mnt_userns, dir, dentry, delegated_inode</code>
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
