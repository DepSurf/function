# Function: <code>setattr_prepare</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81264c60)
Location: fs/attr.c:57
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
ffffffff81264c60-ffffffff81264e25: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81272490)
Location: fs/attr.c:58
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
ffffffff81272490-ffffffff81272655: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81294db0)
Location: fs/attr.c:59
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
ffffffff81294db0-ffffffff81294f75: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812baf70)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff812baf70-ffffffff812bb161: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812d0160)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff812d0160-ffffffff812d0351: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812ed180)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff812ed180-ffffffff812ed36d: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812febe0)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff812febe0-ffffffff812fedcd: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81337ce0)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81337ce0-ffffffff81337ecd: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81343640)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81343640-ffffffff8134382d: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int setattr_prepare(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81349940)
Location: fs/attr.c:96
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81349940-ffffffff81349b8b: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int setattr_prepare(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81397690)
Location: fs/attr.c:96
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81397690-ffffffff813978e0: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int setattr_prepare(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81419f40)
Location: fs/attr.c:102
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81419f40-ffffffff8141a30a: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int setattr_prepare(struct user_namespace *mnt_userns, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814a5650)
Location: fs/attr.c:164
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff814a5650-ffffffff814a59da: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int setattr_prepare(struct mnt_idmap *idmap, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814da7d0)
Location: fs/attr.c:165
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff814da7d0-ffffffff814daa83: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int setattr_prepare(struct mnt_idmap *idmap, struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff8150cd70)
Location: fs/attr.c:165
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff8150cd70-ffffffff8150d023: setattr_prepare (STB_GLOBAL)
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
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffff8000103b00d0)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffff8000103b00d0-ffff8000103b02d0: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (c058f944)
Location: fs/attr.c:61
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
c058f944-c058fb48: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (c0000000004ab7c0)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
c0000000004ab7c0-c0000000004abac8: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffe000274510)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffe000274510-ffffffe000274698: setattr_prepare (STB_GLOBAL)
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
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f71c0)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff812f71c0-ffffffff812f73ad: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812e7de0)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff812e7de0-ffffffff812e7fcd: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f4fd0)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff812f4fd0-ffffffff812f51bd: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int setattr_prepare(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81306160)
Location: fs/attr.c:61
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
  - fs/ecryptfs/inode.c:ecryptfs_setattr
  - fs/fuse/dir.c:fuse_do_setattr
```
**Symbols:**

```
ffffffff81306160-ffffffff8130634d: setattr_prepare (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>dentry, attr</code> ➡️ <code>mnt_userns, dentry, attr</code>
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
