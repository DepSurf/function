# Function: <code>psi_task_change</code>

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
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:510
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff810efbe9-ffffffff810efc6c: psi_task_change.cold.13 (STB_LOCAL)
ffffffff810ef4d0-ffffffff810ef6e5: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:746
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff810f7644-ffffffff810f76c8: psi_task_change.cold (STB_LOCAL)
ffffffff810f6860-ffffffff810f6b77: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff811033e4-ffffffff81103468: psi_task_change.cold (STB_LOCAL)
ffffffff811025f0-ffffffff81102907: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110d6f0)
Location: kernel/sched/psi.c:767
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff8110d6f0-ffffffff8110d7bd: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110a9e0)
Location: kernel/sched/psi.c:783
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff8110a9e0-ffffffff8110aaad: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110c5b0)
Location: kernel/sched/psi.c:788
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff8110c5b0-ffffffff8110c696: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112b5d0)
Location: kernel/sched/psi.c:800
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff8112b5d0-ffffffff8112b6f7: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8114bd00)
Location: kernel/sched/psi.c:799
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:psi_memstall_leave
  - kernel/sched/build_utility.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff8114bd00-ffffffff8114be35: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117a7e0)
Location: kernel/sched/psi.c:885
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff8117a7e0-ffffffff8117a8ae: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118b340)
Location: kernel/sched/psi.c:908
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff8118b340-ffffffff8118b40e: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81199c70)
Location: kernel/sched/psi.c:897
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:cgroup_move_task
  - kernel/sched/build_utility.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff81199c70-ffffffff81199d3e: psi_task_change (STB_GLOBAL)
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
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff8000101672b0)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:dequeue_task
  - kernel/sched/core.c:enqueue_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffff8000101672b0-ffff800010167668: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b40dc)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
c03b40dc-c03b44d0: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bee10)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
c0000000001bee10-c0000000001bf33c: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe0001098e8)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:move_queued_task
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffe0001098e8-ffffffe000109bfc: psi_task_change (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff810fc6f4-ffffffff810fc778: psi_task_change.cold (STB_LOCAL)
ffffffff810fb900-ffffffff810fbc17: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff810ec904-ffffffff810ec988: psi_task_change.cold (STB_LOCAL)
ffffffff810ebb20-ffffffff810ebe37: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff810f98b4-ffffffff810f9938: psi_task_change.cold (STB_LOCAL)
ffffffff810f8ac0-ffffffff810f8dd7: psi_task_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void psi_task_change(struct task_struct *task, int clear, int set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/psi.c (0)
Location: kernel/sched/psi.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:deactivate_task
  - kernel/sched/core.c:activate_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:cgroup_move_task
  - kernel/sched/psi.c:psi_memstall_leave
  - kernel/sched/psi.c:psi_memstall_enter
```
**Symbols:**

```
ffffffff81104a14-ffffffff81104a98: psi_task_change.cold (STB_LOCAL)
ffffffff81103c10-ffffffff81103f27: psi_task_change (STB_GLOBAL)
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
