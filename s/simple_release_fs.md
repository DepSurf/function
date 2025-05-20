# Function: <code>simple_release_fs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234110)
Location: fs/libfs.c:559
Inline: False
Direct callers:
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - security/inode.c:securityfs_create_file
  - security/inode.c:securityfs_remove
```
**Symbols:**

```
ffffffff81234110-ffffffff8123415a: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125c740)
Location: fs/libfs.c:587
Inline: False
Direct callers:
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
**Symbols:**

```
ffffffff8125c740-ffffffff8125c78a: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126fc90)
Location: fs/libfs.c:595
Inline: False
Direct callers:
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
```
**Symbols:**

```
ffffffff8126fc90-ffffffff8126fcda: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d510)
Location: fs/libfs.c:596
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aafs_create
```
**Symbols:**

```
ffffffff8127d510-ffffffff8127d55a: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8129ff90)
Location: fs/libfs.c:596
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_create_dentry
```
**Symbols:**

```
ffffffff8129ff90-ffffffff8129ffda: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c6d70)
Location: fs/libfs.c:596
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812c6d70-ffffffff812c6dba: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dbf70)
Location: fs/libfs.c:596
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812dbf70-ffffffff812dbfba: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa610)
Location: fs/libfs.c:615
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812fa610-ffffffff812fa65a: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130c580)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff8130c580-ffffffff8130c5ca: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345b70)
Location: fs/libfs.c:689
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/char/mem.c:chr_dev_init
```
**Symbols:**

```
ffffffff81345b70-ffffffff81345bba: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81352020)
Location: fs/libfs.c:691
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/char/mem.c:chr_dev_init
```
**Symbols:**

```
ffffffff81352020-ffffffff8135206a: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813593b0)
Location: fs/libfs.c:694
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813593b0-ffffffff813593fa: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a7850)
Location: fs/libfs.c:703
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813a7850-ffffffff813a789a: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b190)
Location: fs/libfs.c:730
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:debugfs_remove
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff8142b190-ffffffff8142b1e6: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8370)
Location: fs/libfs.c:731
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff814b8370-ffffffff814b83c6: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ed580)
Location: fs/libfs.c:726
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff814ed580-ffffffff814ed5d6: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff815212e0)
Location: fs/libfs.c:996
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/debugfs/inode.c:remove_one
  - fs/debugfs/inode.c:debugfs_create_symlink
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:debugfs_create_dir
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/debugfs/inode.c:__debugfs_create_file
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:remove_one
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
  - drivers/gpu/drm/drm_drv.c:drm_dev_init_release
```
**Symbols:**

```
ffffffff815212e0-ffffffff81521336: simple_release_fs (STB_GLOBAL)
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
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c0e50)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffff8000103c0e50-ffff8000103c0ef8: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d6a4)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
c059d6a4-c059d70c: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004bf770)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
c0000000004bf770-c0000000004bf830: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000281264)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffe000281264-ffffffe0002812f8: simple_release_fs (STB_GLOBAL)
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
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81304b60)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81304b60-ffffffff81304baa: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f5780)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff812f5780-ffffffff812f57ca: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81302950)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff81302950-ffffffff8130299a: simple_release_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void simple_release_fs(struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813135f0)
Location: fs/libfs.c:620
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_release_fs
  - fs/debugfs/inode.c:failed_creating
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove_recursive
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:__create_dir
  - fs/tracefs/inode.c:tracefs_create_file
  - security/inode.c:securityfs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/apparmor/apparmorfs.c:aafs_remove
```
**Symbols:**

```
ffffffff813135f0-ffffffff8131363c: simple_release_fs (STB_GLOBAL)
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
