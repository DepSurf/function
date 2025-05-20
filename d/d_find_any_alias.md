# Function: <code>d_find_any_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81222c50)
Location: fs/dcache.c:1921
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/kernfs/file.c:kernfs_notify_workfn
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff81222c50-ffffffff81222ca0: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124aa40)
Location: fs/dcache.c:1880
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff8124aa40-ffffffff8124aa9b: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125da00)
Location: fs/dcache.c:1889
Inline: False
Direct callers:
  - fs/dcache.c:__d_obtain_alias
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff8125da00-ffffffff8125da5b: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126b440)
Location: fs/dcache.c:1919
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff8126b440-ffffffff8126b49b: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128dcc0)
Location: fs/dcache.c:1931
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
```
**Symbols:**

```
ffffffff8128dcc0-ffffffff8128dd1b: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b4a80)
Location: fs/dcache.c:921
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812b4a80-ffffffff812b4adb: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9d40)
Location: fs/dcache.c:934
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812c9d40-ffffffff812c9d9b: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6730)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812e6730-ffffffff812e678a: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8290)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812f8290-ffffffff812f82ea: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81332f72)
Location: fs/dcache.c:981
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_parent
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81331090-ffffffff813310e7: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133e4a2)
Location: fs/dcache.c:988
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:evict_dentries_for_decrypted_inodes
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_parent
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8133ca20-ffffffff8133ca77: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81344892)
Location: fs/dcache.c:991
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81342ea0-ffffffff81342ef7: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81392382)
Location: fs/dcache.c:991
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81390800-ffffffff81390857: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81414033)
Location: fs/dcache.c:1016
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81411990-ffffffff814119eb: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149f483)
Location: fs/dcache.c:1016
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8149c390-ffffffff8149c3eb: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d47a3)
Location: fs/dcache.c:1016
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff814d16e0-ffffffff814d173b: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8150699d)
Location: fs/dcache.c:941
Inline: True
Inline callers:
  - fs/dcache.c:__d_obtain_alias
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/crypto/keyring.c:try_to_lock_encrypted_files
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81503ff0-ffffffff8150404b: d_find_any_alias (STB_GLOBAL)
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
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a5b88)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffff8000103a5b88-ffff8000103a5c24: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c05876e8)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
c05876e8-c0587748: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049f480)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
c00000000049f480-c00000000049f560: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026c85e)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffe00026c85e-ffffffe00026c8ec: d_find_any_alias (STB_GLOBAL)
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
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0870)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812f0870-ffffffff812f08ca: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e14a0)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812e14a0-ffffffff812e14fa: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ee680)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812ee680-ffffffff812ee6da: d_find_any_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *d_find_any_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff190)
Location: fs/dcache.c:960
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/dcache.c:__d_obtain_alias
  - fs/crypto/keyring.c:do_remove_key
  - fs/ext4/fsync.c:ext4_sync_file
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff812ff190-ffffffff812ff1e8: d_find_any_alias (STB_GLOBAL)
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
