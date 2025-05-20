# Function: <code>fileattr_fill_flags</code>

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
void fileattr_fill_flags(struct fileattr *fa, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8133c8f0)
Location: fs/ioctl.c:701
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/efivarfs/inode.c:efivarfs_fileattr_get
```
**Symbols:**

```
ffffffff8133c8f0-ffffffff8133c975: fileattr_fill_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fileattr_fill_flags(struct fileattr *fa, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8138a5f0)
Location: fs/ioctl.c:498
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/efivarfs/inode.c:efivarfs_fileattr_get
```
**Symbols:**

```
ffffffff8138a5f0-ffffffff8138a675: fileattr_fill_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fileattr_fill_flags(struct fileattr *fa, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff8140b900)
Location: fs/ioctl.c:494
Inline: False
Direct callers:
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/efivarfs/inode.c:efivarfs_fileattr_get
```
**Symbols:**

```
ffffffff8140b900-ffffffff8140b989: fileattr_fill_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fileattr_fill_flags(struct fileattr *fa, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814962c0)
Location: fs/ioctl.c:494
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fileattr_get
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/efivarfs/inode.c:efivarfs_fileattr_get
```
**Symbols:**

```
ffffffff814962c0-ffffffff81496349: fileattr_fill_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fileattr_fill_flags(struct fileattr *fa, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814cb410)
Location: fs/ioctl.c:494
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fileattr_get
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/efivarfs/inode.c:efivarfs_fileattr_get
```
**Symbols:**

```
ffffffff814cb410-ffffffff814cb499: fileattr_fill_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fileattr_fill_flags(struct fileattr *fa, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ioctl.c (ffffffff814fdcc0)
Location: fs/ioctl.c:495
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fileattr_get
  - fs/ioctl.c:do_vfs_ioctl
  - fs/ext4/ioctl.c:ext4_fileattr_get
  - fs/fuse/ioctl.c:fuse_fileattr_get
  - fs/efivarfs/inode.c:efivarfs_fileattr_get
```
**Symbols:**

```
ffffffff814fdcc0-ffffffff814fdd49: fileattr_fill_flags (STB_GLOBAL)
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
