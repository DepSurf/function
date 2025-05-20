# Function: <code>kthread_set_per_cpu</code>

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
void kthread_set_per_cpu(struct task_struct *k, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc1b0)
Location: kernel/kthread.c:512
Inline: False
Direct callers:
  - kernel/workqueue.c:rebind_workers
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:worker_attach_to_pool
```
**Symbols:**

```
ffffffff810cc1b0-ffffffff810cc1f3: kthread_set_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kthread_set_per_cpu(struct task_struct *k, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cdc90)
Location: kernel/kthread.c:539
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff810cdc90-ffffffff810cdcd3: kthread_set_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kthread_set_per_cpu(struct task_struct *k, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0ee0)
Location: kernel/kthread.c:539
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_offline_cpu
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff810e0ee0-ffffffff810e0f23: kthread_set_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kthread_set_per_cpu(struct task_struct *k, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fb2a0)
Location: kernel/kthread.c:599
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff810fb2a0-ffffffff810fb2fb: kthread_set_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kthread_set_per_cpu(struct task_struct *k, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111e1b0)
Location: kernel/kthread.c:599
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_workers
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff8111e1b0-ffffffff8111e20b: kthread_set_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kthread_set_per_cpu(struct task_struct *k, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112b410)
Location: kernel/kthread.c:600
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_worker
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff8112b410-ffffffff8112b46b: kthread_set_per_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kthread_set_per_cpu(struct task_struct *k, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135b60)
Location: kernel/kthread.c:599
Inline: False
Direct callers:
  - kernel/workqueue.c:workqueue_online_cpu
  - kernel/workqueue.c:unbind_worker
  - kernel/workqueue.c:worker_detach_from_pool
  - kernel/workqueue.c:worker_attach_to_pool
  - kernel/smpboot.c:__smpboot_create_thread
  - kernel/sched/core.c:init_idle
```
**Symbols:**

```
ffffffff81135b60-ffffffff81135bbb: kthread_set_per_cpu (STB_GLOBAL)
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
