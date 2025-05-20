# Function: <code>__kthread_init_worker</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a96f7)
Location: kernel/kthread.c:577
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/spi/spi.c:spi_register_master
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff810a8db0-ffffffff810a8e06: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5ba0)
Location: kernel/kthread.c:582
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/spi/spi.c:spi_register_controller
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff810a5ba0-ffffffff810a5bf6: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac170)
Location: kernel/kthread.c:589
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/spi/spi.c:spi_register_controller
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff810ac170-ffffffff810ac1c6: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b2ac0)
Location: kernel/kthread.c:607
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/spi/spi.c:spi_register_controller
  - drivers/md/dm-rq.c:dm_old_init_request_queue
```
**Symbols:**

```
ffffffff810b2ac0-ffffffff810b2b16: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bbd40)
Location: kernel/kthread.c:609
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:lo_ioctl
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff810bbd40-ffffffff810bbd96: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1e90)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff810c1e90-ffffffff810c1ee6: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c83f0)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff810c83f0-ffffffff810c8446: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d0e66)
Location: kernel/kthread.c:654
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - drivers/block/loop.c:loop_configure
  - drivers/spi/spi.c:spi_init_queue
```
**Symbols:**

```
ffffffff810cff90-ffffffff810cffdf: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cb916)
Location: kernel/kthread.c:680
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff810ca980-ffffffff810ca9cf: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd196)
Location: kernel/kthread.c:707
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff810cc4a0-ffffffff810cc4ef: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e036a)
Location: kernel/kthread.c:707
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810df7b0-ffffffff810df7ff: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810f9bd0)
Location: kernel/kthread.c:767
Inline: True
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff810f9bd0-ffffffff810f9c2b: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111c5b0)
Location: kernel/kthread.c:768
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff8111c5b0-ffffffff8111c60b: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81129800)
Location: kernel/kthread.c:769
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff81129800-ffffffff8112985b: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81133e40)
Location: kernel/kthread.c:786
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/build_utility.c:sugov_kthread_create
```
**Symbols:**

```
ffffffff81133e40-ffffffff81133e9b: __kthread_init_worker (STB_GLOBAL)
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
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010127278)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffff800010127278-ffff8000101272c0: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0379dc8)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c0379dc8-c0379e08: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000171b70)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
c000000000171b70-c000000000171ba8: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000df80e)
Location: kernel/kthread.c:618
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
Direct callers:
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffe0000ded66-ffffffe0000dedaa: __kthread_init_worker (STB_GLOBAL)
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
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2770)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff810c2770-ffffffff810c27c6: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b0fc0)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff810b0fc0-ffffffff810b1016: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1cc0)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff810c1cc0-ffffffff810c1d16: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __kthread_init_worker(struct kthread_worker *worker, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca0f0)
Location: kernel/kthread.c:618
Inline: False
Direct callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_set_fd
  - drivers/spi/spi.c:spi_register_controller
```
**Symbols:**

```
ffffffff810ca0f0-ffffffff810ca146: __kthread_init_worker (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
