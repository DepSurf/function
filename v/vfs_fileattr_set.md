# Function: <code>vfs_fileattr_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133d150)
Location: fs/ioctl.c:867
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
```
**Symbols:**

```
ffffffff8133d150-ffffffff8133d3c8: vfs_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138ac00)
Location: fs/ioctl.c:672
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
```
**Symbols:**

```
ffffffff8138ac00-ffffffff8138ad4e: vfs_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140be70)
Location: fs/ioctl.c:668
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
```
**Symbols:**

```
ffffffff8140be70-ffffffff8140bfcf: vfs_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_fileattr_set(struct user_namespace *mnt_userns, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496890)
Location: fs/ioctl.c:668
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
```
**Symbols:**

```
ffffffff81496890-ffffffff814969ef: vfs_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb8d0)
Location: fs/ioctl.c:668
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
```
**Symbols:**

```
ffffffff814cb8d0-ffffffff814cba2f: vfs_fileattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_fileattr_set(struct mnt_idmap *idmap, struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fe180)
Location: fs/ioctl.c:669
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_set
```
**Symbols:**

```
ffffffff814fe180-ffffffff814fe2df: vfs_fileattr_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
