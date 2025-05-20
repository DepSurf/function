# Function: <code>migrate_swap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abe00)
Location: kernel/sched/core.c:1376
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810abe00-ffffffff810abf3b: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aeaa0)
Location: kernel/sched/core.c:1323
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810aeaa0-ffffffff810aebc2: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4be0)
Location: kernel/sched/core.c:1334
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b4be0-ffffffff810b4cfa: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0cd0)
Location: kernel/sched/core.c:1266
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b0cd0-ffffffff810b0de5: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8120)
Location: kernel/sched/core.c:1285
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810b8120-ffffffff810b8238: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfc20)
Location: kernel/sched/core.c:1283
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810bfc20-ffffffff810bfd38: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8fa0)
Location: kernel/sched/core.c:1279
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_fault
```
**Symbols:**

```
ffffffff810c8fa0-ffffffff810c90ad: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0b40)
Location: kernel/sched/core.c:1719
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d0b40-ffffffff810d0c6f: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810daaf0)
Location: kernel/sched/core.c:1839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810daaf0-ffffffff810dac1f: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3990)
Location: kernel/sched/core.c:1909
Inline: False
```
**Symbols:**

```
ffffffff810e3990-ffffffff810e3aac: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1400)
Location: kernel/sched/core.c:2535
Inline: False
```
**Symbols:**

```
ffffffff810e1400-ffffffff810e14f2: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3220)
Location: kernel/sched/core.c:2556
Inline: False
```
**Symbols:**

```
ffffffff810e3220-ffffffff810e330f: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f9cc0)
Location: kernel/sched/core.c:3124
Inline: False
```
**Symbols:**

```
ffffffff810f9cc0-ffffffff810f9dac: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116260)
Location: kernel/sched/core.c:3223
Inline: False
```
**Symbols:**

```
ffffffff81116260-ffffffff8111638e: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113d730)
Location: kernel/sched/core.c:3279
Inline: False
```
**Symbols:**

```
ffffffff8113d730-ffffffff8113d85e: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114a600)
Location: kernel/sched/core.c:3456
Inline: False
```
**Symbols:**

```
ffffffff8114a600-ffffffff8114a72e: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81156170)
Location: kernel/sched/core.c:3477
Inline: False
```
**Symbols:**

```
ffffffff81156170-ffffffff8115629e: migrate_swap (STB_GLOBAL)
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
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013a668)
Location: kernel/sched/core.c:1839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffff80001013a668-ffff80001013a7ec: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000187f50)
Location: kernel/sched/core.c:1839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
c000000000187f50-c000000000188180: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4fa0)
Location: kernel/sched/core.c:1839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d4fa0-ffffffff810d50cf: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c35f0)
Location: kernel/sched/core.c:1839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810c35f0-ffffffff810c371f: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1de0)
Location: kernel/sched/core.c:1839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810d1de0-ffffffff810d1f0f: migrate_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int migrate_swap(struct task_struct *cur, struct task_struct *p, int target_cpu, int curr_cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc800)
Location: kernel/sched/core.c:1839
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_numa_migrate
```
**Symbols:**

```
ffffffff810dc800-ffffffff810dc94d: migrate_swap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int target_cpu</code>
</li>
<li>
<b>Param added. </b>
<code>int curr_cpu</code>
</li>
</ul>
</details>
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
