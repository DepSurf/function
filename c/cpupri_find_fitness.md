# Function: <code>cpupri_find_fitness</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810ff980)
Location: kernel/sched/cpupri.c:120
Inline: False
Direct callers:
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff810ff980-ffffffff810ffaef: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff810fe470)
Location: kernel/sched/cpupri.c:144
Inline: False
Direct callers:
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff810fe470-ffffffff810fe5c4: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff81100850)
Location: kernel/sched/cpupri.c:144
Inline: False
Direct callers:
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff81100850-ffffffff811009a6: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/cpupri.c (ffffffff8111c8b0)
Location: kernel/sched/cpupri.c:144
Inline: False
Direct callers:
  - kernel/sched/rt.c:find_lowest_rq
  - kernel/sched/cpupri.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff8111c8b0-ffffffff8111ca29: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81148c90)
Location: kernel/sched/cpupri.c:143
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff81148c90-ffffffff81148e42: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81177500)
Location: kernel/sched/cpupri.c:143
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff81177500-ffffffff811776c2: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81188150)
Location: kernel/sched/cpupri.c:143
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff81188150-ffffffff811882fa: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cpupri_find_fitness(struct cpupri *cp, struct task_struct *p, struct cpumask *lowest_mask, bool (*fitness_fn)(struct task_struct *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81196a10)
Location: kernel/sched/cpupri.c:144
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:find_lowest_rq
  - kernel/sched/build_utility.c:cpupri_find_fitness
```
**Symbols:**

```
ffffffff81196a10-ffffffff81196bd2: cpupri_find_fitness (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
