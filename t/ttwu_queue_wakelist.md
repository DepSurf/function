# Function: <code>ttwu_queue_wakelist</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd4f0)
Location: kernel/sched/core.c:2467
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810dd4f0-ffffffff810dd5bf: ttwu_queue_wakelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810db690)
Location: kernel/sched/core.c:3153
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810db690-ffffffff810db776: ttwu_queue_wakelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbba0)
Location: kernel/sched/core.c:3174
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810dbba0-ffffffff810dbc89: ttwu_queue_wakelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810efd60)
Location: kernel/sched/core.c:3744
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff810efd60-ffffffff810eff12: ttwu_queue_wakelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110cf90)
Location: kernel/sched/core.c:3851
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff8110cf90-ffffffff8110d14b: ttwu_queue_wakelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81133a30)
Location: kernel/sched/core.c:3915
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff81133a30-ffffffff81133beb: ttwu_queue_wakelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81142450)
Location: kernel/sched/core.c:3996
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff81142450-ffffffff8114260b: ttwu_queue_wakelist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool ttwu_queue_wakelist(struct task_struct *p, int cpu, int wake_flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114d810)
Location: kernel/sched/core.c:4018
Inline: True
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:try_to_wake_up
```
**Symbols:**

```
ffffffff8114d810-ffffffff8114d9cb: ttwu_queue_wakelist (STB_LOCAL)
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
