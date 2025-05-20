# Function: <code>task_gtime</code>

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
In kernel/exit.c (0)
Location: include/linux/sched.h:2060
Inline: True
```
```
In fs/proc/array.c (ffffffff812805df)
Location: include/linux/sched.h:2060
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (0)
Location: include/linux/sched.h:2202
Inline: True
```
```
In fs/proc/array.c (ffffffff812ad63e)
Location: include/linux/sched.h:2202
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (0)
Location: include/linux/sched.h:2275
Inline: True
```
```
In fs/proc/array.c (ffffffff812c2fba)
Location: include/linux/sched.h:2275
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (0)
Location: include/linux/sched/cputime.h:31
Inline: True
```
```
In fs/proc/array.c (ffffffff812d023e)
Location: include/linux/sched/cputime.h:31
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (0)
Location: include/linux/sched/cputime.h:32
Inline: True
```
```
In fs/proc/array.c (ffffffff812f4a36)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810926be)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/array.c (ffffffff81321666)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff8109a9a2)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_consider_task
```
```
In fs/proc/array.c (ffffffff81338776)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff8109ec0f)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (ffffffff81360e34)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810a519f)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (ffffffff81379094)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810aceeb)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/array.c (ffffffff813c2140)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810a85b4)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/array.c (ffffffff813d428f)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810a9476)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/array.c (ffffffff813db0cf)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810baf66)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/array.c (ffffffff8142c78f)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810d193d)
Location: include/linux/sched/cputime.h:33
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/array.c (ffffffff814a6042)
Location: include/linux/sched/cputime.h:33
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810f038d)
Location: include/linux/sched/cputime.h:33
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/array.c (ffffffff8153b682)
Location: include/linux/sched/cputime.h:33
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810fc34d)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
```
```
In fs/proc/array.c (ffffffff815739ad)
Location: include/linux/sched/cputime.h:24
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 task_gtime(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81182850)
Location: kernel/sched/cputime.c:824
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:__exit_signal
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff81182850-ffffffff811828f7: task_gtime (STB_GLOBAL)
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
In kernel/exit.c (ffff8000100fb100)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (ffff800010445584)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (c0358f98)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (c060a5b8)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (c000000000142540)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (c00000000055af8c)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffe0000c4d92)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (ffffffe0002db4f2)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff8109eabf)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (ffffffff81371674)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 task_gtime(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cputime.c (ffffffff810c8a10)
Location: kernel/sched/cputime.c:836
Inline: False
Direct callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
**Symbols:**

```
ffffffff810c8a10-ffffffff810c8ab5: task_gtime (STB_GLOBAL)
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
In kernel/exit.c (ffffffff8109ea6f)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (ffffffff8136f144)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
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
In kernel/exit.c (ffffffff810a6986)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - kernel/exit.c:wait_task_zombie
  - kernel/exit.c:release_task
```
```
In fs/proc/array.c (ffffffff81382ad4)
Location: include/linux/sched/cputime.h:32
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
