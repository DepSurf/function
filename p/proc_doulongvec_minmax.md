# Function: <code>proc_doulongvec_minmax</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81088560)
Location: kernel/sysctl.c:2453
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
```
**Symbols:**

```
ffffffff81088560-ffffffff8108859a: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108be4f)
Location: kernel/sysctl.c:2591
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
```
**Symbols:**

```
ffffffff8108bd70-ffffffff8108bdaa: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81090daf)
Location: kernel/sysctl.c:2579
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
```
**Symbols:**

```
ffffffff81090cd0-ffffffff81090d0a: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8108d4bf)
Location: kernel/sysctl.c:2786
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
```
**Symbols:**

```
ffffffff8108d400-ffffffff8108d429: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81094ddf)
Location: kernel/sysctl.c:2819
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
```
**Symbols:**

```
ffffffff81094d20-ffffffff81094d49: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810987bd)
Location: kernel/sysctl.c:2827
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
```
**Symbols:**

```
ffffffff810986b0-ffffffff810986d9: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a0b4d)
Location: kernel/sysctl.c:2886
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810a0a40-ffffffff810a0a69: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a54a5)
Location: kernel/sysctl.c:2967
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810a5380-ffffffff810a53af: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810aba85)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810ab960-ffffffff810ab98f: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b304b)
Location: kernel/sysctl.c:1216
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810b2f30-ffffffff810b2f5f: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ae87b)
Location: kernel/sysctl.c:1215
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810ae760-ffffffff810ae78f: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810af81b)
Location: kernel/sysctl.c:1286
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810af700-ffffffff810af72f: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810c216b)
Location: kernel/sysctl.c:1330
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810c2050-ffffffff810c207f: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810d98d7)
Location: kernel/sysctl.c:1139
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/umh.c:proc_cap_handler
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810d97a0-ffffffff810d97db: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810f8927)
Location: kernel/sysctl.c:1146
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/umh.c:proc_cap_handler
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810f87d0-ffffffff810f880b: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81104d07)
Location: kernel/sysctl.c:1124
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:proc_cap_handler
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff81104bb0-ffffffff81104beb: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff8110e657)
Location: kernel/sysctl.c:1124
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/umh.c:proc_cap_handler
  - kernel/umh.c:proc_cap_handler
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
  - net/ipv4/sysctl_net_ipv4.c:ipv4_ping_group_range
```
**Symbols:**

```
ffffffff8110e500-ffffffff8110e53b: proc_doulongvec_minmax (STB_GLOBAL)
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
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffff80001010418c)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffff800010104018-ffff800010104080: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c0360328)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
c03601dc-c036022c: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (c00000000014c224)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
c00000000014c0c0-c00000000014c100: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffe0000c9f9c)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffe0000c9e96-ffffffe0000c9ee6: proc_doulongvec_minmax (STB_GLOBAL)
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
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a53a5)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810a5280-ffffffff810a52af: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff81093d85)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff81093c60-ffffffff81093c8f: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810a5355)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810a5230-ffffffff810a525f: proc_doulongvec_minmax (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int proc_doulongvec_minmax(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ad415)
Location: kernel/sysctl.c:2969
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_taint
Direct callers:
  - kernel/hung_task.c:proc_dohung_task_timeout_secs
  - mm/page-writeback.c:dirty_bytes_handler
  - mm/page-writeback.c:dirty_background_bytes_handler
  - mm/util.c:overcommit_kbytes_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_overcommit_handler
  - mm/hugetlb.c:hugetlb_sysctl_handler_common
  - fs/file_table.c:proc_nr_files
  - fs/dcache.c:proc_nr_dentry
  - fs/inode.c:proc_nr_inodes
  - fs/quota/dquot.c:do_proc_dqstats
  - ipc/ipc_sysctl.c:proc_ipc_doulongvec_minmax
  - security/min_addr.c:mmap_min_addr_handler
  - net/core/sysctl_net_core.c:proc_dolongvec_minmax_bpf_restricted
```
**Symbols:**

```
ffffffff810ad2f0-ffffffff810ad31f: proc_doulongvec_minmax (STB_GLOBAL)
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
