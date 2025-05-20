# Function: <code>d_obtain_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81225c30)
Location: fs/dcache.c:2005
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_dentry
  - fs/libfs.c:generic_fh_to_dentry
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/ext4/namei.c:ext4_get_parent
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81225c30-ffffffff81225c45: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124dd40)
Location: fs/dcache.c:1961
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/libfs.c:generic_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8124dd40-ffffffff8124dd55: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81260e20)
Location: fs/dcache.c:1970
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/libfs.c:generic_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81260e20-ffffffff81260e35: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126e5f0)
Location: fs/dcache.c:2000
Inline: True
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/libfs.c:generic_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff8126e5f0-ffffffff8126e620: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81290f10)
Location: fs/dcache.c:2012
Inline: True
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81290f10-ffffffff81290f40: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b75e0)
Location: fs/dcache.c:2036
Inline: True
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff812b75e0-ffffffff812b760e: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812cc740)
Location: fs/dcache.c:2017
Inline: True
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff812cc740-ffffffff812cc76e: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e9340)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff812e9340-ffffffff812e9355: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812faee0)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff812faee0-ffffffff812faef5: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81333020)
Location: fs/dcache.c:2110
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81333020-ffffffff81333035: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e550)
Location: fs/dcache.c:2117
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8133e550-ffffffff8133e565: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81344940)
Location: fs/dcache.c:2144
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81344940-ffffffff81344955: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81392430)
Location: fs/dcache.c:2145
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81392430-ffffffff81392445: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414100)
Location: fs/dcache.c:2170
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff81414100-ffffffff8141411d: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f560)
Location: fs/dcache.c:2170
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff8149f560-ffffffff8149f57d: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d4880)
Location: fs/dcache.c:2170
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:__kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
  - security/selinux/selinuxfs.c:sel_make_policy_nodes
```
**Symbols:**

```
ffffffff814d4880-ffffffff814d489d: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81506bc0)
Location: fs/dcache.c:1994
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/kernfs/mount.c:kernfs_fh_to_parent
  - fs/kernfs/mount.c:kernfs_fh_to_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81506bc0-ffffffff81506bdd: d_obtain_alias (STB_GLOBAL)
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
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103aa210)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffff8000103aa210-ffff8000103aa240: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c058b1e8)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
c058b1e8-c058b208: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a50c0)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
c0000000004a50c0-c0000000004a50d8: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026ff8c)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffe00026ff8c-ffffffe00026ffb8: d_obtain_alias (STB_GLOBAL)
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
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f34c0)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff812f34c0-ffffffff812f34d5: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e40f0)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff812e40f0-ffffffff812e4105: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f12d0)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff812f12d0-ffffffff812f12e5: d_obtain_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_obtain_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81302490)
Location: fs/dcache.c:2089
Inline: False
Direct callers:
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_parent
  - fs/libfs.c:generic_fh_to_dentry
  - fs/kernfs/mount.c:kernfs_get_parent_dentry
  - fs/ext4/namei.c:ext4_get_parent
  - fs/squashfs/export.c:squashfs_export_iget
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fat/nfs.c:fat_fh_to_parent_nostale
  - fs/fuse/inode.c:fuse_get_parent
  - fs/fuse/inode.c:fuse_get_dentry
```
**Symbols:**

```
ffffffff81302490-ffffffff813024a5: d_obtain_alias (STB_GLOBAL)
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
