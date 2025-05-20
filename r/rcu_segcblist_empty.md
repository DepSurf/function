# Function: <code>rcu_segcblist_empty</code>

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
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f69ad)
Location: kernel/rcu/rcu_segcblist.h:72
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:72
Inline: True
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
In kernel/rcu/tree.c (ffffffff81100b0b)
Location: kernel/rcu/rcu_segcblist.h:50
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:50
Inline: True
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
In kernel/rcu/tree.c (ffffffff811089b5)
Location: kernel/rcu/rcu_segcblist.h:50
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:50
Inline: True
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
In kernel/rcu/tree.c (ffffffff81113df5)
Location: kernel/rcu/rcu_segcblist.h:50
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:50
Inline: True
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
In kernel/rcu/tree.c (ffffffff8111da15)
Location: kernel/rcu/rcu_segcblist.h:37
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/rcu/rcu_segcblist.c (0)
Location: kernel/rcu/rcu_segcblist.h:37
Inline: True
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
In kernel/rcu/srcutree.c (ffffffff81125b80)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff8112a1e8)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b115)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff81133496)
Location: kernel/rcu/rcu_segcblist.h:38
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff81138758)
Location: kernel/rcu/rcu_segcblist.h:38
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811396c5)
Location: kernel/rcu/rcu_segcblist.h:38
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff81be1fe1)
Location: kernel/rcu/rcu_segcblist.h:38
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff81134028)
Location: kernel/rcu/rcu_segcblist.h:38
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81134195)
Location: kernel/rcu/rcu_segcblist.h:38
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff81bd4071)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff81134d98)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81134f75)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff81cae204)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff81157598)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff81157775)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff81172b69)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff81e5e7b8)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff81180239)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_needs_cpu
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811809d5)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff811aa5b6)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811ad854)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff811ba775)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_needs_cpu
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb245)
Location: kernel/rcu/rcu_segcblist.h:41
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff811bc4e6)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811bf57e)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff811cd0ac)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_needs_cpu
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdbe5)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/update.c (ffffffff811cca7e)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:show_rcu_tasks_generic_gp_kthread
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic_timer
  - kernel/rcu/update.c:cblist_init_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811cf9ee)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff83903b24)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_needs_cpu
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2805)
Location: kernel/rcu/rcu_segcblist.h:43
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffff80001018bba8)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffff8000101920d0)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffff800010193140)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (c03d9c94)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (c03dfb0c)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/rcu/rcu_segcblist.c (c03e0498)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (c0000000001e6314)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (c0000000001ed6f0)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/rcu/rcu_segcblist.c (c0000000001ee218)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffe0001202ca)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffe000124ec8)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
  - kernel/rcu/tree.c:rcu_core
```
```
In kernel/rcu/rcu_segcblist.c (ffffffe0001257d6)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8111e160)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff811227c8)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811236f5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8110f1cc)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff828b0f86)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init_nohz
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811161b5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8111c050)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff811206b8)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff811215e5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
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
In kernel/rcu/srcutree.c (ffffffff8112777e)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_torture_stats_print
```
```
In kernel/rcu/tree.c (ffffffff8112c978)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_needs_cpu
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_prepare_cpu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/tree.c:rcu_do_batch
```
```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dbf5)
Location: kernel/rcu/rcu_segcblist.h:47
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_disable
```
</details>
</li>
</ul>

## Differences
