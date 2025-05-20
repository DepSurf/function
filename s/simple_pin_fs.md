# Function: <code>simple_pin_fs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234070)
Location: fs/libfs.c:538
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_file
```
**Symbols:**

```
ffffffff81234070-ffffffff8123410c: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125c6a0)
Location: fs/libfs.c:566
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_pin_fs
```
**Symbols:**

```
ffffffff8125c6a0-ffffffff8125c73e: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8126fbf0)
Location: fs/libfs.c:574
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_pin_fs
```
**Symbols:**

```
ffffffff8126fbf0-ffffffff8126fc8e: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127d460)
Location: fs/libfs.c:575
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aafs_create
```
**Symbols:**

```
ffffffff8127d460-ffffffff8127d501: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8129fee0)
Location: fs/libfs.c:575
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - security/inode.c:securityfs_create_dentry
```
**Symbols:**

```
ffffffff8129fee0-ffffffff8129ff81: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c7600)
Location: fs/libfs.c:575
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812c7600-ffffffff812c76a0: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dc1a0)
Location: fs/libfs.c:575
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812dc1a0-ffffffff812dc240: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fa840)
Location: fs/libfs.c:594
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812fa840-ffffffff812fa8e3: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130d020)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff8130d020-ffffffff8130d0c3: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81346b40)
Location: fs/libfs.c:668
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - drivers/char/mem.c:chr_dev_init
```
**Symbols:**

```
ffffffff81346b40-ffffffff81346be6: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81353030)
Location: fs/libfs.c:670
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_mk_null_file
  - drivers/char/mem.c:chr_dev_init
```
**Symbols:**

```
ffffffff81353030-ffffffff813530d6: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81359d30)
Location: fs/libfs.c:673
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81359d30-ffffffff81359dd6: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a81d0)
Location: fs/libfs.c:682
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff813a81d0-ffffffff813a8276: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142b0e0)
Location: fs/libfs.c:709
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:debugfs_remove
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff8142b0e0-ffffffff8142b18b: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b82b0)
Location: fs/libfs.c:710
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/tracefs/inode.c:tracefs_remove
  - fs/tracefs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814b82b0-ffffffff814b835b: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ed4c0)
Location: fs/libfs.c:705
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/tracefs/inode.c:tracefs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff814ed4c0-ffffffff814ed56b: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521220)
Location: fs/libfs.c:975
Inline: False
Direct callers:
  - kernel/resource.c:iomem_init_inode
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:debugfs_lookup_and_remove
  - fs/tracefs/inode.c:tracefs_remove
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - drivers/gpu/drm/drm_drv.c:drm_dev_init
```
**Symbols:**

```
ffffffff81521220-ffffffff815212cb: simple_pin_fs (STB_GLOBAL)
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
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c1190)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffff8000103c1190-ffff8000103c12dc: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059d5d8)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c059d5d8-c059d6a4: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004bf5f0)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
c0000000004bf5f0-c0000000004bf76c: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe00028156a)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffe00028156a-ffffffe00028168e: simple_pin_fs (STB_GLOBAL)
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
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81305600)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81305600-ffffffff813056a3: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f6220)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff812f6220-ffffffff812f62c3: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813033f0)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff813033f0-ffffffff81303493: simple_pin_fs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int simple_pin_fs(struct file_system_type *type, struct vfsmount **mount, int *count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81313550)
Location: fs/libfs.c:599
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_pin_fs
  - fs/debugfs/inode.c:start_creating
  - security/inode.c:securityfs_create_dentry
  - security/apparmor/apparmorfs.c:aa_create_aafs
```
**Symbols:**

```
ffffffff81313550-ffffffff813135ef: simple_pin_fs (STB_GLOBAL)
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
