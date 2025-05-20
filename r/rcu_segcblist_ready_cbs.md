# Function: <code>rcu_segcblist_ready_cbs</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f72f5)
Location: kernel/rcu/rcu_segcblist.c:120
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_extract_done_cbs
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_dequeue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff810f70a0-ffffffff810f70bb: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8110149f)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff81101080-ffffffff8110109b: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8110992c)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff81109500-ffffffff8110951b: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811150fc)
Location: kernel/rcu/rcu_segcblist.c:92
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff81114cd0-ffffffff81114ceb: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111ef2c)
Location: kernel/rcu/rcu_segcblist.c:79
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffff8111eb00-ffffffff8111eb1b: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b64f)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff8112b170-ffffffff8112b18a: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139710)
Location: kernel/rcu/rcu_segcblist.c:182
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81139710-ffffffff8113972d: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811341e0)
Location: kernel/rcu/rcu_segcblist.c:182
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811341e0-ffffffff811341fd: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134fe0)
Location: kernel/rcu/rcu_segcblist.c:280
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81134fe0-ffffffff81134ffe: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811577e0)
Location: kernel/rcu/rcu_segcblist.c:280
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811577e0-ffffffff811577fe: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180a60)
Location: kernel/rcu/rcu_segcblist.c:278
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81180a60-ffffffff81180a84: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb2f0)
Location: kernel/rcu/rcu_segcblist.c:278
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811bb2f0-ffffffff811bb314: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdc90)
Location: kernel/rcu/rcu_segcblist.c:278
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811cdc90-ffffffff811cdcb4: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e28b0)
Location: kernel/rcu/rcu_segcblist.c:278
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:show_rcu_nocb_state
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_pending
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811e28b0-ffffffff811e28d4: rcu_segcblist_ready_cbs (STB_GLOBAL)
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff8000101938ac)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffff8000101931c8-ffff800010193210: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0bec)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
c03e0588-c03e05c0: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee908)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
c0000000001ee2a0-c0000000001ee2d8: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125d44)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
```
**Symbols:**

```
ffffffe000125832-ffffffe000125862: rcu_segcblist_ready_cbs (STB_GLOBAL)
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
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123c2f)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81123750-ffffffff8112376a: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111669d)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:show_rcu_gp_kthreads
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81116210-ffffffff8111622a: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121b1f)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81121640-ffffffff8112165a: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool rcu_segcblist_ready_cbs(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e12f)
Location: kernel/rcu/rcu_segcblist.c:193
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff8112dc50-ffffffff8112dc6a: rcu_segcblist_ready_cbs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
