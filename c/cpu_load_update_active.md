# Function: <code>cpu_load_update_active</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpu_load_update_active(struct rq *this_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bfd10)
Location: kernel/sched/fair.c:4862
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810bfd10-ffffffff810bfdad: cpu_load_update_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpu_load_update_active(struct rq *this_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c5bf0)
Location: kernel/sched/fair.c:5092
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810c5bf0-ffffffff810c5c8d: cpu_load_update_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpu_load_update_active(struct rq *this_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf7c0)
Location: kernel/sched/fair.c:5236
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810bf7c0-ffffffff810bf85d: cpu_load_update_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpu_load_update_active(struct rq *this_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c6fb0)
Location: kernel/sched/fair.c:5575
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810c6fb0-ffffffff810c7036: cpu_load_update_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpu_load_update_active(struct rq *this_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ceeb0)
Location: kernel/sched/fair.c:5771
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810ceeb0-ffffffff810cef36: cpu_load_update_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_load_update_active(struct rq *this_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d8420)
Location: kernel/sched/fair.c:5511
Inline: False
Direct callers:
  - kernel/sched/core.c:scheduler_tick
```
**Symbols:**

```
ffffffff810d8420-ffffffff810d84a6: cpu_load_update_active (STB_GLOBAL)
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
</ul>
