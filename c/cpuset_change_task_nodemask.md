# Function: <code>cpuset_change_task_nodemask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8111b630)
Location: kernel/cpuset.c:1032
Inline: True
Direct callers:
  - kernel/cpuset.c:update_tasks_nodemask
  - kernel/cpuset.c:cpuset_attach
```
**Symbols:**

```
ffffffff8111b630-ffffffff8111b72f: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff81123540)
Location: kernel/cpuset.c:1043
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81123540-ffffffff81123617: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpuset.c (ffffffff8112b220)
Location: kernel/cpuset.c:1043
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_attach
  - kernel/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8112b220-ffffffff8112b48a: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8112c550)
Location: kernel/cgroup/cpuset.c:1047
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8112c550-ffffffff8112c681: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81139380)
Location: kernel/cgroup/cpuset.c:1058
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81139380-ffffffff811394b1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81148450)
Location: kernel/cgroup/cpuset.c:1059
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81148450-ffffffff81148581: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81153f70)
Location: kernel/cgroup/cpuset.c:1582
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81153f70-ffffffff811540a1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811604c0)
Location: kernel/cgroup/cpuset.c:1543
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811604c0-ffffffff811605f1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116c190)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8116c190-ffffffff8116c2c1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117e0c0)
Location: kernel/cgroup/cpuset.c:1619
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8117e0c0-ffffffff8117e1f1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117af30)
Location: kernel/cgroup/cpuset.c:1642
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8117af30-ffffffff8117b061: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8117c7b0)
Location: kernel/cgroup/cpuset.c:1642
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8117c7b0-ffffffff8117c8e1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811a4340)
Location: kernel/cgroup/cpuset.c:1693
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811a4340-ffffffff811a4471: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811d3df0)
Location: kernel/cgroup/cpuset.c:1731
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811d3df0-ffffffff811d3f2b: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81217bb0)
Location: kernel/cgroup/cpuset.c:1920
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81217bb0-ffffffff81217ceb: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8122d3d0)
Location: kernel/cgroup/cpuset.c:1955
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8122d3d0-ffffffff8122d50b: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff812456a0)
Location: kernel/cgroup/cpuset.c:2736
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach_task
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff812456a0-ffffffff812457db: cpuset_change_task_nodemask (STB_LOCAL)
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
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffff8000101e1048)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffff8000101e1048-ffff8000101e1120: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c0421cf8)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
c0421cf8-c0421d7c: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (c00000000024eff0)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
c00000000024eff0-c00000000024f12c: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffe000157d98)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffe000157d98-ffffffe000157e48: cpuset_change_task_nodemask (STB_LOCAL)
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
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff811647b0)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff811647b0-ffffffff811648e1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81157a00)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81157a00-ffffffff81157b25: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff81162580)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff81162580-ffffffff811626b1: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpuset_change_task_nodemask(struct task_struct *tsk, nodemask_t *newmems);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cpuset.c (ffffffff8116fb00)
Location: kernel/cgroup/cpuset.c:1617
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_attach
  - kernel/cgroup/cpuset.c:update_tasks_nodemask
```
**Symbols:**

```
ffffffff8116fb00-ffffffff8116fc2f: cpuset_change_task_nodemask (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
