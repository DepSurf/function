# Function: <code>securityfs_create_symlink</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813a1b20)
Location: security/inode.c:254
Inline: False
```
**Symbols:**

```
ffffffff813a1b20-ffffffff813a1ba2: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813c7920)
Location: security/inode.c:254
Inline: False
```
**Symbols:**

```
ffffffff813c7920-ffffffff813c79a2: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813f6f50)
Location: security/inode.c:254
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff813f6f50-ffffffff813f6fdd: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81412a00)
Location: security/inode.c:255
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff81412a00-ffffffff81412a8c: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81440440)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff81440440-ffffffff814404c3: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81459d10)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff81459d10-ffffffff81459d93: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814acf90)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff814acf90-ffffffff814ad013: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814ca4e0)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff814ca4e0-ffffffff814ca563: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814d0b10)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff814d0b10-ffffffff814d0b93: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81529840)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff81529840-ffffffff815298c3: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff815bf050)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff815bf050-ffffffff815bf0e5: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8166b430)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff8166b430-ffffffff8166b4c5: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816a3b90)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff816a3b90-ffffffff816a3c25: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff816e05f0)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff816e05f0-ffffffff816e0685: securityfs_create_symlink (STB_GLOBAL)
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
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffff800010546060)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffff800010546060-ffff8000105460f0: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c06fbe38)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
c06fbe38-c06fbec4: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (c00000000069ca30)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
c00000000069ca30-c00000000069caf8: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffe0003a1b84)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffe0003a1b84-ffffffe0003a1bfe: securityfs_create_symlink (STB_GLOBAL)
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
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff814522f0)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff814522f0-ffffffff81452373: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81442d40)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff81442d40-ffffffff81442dc3: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8144e390)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff8144e390-ffffffff8144e413: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *securityfs_create_symlink(const char *name, struct dentry *parent, const char *target, const struct inode_operations *iops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81465760)
Location: security/inode.c:260
Inline: False
Direct callers:
  - security/apparmor/apparmorfs.c:aa_create_aafs
  - security/integrity/ima/ima_fs.c:ima_fs_init
  - security/integrity/evm/evm_secfs.c:evm_init_secfs
```
**Symbols:**

```
ffffffff81465760-ffffffff814657e3: securityfs_create_symlink (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
