# Function: <code>select_idle_core</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd575)
Location: kernel/sched/fair.c:5675
Inline: True
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
In kernel/sched/fair.c (ffffffff810b7404)
Location: kernel/sched/fair.c:5620
Inline: True
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
In kernel/sched/fair.c (ffffffff810be934)
Location: kernel/sched/fair.c:6066
Inline: True
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
In kernel/sched/fair.c (ffffffff810c6aa5)
Location: kernel/sched/fair.c:6298
Inline: True
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
In kernel/sched/fair.c (ffffffff810cf015)
Location: kernel/sched/fair.c:6039
Inline: True
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
In kernel/sched/fair.c (ffffffff810d78c6)
Location: kernel/sched/fair.c:5904
Inline: True
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
In kernel/sched/fair.c (ffffffff810e1ee2)
Location: kernel/sched/fair.c:5859
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea2a0)
Location: kernel/sched/fair.c:6031
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff810ea2a0-ffffffff810ea3ff: select_idle_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, struct sched_domain *sd, int target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e7e60)
Location: kernel/sched/fair.c:6080
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_sibling
```
**Symbols:**

```
ffffffff810e7e60-ffffffff810e7f9a: select_idle_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, int core, struct cpumask *cpus, int *idle_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebbb0)
Location: kernel/sched/fair.c:6151
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_cpu
```
**Symbols:**

```
ffffffff810ebbb0-ffffffff810ebd06: select_idle_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, int core, struct cpumask *cpus, int *idle_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81103730)
Location: kernel/sched/fair.c:6202
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_cpu
```
**Symbols:**

```
ffffffff81103730-ffffffff81103987: select_idle_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, int core, struct cpumask *cpus, int *idle_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8111f600)
Location: kernel/sched/fair.c:6259
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_cpu
```
**Symbols:**

```
ffffffff8111f600-ffffffff8111f85c: select_idle_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, int core, struct cpumask *cpus, int *idle_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811447f0)
Location: kernel/sched/fair.c:6634
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_cpu
```
**Symbols:**

```
ffffffff811447f0-ffffffff81144988: select_idle_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, int core, struct cpumask *cpus, int *idle_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81154d10)
Location: kernel/sched/fair.c:6887
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_cpu
```
**Symbols:**

```
ffffffff81154d10-ffffffff81154ea8: select_idle_core (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int select_idle_core(struct task_struct *p, int core, struct cpumask *cpus, int *idle_cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81160a70)
Location: kernel/sched/fair.c:7283
Inline: False
Direct callers:
  - kernel/sched/fair.c:select_idle_cpu
  - kernel/sched/fair.c:select_idle_cpu
```
**Symbols:**

```
ffffffff81160a70-ffffffff81160c08: select_idle_core (STB_LOCAL)
```
</details>
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
In kernel/sched/fair.c (ffff800010142de0)
Location: kernel/sched/fair.c:5859
Inline: True
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
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5917
Inline: True
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
In kernel/sched/fair.c (c000000000190fcc)
Location: kernel/sched/fair.c:5859
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5917
Inline: True
```
</details>
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
In kernel/sched/fair.c (ffffffff810dc092)
Location: kernel/sched/fair.c:5859
Inline: True
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
In kernel/sched/fair.c (ffffffff810cb0a2)
Location: kernel/sched/fair.c:5859
Inline: True
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
In kernel/sched/fair.c (ffffffff810d8412)
Location: kernel/sched/fair.c:5859
Inline: True
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
In kernel/sched/fair.c (ffffffff810e3eb2)
Location: kernel/sched/fair.c:5859
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int core</code>
</li>
<li>
<b>Param added. </b>
<code>struct cpumask *cpus</code>
</li>
<li>
<b>Param added. </b>
<code>int *idle_cpu</code>
</li>
<li>
<b>Param removed. </b>
<code>struct sched_domain *sd</code>
</li>
<li>
<b>Param removed. </b>
<code>int target</code>
</li>
</ul>
</details>
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
