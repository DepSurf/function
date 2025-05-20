# Function: <code>kthread_flush_worker</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a8ff0)
Location: kernel/kthread.c:1130
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - drivers/block/loop.c:loop_clr_fd
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff810a8ff0-ffffffff810a909a: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a5d90)
Location: kernel/kthread.c:1135
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_clr_fd
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff810a5d90-ffffffff810a5e3a: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac360)
Location: kernel/kthread.c:1140
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_clr_fd
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff810ac360-ffffffff810ac3ea: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b2ca0)
Location: kernel/kthread.c:1158
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:loop_clr_fd
  - drivers/md/dm.c:__dm_suspend
  - drivers/md/dm.c:__dm_destroy
```
**Symbols:**

```
ffffffff810b2ca0-ffffffff810b2d2a: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bbf20)
Location: kernel/kthread.c:1160
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
```
**Symbols:**

```
ffffffff810bbf20-ffffffff810bbfaa: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2070)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffffffff810c2070-ffffffff810c20fc: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c85d0)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffffffff810c85d0-ffffffff810c865c: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d05d0)
Location: kernel/kthread.c:1206
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_unregister_controller
```
**Symbols:**

```
ffffffff810d05d0-ffffffff810d0691: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810caff0)
Location: kernel/kthread.c:1260
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
```
**Symbols:**

```
ffffffff810caff0-ffffffff810cb0b1: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cc960)
Location: kernel/kthread.c:1318
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
```
**Symbols:**

```
ffffffff810cc960-ffffffff810cca21: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810dffe0)
Location: kernel/kthread.c:1318
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
```
**Symbols:**

```
ffffffff810dffe0-ffffffff810e00a1: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fad60)
Location: kernel/kthread.c:1378
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff810fad60-ffffffff810fae2d: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111dbc0)
Location: kernel/kthread.c:1378
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff8111dbc0-ffffffff8111dc8d: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112adb0)
Location: kernel/kthread.c:1379
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
```
**Symbols:**

```
ffffffff8112adb0-ffffffff8112ae7d: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff811354d0)
Location: kernel/kthread.c:1396
Inline: False
Direct callers:
  - kernel/workqueue.c:alloc_and_link_pwqs
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/build_utility.c:sugov_exit
  - kernel/sched/build_utility.c:sugov_init
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_vblank_off
```
**Symbols:**

```
ffffffff811354d0-ffffffff8113559d: kthread_flush_worker (STB_GLOBAL)
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
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128010)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffff800010128010-ffff8000101280ac: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a218)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
c037a218-c037a2cc: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c000000000171e90)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
c000000000171e90-c000000000171f64: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000def44)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffffffe0000def44-ffffffe0000defca: kthread_flush_worker (STB_GLOBAL)
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
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2950)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffffffff810c2950-ffffffff810c29dc: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b11a0)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffffffff810b11a0-ffffffff810b122c: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c1ea0)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffffffff810c1ea0-ffffffff810c1f2c: kthread_flush_worker (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kthread_flush_worker(struct kthread_worker *worker);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca480)
Location: kernel/kthread.c:1170
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_destroy_worker
  - kernel/sched/cpufreq_schedutil.c:sugov_exit
  - kernel/sched/cpufreq_schedutil.c:sugov_init
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/block/loop.c:__loop_clr_fd
  - drivers/spi/spi.c:spi_destroy_queue
```
**Symbols:**

```
ffffffff810ca480-ffffffff810ca50c: kthread_flush_worker (STB_GLOBAL)
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
