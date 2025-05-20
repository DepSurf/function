# Function: <code>set_cpus_allowed_ptr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ab720)
Location: kernel/sched/core.c:1261
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:kernel_init_freeable
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/workqueue.c:workqueue_cpu_up_callback
  - kernel/kthread.c:kthread_create_on_node
  - kernel/kthread.c:kthreadd
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/cpuset.c:update_tasks_cpumask
  - kernel/cpuset.c:cpuset_attach
  - mm/vmscan.c:kswapd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff810ab720-ffffffff810ab732: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81fa6e88)
Location: kernel/sched/core.c:1197
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:kernel_init_freeable
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/cpuset.c:cpuset_fork
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff810ae380-ffffffff810ae392: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81fe2a2a)
Location: kernel/sched/core.c:1208
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:kernel_init_freeable
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cpuset.c:cpuset_fork
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
  - drivers/acpi/processor_throttling.c:acpi_processor_get_throttling
```
**Symbols:**

```
ffffffff810b44e0-ffffffff810b44f2: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff820c32f2)
Location: kernel/sched/core.c:1132
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810b04e0-ffffffff810b04f2: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff826cb3a8)
Location: kernel/sched/core.c:1147
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810b7910-ffffffff810b7922: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff826f5524)
Location: kernel/sched/core.c:1144
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810bf480-ffffffff810bf492: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828ac36e)
Location: kernel/sched/core.c:1139
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810c8780-ffffffff810c8792: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828c4c46)
Location: kernel/sched/core.c:1581
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810d0190-ffffffff810d01a2: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828cd21d)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810da140-ffffffff810da152: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82cee691)
Location: kernel/sched/core.c:1771
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:rebind_workers
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810e2de0-ffffffff810e2df2: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff82fdad49)
Location: kernel/sched/core.c:2395
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:rebind_workers
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810e0530-ffffffff810e0542: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff831e5847)
Location: kernel/sched/core.c:2416
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wq_worker_affinity
  - fs/io-wq.c:create_io_worker
```
**Symbols:**

```
ffffffff810e2350-ffffffff810e2362: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff832c97b7)
Location: kernel/sched/core.c:2851
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - fs/io_uring.c:io_sq_thread
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_init_new_worker
```
**Symbols:**

```
ffffffff810f86c0-ffffffff810f8721: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8347ca49)
Location: kernel/sched/core.c:2950
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io_uring.c:io_sq_thread
  - io_uring/io-wq.c:io_init_new_worker
```
**Symbols:**

```
ffffffff811149a0-ffffffff81114a1e: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff83ea7f7e)
Location: kernel/sched/core.c:3017
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_init_new_worker
```
**Symbols:**

```
ffffffff8113bd50-ffffffff8113bda9: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff836ccffe)
Location: kernel/sched/core.c:3193
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_worker
  - kernel/workqueue.c:unbind_worker
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_init_new_worker
```
**Symbols:**

```
ffffffff8114f270-ffffffff8114f2c9: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff838fe3de)
Location: kernel/sched/core.c:3223
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_worker
  - kernel/workqueue.c:unbind_worker
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:kthread
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_fork
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - kernel/trace/trace_hwlat.c:move_to_next_cpu
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/sqpoll.c:io_sq_thread
  - io_uring/io-wq.c:io_init_new_worker
```
**Symbols:**

```
ffffffff8115b110-ffffffff8115b169: set_cpus_allowed_ptr (STB_GLOBAL)
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
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff800011444aec)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffff800010139b48-ffff800010139b80: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c151eb7c)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
c038991c-c038993c: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000013692b0)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
c000000000187060-c000000000187078: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe000006992)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffe0000e9728-ffffffe0000e975c: set_cpus_allowed_ptr (STB_GLOBAL)
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
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828b6010)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810d45f0-ffffffff810d4602: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828ae19b)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810c2c40-ffffffff810c2c52: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828c8f0f)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810d1430-ffffffff810d1442: set_cpus_allowed_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_cpus_allowed_ptr(struct task_struct *p, const struct cpumask *new_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff828ce266)
Location: kernel/sched/core.c:1701
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init_smp
Direct callers:
  - init/main.c:rest_init
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/kthread.c:kthreadd
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/reboot.c:migrate_to_reboot_cpu
  - kernel/irq/manage.c:irq_thread_check_affinity
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_cpumask
  - mm/vmscan.c:kswapd_cpu_online
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd_cpu_online
  - mm/compaction.c:kcompactd
```
**Symbols:**

```
ffffffff810dbd90-ffffffff810dbda2: set_cpus_allowed_ptr (STB_GLOBAL)
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
