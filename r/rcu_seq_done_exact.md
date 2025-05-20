# Function: <code>rcu_seq_done_exact</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b6524)
Location: kernel/rcu/rcu.h:126
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:cond_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c9184)
Location: kernel/rcu/rcu.h:163
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:cond_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/rcu/tree.c:kvfree_rcu_bulk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811db404)
Location: kernel/rcu/rcu.h:164
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:cond_synchronize_rcu_expedited_full
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:cond_synchronize_rcu_full
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_monitor
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kfree_rcu_work
  - kernel/rcu/tree.c:kvfree_rcu_bulk
  - kernel/rcu/tree.c:kvfree_rcu_bulk
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
