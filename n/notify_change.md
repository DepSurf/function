# Function: <code>notify_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812295c0)
Location: fs/attr.c:232
Inline: False
Direct callers:
  - fs/open.c:do_truncate
  - fs/open.c:chmod_common
  - fs/open.c:chown_common
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:utimes_common
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812295c0-ffffffff8122991b: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81251c30)
Location: fs/attr.c:208
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:utimes_common
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff81251c30-ffffffff81252062: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81264e30)
Location: fs/attr.c:221
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:utimes_common
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff81264e30-ffffffff8126528c: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81272660)
Location: fs/attr.c:222
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:utimes_common
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff81272660-ffffffff81272a8c: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81294f80)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:utimes_common
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff81294f80-ffffffff812953b2: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812bb170)
Location: fs/attr.c:225
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812bb170-ffffffff812bb5c7: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812d0360)
Location: fs/attr.c:226
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812d0360-ffffffff812d07b8: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812ed370)
Location: fs/attr.c:226
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff812ed370-ffffffff812ed7ea: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812fedd0)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812fedd0-ffffffff812ff2a7: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81337ed0)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:utimes_common
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff81337ed0-ffffffff81338397: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81343830)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:vfs_utimes
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
  - drivers/base/devtmpfs.c:handle_create
```
**Symbols:**

```
ffffffff81343830-ffffffff81343d24: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int notify_change(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81349b90)
Location: fs/attr.c:282
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:vfs_utimes
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81349b90-ffffffff8134a0c8: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int notify_change(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81397950)
Location: fs/attr.c:310
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:vfs_utimes
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81397950-ffffffff81397e27: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int notify_change(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814199d0)
Location: fs/attr.c:326
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:vfs_utimes
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff814199d0-ffffffff81419f3c: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int notify_change(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814a59f0)
Location: fs/attr.c:380
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:__file_remove_privs
  - fs/utimes.c:vfs_utimes
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff814a59f0-ffffffff814a5fa2: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int notify_change(struct mnt_idmap *idmap, struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814daaa0)
Location: fs/attr.c:381
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:__file_remove_privs
  - fs/utimes.c:vfs_utimes
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff814daaa0-ffffffff814daf4d: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int notify_change(struct mnt_idmap *idmap, struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff8150d040)
Location: fs/attr.c:381
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:__file_remove_privs
  - fs/utimes.c:vfs_utimes
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:devtmpfs_work_loop
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff8150d040-ffffffff8150d50a: notify_change (STB_GLOBAL)
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
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffff8000103b02d0)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffff8000103b02d0-ffff8000103b06d0: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (c058fb48)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/utimes.c:utimes_common
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c058fb48-c058fffc: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (c0000000004abad0)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
c0000000004abad0-c0000000004ac0e8: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffe000274698)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffe000274698-ffffffe000274a6e: notify_change (STB_GLOBAL)
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
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f73b0)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812f73b0-ffffffff812f7887: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812e7fd0)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812e7fd0-ffffffff812e84a7: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f51c0)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff812f51c0-ffffffff812f5697: notify_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int notify_change(struct dentry *dentry, struct iattr *attr, struct inode **delegated_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81306350)
Location: fs/attr.c:223
Inline: False
Direct callers:
  - fs/open.c:chown_common
  - fs/open.c:chmod_common
  - fs/open.c:do_truncate
  - fs/inode.c:file_remove_privs
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/ecryptfs/inode.c:ecryptfs_truncate
  - drivers/base/devtmpfs.c:handle_remove
```
**Symbols:**

```
ffffffff81306350-ffffffff81306827: notify_change (STB_GLOBAL)
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
<code>dentry, attr, delegated_inode</code> ➡️ <code>mnt_userns, dentry, attr, delegated_inode</code>
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
