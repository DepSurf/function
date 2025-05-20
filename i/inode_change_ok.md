# Function: <code>inode_change_ok</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int inode_change_ok(const struct inode *inode, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81229360)
Location: fs/attr.c:68
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81229360-ffffffff812295b6: inode_change_ok (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int inode_change_ok(const struct inode *inode, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81251a90)
Location: fs/attr.c:55
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81251a90-ffffffff81251c22: inode_change_ok (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
