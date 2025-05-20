# Function: <code>cgroup_move_task</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ef900)
Location: kernel/sched/psi.c:659
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff810ef900-ffffffff810efa56: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6dd0)
Location: kernel/sched/psi.c:901
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff810f6dd0-ffffffff810f6f0f: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81102b60)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff81102b60-ffffffff81102c9f: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110db90)
Location: kernel/sched/psi.c:949
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8110db90-ffffffff8110dcf3: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110aee0)
Location: kernel/sched/psi.c:965
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8110aee0-ffffffff8110b050: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110cb10)
Location: kernel/sched/psi.c:977
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8110cb10-ffffffff8110cbe1: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112bb70)
Location: kernel/sched/psi.c:992
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8112bb70-ffffffff8112bc3c: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114c320)
Location: kernel/sched/psi.c:990
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8114c320-ffffffff8114c400: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117aeb0)
Location: kernel/sched/psi.c:1120
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8117aeb0-ffffffff8117af8f: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118ba10)
Location: kernel/sched/psi.c:1143
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8118ba10-ffffffff8118baef: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119a370)
Location: kernel/sched/psi.c:1135
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff8119a370-ffffffff8119a44f: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff8000101679b0)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffff8000101679b0-ffff800010167b24: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b47d4)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
c03b47d4-c03b4948: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bf7e0)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
c0000000001bf7e0-c0000000001bf9d0: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000109f12)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffe000109f12-ffffffe00010a080: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fbe70)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff810fbe70-ffffffff810fbfaf: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810ec080)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff810ec080-ffffffff810ec1bf: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f9030)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff810f9030-ffffffff810f916f: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_move_task(struct task_struct *task, struct css_set *to);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81104170)
Location: kernel/sched/psi.c:902
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:css_set_move_task
```
**Symbols:**

```
ffffffff81104170-ffffffff811042ad: cgroup_move_task (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
