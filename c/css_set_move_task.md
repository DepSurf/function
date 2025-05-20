# Function: <code>css_set_move_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811167a0)
Location: kernel/cgroup.c:697
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_taskset_migrate
  - kernel/cgroup.c:cgroup_post_fork
  - kernel/cgroup.c:cgroup_exit
```
**Symbols:**

```
ffffffff811167a0-ffffffff811169e0: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff8111da40)
Location: kernel/cgroup.c:739
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_exit
  - kernel/cgroup.c:cgroup_post_fork
  - kernel/cgroup.c:cgroup_taskset_migrate
```
**Symbols:**

```
ffffffff8111da40-ffffffff8111dc84: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81125d70)
Location: kernel/cgroup.c:742
Inline: False
Direct callers:
  - kernel/cgroup.c:cgroup_exit
  - kernel/cgroup.c:cgroup_post_fork
  - kernel/cgroup.c:cgroup_taskset_migrate
```
**Symbols:**

```
ffffffff81125d70-ffffffff81125fb4: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81124da0)
Location: kernel/cgroup/cgroup.c:660
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81124da0-ffffffff81124f8b: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81131040)
Location: kernel/cgroup/cgroup.c:787
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81131040-ffffffff81131232: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8113f770)
Location: kernel/cgroup/cgroup.c:790
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff8113f770-ffffffff8113f974: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114b190)
Location: kernel/cgroup/cgroup.c:825
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff8114b190-ffffffff8114b398: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81156a40)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81156a40-ffffffff81156c52: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811626b0)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff811626b0-ffffffff811628c2: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81173c80)
Location: kernel/cgroup/cgroup.c:871
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81173c80-ffffffff81173e8d: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81170960)
Location: kernel/cgroup/cgroup.c:868
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81170960-ffffffff81170b6d: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81171590)
Location: kernel/cgroup/cgroup.c:868
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81171590-ffffffff8117179d: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81197ea0)
Location: kernel/cgroup/cgroup.c:899
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81197ea0-ffffffff811980ad: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811c7f80)
Location: kernel/cgroup/cgroup.c:901
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff811c7f80-ffffffff811c81c0: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8120af60)
Location: kernel/cgroup/cgroup.c:906
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff8120af60-ffffffff8120b1a0: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81220540)
Location: kernel/cgroup/cgroup.c:890
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81220540-ffffffff8122078b: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81238290)
Location: kernel/cgroup/cgroup.c:870
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81238290-ffffffff812384db: css_set_move_task (STB_LOCAL)
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
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d3cd0)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffff8000101d3cd0-ffff8000101d3ec0: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041687c)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
c041687c-c0416acc: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c00000000023f000)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
c00000000023f000-c00000000023f288: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014d290)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffe00014d290-ffffffe00014d424: css_set_move_task (STB_LOCAL)
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
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115acd0)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff8115acd0-ffffffff8115aee2: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114dfc0)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff8114dfc0-ffffffff8114e1d2: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81158aa0)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81158aa0-ffffffff81158cb2: css_set_move_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void css_set_move_task(struct task_struct *task, struct css_set *from_cset, struct css_set *to_cset, bool use_mg_tasks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81165b20)
Location: kernel/cgroup/cgroup.c:878
Inline: False
Direct callers:
  - kernel/cgroup/cgroup.c:cgroup_exit
  - kernel/cgroup/cgroup.c:cgroup_post_fork
  - kernel/cgroup/cgroup.c:cgroup_migrate_execute
```
**Symbols:**

```
ffffffff81165b20-ffffffff81165d32: css_set_move_task (STB_LOCAL)
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
