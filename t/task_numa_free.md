# Function: <code>task_numa_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ba4b0)
Location: kernel/sched/fair.c:2055
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810ba4b0-ffffffff810ba56f: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd910)
Location: kernel/sched/fair.c:2168
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810bd910-ffffffff810bd9cf: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2e70)
Location: kernel/sched/fair.c:2300
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810c2e70-ffffffff810c2f2f: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bdb40)
Location: kernel/sched/fair.c:2296
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810bdb40-ffffffff810bdc03: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5830)
Location: kernel/sched/fair.c:2348
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810c5830-ffffffff810c58f3: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cd1e0)
Location: kernel/sched/fair.c:2376
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810cd1e0-ffffffff810cd2a3: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d5be0)
Location: kernel/sched/fair.c:2322
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810d5be0-ffffffff810d5ca3: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de690)
Location: kernel/sched/fair.c:2400
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810de690-ffffffff810de79f: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8be0)
Location: kernel/sched/fair.c:2358
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810e8be0-ffffffff810e8cef: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f33b0)
Location: kernel/sched/fair.c:2587
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
  - fs/exec.c:__do_execve_file
```
**Symbols:**

```
ffffffff810f33b0-ffffffff810f34e7: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f15f0)
Location: kernel/sched/fair.c:2601
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810f15f0-ffffffff810f1727: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f38e0)
Location: kernel/sched/fair.c:2598
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810f38e0-ffffffff810f3a14: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110d180)
Location: kernel/sched/fair.c:2587
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8110d180-ffffffff8110d2b4: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81128d60)
Location: kernel/sched/fair.c:2605
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81128d60-ffffffff81128ebd: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811527a0)
Location: kernel/sched/fair.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff811527a0-ffffffff811528fd: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81162040)
Location: kernel/sched/fair.c:2800
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff81162040-ffffffff8116219b: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116eb10)
Location: kernel/sched/fair.c:3029
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff8116eb10-ffffffff8116ec6b: task_numa_free (STB_GLOBAL)
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
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010148ab0)
Location: kernel/sched/fair.c:2358
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffff800010148ab0-ffff800010148c34: task_numa_free (STB_GLOBAL)
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
In kernel/fork.c (0)
Location: include/linux/sched/numa_balancing.h:37
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched/numa_balancing.h:37
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c00000000019a570)
Location: kernel/sched/fair.c:2358
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
c00000000019a570-c00000000019a760: task_numa_free (STB_GLOBAL)
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
In kernel/fork.c (0)
Location: include/linux/sched/numa_balancing.h:37
Inline: True
```
```
In fs/exec.c (0)
Location: include/linux/sched/numa_balancing.h:37
Inline: True
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
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e2d90)
Location: kernel/sched/fair.c:2358
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810e2d90-ffffffff810e2e9f: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1ea0)
Location: kernel/sched/fair.c:2358
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810d1ea0-ffffffff810d1faf: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810df110)
Location: kernel/sched/fair.c:2358
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810df110-ffffffff810df21f: task_numa_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void task_numa_free(struct task_struct *p, bool final);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eac50)
Location: kernel/sched/fair.c:2358
Inline: False
Direct callers:
  - kernel/fork.c:__put_task_struct
```
**Symbols:**

```
ffffffff810eac50-ffffffff810ead5f: task_numa_free (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool final</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
