# Function: <code>psi_flags_change</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:752
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff8110c6a0-ffffffff8110c6f5: psi_flags_change (STB_LOCAL)
ffffffff8110df6b-ffffffff8110dfa8: psi_flags_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:768
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff81109890-ffffffff811098e5: psi_flags_change (STB_LOCAL)
ffffffff81bde81c-ffffffff81bde859: psi_flags_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:773
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff8110b710-ffffffff8110b765: psi_flags_change (STB_LOCAL)
ffffffff81bd09c4-ffffffff81bd0a01: psi_flags_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:785
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_switch
  - kernel/sched/psi.c:psi_task_change
```
**Symbols:**

```
ffffffff8112a0f0-ffffffff8112a145: psi_flags_change (STB_LOCAL)
ffffffff81ca93cc-ffffffff81ca9409: psi_flags_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/psi.c:784
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff8113db40-ffffffff8113dba9: psi_flags_change (STB_LOCAL)
ffffffff81e56b92-ffffffff81e56bcf: psi_flags_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168660)
Location: kernel/sched/psi.c:870
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff81168660-ffffffff811686ff: psi_flags_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81178ce0)
Location: kernel/sched/psi.c:893
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff81178ce0-ffffffff81178d7f: psi_flags_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void psi_flags_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81186a30)
Location: kernel/sched/psi.c:882
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_switch
  - kernel/sched/build_utility.c:psi_task_change
```
**Symbols:**

```
ffffffff81186a30-ffffffff81186acf: psi_flags_change (STB_LOCAL)
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
