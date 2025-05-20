# Function: <code>bpf_selem_unlink</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812302ab)
Location: kernel/bpf/bpf_local_storage.c:194
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
```
**Symbols:**

```
ffffffff8122fca0-ffffffff8122fcc1: bpf_selem_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225864)
Location: kernel/bpf/bpf_local_storage.c:197
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
```
**Symbols:**

```
ffffffff81225260-ffffffff81225281: bpf_selem_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem *selem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d874)
Location: kernel/bpf/bpf_local_storage.c:197
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
```
**Symbols:**

```
ffffffff8125d200-ffffffff8125d221: bpf_selem_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem *selem, bool use_trace_rcu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7b90)
Location: kernel/bpf/bpf_local_storage.c:226
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
```
**Symbols:**

```
ffffffff812a7370-ffffffff812a739e: bpf_selem_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem *selem, bool use_trace_rcu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81306591)
Location: kernel/bpf/bpf_local_storage.c:235
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
```
**Symbols:**

```
ffffffff81305a60-ffffffff81305a8e: bpf_selem_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem *selem, bool reuse_now);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff813354c1)
Location: kernel/bpf/bpf_local_storage.c:407
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
```
**Symbols:**

```
ffffffff81334740-ffffffff8133476e: bpf_selem_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_selem_unlink(struct bpf_local_storage_elem *selem, bool reuse_now);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81359b21)
Location: kernel/bpf/bpf_local_storage.c:407
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_local_storage_map_free
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_delete_recur
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_delete
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_delete_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_delete_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_delete
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_delete_elem
```
**Symbols:**

```
ffffffff81358e50-ffffffff81358e7e: bpf_selem_unlink (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool use_trace_rcu</code>
</li>
</ul>
</details>
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
<code>bool reuse_now</code>
</li>
<li>
<b>Param removed. </b>
<code>bool use_trace_rcu</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
