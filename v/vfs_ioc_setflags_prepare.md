# Function: <code>vfs_ioc_setflags_prepare</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812eae30)
Location: fs/inode.c:2202
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812eae30-ffffffff812eae57: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fc970)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812fc970-ffffffff812fc997: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81335110)
Location: fs/inode.c:2304
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
```
**Symbols:**

```
ffffffff81335110-ffffffff8133515b: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81340a80)
Location: fs/inode.c:2305
Inline: False
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_ioc_setxflags
```
**Symbols:**

```
ffffffff81340a80-ffffffff81340acb: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ac338)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffff8000103ac338-ffff8000103ac390: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d824)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
c058d824-c058d85c: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a7a90)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
**Symbols:**

```
c0000000004a7a90-c0000000004a7af8: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe00027196c)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
```
**Symbols:**

```
ffffffe00027196c-ffffffe0002719c0: vfs_ioc_setflags_prepare (STB_GLOBAL)
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
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4f50)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812f4f50-ffffffff812f4f77: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e5b70)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812e5b70-ffffffff812e5b97: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2d60)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff812f2d60-ffffffff812f2d87: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int vfs_ioc_setflags_prepare(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81304470)
Location: fs/inode.c:2244
Inline: True
Direct callers:
  - fs/ext4/ioctl.c:ext4_ioctl_setflags
  - fs/efivarfs/file.c:efivarfs_file_ioctl
```
**Symbols:**

```
ffffffff81304470-ffffffff81304497: vfs_ioc_setflags_prepare (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
