# Function: <code>__vfs_removexattr</code>

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
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126d910)
Location: fs/xattr.c:370
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8126d910-ffffffff8126d975: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b130)
Location: fs/xattr.c:370
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8127b130-ffffffff8127b191: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129dbc0)
Location: fs/xattr.c:371
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8129dbc0-ffffffff8129dc23: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4270)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff812c4270-ffffffff812c42d3: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9470)
Location: fs/xattr.c:368
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff812d9470-ffffffff812d94d3: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7a00)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff812f7a00-ffffffff812f7a65: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309600)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81309600-ffffffff81309665: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81342b10)
Location: fs/xattr.c:406
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81342b10-ffffffff81342b75: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134ed40)
Location: fs/xattr.c:444
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8134ed40-ffffffff8134eda5: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __vfs_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81355930)
Location: fs/xattr.c:458
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81355930-ffffffff8135599f: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __vfs_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a3d50)
Location: fs/xattr.c:459
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff813a3d50-ffffffff813a3dbf: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __vfs_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81427b90)
Location: fs/xattr.c:460
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81427b90-ffffffff81427c0f: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __vfs_removexattr(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b4fa0)
Location: fs/xattr.c:484
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff814b4fa0-ffffffff814b5069: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __vfs_removexattr(struct mnt_idmap *idmap, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e9e10)
Location: fs/xattr.c:505
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff814e9e10-ffffffff814e9ed9: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __vfs_removexattr(struct mnt_idmap *idmap, struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151dcb0)
Location: fs/xattr.c:505
Inline: False
Direct callers:
  - fs/xattr.c:__vfs_removexattr_locked
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff8151dcb0-ffffffff8151dd79: __vfs_removexattr (STB_GLOBAL)
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
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bd790)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffff8000103bd790-ffff8000103bd7fc: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059acac)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
c059acac-c059ad24: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bb390)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
c0000000004bb390-c0000000004bb440: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027e9fe)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffe00027e9fe-ffffffe00027ea6a: __vfs_removexattr (STB_GLOBAL)
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
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301be0)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81301be0-ffffffff81301c45: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2800)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff812f2800-ffffffff812f2865: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ff9d0)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff812ff9d0-ffffffff812ffa35: __vfs_removexattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __vfs_removexattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81310d10)
Location: fs/xattr.c:369
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_killpriv
  - security/integrity/ima/ima_appraise.c:ima_inode_post_setattr
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
```
**Symbols:**

```
ffffffff81310d10-ffffffff81310d75: __vfs_removexattr (STB_GLOBAL)
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
<code>dentry, name</code> ➡️ <code>mnt_userns, dentry, name</code>
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
