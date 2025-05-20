# Function: <code>decay_load_missed</code>

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
In kernel/sched/fair.c (ffffffff810b2823)
Location: kernel/sched/fair.c:4302
Inline: True
Inline callers:
  - kernel/sched/fair.c:__update_cpu_load
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
In kernel/sched/fair.c (ffffffff810b6cca)
Location: kernel/sched/fair.c:4652
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
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
In kernel/sched/fair.c (ffffffff810bc59a)
Location: kernel/sched/fair.c:4882
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
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
In kernel/sched/fair.c (ffffffff810b71ea)
Location: kernel/sched/fair.c:5025
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
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
In kernel/sched/fair.c (ffffffff810be33a)
Location: kernel/sched/fair.c:5364
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int decay_load_missed(long unsigned int load, long unsigned int missed_updates, int idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c53b0)
Location: kernel/sched/fair.c:5551
Inline: True
Direct callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
```
**Symbols:**

```
ffffffff810c53b0-ffffffff810c540b: decay_load_missed (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810ceae7)
Location: kernel/sched/fair.c:5293
Inline: True
Inline callers:
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
  - kernel/sched/fair.c:cpu_load_update
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
</ul>
