# Function: <code>kthread_cancel_work_sync</code>

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
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a93b0)
Location: kernel/kthread.c:1102
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
```
**Symbols:**

```
ffffffff810a93b0-ffffffff810a93c2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810a60b0)
Location: kernel/kthread.c:1107
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
```
**Symbols:**

```
ffffffff810a60b0-ffffffff810a60c2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ac5c0)
Location: kernel/kthread.c:1112
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
```
**Symbols:**

```
ffffffff810ac5c0-ffffffff810ac5d2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b30f0)
Location: kernel/kthread.c:1130
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810b30f0-ffffffff810b3102: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810bc180)
Location: kernel/kthread.c:1132
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810bc180-ffffffff810bc192: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2370)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810c2370-ffffffff810c2382: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c88d0)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810c88d0-ffffffff810c88e2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810d12e0)
Location: kernel/kthread.c:1178
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810d12e0-ffffffff810d12f2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cbdb0)
Location: kernel/kthread.c:1232
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810cbdb0-ffffffff810cbdc2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810cd700)
Location: kernel/kthread.c:1290
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810cd700-ffffffff810cd712: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810e08f0)
Location: kernel/kthread.c:1290
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810e08f0-ffffffff810e0902: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810fa6d0)
Location: kernel/kthread.c:1350
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810fa6d0-ffffffff810fa6ea: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8111d4d0)
Location: kernel/kthread.c:1350
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff8111d4d0-ffffffff8111d4ea: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff8112a5f0)
Location: kernel/kthread.c:1351
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff8112a5f0-ffffffff8112a60a: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff81134c80)
Location: kernel/kthread.c:1368
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sugov_stop
  - drivers/gpu/drm/drm_vblank_work.c:drm_vblank_work_cancel_sync
  - drivers/watchdog/watchdog_dev.c:watchdog_dev_suspend
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff81134c80-ffffffff81134c9a: kthread_cancel_work_sync (STB_GLOBAL)
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
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffff800010128d90)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffff800010128d90-ffff800010128dc0: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c037a67c)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
c037a67c-c037a69c: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (c0000000001723a0)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
c0000000001723a0-c0000000001723b8: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffe0000dfcce)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffe0000dfcce-ffffffe0000dfcfa: kthread_cancel_work_sync (STB_GLOBAL)
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
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c2c50)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810c2c50-ffffffff810c2c62: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810b1490)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810b1490-ffffffff810b14a2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810c21a0)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810c21a0-ffffffff810c21b2: kthread_cancel_work_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool kthread_cancel_work_sync(struct kthread_work *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kthread.c (ffffffff810ca760)
Location: kernel/kthread.c:1142
Inline: False
Direct callers:
  - kernel/sched/cpufreq_schedutil.c:sugov_stop
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_unregister
```
**Symbols:**

```
ffffffff810ca760-ffffffff810ca772: kthread_cancel_work_sync (STB_GLOBAL)
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
