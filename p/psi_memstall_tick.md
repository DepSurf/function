# Function: <code>psi_memstall_tick</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ef6f0)
Location: kernel/sched/psi.c:550
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810ef6f0-ffffffff810ef784: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6b80)
Location: kernel/sched/psi.c:790
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810f6b80-ffffffff810f6c16: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81102910)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81102910-ffffffff811029a6: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d930)
Location: kernel/sched/psi.c:838
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff8110d930-ffffffff8110d9c6: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110ac20)
Location: kernel/sched/psi.c:854
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff8110ac20-ffffffff8110acb6: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010167668)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffff800010167668-ffff800010167744: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b44d0)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
c03b44d0-c03b4584: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bf340)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
c0000000001bf340-c0000000001bf484: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109bfc)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffe000109bfc-ffffffe000109caa: psi_memstall_tick (STB_GLOBAL)
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
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fbc20)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810fbc20-ffffffff810fbcb6: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ebe40)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810ebe40-ffffffff810ebed6: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f8de0)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810f8de0-ffffffff810f8e76: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void psi_memstall_tick(struct task_struct *task, int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103f30)
Location: kernel/sched/psi.c:791
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff81103f30-ffffffff81103fc6: psi_memstall_tick (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
