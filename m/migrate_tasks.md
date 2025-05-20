# Function: <code>migrate_tasks</code>

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
In kernel/sched/core.c (ffffffff810ac315)
Location: kernel/sched/core.c:5226
Inline: True
Inline callers:
  - kernel/sched/core.c:migration_call
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
In kernel/sched/core.c (ffffffff810b2be5)
Location: kernel/sched/core.c:5486
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
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
In kernel/sched/core.c (ffffffff810b91c8)
Location: kernel/sched/core.c:5520
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3cd7)
Location: kernel/sched/core.c:5403
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810baf74)
Location: kernel/sched/core.c:5482
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c244e)
Location: kernel/sched/core.c:5608
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cb73e)
Location: kernel/sched/core.c:5591
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3757)
Location: kernel/sched/core.c:6043
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddccc)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void migrate_tasks(struct rq *dead_rq, struct rq_flags *rf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e2f80)
Location: kernel/sched/core.c:6472
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_cpu_dying
```
**Symbols:**

```
ffffffff810e2f80-ffffffff810e3177: migrate_tasks (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013d5d4)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038d614)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000018c438)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7ebc)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6887)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d46ac)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfab2)
Location: kernel/sched/core.c:6237
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_cpu_dying
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
