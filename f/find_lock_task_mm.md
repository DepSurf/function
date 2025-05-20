# Function: <code>find_lock_task_mm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811907d0)
Location: mm/oom_kill.c:102
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:dump_header
  - mm/oom_kill.c:oom_kill_process
  - mm/memcontrol.c:task_in_mem_cgroup
```
**Symbols:**

```
ffffffff811907d0-ffffffff8119084b: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811a4950)
Location: mm/oom_kill.c:107
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:__oom_reap_task
  - mm/memcontrol.c:task_in_mem_cgroup
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811a4950-ffffffff811a49cb: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811b5240)
Location: mm/oom_kill.c:107
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:oom_kill_process
  - mm/memcontrol.c:task_in_mem_cgroup
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811b5240-ffffffff811b52bb: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811bcf60)
Location: mm/oom_kill.c:110
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/memcontrol.c:task_in_mem_cgroup
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811bcf60-ffffffff811bcfdb: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811d1b70)
Location: mm/oom_kill.c:112
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/memcontrol.c:task_in_mem_cgroup
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811d1b70-ffffffff811d1beb: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff811f29a0)
Location: mm/oom_kill.c:112
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/memcontrol.c:task_in_mem_cgroup
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff811f29a0-ffffffff811f2a1b: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81204840)
Location: mm/oom_kill.c:120
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:dump_header
  - mm/memcontrol.c:task_in_mem_cgroup
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff81204840-ffffffff812048bb: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121bc30)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff8121bc30-ffffffff8121bcaf: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812295c0)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff812295c0-ffffffff8122963f: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81256775)
Location: mm/oom_kill.c:133
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
**Symbols:**

```
ffffffff81256f00-ffffffff81256f7f: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81260ea0)
Location: mm/oom_kill.c:135
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81260ea0-ffffffff81260f24: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81265a00)
Location: mm/oom_kill.c:135
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff81265a00-ffffffff81265a84: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812a2230)
Location: mm/oom_kill.c:136
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
```
**Symbols:**

```
ffffffff812a2230-ffffffff812a22b4: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff812fb05a)
Location: mm/oom_kill.c:133
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
**Symbols:**

```
ffffffff812fa5e0-ffffffff812fa66d: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813643aa)
Location: mm/oom_kill.c:133
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
**Symbols:**

```
ffffffff81364d80-ffffffff81364e0d: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8139687a)
Location: mm/oom_kill.c:133
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
**Symbols:**

```
ffffffff81397240-ffffffff813972cd: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff813c018a)
Location: mm/oom_kill.c:133
Inline: True
Inline callers:
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_badness
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
```
**Symbols:**

```
ffffffff813c1070-ffffffff813c10fd: find_lock_task_mm (STB_GLOBAL)
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
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffff8000102b72d0)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffff8000102b72d0-ffff8000102b73a0: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c04e3ffc)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
c04e3ffc-c04e4088: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (c00000000036eed0)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
c00000000036eed0-c00000000036efb4: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffe0001db646)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffe0001db646-ffffffe0001db6ea: find_lock_task_mm (STB_GLOBAL)
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
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81221c10)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff81221c10-ffffffff81221c8f: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff81214dc0)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff81214dc0-ffffffff81214e3f: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8121f9b0)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff8121f9b0-ffffffff8121fa2f: find_lock_task_mm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct task_struct *find_lock_task_mm(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/oom_kill.c (ffffffff8122ea50)
Location: mm/oom_kill.c:132
Inline: False
Direct callers:
  - kernel/cpu.c:clear_tasks_mm_cpumask
  - mm/oom_kill.c:__oom_kill_process
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
**Symbols:**

```
ffffffff8122ea50-ffffffff8122ead7: find_lock_task_mm (STB_GLOBAL)
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
