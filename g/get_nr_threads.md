# Function: <code>get_nr_threads</code>

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
In kernel/sched/debug.c (ffffffff810c804b)
Location: include/linux/sched.h:2687
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff8127bba3)
Location: include/linux/sched.h:2687
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
```
```
In fs/proc/array.c (ffffffff8127fe5b)
Location: include/linux/sched.h:2687
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffffffff810cc63b)
Location: include/linux/sched.h:2956
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff812a8893)
Location: include/linux/sched.h:2956
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
```
```
In fs/proc/array.c (ffffffff812acea5)
Location: include/linux/sched.h:2956
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffffffff810d265b)
Location: include/linux/sched.h:3070
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff812be173)
Location: include/linux/sched.h:3070
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
```
```
In fs/proc/array.c (ffffffff812c2776)
Location: include/linux/sched.h:3070
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:530
Inline: True
```
```
In kernel/seccomp.c (ffffffff81150212)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff812cb947)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
```
```
In fs/proc/array.c (ffffffff812cfa06)
Location: include/linux/sched/signal.h:530
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:531
Inline: True
```
```
In kernel/seccomp.c (ffffffff8115cdb7)
Location: include/linux/sched/signal.h:531
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff812f0127)
Location: include/linux/sched/signal.h:531
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
```
```
In fs/proc/array.c (ffffffff812f4188)
Location: include/linux/sched/signal.h:531
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:559
Inline: True
```
```
In kernel/sched/membarrier.c (ffffffff810e4145)
Location: include/linux/sched/signal.h:559
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In kernel/seccomp.c (ffffffff8116b6dc)
Location: include/linux/sched/signal.h:559
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff8131d0d7)
Location: include/linux/sched/signal.h:559
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81321590)
Location: include/linux/sched/signal.h:559
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:601
Inline: True
```
```
In kernel/sched/membarrier.c (ffffffff810ee8c5)
Location: include/linux/sched/signal.h:601
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In kernel/seccomp.c (ffffffff81178bcc)
Location: include/linux/sched/signal.h:601
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff813343b7)
Location: include/linux/sched/signal.h:601
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813386a0)
Location: include/linux/sched/signal.h:601
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:632
Inline: True
```
```
In kernel/sched/membarrier.c (ffffffff810f56e8)
Location: include/linux/sched/signal.h:632
Inline: True
Inline callers:
  - kernel/sched/membarrier.c:membarrier_register_private_expedited
  - kernel/sched/membarrier.c:membarrier_register_global_expedited
```
```
In kernel/seccomp.c (ffffffff81185c76)
Location: include/linux/sched/signal.h:632
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff8135c867)
Location: include/linux/sched/signal.h:632
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81360d5f)
Location: include/linux/sched/signal.h:632
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:624
Inline: True
```
```
In kernel/seccomp.c (ffffffff81191cc3)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff81374e07)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff81378fbf)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffffffff81107ccb)
Location: include/linux/sched/signal.h:647
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/seccomp.c (ffffffff811a69bc)
Location: include/linux/sched/signal.h:647
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff813bc9f7)
Location: include/linux/sched/signal.h:647
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813c206f)
Location: include/linux/sched/signal.h:647
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffffffff811064db)
Location: include/linux/sched/signal.h:660
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/seccomp.c (ffffffff811a3fcc)
Location: include/linux/sched/signal.h:660
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff813ce4a7)
Location: include/linux/sched/signal.h:660
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813d41be)
Location: include/linux/sched/signal.h:660
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffffffff8110851b)
Location: include/linux/sched/signal.h:666
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/seccomp.c (ffffffff811a4a70)
Location: include/linux/sched/signal.h:666
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff813d512e)
Location: include/linux/sched/signal.h:666
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813daffe)
Location: include/linux/sched/signal.h:666
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffffffff8112668b)
Location: include/linux/sched/signal.h:664
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff81426a6e)
Location: include/linux/sched/signal.h:664
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8142c6fb)
Location: include/linux/sched/signal.h:664
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/build_utility.c (ffffffff81146dcb)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff814a03fe)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff814a5fad)
Location: include/linux/sched/signal.h:704
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/build_utility.c (ffffffff8117480b)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff8153531e)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8153b5ed)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/build_utility.c (ffffffff81185414)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff8156d4ee)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8157391d)
Location: include/linux/sched/signal.h:705
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/build_utility.c (ffffffff81193b74)
Location: include/linux/sched/signal.h:697
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:proc_sched_show_task
```
```
In fs/proc/base.c (ffffffff815a5e66)
Location: include/linux/sched/signal.h:697
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff815ac2c5)
Location: include/linux/sched/signal.h:697
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffff800010162dd8)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/seccomp.c (ffff800010209620)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffff80001043e630)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffff8000104454b0)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (c03af3f8)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/seccomp.c (c0448450)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (c06052dc)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (c060a500)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (c0000000001b954c)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/seccomp.c (c0000000002866fc)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (c000000000554190)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (c00000000055aeac)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (ffffffe0001069a6)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/sched/debug.c:proc_sched_show_task
  - kernel/sched/debug.c:proc_sched_show_task
```
```
In kernel/seccomp.c (ffffffe00016b6da)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffe0002d4e86)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffe0002db45e)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:624
Inline: True
```
```
In kernel/seccomp.c (ffffffff8118a2e3)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff8136d3e7)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8137159f)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:624
Inline: True
```
```
In kernel/seccomp.c (ffffffff8117d413)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff8135de77)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8136202f)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:624
Inline: True
```
```
In kernel/seccomp.c (ffffffff811880b3)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff8136aeb7)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8136f06f)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
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
In kernel/sched/debug.c (0)
Location: include/linux/sched/signal.h:624
Inline: True
```
```
In kernel/seccomp.c (ffffffff81195a11)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
```
In fs/proc/base.c (ffffffff8137e8c7)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_getattr
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff813829ff)
Location: include/linux/sched/signal.h:624
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
</ul>

## Differences
