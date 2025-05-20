# Function: <code>init_wait_var_entry</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d9940)
Location: kernel/sched/wait_bit.c:173
Inline: False
```
**Symbols:**

```
ffffffff810d9940-ffffffff810d9983: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810e3440)
Location: kernel/sched/wait_bit.c:173
Inline: False
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810e3440-ffffffff810e3483: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ea050)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810ea050-ffffffff810ea096: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f5a20)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810f5a20-ffffffff810f5a66: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ff160)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/ext4/inode.c:ext4_break_layouts
```
**Symbols:**

```
ffffffff810ff160-ffffffff810ff1ae: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810fdc60)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
**Symbols:**

```
ffffffff810fdc60-ffffffff810fdcae: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81100040)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/ext4/inode.c:ext4_break_layouts
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
**Symbols:**

```
ffffffff81100040-ffffffff8110008e: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff8111c0e0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
**Symbols:**

```
ffffffff8111c0e0-ffffffff8111c12e: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113b8a0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_kill
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
**Symbols:**

```
ffffffff8113b8a0-ffffffff8113b905: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811662e0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
**Symbols:**

```
ffffffff811662e0-ffffffff81166345: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176750)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
**Symbols:**

```
ffffffff81176750-ffffffff811767b5: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811849d0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/softirq.c:tasklet_unlock_wait
  - kernel/softirq.c:tasklet_kill
  - kernel/sched/core.c:affine_move_task
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/super.c:grab_super
  - fs/super.c:super_lock
  - fs/notify/fsnotify.c:fsnotify_sb_delete
  - fs/fuse/dax.c:fuse_dax_break_layouts
```
**Symbols:**

```
ffffffff811849d0-ffffffff81184a35: init_wait_var_entry (STB_GLOBAL)
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
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010158ef0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffff800010158ef0-ffff800010158f44: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c03a62f0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
c03a62f0-c03a6354: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0000000001ad480)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
c0000000001ad480-c0000000001ad4d0: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0000ff0aa)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffe0000ff0aa-ffffffe0000ff0fa: init_wait_var_entry (STB_GLOBAL)
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
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810eee20)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810eee20-ffffffff810eee66: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810deea0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810deea0-ffffffff810deee6: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ebf50)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810ebf50-ffffffff810ebf96: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_wait_var_entry(struct wait_bit_queue_entry *wbq_entry, void *var, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f6fa0)
Location: kernel/sched/wait_bit.c:174
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810f6fa0-ffffffff810f6fe6: init_wait_var_entry (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
