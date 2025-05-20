# Function: <code>__var_waitqueue</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810d9ab5)
Location: kernel/sched/wait_bit.c:152
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
```
**Symbols:**

```
ffffffff810d9910-ffffffff810d9939: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810e35b5)
Location: kernel/sched/wait_bit.c:152
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810e3410-ffffffff810e3439: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ea1c5)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810ea020-ffffffff810ea049: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f5b95)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810f59f0-ffffffff810f5a19: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ff130)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_unmount_inodes
  - fs/ext4/inode.c:ext4_break_layouts
```
**Symbols:**

```
ffffffff810ff130-ffffffff810ff159: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810fdc30)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
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
ffffffff810fdc30-ffffffff810fdc59: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81100010)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
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
ffffffff81100010-ffffffff81100039: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff8111c0b0)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
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
ffffffff8111c0b0-ffffffff8111c0d9: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113b870)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
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
ffffffff8113b870-ffffffff8113b89f: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811662a0)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
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
ffffffff811662a0-ffffffff811662cf: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176710)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
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
ffffffff81176710-ffffffff8117673f: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184990)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
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
ffffffff81184990-ffffffff811849bf: __var_waitqueue (STB_GLOBAL)
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
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010159200)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffff800010158ea0-ffff800010158eec: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c03a6560)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
c03a62b8-c03a62f0: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0000000001ad6d0)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
c0000000001ad440-c0000000001ad480: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0000ff2bc)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffe0000ff06a-ffffffe0000ff0aa: __var_waitqueue (STB_GLOBAL)
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
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810eef95)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810eedf0-ffffffff810eee19: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810df015)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810dee70-ffffffff810dee99: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810ec0c5)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810ebf20-ffffffff810ebf49: __var_waitqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
wait_queue_head_t *__var_waitqueue(void *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff810f7115)
Location: kernel/sched/wait_bit.c:153
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
Direct callers:
  - kernel/events/core.c:perf_event_free_task
  - mm/shmem.c:shmem_evict_inode
  - fs/notify/fsnotify.c:fsnotify_sb_delete
```
**Symbols:**

```
ffffffff810f6f70-ffffffff810f6f99: __var_waitqueue (STB_GLOBAL)
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
