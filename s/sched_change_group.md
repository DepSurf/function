# Function: <code>sched_change_group</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa4b0)
Location: kernel/sched/core.c:7797
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810aa4b0-ffffffff810aa573: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b05b0)
Location: kernel/sched/core.c:7950
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810b05b0-ffffffff810b066f: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810acad0)
Location: kernel/sched/core.c:6164
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810acad0-ffffffff810acb8d: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3b70)
Location: kernel/sched/core.c:6232
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810b3b70-ffffffff810b3c30: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb2d0)
Location: kernel/sched/core.c:6352
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810bb2d0-ffffffff810bb392: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c4160)
Location: kernel/sched/core.c:6333
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810c4160-ffffffff810c4222: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9f60)
Location: kernel/sched/core.c:6808
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810c9f60-ffffffff810ca027: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d3170)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810d3170-ffffffff810d325d: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dccd0)
Location: kernel/sched/core.c:7245
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810dccd0-ffffffff810dcd97: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d9540)
Location: kernel/sched/core.c:8210
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810d9540-ffffffff810d960a: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dbc90)
Location: kernel/sched/core.c:8579
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810dbc90-ffffffff810dbd5a: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810eff20)
Location: kernel/sched/core.c:9817
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810eff20-ffffffff810effea: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8110d2e0)
Location: kernel/sched/core.c:10140
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff8110d2e0-ffffffff8110d3ba: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114217b)
Location: kernel/sched/core.c:10320
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8114de6d)
Location: kernel/sched/core.c:10480
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81159c96)
Location: kernel/sched/core.c:10444
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_move_task
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff8000101334f0)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffff8000101334f0-ffff8000101335dc: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c0382a64)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
c0382a64-c0382b2c: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c00000000017e5c0)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
c00000000017e5c0-c00000000017e700: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e5ef8)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffe0000e5ef8-ffffffe0000e5fce: sched_change_group (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cd490)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810cd490-ffffffff810cd557: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bbcf0)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810bbcf0-ffffffff810bbddd: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc970)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810cc970-ffffffff810cca5d: sched_change_group (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void sched_change_group(struct task_struct *tsk, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d5300)
Location: kernel/sched/core.c:7011
Inline: True
Direct callers:
  - kernel/sched/core.c:cpu_cgroup_fork
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
  - kernel/sched/core.c:sched_move_task
```
**Symbols:**

```
ffffffff810d5300-ffffffff810d53c7: sched_change_group (STB_LOCAL)
```
</details>
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
