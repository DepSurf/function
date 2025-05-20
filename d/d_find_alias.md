# Function: <code>d_find_alias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81222d80)
Location: fs/dcache.c:891
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/devpts/inode.c:devpts_get_priv
  - fs/devpts/inode.c:devpts_pty_kill
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff81222d80-ffffffff81222ea6: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124ab80)
Location: fs/dcache.c:899
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8124ab80-ffffffff8124aca4: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125db40)
Location: fs/dcache.c:899
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8125db40-ffffffff8125dc64: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126b930)
Location: fs/dcache.c:931
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8126b930-ffffffff8126ba60: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e1c0)
Location: fs/dcache.c:943
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/commoncap.c:cap_inode_getsecurity
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:common_lsm_audit
```
**Symbols:**

```
ffffffff8128e1c0-ffffffff8128e2f0: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b5b80)
Location: fs/dcache.c:965
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812b5b80-ffffffff812b5c46: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ca3b0)
Location: fs/dcache.c:978
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812ca3b0-ffffffff812ca476: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e6e20)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812e6e20-ffffffff812e6ef5: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f8990)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812f8990-ffffffff812f8a65: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813319b0)
Location: fs/dcache.c:1025
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff813319b0-ffffffff81331a7f: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133d350)
Location: fs/dcache.c:1032
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff8133d350-ffffffff8133d41f: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81343960)
Location: fs/dcache.c:1035
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81343960-ffffffff81343a2f: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81391380)
Location: fs/dcache.c:1035
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81391380-ffffffff8139144f: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814119f0)
Location: fs/dcache.c:1060
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff814119f0-ffffffff81411ab7: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149c400)
Location: fs/dcache.c:1060
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8149c400-ffffffff8149c4c7: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d1750)
Location: fs/dcache.c:1060
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff814d1750-ffffffff814d1817: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81504060)
Location: fs/dcache.c:985
Inline: False
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/proc/inode.c:proc_invalidate_siblings_dcache
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81504060-ffffffff81504127: d_find_alias (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a6760)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffff8000103a6760-ffff8000103a68c8: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0587db8)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
c0587db8-c0587eb0: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c0000000004a0140)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
c0000000004a0140-c0000000004a0320: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026d1ee)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffe00026d1ee-ffffffe00026d36c: d_find_alias (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f0f70)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812f0f70-ffffffff812f1045: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e1ba0)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812e1ba0-ffffffff812e1c75: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eed80)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812eed80-ffffffff812eee55: d_find_alias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct dentry *d_find_alias(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812ff7f0)
Location: fs/dcache.c:1004
Inline: True
Direct callers:
  - mm/shmem.c:shmem_fh_to_dentry
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
  - fs/fat/namei_vfat.c:vfat_lookup
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/selinux/hooks.c:inode_doinit_with_dentry
  - security/lsm_audit.c:dump_common_audit_data
```
**Symbols:**

```
ffffffff812ff7f0-ffffffff812ff8cd: d_find_alias (STB_GLOBAL)
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
