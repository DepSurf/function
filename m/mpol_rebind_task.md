# Function: <code>mpol_rebind_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new, enum mpol_rebind_step step);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e12a0)
Location: mm/mempolicy.c:431
Inline: False
```
**Symbols:**

```
ffffffff811e12a0-ffffffff811e12b7: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new, enum mpol_rebind_step step);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ffc90)
Location: mm/mempolicy.c:428
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff811ffc90-ffffffff811ffca7: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new, enum mpol_rebind_step step);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812117b0)
Location: mm/mempolicy.c:430
Inline: False
Direct callers:
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:cpuset_change_task_nodemask
  - kernel/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff812117b0-ffffffff812117c7: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8121d0e0)
Location: mm/mempolicy.c:365
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff8121d0e0-ffffffff8121d0f7: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812382d0)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff812382d0-ffffffff812382e7: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8125b850)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff8125b850-ffffffff8125b867: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81270100)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81270100-ffffffff81270117: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8128b710)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff8128b710-ffffffff8128b727: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8129b280)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff8129b280-ffffffff8129b297: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812ce5c0)
Location: mm/mempolicy.c:393
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff812ce5c0-ffffffff812ce5d7: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d9550)
Location: mm/mempolicy.c:393
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff812d9550-ffffffff812d9567: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812e0dd0)
Location: mm/mempolicy.c:393
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff812e0dd0-ffffffff812e0de7: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81327fd0)
Location: mm/mempolicy.c:366
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81327fd0-ffffffff81328049: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81397230)
Location: mm/mempolicy.c:370
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81397230-ffffffff8139724f: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81416d10)
Location: mm/mempolicy.c:370
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81416d10-ffffffff81416da1: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff8144a250)
Location: mm/mempolicy.c:370
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff8144a250-ffffffff8144a2e1: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81483ce0)
Location: mm/mempolicy.c:372
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81483ce0-ffffffff81483d71: mpol_rebind_task (STB_GLOBAL)
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
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffff80001033a080)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffff80001033a080-ffff80001033a0b4: mpol_rebind_task (STB_GLOBAL)
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/mempolicy.h:262
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (c0000000004146f0)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
c0000000004146f0-c000000000414708: mpol_rebind_task (STB_GLOBAL)
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
In kernel/cgroup/cpuset.c (0)
Location: include/linux/mempolicy.h:262
Inline: True
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
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81293860)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81293860-ffffffff81293877: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81285470)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81285470-ffffffff81285487: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81291670)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff81291670-ffffffff81291687: mpol_rebind_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mpol_rebind_task(struct task_struct *tsk, const nodemask_t *new);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812a1480)
Location: mm/mempolicy.c:367
Inline: False
Direct callers:
  - kernel/cgroup/cpuset.c:cpuset_change_task_nodemask
```
**Symbols:**

```
ffffffff812a1480-ffffffff812a1497: mpol_rebind_task (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>enum mpol_rebind_step step</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
