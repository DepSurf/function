# Function: <code>init_special_inode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81227960)
Location: fs/inode.c:1909
Inline: True
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_mknod
  - fs/ext4/namei.c:ext4_rename
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81227960-ffffffff812279d5: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124fea0)
Location: fs/inode.c:1926
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_mount
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff8124fea0-ffffffff8124ff15: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262dc0)
Location: fs/inode.c:1976
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81262dc0-ffffffff81262e35: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81270660)
Location: fs/inode.c:1966
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81270660-ffffffff812706d6: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292fa0)
Location: fs/inode.c:1979
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
```
**Symbols:**

```
ffffffff81292fa0-ffffffff81293016: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1971
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812baddd-ffffffff812bae00: init_special_inode.cold.34 (STB_LOCAL)
ffffffff812b8ac0-ffffffff812b8b1a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:1978
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812cffcd-ffffffff812cfff0: init_special_inode.cold.34 (STB_LOCAL)
ffffffff812cdc10-ffffffff812cdc6a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2016
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812ecf20-ffffffff812ecf43: init_special_inode.cold (STB_LOCAL)
ffffffff812ea380-ffffffff812ea3da: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812fea9d-ffffffff812feac0: init_special_inode.cold (STB_LOCAL)
ffffffff812fc4d0-ffffffff812fc52a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2111
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff81337b9b-ffffffff81337bbe: init_special_inode.cold (STB_LOCAL)
ffffffff81334f50-ffffffff81334faa: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2112
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:mknod_ptmx
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_whiteout_for_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_init_inode
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_mk_null_file
```
**Symbols:**

```
ffffffff81bea70f-ffffffff81bea732: init_special_inode.cold (STB_LOCAL)
ffffffff813408c0-ffffffff8134091a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2121
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_init_inode
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81bdc74b-ffffffff81bdc76f: init_special_inode.cold (STB_LOCAL)
ffffffff81346cf0-ffffffff81346d45: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2126
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_init_inode
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81cc3be4-ffffffff81cc3c08: init_special_inode.cold (STB_LOCAL)
ffffffff81394750-ffffffff813947a5: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2207
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_init_inode
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81e76411-ffffffff81e76443: init_special_inode.cold (STB_LOCAL)
ffffffff81416350-ffffffff814163dd: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a16f0)
Location: fs/inode.c:2260
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_init_inode
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814a16f0-ffffffff814a17af: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d72a0)
Location: fs/inode.c:2304
Inline: True
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_init_inode
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814d72a0-ffffffff814d735f: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81509620)
Location: fs/inode.c:2307
Inline: True
Direct callers:
  - mm/shmem.c:__shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/devpts/inode.c:devpts_fill_super
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_init_inode
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81509620-ffffffff815096df: init_special_inode (STB_GLOBAL)
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
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103abe40)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffff8000103abe40-ffff8000103abf18: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058d260)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c058d260-c058d2f4: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a7300)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c0000000004a7300-c0000000004a73d0: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe00027144a)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffe00027144a-ffffffe00027150a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f707d-ffffffff812f70a0: init_special_inode.cold (STB_LOCAL)
ffffffff812f4ab0-ffffffff812f4b0a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812e7c9d-ffffffff812e7cc0: init_special_inode.cold (STB_LOCAL)
ffffffff812e56d0-ffffffff812e572a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f4e8d-ffffffff812f4eb0: init_special_inode.cold (STB_LOCAL)
ffffffff812f28c0-ffffffff812f291a: init_special_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void init_special_inode(struct inode *inode, umode_t mode, dev_t rdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/inode.c (0)
Location: fs/inode.c:2027
Inline: False
Direct callers:
  - mm/shmem.c:shmem_get_inode
  - fs/devpts/inode.c:devpts_pty_new
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/namei.c:ext4_rename
  - fs/ext4/namei.c:ext4_mknod
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/squashfs/inode.c:squashfs_read_inode
  - fs/ramfs/inode.c:ramfs_get_inode
  - fs/hugetlbfs/inode.c:hugetlbfs_get_inode
  - fs/ecryptfs/inode.c:ecryptfs_inode_set
  - fs/fuse/inode.c:fuse_iget
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff8130601d-ffffffff81306040: init_special_inode.cold (STB_LOCAL)
ffffffff81303fd0-ffffffff8130402a: init_special_inode (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
