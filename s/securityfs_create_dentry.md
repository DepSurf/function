# Function: <code>securityfs_create_dentry</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813753b0)
Location: security/inode.c:113
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
```
**Symbols:**

```
ffffffff813753b0-ffffffff81375517: securityfs_create_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8138bce0)
Location: security/inode.c:113
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_dir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
  - security/apparmor/apparmorfs.c:__aa_fs_ns_mkdir
```
**Symbols:**

```
ffffffff8138bce0-ffffffff8138be47: securityfs_create_dentry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813a18c0)
Location: security/inode.c:101
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff813a18c0-ffffffff813a1ad4: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813c76c0)
Location: security/inode.c:101
Inline: False
Direct callers:
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff813c76c0-ffffffff813c78d4: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813f6d00)
Location: security/inode.c:101
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff813f6d00-ffffffff813f6f01: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814127b0)
Location: security/inode.c:102
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff814127b0-ffffffff814129b1: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814401e0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff814401e0-ffffffff814403fd: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81459ab0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff81459ab0-ffffffff81459ccd: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814acd30)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff814acd30-ffffffff814acf4d: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814ca280)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff814ca280-ffffffff814ca49d: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814d08b0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff814d08b0-ffffffff814d0acd: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff815295e0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff815295e0-ffffffff815297fd: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff815bedb0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff815bedb0-ffffffff815befdf: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8166b160)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff8166b160-ffffffff8166b38f: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816a38c0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff816a38c0-ffffffff816a3aef: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816e0340)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff816e0340-ffffffff816e0545: securityfs_create_dentry (STB_LOCAL)
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
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffff800010545d78)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffff800010545d78-ffff800010545fb4: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c06fbba0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
c06fbba0-c06fbdd0: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c00000000069c6e0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
c00000000069c6e0-c00000000069c9e0: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffe0003a191c)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffe0003a191c-ffffffe0003a1afa: securityfs_create_dentry (STB_LOCAL)
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
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81452090)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff81452090-ffffffff814522ad: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81442ae0)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff81442ae0-ffffffff81442cfd: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8144e130)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff8144e130-ffffffff8144e34d: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *securityfs_create_dentry(const char *name, umode_t mode, struct dentry *parent, void *data, const struct file_operations *fops, const struct inode_operations *iops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81465500)
Location: security/inode.c:107
Inline: False
Direct callers:
  - security/inode.c:securityfs_init
  - security/inode.c:securityfs_create_symlink
  - security/inode.c:securityfs_create_dir
```
**Symbols:**

```
ffffffff81465500-ffffffff8146571d: securityfs_create_dentry (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
