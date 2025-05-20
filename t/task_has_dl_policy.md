# Function: <code>task_has_dl_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a9825)
Location: kernel/sched/sched.h:116
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810af61f)
Location: kernel/sched/sched.h:124
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b575c)
Location: kernel/sched/sched.h:131
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff810b1983)
Location: kernel/sched/sched.h:153
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:153
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
In kernel/sched/core.c (ffffffff810b589d)
Location: kernel/sched/sched.h:154
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (0)
Location: kernel/sched/sched.h:154
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
In kernel/sched/core.c (ffffffff810c169f)
Location: kernel/sched/sched.h:184
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810d8962)
Location: kernel/sched/sched.h:184
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
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
In kernel/sched/core.c (ffffffff810ca9cf)
Location: kernel/sched/sched.h:191
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810e2462)
Location: kernel/sched/sched.h:191
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff810ead87)
Location: kernel/sched/sched.h:191
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810d268e)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810e8f66)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff810f1ba0)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810dcafe)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810f4a46)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff810fd860)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810e570b)
Location: kernel/sched/sched.h:191
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810fe157)
Location: kernel/sched/sched.h:191
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff8110805f)
Location: kernel/sched/sched.h:191
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810e3314)
Location: kernel/sched/sched.h:194
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810fc7f9)
Location: kernel/sched/sched.h:194
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff8110686f)
Location: kernel/sched/sched.h:194
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810e54b0)
Location: kernel/sched/sched.h:196
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810feb4d)
Location: kernel/sched/sched.h:196
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff811088b5)
Location: kernel/sched/sched.h:196
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810f55db)
Location: kernel/sched/sched.h:196
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff8111a590)
Location: kernel/sched/sched.h:196
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff81126a25)
Location: kernel/sched/sched.h:196
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff8111204c)
Location: kernel/sched/sched.h:214
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/build_policy.c (ffffffff8113a530)
Location: kernel/sched/sched.h:214
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff81147172)
Location: kernel/sched/sched.h:214
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff8113903c)
Location: kernel/sched/sched.h:215
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/build_policy.c (ffffffff81164dd6)
Location: kernel/sched/sched.h:215
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff81174b96)
Location: kernel/sched/sched.h:215
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff811482ab)
Location: kernel/sched/sched.h:215
Inline: True
Inline callers:
  - kernel/sched/core.c:__do_sys_sched_setattr
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/build_policy.c (ffffffff81175576)
Location: kernel/sched/sched.h:215
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff811857a3)
Location: kernel/sched/sched.h:215
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff81153aa0)
Location: kernel/sched/sched.h:204
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_sched_setattr
  - kernel/sched/core.c:__x64_sys_sched_setattr
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
```
```
In kernel/sched/build_policy.c (ffffffff8118387a)
Location: kernel/sched/sched.h:204
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:sched_dl_overflow
  - kernel/sched/build_policy.c:sched_dl_overflow
```
```
In kernel/sched/build_utility.c (ffffffff81193ee7)
Location: kernel/sched/sched.h:204
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
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
In kernel/sched/core.c (ffff80001013c62c)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffff800010157108)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffff8000101630b0)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (c038c9f0)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (c03a4cbc)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (c03af760)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (c00000000018ac94)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (c0000000001abbd8)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (c0000000001b98a4)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffe0000ebe40)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffe0000fdfb4)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffe000106c80)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810d6d0e)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810ede46)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff810f6b80)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810c55fe)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810dded6)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff810e6d50)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810d394e)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810eaf76)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff810f3d90)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
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
In kernel/sched/core.c (ffffffff810de8f9)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_setaffinity
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
```
In kernel/sched/deadline.c (ffffffff810f5f67)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/deadline.c:sched_dl_overflow
```
```
In kernel/sched/debug.c (ffffffff810fed80)
Location: kernel/sched/sched.h:185
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
</details>
</li>
</ul>

## Differences
