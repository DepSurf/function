# Function: <code>vfs_fileattr_get</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int vfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133d696)
Location: fs/ioctl.c:732
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:vfs_fileattr_set
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
```
**Symbols:**

```
ffffffff8133c810-ffffffff8133c83a: vfs_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int vfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138b016)
Location: fs/ioctl.c:529
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:vfs_fileattr_set
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
```
**Symbols:**

```
ffffffff8138a510-ffffffff8138a53a: vfs_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int vfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140c2c4)
Location: fs/ioctl.c:525
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:vfs_fileattr_set
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
```
**Symbols:**

```
ffffffff8140b630-ffffffff8140b66a: vfs_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int vfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff81496cf4)
Location: fs/ioctl.c:525
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:vfs_fileattr_set
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
```
**Symbols:**

```
ffffffff81495fa0-ffffffff81495fda: vfs_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int vfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cbbca)
Location: fs/ioctl.c:525
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:vfs_fileattr_set
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
```
**Symbols:**

```
ffffffff814cafe0-ffffffff814cb01a: vfs_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int vfs_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fe47a)
Location: fs/ioctl.c:526
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ioctl.c:vfs_fileattr_set
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_fileattr_get
```
**Symbols:**

```
ffffffff814fd890-ffffffff814fd8ca: vfs_fileattr_get (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
