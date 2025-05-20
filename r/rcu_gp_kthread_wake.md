# Function: <code>rcu_gp_kthread_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e4760)
Location: kernel/rcu/tree.c:1608
Inline: True
Direct callers:
  - kernel/rcu/tree.c:force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810e4760-ffffffff810e47aa: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rcu_gp_kthread_wake(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ea8b0)
Location: kernel/rcu/tree.c:1716
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:note_gp_changes
```
**Symbols:**

```
ffffffff810ea8b0-ffffffff810ea8ee: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rcu_gp_kthread_wake(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f1610)
Location: kernel/rcu/tree.c:1718
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
```
**Symbols:**

```
ffffffff810f1610-ffffffff810f164e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rcu_gp_kthread_wake(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f24b0)
Location: kernel/rcu/tree.c:1792
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
```
**Symbols:**

```
ffffffff810f24b0-ffffffff810f24ef: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_gp_kthread_wake(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc240)
Location: kernel/rcu/tree.c:1864
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
```
**Symbols:**

```
ffffffff810fc240-ffffffff810fc27d: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_gp_kthread_wake(struct rcu_state *rsp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811048a0)
Location: kernel/rcu/tree.c:1724
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
```
**Symbols:**

```
ffffffff811048a0-ffffffff811048dd: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110280)
Location: kernel/rcu/tree.c:1573
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81110280-ffffffff811102da: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81119ed0)
Location: kernel/rcu/tree.c:1225
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81119ed0-ffffffff81119f3e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811262e0)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811262e0-ffffffff8112634e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133ac0)
Location: kernel/rcu/tree.c:1433
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81133ac0-ffffffff81133b2e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112f240)
Location: kernel/rcu/tree.c:1513
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rdp
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff8112f240-ffffffff8112f2ae: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112f7a0)
Location: kernel/rcu/tree.c:1517
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff8112f7a0-ffffffff8112f80e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811510d0)
Location: kernel/rcu/tree.c:1470
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811510d0-ffffffff8115113e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81179190)
Location: kernel/rcu/tree.c:1486
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81179190-ffffffff81179212: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b08b0)
Location: kernel/rcu/tree.c:1061
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811b08b0-ffffffff811b0932: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c2880)
Location: kernel/rcu/tree.c:1021
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811c2880-ffffffff811c2902: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d4830)
Location: kernel/rcu/tree.c:1063
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_preempt_deferred_qs_irqrestore
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff811d4830-ffffffff811d48b2: rcu_gp_kthread_wake (STB_LOCAL)
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
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018be58)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffff80001018be58-ffff80001018bed8: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03db5d8)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
c03db5d8-c03db668: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e7fc0)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
c0000000001e7fc0-c0000000001e805c: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120d18)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffe000120d18-ffffffe000120d8a: rcu_gp_kthread_wake (STB_LOCAL)
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
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e8c0)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff8111e8c0-ffffffff8111e92e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f870)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff8110f870-ffffffff8110f8de: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c7b0)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rnp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff8111c7b0-ffffffff8111c81e: rcu_gp_kthread_wake (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_gp_kthread_wake();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81128ed0)
Location: kernel/rcu/tree.c:1233
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_force_quiescent_state
  - kernel/rcu/tree.c:rcu_report_qs_rsp
  - kernel/rcu/tree.c:note_gp_changes
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
```
**Symbols:**

```
ffffffff81128ed0-ffffffff81128f3e: rcu_gp_kthread_wake (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct rcu_state *rsp</code>
</li>
</ul>
</details>
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
