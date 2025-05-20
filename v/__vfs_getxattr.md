# Function: <code>__vfs_getxattr</code>

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
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8126d8a0)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8126d8a0-ffffffff8126d90f: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8127b0c0)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8127b0c0-ffffffff8127b12f: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8129db40)
Location: fs/xattr.c:304
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8129db40-ffffffff8129dbb1: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812c41f0)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff812c41f0-ffffffff812c4261: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812d93f0)
Location: fs/xattr.c:302
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff812d93f0-ffffffff812d9461: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f7980)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff812f7980-ffffffff812f79f1: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81309580)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81309580-ffffffff813095f1: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81343de6)
Location: fs/xattr.c:340
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81342a90-ffffffff81342b01: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81350156)
Location: fs/xattr.c:378
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_xattr
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8134ecc0-ffffffff8134ed31: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81356caf)
Location: fs/xattr.c:390
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813558b0-ffffffff81355921: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff813a576f)
Location: fs/xattr.c:391
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff813a3cd0-ffffffff813a3d41: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81428e05)
Location: fs/xattr.c:392
Inline: True
Inline callers:
  - fs/xattr.c:vfs_getxattr
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81427b00-ffffffff81427b83: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814b4ec0)
Location: fs/xattr.c:413
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814b4ec0-ffffffff814b4f8f: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff814e9d30)
Location: fs/xattr.c:411
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff814e9d30-ffffffff814e9dff: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff8151dbd0)
Location: fs/xattr.c:411
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_file_xattr
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_xattr_get
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_read_protected_xattrs
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff8151dbd0-ffffffff8151dc9f: __vfs_getxattr (STB_GLOBAL)
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
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffff8000103bd710)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffff8000103bd710-ffff8000103bd78c: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c059ac34)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c059ac34-c059acac: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (c0000000004bb2e0)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
c0000000004bb2e0-c0000000004bb38c: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffe00027e998)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffe00027e998-ffffffe00027e9fe: __vfs_getxattr (STB_GLOBAL)
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
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81301b60)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81301b60-ffffffff81301bd1: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812f2780)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff812f2780-ffffffff812f27f1: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff812ff950)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff812ff950-ffffffff812ff9c1: __vfs_getxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t __vfs_getxattr(struct dentry *dentry, struct inode *inode, const char *name, void *value, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/xattr.c (ffffffff81310c90)
Location: fs/xattr.c:303
Inline: False
Direct callers:
  - fs/xattr.c:vfs_getxattr
  - fs/ecryptfs/inode.c:ecryptfs_getxattr_lower
  - security/commoncap.c:get_vfs_caps_from_disk
  - security/commoncap.c:cap_inode_need_killpriv
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:inode_doinit_use_xattr
  - security/selinux/hooks.c:sb_finish_set_opts
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/integrity/evm/evm_main.c:evm_verify_hmac
```
**Symbols:**

```
ffffffff81310c90-ffffffff81310d01: __vfs_getxattr (STB_GLOBAL)
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
