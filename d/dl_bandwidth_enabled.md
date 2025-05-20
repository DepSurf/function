# Function: <code>dl_bandwidth_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:179
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:179
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:187
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:187
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:194
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:194
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:216
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:216
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/sched.h:217
Inline: True
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:217
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c16b0)
Location: kernel/sched/sched.h:273
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810d7005)
Location: kernel/sched/sched.h:273
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ca9e0)
Location: kernel/sched/sched.h:280
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810e1555)
Location: kernel/sched/sched.h:280
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d269d)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810e7ff9)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dcb0d)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/deadline.c (ffffffff810f3e2e)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e577b)
Location: kernel/sched/sched.h:286
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810fd7f4)
Location: kernel/sched/sched.h:286
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3384)
Location: kernel/sched/sched.h:265
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810fbdb4)
Location: kernel/sched/sched.h:265
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e5520)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810fe0d0)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f4aa4)
Location: kernel/sched/sched.h:276
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff811175b7)
Location: kernel/sched/sched.h:276
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811114dc)
Location: kernel/sched/sched.h:294
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/build_policy.c (ffffffff811345ad)
Location: kernel/sched/sched.h:294
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113849c)
Location: kernel/sched/sched.h:295
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/build_policy.c (ffffffff8115eace)
Location: kernel/sched/sched.h:295
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff811475a6)
Location: kernel/sched/sched.h:289
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/build_policy.c (ffffffff8116f1be)
Location: kernel/sched/sched.h:289
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81152dd6)
Location: kernel/sched/sched.h:276
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/build_policy.c (ffffffff8117ca3e)
Location: kernel/sched/sched.h:276
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013c638)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/deadline.c (ffff8000101560d8)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038c9f4)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/deadline.c (c03a3d30)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018aca0)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/deadline.c (c0000000001aa940)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ebe44)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/deadline.c (ffffffe0000fbf78)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d6d1d)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810ed22e)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c560d)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/deadline.c (ffffffff810dd2ce)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d395d)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
```
```
In kernel/sched/deadline.c (ffffffff810ea35e)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de97e)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
```
```
In kernel/sched/deadline.c (ffffffff810f531b)
Location: kernel/sched/sched.h:274
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
</details>
</li>
</ul>

## Differences
