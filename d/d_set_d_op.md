# Function: <code>d_set_d_op</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81222940)
Location: fs/dcache.c:1662
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
**Symbols:**

```
ffffffff81222940-ffffffff81222a15: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124a5d0)
Location: fs/dcache.c:1698
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
**Symbols:**

```
ffffffff8124a5d0-ffffffff8124a6a5: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125d550)
Location: fs/dcache.c:1707
Inline: False
Direct callers:
  - mm/shmem.c:__shmem_file_setup
  - mm/shmem.c:__shmem_file_setup
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
**Symbols:**

```
ffffffff8125d550-ffffffff8125d625: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126ad70)
Location: fs/dcache.c:1737
Inline: False
Direct callers:
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
**Symbols:**

```
ffffffff8126ad70-ffffffff8126adf0: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128d5f0)
Location: fs/dcache.c:1749
Inline: False
Direct callers:
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
**Symbols:**

```
ffffffff8128d5f0-ffffffff8128d670: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b42d0)
Location: fs/dcache.c:1757
Inline: False
Direct callers:
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
  - fs/hugetlbfs/inode.c:hugetlb_file_setup
```
**Symbols:**

```
ffffffff812b42d0-ffffffff812b4349: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812c9590)
Location: fs/dcache.c:1760
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812c9590-ffffffff812c9609: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e5eb0)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812e5eb0-ffffffff812e5f30: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812f7960)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812f7960-ffffffff812f79e0: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81330590)
Location: fs/dcache.c:1855
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81330590-ffffffff81330610: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8133bf20)
Location: fs/dcache.c:1862
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8133bf20-ffffffff8133bfa0: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff813423b0)
Location: fs/dcache.c:1889
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff813423b0-ffffffff81342430: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8138fd10)
Location: fs/dcache.c:1890
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/libfs.c:generic_set_encrypted_ci_d_ops
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8138fd10-ffffffff8138fd90: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411330)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff81411330-ffffffff814113ba: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8149bf00)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff8149bf00-ffffffff8149bf8a: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff814d1140)
Location: fs/dcache.c:1915
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff814d1140-ffffffff814d11ca: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff815039d0)
Location: fs/dcache.c:1775
Inline: False
Direct callers:
  - fs/dcache.c:d_alloc_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff815039d0-ffffffff81503a5a: d_set_d_op (STB_GLOBAL)
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
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffff8000103a4f88)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffff8000103a4f88-ffff8000103a5080: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c05870f8)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c05870f8-c058723c: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (c00000000049eac0)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
c00000000049eac0-c00000000049ebd4: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffe00026bd90)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffe00026bd90-ffffffe00026be4a: d_set_d_op (STB_GLOBAL)
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
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812eff40)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812eff40-ffffffff812effc0: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812e0b70)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812e0b70-ffffffff812e0bf0: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812edd50)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812edd50-ffffffff812eddd0: d_set_d_op (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void d_set_d_op(struct dentry *dentry, const struct dentry_operations *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812fed70)
Location: fs/dcache.c:1834
Inline: False
Direct callers:
  - fs/file_table.c:alloc_file_pseudo
  - fs/dcache.c:__d_alloc
  - fs/proc/base.c:proc_task_instantiate
  - fs/proc/base.c:proc_pid_instantiate
  - fs/proc/base.c:proc_pident_instantiate
  - fs/proc/base.c:proc_map_files_instantiate
  - fs/proc/generic.c:proc_lookup_de
  - fs/proc/fd.c:proc_fdinfo_instantiate
  - fs/proc/fd.c:proc_fd_instantiate
  - fs/proc/namespaces.c:proc_ns_instantiate
  - fs/proc/proc_sysctl.c:proc_sys_lookup
```
**Symbols:**

```
ffffffff812fed70-ffffffff812fedf0: d_set_d_op (STB_GLOBAL)
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
