# Function: <code>select_idle_capacity</code>

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
int select_idle_capacity(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea100)
Location: kernel/sched/fair.c:6160
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff810ea100-ffffffff810ea2a0: select_idle_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int select_idle_capacity(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8060)
Location: kernel/sched/fair.c:6211
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff810e8060-ffffffff810e81cc: select_idle_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec1eb)
Location: kernel/sched/fair.c:6293
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811048b7)
Location: kernel/sched/fair.c:6361
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81121d1d)
Location: kernel/sched/fair.c:6430
Inline: True
Inline callers:
  - kernel/sched/fair.c:select_idle_sibling
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int select_idle_capacity(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81145540)
Location: kernel/sched/fair.c:6801
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff81145540-ffffffff811458d2: select_idle_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int select_idle_capacity(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811562d0)
Location: kernel/sched/fair.c:7054
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff811562d0-ffffffff8115669e: select_idle_capacity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int select_idle_capacity(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81162ca0)
Location: kernel/sched/fair.c:7426
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff81162ca0-ffffffff81162fcb: select_idle_capacity (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
