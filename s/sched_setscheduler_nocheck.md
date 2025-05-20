# Function: <code>sched_setscheduler_nocheck</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa190)
Location: kernel/sched/core.c:4079
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810aa190-ffffffff810aa1a2: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ad96f)
Location: kernel/sched/core.c:4329
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810ace10-ffffffff810ace22: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3a6f)
Location: kernel/sched/core.c:4366
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810b2ea0-ffffffff810b2eb2: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0fdf)
Location: kernel/sched/core.c:4266
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810aedc0-ffffffff810aedd2: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b841f)
Location: kernel/sched/core.c:4310
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810b6000-ffffffff810b6012: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bff1f)
Location: kernel/sched/core.c:4445
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810bdd00-ffffffff810bdd12: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c928f)
Location: kernel/sched/core.c:4430
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810c6eb0-ffffffff810c6ec2: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0e5f)
Location: kernel/sched/core.c:4867
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810cd400-ffffffff810cd412: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dae0f)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810d6e30-ffffffff810d6e42: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3c98)
Location: kernel/sched/core.c:5315
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810e17f0-ffffffff810e187d: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e16e8)
Location: kernel/sched/core.c:6090
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810e30a0-ffffffff810e312d: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e34f8)
Location: kernel/sched/core.c:6391
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810e5240-ffffffff810e52cd: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f59e6)
Location: kernel/sched/core.c:7555
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810fc200-ffffffff810fc28d: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81112526)
Location: kernel/sched/core.c:7663
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff81118780-ffffffff8111881f: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811395b6)
Location: kernel/sched/core.c:7805
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff8113fe70-ffffffff8113ff0f: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81148826)
Location: kernel/sched/core.c:7914
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/trace/trace_osnoise.c:timerlat_main
```
**Symbols:**

```
ffffffff8114c340-ffffffff8114c3df: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81154046)
Location: kernel/sched/core.c:7975
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_fifo_low
  - kernel/sched/core.c:sched_set_fifo
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:kthread
  - kernel/rcu/tree.c:rcu_spawn_cpu_nocb_kthread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
  - kernel/trace/trace_osnoise.c:timerlat_main
```
**Symbols:**

```
ffffffff81158000-ffffffff8115809f: sched_setscheduler_nocheck (STB_GLOBAL)
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
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013aa18)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffff800010137638-ffff800010137680: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a45c)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
c0386544-c0386564: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0000000001884bc)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
c000000000182cd0-c000000000182cec: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ea1e2)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:__setup_irq
  - kernel/irq/manage.c:__setup_irq
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffe0000e7cdc-ffffffe0000e7d1a: sched_setscheduler_nocheck (STB_GLOBAL)
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
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d52bf)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810d1400-ffffffff810d1412: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c390f)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810bf770-ffffffff810bf782: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d20ff)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810cf4c0-ffffffff810cf4d2: sched_setscheduler_nocheck (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int sched_setscheduler_nocheck(struct task_struct *p, int policy, const struct sched_param *param);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcb8f)
Location: kernel/sched/core.c:5082
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_set_stop_task
Direct callers:
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/irq/manage.c:setup_irq_thread
  - kernel/rcu/tree.c:rcu_spawn_gp_kthread
```
**Symbols:**

```
ffffffff810d8ae0-ffffffff810d8af2: sched_setscheduler_nocheck (STB_GLOBAL)
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
