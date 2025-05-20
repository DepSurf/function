# Function: <code>may_create</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812181b6)
Location: fs/namei.c:2596
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_rename
```
```
In security/selinux/hooks.c (ffffffff81342ef0)
Location: security/selinux/hooks.c:1762
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81342ef0-ffffffff81342fdf: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81241816)
Location: fs/namei.c:2812
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In security/selinux/hooks.c (ffffffff81379c80)
Location: security/selinux/hooks.c:1835
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81379c80-ffffffff81379d7c: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812546a6)
Location: fs/namei.c:2776
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In security/selinux/hooks.c (ffffffff81392370)
Location: security/selinux/hooks.c:1843
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81392370-ffffffff8139247e: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812601ea)
Location: fs/namei.c:2821
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In security/selinux/hooks.c (ffffffff813a8a10)
Location: security/selinux/hooks.c:1833
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff813a8a10-ffffffff813a8b44: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812828ca)
Location: fs/namei.c:2819
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
```
```
In security/selinux/hooks.c (ffffffff813ce940)
Location: security/selinux/hooks.c:1847
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff813ce940-ffffffff813cea74: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ab868)
Location: fs/namei.c:2820
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff81400370)
Location: security/selinux/hooks.c:1950
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81400370-ffffffff8140049c: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812be478)
Location: fs/namei.c:2839
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff8141c3d0)
Location: security/selinux/hooks.c:1764
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff8141c3d0-ffffffff8141c51b: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812db090)
Location: fs/namei.c:2837
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff81449dc0)
Location: security/selinux/hooks.c:1808
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81449dc0-ffffffff81449f0b: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ecba0)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff81463960)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81463960-ffffffff81463aab: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813268d8)
Location: fs/namei.c:2732
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff814b7420)
Location: security/selinux/hooks.c:1763
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff814b7420-ffffffff814b753c: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81331d4d)
Location: fs/namei.c:2730
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff814d5100)
Location: security/selinux/hooks.c:1772
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff814d5100-ffffffff814d521b: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81335dfe)
Location: fs/namei.c:2824
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff814dbee0)
Location: security/selinux/hooks.c:1832
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff814dbee0-ffffffff814dc00a: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813838ed)
Location: fs/namei.c:2893
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff81535370)
Location: security/selinux/hooks.c:1824
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81535370-ffffffff8153549a: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81402e1b)
Location: fs/namei.c:2989
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkobj
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
```
```
In security/selinux/hooks.c (ffffffff815cb6b0)
Location: security/selinux/hooks.c:1762
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81401e80-ffffffff8140200c: may_create (STB_LOCAL)
ffffffff815cb6b0-ffffffff815cb817: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct user_namespace *mnt_userns, struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148d20b)
Location: fs/namei.c:2968
Inline: True
Inline callers:
  - fs/namei.c:vfs_mkobj
Direct callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
```
```
In security/selinux/hooks.c (ffffffff81678800)
Location: security/selinux/hooks.c:1761
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff8148c010-ffffffff8148c1a4: may_create (STB_LOCAL)
ffffffff81678800-ffffffff81678967: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct mnt_idmap *idmap, struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c3e16)
Location: fs/namei.c:2999
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff816b0a50)
Location: security/selinux/hooks.c:1771
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff816b0a50-ffffffff816b0b98: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct mnt_idmap *idmap, struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f64ef)
Location: fs/namei.c:3016
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mknod
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff816eda00)
Location: security/selinux/hooks.c:1811
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff816eda00-ffffffff816edb4b: may_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff8000103962f8)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffff8000105518f0)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffff8000105518f0-ffff800010551a50: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057b718)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (c0705794)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
c0705794-c070590c: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048e6e0)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (c0000000006aa170)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
c0000000006aa170-c0000000006aa310: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000264944)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffe0003aaaa8)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffe0003aaaa8-ffffffe0003aabb0: may_create (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e5180)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff8145bf40)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff8145bf40-ffffffff8145c08b: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d5dc0)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff8144c970)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff8144c970-ffffffff8144cabb: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2f90)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff81457fe0)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff81457fe0-ffffffff8145812b: may_create (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
int may_create(struct inode *dir, struct dentry *child);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f2ece)
Location: fs/namei.c:2830
Inline: True
Inline callers:
  - fs/namei.c:vfs_rename
  - fs/namei.c:vfs_link
  - fs/namei.c:vfs_mkdir
  - fs/namei.c:vfs_mkobj
```
```
In security/selinux/hooks.c (ffffffff8146cf40)
Location: security/selinux/hooks.c:1810
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mknod
  - security/selinux/hooks.c:selinux_inode_mkdir
  - security/selinux/hooks.c:selinux_inode_symlink
  - security/selinux/hooks.c:selinux_inode_create
```
**Symbols:**

```
ffffffff8146cf40-ffffffff8146d08b: may_create (STB_LOCAL)
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
<code>dir, child</code> ➡️ <code>mnt_userns, dir, child</code>
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
