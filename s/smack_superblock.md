# Function: <code>smack_superblock</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c2c95)
Location: security/smack/smack.h:396
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e8f55)
Location: security/smack/smack.h:396
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_bprm_set_creds
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f7b6e)
Location: security/smack/smack.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8155272e)
Location: security/smack/smack.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ec1ba)
Location: security/smack/smack.h:361
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169be7a)
Location: security/smack/smack.h:352
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d49fa)
Location: security/smack/smack.h:353
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81710d4d)
Location: security/smack/smack.h:352
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_d_instantiate
  - security/smack/smack_lsm.c:smack_mmap_file
  - security/smack/smack_lsm.c:smack_inode_removexattr
  - security/smack/smack_lsm.c:smack_inode_permission
  - security/smack/smack_lsm.c:smack_bprm_creds_for_exec
  - security/smack/smack_lsm.c:smack_sb_statfs
  - security/smack/smack_lsm.c:smack_set_mnt_opts
  - security/smack/smack_lsm.c:smack_fs_context_submount
  - security/smack/smack_lsm.c:smack_sb_alloc_security
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
