# Function: <code>get_tree_single</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cf610)
Location: fs/super.c:1206
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff812cf610-ffffffff812cf625: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e1940)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff812e1940-ffffffff812e1955: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813183a0)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff813183a0-ffffffff8131845b: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81323830)
Location: fs/super.c:1172
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff81323830-ffffffff813238eb: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81329830)
Location: fs/super.c:1174
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff81329830-ffffffff813298eb: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81376f20)
Location: fs/super.c:1174
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff81376f20-ffffffff81376fdb: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f61b0)
Location: fs/super.c:1173
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff813f61b0-ffffffff813f6260: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147fcf0)
Location: fs/super.c:1174
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff8147fcf0-ffffffff8147fd18: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b49e0)
Location: fs/super.c:1185
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff814b49e0-ffffffff814b4a08: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6150)
Location: fs/super.c:1291
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff814e6150-ffffffff814e61eb: get_tree_single (STB_GLOBAL)
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
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388d20)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffff800010388d20-ffff800010388d58: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c0571338)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
c0571338-c057135c: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047fc90)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
c00000000047fc90-c00000000047fcac: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025b252)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffe00025b252-ffffffe00025b286: get_tree_single (STB_GLOBAL)
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
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9f20)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff812d9f20-ffffffff812d9f35: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812caba0)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff812caba0-ffffffff812cabb5: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7d30)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff812d7d30-ffffffff812d7d45: get_tree_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_tree_single(struct fs_context *fc, int (*fill_super)(struct super_block *, struct fs_context *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8b70)
Location: fs/super.c:1225
Inline: False
Direct callers:
  - fs/configfs/mount.c:configfs_get_tree
  - fs/fuse/control.c:fuse_ctl_get_tree
  - fs/efivarfs/super.c:efivarfs_get_tree
  - security/inode.c:securityfs_get_tree
  - security/selinux/selinuxfs.c:sel_get_tree
  - security/smack/smackfs.c:smk_get_tree
  - security/apparmor/apparmorfs.c:apparmorfs_get_tree
```
**Symbols:**

```
ffffffff812e8b70-ffffffff812e8b85: get_tree_single (STB_GLOBAL)
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
