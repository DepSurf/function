# Function: <code>rcu_seq_ctr</code>

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
In kernel/rcu/srcutree.c (ffffffff810f1ad5)
Location: kernel/rcu/rcu.h:71
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff810f2f9d)
Location: kernel/rcu/rcu.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/srcutree.c (ffffffff810fb848)
Location: kernel/rcu/rcu.h:71
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff810fdae6)
Location: kernel/rcu/rcu.h:71
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/srcutree.c (ffffffff81103d58)
Location: kernel/rcu/rcu.h:48
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff811067de)
Location: kernel/rcu/rcu.h:48
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/srcutree.c (ffffffff8110f718)
Location: kernel/rcu/rcu.h:48
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff81114227)
Location: kernel/rcu/rcu.h:48
Inline: True
Inline callers:
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_exp_wait_wake
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
In kernel/rcu/srcutree.c (ffffffff81119468)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff8111b534)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (ffffffff81125838)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff811278df)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (ffffffff81132685)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff81137ade)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
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
In kernel/rcu/srcutree.c (ffffffff8112de75)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff8113311e)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
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
In kernel/rcu/srcutree.c (ffffffff8112e3c5)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff8113318e)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
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
In kernel/rcu/srcutree.c (ffffffff8114f895)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff8115542e)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_init
  - kernel/rcu/tree.c:rcu_gp_init
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
In kernel/rcu/srcutree.c (ffffffff81176b1d)
Location: kernel/rcu/rcu.h:32
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff8117eeff)
Location: kernel/rcu/rcu.h:32
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
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
In kernel/rcu/srcutree.c (ffffffff811acf0d)
Location: kernel/rcu/rcu.h:31
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
```
```
In kernel/rcu/tree.c (ffffffff811b61d3)
Location: kernel/rcu/rcu.h:31
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
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
In kernel/rcu/srcutree.c (ffffffff811bee62)
Location: kernel/rcu/rcu.h:68
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff811c8afc)
Location: kernel/rcu/rcu.h:68
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
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
In kernel/rcu/srcutree.c (ffffffff811cf2d2)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:srcu_funnel_gp_start
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (ffffffff811dfe79)
Location: kernel/rcu/rcu.h:69
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:exp_funnel_lock
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:rcu_gp_cleanup
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
In kernel/rcu/srcutree.c (ffff80001018abf8)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffff80001018fe04)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (c03d91a0)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
```
In kernel/rcu/tree.c (c03dbd78)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (c0000000001e5e04)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (c0000000001e8f2c)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (ffffffe00011ff60)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffe000122456)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (ffffffff8111de18)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff8111febf)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (ffffffff8110ee96)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff81112765)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (ffffffff8111bd08)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff8111ddaf)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
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
In kernel/rcu/srcutree.c (ffffffff81126e89)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:__call_srcu
```
```
In kernel/rcu/tree.c (ffffffff81128d0e)
Location: kernel/rcu/rcu.h:30
Inline: True
Inline callers:
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:synchronize_rcu_expedited
  - kernel/rcu/tree.c:rcu_exp_wait_wake
  - kernel/rcu/tree.c:print_cpu_stall_info
  - kernel/rcu/tree.c:print_cpu_stall_info
```
</details>
</li>
</ul>

## Differences
