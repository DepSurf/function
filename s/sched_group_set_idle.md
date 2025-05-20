# Function: <code>sched_group_set_idle</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sched_group_set_idle(struct task_group *tg, long int idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11652
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_idle_write_s64
```
**Symbols:**

```
ffffffff81ca6811-ffffffff81ca6834: sched_group_set_idle.cold (STB_LOCAL)
ffffffff81111530-ffffffff8111175d: sched_group_set_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sched_group_set_idle(struct task_group *tg, long int idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11770
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_idle_write_s64
```
**Symbols:**

```
ffffffff81e5604d-ffffffff81e56072: sched_group_set_idle.cold (STB_LOCAL)
ffffffff8112d750-ffffffff8112d9ba: sched_group_set_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sched_group_set_idle(struct task_group *tg, long int idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12286
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_idle_write_s64
```
**Symbols:**

```
ffffffff82057271-ffffffff82057296: sched_group_set_idle.cold (STB_LOCAL)
ffffffff81157530-ffffffff8115779e: sched_group_set_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sched_group_set_idle(struct task_group *tg, long int idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:12604
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_idle_write_s64
```
**Symbols:**

```
ffffffff820d5a9b-ffffffff820d5abe: sched_group_set_idle.cold (STB_LOCAL)
ffffffff81167580-ffffffff811677ed: sched_group_set_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sched_group_set_idle(struct task_group *tg, long int idle);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:13027
Inline: False
Direct callers:
  - kernel/sched/core.c:cpu_idle_write_s64
```
**Symbols:**

```
ffffffff821b0b13-ffffffff821b0b36: sched_group_set_idle.cold (STB_LOCAL)
ffffffff81174370-ffffffff811745e6: sched_group_set_idle (STB_GLOBAL)
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
