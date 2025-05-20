# Function: <code>setattr_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812291f0)
Location: fs/attr.c:184
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812291f0-ffffffff812292e4: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81251920)
Location: fs/attr.c:160
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81251920-ffffffff81251a14: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81264af0)
Location: fs/attr.c:173
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81264af0-ffffffff81264be4: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81272320)
Location: fs/attr.c:174
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81272320-ffffffff8127241e: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81294c40)
Location: fs/attr.c:175
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81294c40-ffffffff81294d3e: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812bae00)
Location: fs/attr.c:177
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812bae00-ffffffff812baef7: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812cfff0)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812cfff0-ffffffff812d00e7: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812ed010)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812ed010-ffffffff812ed10b: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812feac0)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812feac0-ffffffff812feb66: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81337bc0)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81337bc0-ffffffff81337c66: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81343520)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81343520-ffffffff813435c6: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void setattr_copy(struct user_namespace *mnt_userns, struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81349810)
Location: fs/attr.c:226
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81349810-ffffffff813498cc: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void setattr_copy(struct user_namespace *mnt_userns, struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81397560)
Location: fs/attr.c:226
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81397560-ffffffff8139761c: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void setattr_copy(struct user_namespace *mnt_userns, struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814198c0)
Location: fs/attr.c:242
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff814198c0-ffffffff814199ca: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setattr_copy(struct user_namespace *mnt_userns, struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814a54a0)
Location: fs/attr.c:302
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff814a54a0-ffffffff814a563e: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setattr_copy(struct mnt_idmap *idmap, struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814da550)
Location: fs/attr.c:303
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff814da550-ffffffff814da664: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setattr_copy(struct mnt_idmap *idmap, struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff8150cae0)
Location: fs/attr.c:303
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
```
**Symbols:**

```
ffffffff8150cae0-ffffffff8150cc05: setattr_copy (STB_GLOBAL)
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
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffff8000103aff90)
Location: fs/attr.c:178
Inline: True
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffff8000103aff90-ffff8000103b003c: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (c058f7c8)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
c058f7c8-c058f880: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (c0000000004ab610)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
c0000000004ab610-c0000000004ab710: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffe0002743ec)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffe0002743ec-ffffffe0002744a4: setattr_copy (STB_GLOBAL)
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
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f70a0)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812f70a0-ffffffff812f7146: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812e7cc0)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812e7cc0-ffffffff812e7d66: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff812f4eb0)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff812f4eb0-ffffffff812f4f56: setattr_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void setattr_copy(struct inode *inode, const struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81306040)
Location: fs/attr.c:178
Inline: False
Direct callers:
  - mm/shmem.c:shmem_setattr
  - fs/libfs.c:simple_setattr
  - fs/proc/base.c:proc_setattr
  - fs/proc/generic.c:proc_notify_change
  - fs/proc/proc_sysctl.c:proc_sys_setattr
  - fs/kernfs/inode.c:kernfs_iop_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/inode.c:ext4_setattr
  - fs/hugetlbfs/inode.c:hugetlbfs_setattr
  - fs/fat/file.c:fat_setattr
```
**Symbols:**

```
ffffffff81306040-ffffffff813060e6: setattr_copy (STB_GLOBAL)
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
<code>inode, attr</code> ➡️ <code>mnt_userns, inode, attr</code>
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
