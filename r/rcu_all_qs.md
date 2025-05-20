# Function: <code>rcu_all_qs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e65b0)
Location: kernel/rcu/tree.c:377
Inline: True
Inline callers:
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_check_callbacks
Direct callers:
  - kernel/workqueue.c:process_one_work
  - mm/mlock.c:apply_mlockall_flags
```
**Symbols:**

```
ffffffff810e65b0-ffffffff810e65d5: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ec5a0)
Location: kernel/rcu/tree.c:368
Inline: False
Direct callers:
  - kernel/workqueue.c:process_one_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - mm/mlock.c:apply_mlockall_flags
```
**Symbols:**

```
ffffffff810ec5a0-ffffffff810ec616: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2db0)
Location: kernel/rcu/tree.c:369
Inline: False
Direct callers:
  - kernel/workqueue.c:process_one_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - mm/mlock.c:apply_mlockall_flags
```
**Symbols:**

```
ffffffff810f2db0-ffffffff810f2e26: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f395e)
Location: kernel/rcu/tree.c:490
Inline: True
Inline callers:
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/workqueue.c:process_one_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - mm/mlock.c:apply_mlockall_flags
```
**Symbols:**

```
ffffffff810f3800-ffffffff810f3879: rcu_all_qs.part.62 (STB_LOCAL)
ffffffff810f3880-ffffffff810f38b4: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fd3a1)
Location: kernel/rcu/tree.c:487
Inline: True
Inline callers:
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
Direct callers:
  - kernel/workqueue.c:process_one_work
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_check_callbacks
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - mm/mlock.c:apply_mlockall_flags
```
**Symbols:**

```
ffffffff810fd250-ffffffff810fd2c9: rcu_all_qs.part.62 (STB_LOCAL)
ffffffff810fd2d0-ffffffff810fd303: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81106080)
Location: kernel/rcu/tree.c:474
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff81106080-ffffffff8110611a: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110d90)
Location: kernel/rcu/tree_plugin.h:979
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81110d90-ffffffff81110e1a: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111cc50)
Location: kernel/rcu/tree_plugin.h:837
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff8111cc50-ffffffff8111ccba: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811291e0)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff811291e0-ffffffff8112924a: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81136960)
Location: kernel/rcu/tree_plugin.h:807
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81136960-ffffffff811369cd: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81131ad0)
Location: kernel/rcu/tree_plugin.h:835
Inline: True
Direct callers:
  - kernel/sched/core.c:affine_move_task
```
**Symbols:**

```
ffffffff81131ad0-ffffffff81131b3d: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811339a0)
Location: kernel/rcu/tree_plugin.h:902
Inline: True
Direct callers:
  - kernel/sched/core.c:affine_move_task
```
**Symbols:**

```
ffffffff811339a0-ffffffff81133a0f: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811564f5)
Location: kernel/rcu/tree_plugin.h:862
Inline: True
Direct callers:
  - kernel/sched/core.c:affine_move_task
```
**Symbols:**

```
ffffffff81caf5b1-ffffffff81caf5c5: rcu_all_qs.cold (STB_LOCAL)
ffffffff811564c0-ffffffff8115654d: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff800010190720)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffff800010190720-ffff8000101907b8: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc0d8)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
c03dc0d8-c03dc16c: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e9500)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
c0000000001e9500-c0000000001e95e0: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0001217a8)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffe0001217a8-ffffffe000121852: rcu_all_qs (STB_GLOBAL)
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
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811217c0)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff811217c0-ffffffff8112182a: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110c30)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff81110c30-ffffffff81110c84: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_all_qs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111f6b0)
Location: kernel/rcu/tree_plugin.h:818
Inline: True
Direct callers:
  - kernel/sched/core.c:_cond_resched
```
**Symbols:**

```
ffffffff8111f6b0-ffffffff8111f71a: rcu_all_qs (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
