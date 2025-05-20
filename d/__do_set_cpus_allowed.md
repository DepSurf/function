# Function: <code>__do_set_cpus_allowed</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc360)
Location: kernel/sched/core.c:2066
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810dc360-ffffffff810dc589: __do_set_cpus_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dd8f0)
Location: kernel/sched/core.c:2073
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr
```
**Symbols:**

```
ffffffff810dd8f0-ffffffff810ddb19: __do_set_cpus_allowed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2451
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff810f1ff0-ffffffff810f22be: __do_set_cpus_allowed (STB_LOCAL)
ffffffff81ca5c2f-ffffffff81ca5c44: __do_set_cpus_allowed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __do_set_cpus_allowed(struct task_struct *p, const struct cpumask *new_mask, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2550
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff8110ddf0-ffffffff8110e0db: __do_set_cpus_allowed (STB_LOCAL)
ffffffff81e55547-ffffffff81e5555c: __do_set_cpus_allowed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __do_set_cpus_allowed(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2552
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff81134b30-ffffffff81134dfc: __do_set_cpus_allowed (STB_LOCAL)
ffffffff820569b4-ffffffff820569c9: __do_set_cpus_allowed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __do_set_cpus_allowed(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2728
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff81143d30-ffffffff81143ffc: __do_set_cpus_allowed (STB_LOCAL)
ffffffff820d50a0-ffffffff820d50b5: __do_set_cpus_allowed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __do_set_cpus_allowed(struct task_struct *p, struct affinity_context *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (0)
Location: kernel/sched/core.c:2756
Inline: False
Direct callers:
  - kernel/sched/core.c:__schedule
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:__set_cpus_allowed_ptr_locked
```
**Symbols:**

```
ffffffff8114f250-ffffffff8114f51c: __do_set_cpus_allowed (STB_LOCAL)
ffffffff821affc3-ffffffff821affd8: __do_set_cpus_allowed.cold (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct affinity_context *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct cpumask *new_mask</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
