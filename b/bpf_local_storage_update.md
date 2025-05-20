# Function: <code>bpf_local_storage_update</code>

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
struct bpf_local_storage_data *bpf_local_storage_update(void *owner, struct bpf_local_storage_map *smap, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fec0)
Location: kernel/bpf/bpf_local_storage.c:324
Inline: False
Direct callers:
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff8122fec0-ffffffff812301bb: bpf_local_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_update(void *owner, struct bpf_local_storage_map *smap, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81225480)
Location: kernel/bpf/bpf_local_storage.c:329
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff81225480-ffffffff8122577a: bpf_local_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_update(void *owner, struct bpf_local_storage_map *smap, void *value, u64 map_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d470)
Location: kernel/bpf/bpf_local_storage.c:329
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff8125d470-ffffffff8125d76a: bpf_local_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_update(void *owner, struct bpf_local_storage_map *smap, void *value, u64 map_flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff812a7600)
Location: kernel/bpf/bpf_local_storage.c:362
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_task_storage_get
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff812a7600-ffffffff812a7a72: bpf_local_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_update(void *owner, struct bpf_local_storage_map *smap, void *value, u64 map_flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81305d20)
Location: kernel/bpf/bpf_local_storage.c:372
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff81305d20-ffffffff813061a2: bpf_local_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_update(void *owner, struct bpf_local_storage_map *smap, void *value, u64 map_flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81334a60)
Location: kernel/bpf/bpf_local_storage.c:552
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff81334a60-ffffffff81334ef5: bpf_local_storage_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_local_storage_data *bpf_local_storage_update(void *owner, struct bpf_local_storage_map *smap, void *value, u64 map_flags, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_local_storage.c (ffffffff81359170)
Location: kernel/bpf/bpf_local_storage.c:552
Inline: False
Direct callers:
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_inode_storage.c:bpf_inode_storage_get
  - kernel/bpf/bpf_inode_storage.c:bpf_fd_inode_storage_update_elem
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_get
  - kernel/bpf/bpf_cgrp_storage.c:bpf_cgrp_storage_update_elem
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get_tracing
  - net/core/bpf_sk_storage.c:bpf_sk_storage_get
  - net/core/bpf_sk_storage.c:bpf_fd_sk_storage_update_elem
```
**Symbols:**

```
ffffffff81359170-ffffffff81359561: bpf_local_storage_update (STB_GLOBAL)
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
<code>gfp_t gfp_flags</code>
</li>
</ul>
</details>
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
