# Function: <code>bpf_local_storage_lookup</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_lookup(struct bpf_local_storage *local_storage, struct bpf_local_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fcd0)
Location: kernel/bpf/bpf_local_storage.c:205
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
**Symbols:**

```
ffffffff8122fcd0-ffffffff8122fd7d: bpf_local_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_lookup(struct bpf_local_storage *local_storage, struct bpf_local_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225290)
Location: kernel/bpf/bpf_local_storage.c:208
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
**Symbols:**

```
ffffffff81225290-ffffffff81225340: bpf_local_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_lookup(struct bpf_local_storage *local_storage, struct bpf_local_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d230)
Location: kernel/bpf/bpf_local_storage.c:208
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_diag_put
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
**Symbols:**

```
ffffffff8125d230-ffffffff8125d32a: bpf_local_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_lookup(struct bpf_local_storage *local_storage, struct bpf_local_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a73a0)
Location: kernel/bpf/bpf_local_storage.c:237
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
**Symbols:**

```
ffffffff812a73a0-ffffffff812a74a0: bpf_local_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_lookup(struct bpf_local_storage *local_storage, struct bpf_local_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81305aa0)
Location: kernel/bpf/bpf_local_storage.c:247
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
**Symbols:**

```
ffffffff81305aa0-ffffffff81305ba0: bpf_local_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_lookup(struct bpf_local_storage *local_storage, struct bpf_local_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81334780)
Location: kernel/bpf/bpf_local_storage.c:419
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
**Symbols:**

```
ffffffff81334780-ffffffff8133487c: bpf_local_storage_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_lookup(struct bpf_local_storage *local_storage, struct bpf_local_storage_map *smap, bool cacheit_lockit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81358e90)
Location: kernel/bpf/bpf_local_storage.c:419
Inline: False
Direct callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_update
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_lookup_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_lookup_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_lookup_elem
```
**Symbols:**

```
ffffffff81358e90-ffffffff81358f8c: bpf_local_storage_lookup (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
