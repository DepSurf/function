# Function: <code>vfs_getxattr_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81231f30)
Location: fs/xattr.c:181
Inline: False
Direct callers:
  - fs/xattr.c:vfs_xattr_cmp
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81231f30-ffffffff81232023: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8125a450)
Location: fs/xattr.c:189
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8125a450-ffffffff8125a547: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126db50)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8126db50-ffffffff8126dc5f: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b370)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8127b370-ffffffff8127b47f: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129ddf0)
Location: fs/xattr.c:269
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8129ddf0-ffffffff8129df07: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c4410)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff812c4410-ffffffff812c4527: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d9610)
Location: fs/xattr.c:267
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff812d9610-ffffffff812d9727: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7b90)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff812f7b90-ffffffff812f7ca4: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309790)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81309790-ffffffff813098a4: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81342ca0)
Location: fs/xattr.c:305
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81342ca0-ffffffff81342db4: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8134efb0)
Location: fs/xattr.c:343
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8134efb0-ffffffff8134f0c4: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813577c0)
Location: fs/xattr.c:355
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff813577c0-ffffffff813578d1: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a3fe0)
Location: fs/xattr.c:355
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_xattr_change
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff813a3fe0-ffffffff813a40f1: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81429310)
Location: fs/xattr.c:357
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_xattr_change
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81429310-ffffffff81429442: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_getxattr_alloc(struct user_namespace *mnt_userns, struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b6270)
Location: fs/xattr.c:378
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814b6270-ffffffff814b63a2: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_getxattr_alloc(struct mnt_idmap *idmap, struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814eaf80)
Location: fs/xattr.c:376
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814eaf80-ffffffff814eb0b2: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_getxattr_alloc(struct mnt_idmap *idmap, struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151ee20)
Location: fs/xattr.c:376
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:find_attach
  - security/integrity/ima/ima_template_lib.c:ima_eventevmsig_init
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8151ee20-ffffffff8151ef52: vfs_getxattr_alloc (STB_GLOBAL)
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
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bd958)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffff8000103bd958-ffff8000103bda7c: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059ae64)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
c059ae64-c059af88: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bb7c0)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
c0000000004bb7c0-c0000000004bb9a4: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027eb9c)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffe00027eb9c-ffffffe00027ec7e: vfs_getxattr_alloc (STB_GLOBAL)
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
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301d70)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81301d70-ffffffff81301e84: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2990)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff812f2990-ffffffff812f2aa4: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ffb60)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff812ffb60-ffffffff812ffc74: vfs_getxattr_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t vfs_getxattr_alloc(struct dentry *dentry, const char *name, char **xattr_value, size_t xattr_size, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81310ea0)
Location: fs/xattr.c:268
Inline: False
Direct callers:
  - security/commoncap.c:cap_inode_getsecurity
  - security/apparmor/domain.c:aa_xattrs_match
  - security/integrity/ima/ima_appraise.c:ima_read_xattr
  - security/integrity/evm/evm_main.c:evm_verify_hmac
  - security/integrity/evm/evm_crypto.c:evm_update_evmxattr
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81310ea0-ffffffff81310fb4: vfs_getxattr_alloc (STB_GLOBAL)
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
<code>dentry, name, xattr_value, xattr_size, flags</code> ➡️ <code>mnt_userns, dentry, name, xattr_value, xattr_size, flags</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>ssize_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
