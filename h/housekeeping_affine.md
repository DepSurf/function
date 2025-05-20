# Function: <code>housekeeping_affine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:191
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/tick.h:282
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:282
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/tick.h:280
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:280
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (0)
Location: include/linux/tick.h:281
Inline: True
```
```
In kernel/rcu/tree.c (0)
Location: include/linux/tick.h:281
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810dc050)
Location: kernel/sched/isolation.c:39
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff810dc050-ffffffff810dc076: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810e4690)
Location: kernel/sched/isolation.c:34
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff810e4690-ffffffff810e46b6: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eee10)
Location: kernel/sched/isolation.c:34
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff810eee10-ffffffff810eee36: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f5c40)
Location: kernel/sched/isolation.c:41
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff810f5c40-ffffffff810f5c66: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff811019d0)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff811019d0-ffffffff811019f6: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110c260)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff8110c260-ffffffff8110c286: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81109480)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff81109480-ffffffff811094a6: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff8110b320)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff8110b320-ffffffff8110b346: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81129b70)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff81129b70-ffffffff81129b93: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113e902)
Location: kernel/sched/isolation.c:65
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff81e56c60-ffffffff81e56c78: housekeeping_affine.cold (STB_LOCAL)
ffffffff8113e8e0-ffffffff8113e957: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81168ec2)
Location: kernel/sched/isolation.c:65
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff82057c3b-ffffffff82057c53: housekeeping_affine.cold (STB_LOCAL)
ffffffff81168ea0-ffffffff81168f16: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81179655)
Location: kernel/sched/isolation.c:65
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff820d645b-ffffffff820d6473: housekeeping_affine.cold (STB_LOCAL)
ffffffff81179610-ffffffff8117968f: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_type type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81187195)
Location: kernel/sched/isolation.c:65
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff821b15ad-ffffffff821b15c5: housekeeping_affine.cold (STB_LOCAL)
ffffffff81187150-ffffffff811871cf: housekeeping_affine (STB_GLOBAL)
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
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffff800010166598)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffff800010166598-ffff8000101665e8: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c03b2a38)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
c03b2a38-c03b2a78: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (c0000000001bdd90)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
c0000000001bdd90-c0000000001bddf4: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffe0001088bc)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffe0001088bc-ffffffe00010890e: housekeeping_affine (STB_GLOBAL)
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
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810face0)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff810face0-ffffffff810fad06: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810eaf00)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
**Symbols:**

```
ffffffff810eaf00-ffffffff810eaf26: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff810f7ea0)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff810f7ea0-ffffffff810f7ec6: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void housekeeping_affine(struct task_struct *t, enum hk_flags flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/isolation.c (ffffffff81102fe0)
Location: kernel/sched/isolation.c:49
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff81102fe0-ffffffff81103006: housekeeping_affine (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum hk_type type</code>
</li>
<li>
<b>Param removed. </b>
<code>enum hk_flags flags</code>
</li>
</ul>
</details>
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
