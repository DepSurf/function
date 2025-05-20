# Function: <code>rcu_seq_end</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4ab0)
Location: kernel/rcu/tree.c:3356
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:synchronize_sched_expedited
Direct callers:
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
**Symbols:**

```
ffffffff810e4ab0-ffffffff810e4add: rcu_seq_end.part.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_seq_end(long unsigned int *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eae90)
Location: kernel/rcu/tree.c:3434
Inline: True
Direct callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
**Symbols:**

```
ffffffff810eae90-ffffffff810eaed0: rcu_seq_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rcu_seq_end(long unsigned int *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2260)
Location: kernel/rcu/tree.c:3432
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:_rcu_barrier
```
**Symbols:**

```
ffffffff810f2260-ffffffff810f22a0: rcu_seq_end (STB_LOCAL)
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
In kernel/rcu/srcutree.c (ffffffff810f1a8f)
Location: kernel/rcu/rcu.h:104
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff810f2f41)
Location: kernel/rcu/rcu.h:104
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:_rcu_barrier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fb7ff)
Location: kernel/rcu/rcu.h:104
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff810fda81)
Location: kernel/rcu/rcu.h:104
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:_rcu_barrier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81103d12)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81106787)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:_rcu_barrier
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110f6d2)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8111167d)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81119422)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8111aeb6)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811257f2)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff811272b4)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8113254c)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff811378e4)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112dd3c)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff81132f24)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e28c)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff81132494)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114f749)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff81154876)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff81174276)
Location: kernel/rcu/rcu.h:71
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff81177249)
Location: kernel/rcu/rcu.h:71
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8117ec24)
Location: kernel/rcu/rcu.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9c2b)
Location: kernel/rcu/rcu.h:70
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811ae94d)
Location: kernel/rcu/rcu.h:70
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff811b46c0)
Location: kernel/rcu/rcu.h:70
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bbb1b)
Location: kernel/rcu/rcu.h:107
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811c0944)
Location: kernel/rcu/rcu.h:107
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff811c87d0)
Location: kernel/rcu/rcu.h:107
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cc015)
Location: kernel/rcu/rcu.h:108
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811d0e24)
Location: kernel/rcu/rcu.h:108
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff811da840)
Location: kernel/rcu/rcu.h:108
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_poll_gp_seq_end_unlocked
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018aba4)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffff80001018d618)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8d30)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (c03db498)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e5d90)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (c0000000001e7e00)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011fef0)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffe000121fca)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111ddd2)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8111f894)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110ee56)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff81111324)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111bcc2)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff8111d784)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126e4c)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_barrier
```
```
In kernel/rcu/tree.c (ffffffff811286a4)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
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
</ul>
