# Function: <code>rcu_seq_snap</code>

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
In kernel/rcu/tree.c (ffffffff810e4af5)
Location: kernel/rcu/tree.c:3364
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
  - kernel/rcu/tree.c:synchronize_sched_expedited
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eaee9)
Location: kernel/rcu/tree.c:3442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2899)
Location: kernel/rcu/tree.c:3440
Inline: True
Inline callers:
  - kernel/rcu/tree.c:_rcu_barrier
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
In kernel/rcu/srcutree.c (ffffffff810f18fb)
Location: kernel/rcu/rcu.h:112
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff810f44d5)
Location: kernel/rcu/rcu.h:112
Inline: True
Inline callers:
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
In kernel/rcu/srcutree.c (ffffffff810fb661)
Location: kernel/rcu/rcu.h:112
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff810fe3a5)
Location: kernel/rcu/rcu.h:112
Inline: True
Inline callers:
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
In kernel/rcu/srcutree.c (ffffffff81103ade)
Location: kernel/rcu/rcu.h:95
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811052b5)
Location: kernel/rcu/rcu.h:95
Inline: True
Inline callers:
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
In kernel/rcu/srcutree.c (ffffffff8110f49e)
Location: kernel/rcu/rcu.h:105
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8111020f)
Location: kernel/rcu/rcu.h:105
Inline: True
Inline callers:
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff811191f8)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8111b397)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff811255c8)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81127774)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff8113316e)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81137a30)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff8112e94e)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81133070)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff8112ebdf)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:get_state_synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811330e0)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff811500cd)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:get_state_synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81155380)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/update.c (ffffffff81172ffd)
Location: kernel/rcu/rcu.h:89
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff8117757a)
Location: kernel/rcu/rcu.h:89
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:get_state_synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8117e2ba)
Location: kernel/rcu/rcu.h:89
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/update.c (ffffffff811a962d)
Location: kernel/rcu/rcu.h:88
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811aebaa)
Location: kernel/rcu/rcu.h:88
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:get_state_synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811b8e0a)
Location: kernel/rcu/rcu.h:88
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/update.c (ffffffff811bb3b0)
Location: kernel/rcu/rcu.h:125
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811c0baf)
Location: kernel/rcu/rcu.h:125
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:get_state_synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811cb44a)
Location: kernel/rcu/rcu.h:125
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/update.c (ffffffff811cb452)
Location: kernel/rcu/rcu.h:126
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
```
```
In kernel/rcu/srcutree.c (ffffffff811d0cf9)
Location: kernel/rcu/rcu.h:126
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:get_state_synchronize_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
```
In kernel/rcu/tree.c (ffffffff811dd75a)
Location: kernel/rcu/rcu.h:126
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:param_set_do_rcu_barrier
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_common
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kvfree_call_rcu
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffff80001018a918)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffff80001018fca8)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (c03d8330)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c03dbc18)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (c0000000001e59d4)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (c0000000001e8db4)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffe00011fc6e)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffe000122324)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff8111dba8)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8111fd54)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff8110ec3c)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff81111754)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff8111ba98)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8111dc44)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
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
In kernel/rcu/srcutree.c (ffffffff81125fe6)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8112acb6)
Location: kernel/rcu/rcu.h:87
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:get_state_synchronize_rcu
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
</details>
</li>
</ul>

## Differences
