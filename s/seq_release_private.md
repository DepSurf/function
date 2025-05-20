# Function: <code>seq_release_private</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81230e60)
Location: fs/seq_file.c:611
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81230e60-ffffffff81230ead: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81259170)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81259170-ffffffff812591bd: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8126c620)
Location: fs/seq_file.c:621
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8126c620-ffffffff8126c667: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8127a1e0)
Location: fs/seq_file.c:607
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8127a1e0-ffffffff8127a227: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8129cc60)
Location: fs/seq_file.c:611
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8129cc60-ffffffff8129cca7: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812c2f90)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff812c2f90-ffffffff812c2fde: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812d7f00)
Location: fs/seq_file.c:602
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff812d7f00-ffffffff812d7f4e: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f6410)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff812f6410-ffffffff812f645f: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81307fe0)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81307fe0-ffffffff8130802f: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81341d70)
Location: fs/seq_file.c:590
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81341d70-ffffffff81341dbf: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8134e430)
Location: fs/seq_file.c:606
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8134e430-ffffffff8134e47f: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff81354770)
Location: fs/seq_file.c:627
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff81354770-ffffffff813547bf: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813a2b50)
Location: fs/seq_file.c:636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - mm/slub.c:slab_debug_trace_release
  - mm/slub.c:slab_debug_trace_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff813a2b50-ffffffff813a2b9f: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814268c0)
Location: fs/seq_file.c:620
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - mm/slub.c:slab_debug_trace_release
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff814268c0-ffffffff81426916: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814b3140)
Location: fs/seq_file.c:620
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - mm/slub.c:slab_debug_trace_release
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff814b3140-ffffffff814b3196: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff814e8190)
Location: fs/seq_file.c:620
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - mm/slub.c:slab_debug_trace_release
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff814e8190-ffffffff814e81e6: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8151c020)
Location: fs/seq_file.c:620
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - kernel/bpf/bpf_iter.c:prepare_seq_file
  - kernel/bpf/bpf_iter.c:iter_release
  - mm/slub.c:slab_debug_trace_release
  - mm/slub.c:slab_debug_trace_open
  - mm/slub.c:slab_debug_trace_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:pid_numa_maps_open
  - fs/proc/task_mmu.c:pid_smaps_open
  - fs/proc/task_mmu.c:pid_maps_open
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8151c020-ffffffff8151c076: seq_release_private (STB_GLOBAL)
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
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffff8000103bbb48)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffff8000103bbb48-ffff8000103bbb9c: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c05992c4)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
c05992c4-c0599318: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (c0000000004b9010)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
c0000000004b9010-c0000000004b9090: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffe00027d5c4)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffe00027d5c4-ffffffe00027d61c: seq_release_private (STB_GLOBAL)
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
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff813005c0)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff813005c0-ffffffff8130060f: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812f11e0)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff812f11e0-ffffffff812f122f: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff812fe3b0)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff812fe3b0-ffffffff812fe3ff: seq_release_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int seq_release_private(struct inode *inode, struct file *file);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/seq_file.c (ffffffff8130f6f0)
Location: fs/seq_file.c:614
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:__tracing_open
  - fs/proc_namespace.c:mounts_release
  - fs/proc/task_mmu.c:proc_map_release
  - fs/proc/task_mmu.c:proc_maps_open
  - fs/proc/generic.c:proc_seq_release
  - fs/proc/proc_net.c:seq_release_net
  - ipc/util.c:sysvipc_proc_release
```
**Symbols:**

```
ffffffff8130f6f0-ffffffff8130f73f: seq_release_private (STB_GLOBAL)
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
