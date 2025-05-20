# Function: <code>kthread_bind_mask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a0c70)
Location: kernel/kthread.c:364
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/workqueue.c:__alloc_workqueue_key
```
**Symbols:**

```
ffffffff810a0c70-ffffffff810a0c85: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a4360)
Location: kernel/kthread.c:364
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810a4360-ffffffff810a4375: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a9bd0)
Location: kernel/kthread.c:394
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffff810a9bd0-ffffffff810a9be5: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a6810)
Location: kernel/kthread.c:398
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810a6810-ffffffff810a6825: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810acf80)
Location: kernel/kthread.c:405
Inline: False
Direct callers:
  - kernel/workqueue.c:__alloc_workqueue_key
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810acf80-ffffffff810acf95: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b3ce0)
Location: kernel/kthread.c:419
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810b3ce0-ffffffff810b3cf5: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bce30)
Location: kernel/kthread.c:419
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810bce30-ffffffff810bce45: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2d10)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810c2d10-ffffffff810c2d25: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c92e0)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810c92e0-ffffffff810c92f5: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d16d0)
Location: kernel/kthread.c:464
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810d16d0-ffffffff810d16e5: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc100)
Location: kernel/kthread.c:466
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - fs/io-wq.c:create_io_worker
```
**Symbols:**

```
ffffffff810cc100-ffffffff810cc115: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cdbe0)
Location: kernel/kthread.c:493
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810cdbe0-ffffffff810cdbf5: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e0dc0)
Location: kernel/kthread.c:493
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810e0dc0-ffffffff810e0e28: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fb220)
Location: kernel/kthread.c:552
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810fb220-ffffffff810fb29c: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111e120)
Location: kernel/kthread.c:552
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff8111e120-ffffffff8111e19c: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112b380)
Location: kernel/kthread.c:553
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff8112b380-ffffffff8112b3fc: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81135ad0)
Location: kernel/kthread.c:552
Inline: False
Direct callers:
  - kernel/workqueue.c:init_rescuer
  - kernel/workqueue.c:create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff81135ad0-ffffffff81135b4c: kthread_bind_mask (STB_GLOBAL)
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
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128f48)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffff800010128f48-ffff800010128f80: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037b4e0)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c037b4e0-c037b500: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000173750)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
c000000000173750-c000000000173768: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfe10)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
```
**Symbols:**

```
ffffffe0000dfe10-ffffffe0000dfe44: kthread_bind_mask (STB_GLOBAL)
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
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c3660)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810c3660-ffffffff810c3675: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1e90)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810b1e90-ffffffff810b1ea5: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2bb0)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810c2bb0-ffffffff810c2bc5: kthread_bind_mask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kthread_bind_mask(struct task_struct *p, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caff0)
Location: kernel/kthread.c:428
Inline: False
Direct callers:
  - kernel/workqueue.c:create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810caff0-ffffffff810cb005: kthread_bind_mask (STB_GLOBAL)
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
