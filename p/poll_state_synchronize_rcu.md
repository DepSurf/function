# Function: <code>poll_state_synchronize_rcu</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133555)
Location: kernel/rcu/tree.c:3863
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu
```
**Symbols:**

```
ffffffff8112f340-ffffffff8112f366: poll_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81155545)
Location: kernel/rcu/tree.c:3829
Inline: True
Inline callers:
  - kernel/rcu/tree.c:cond_synchronize_rcu
```
**Symbols:**

```
ffffffff811508f0-ffffffff81150916: poll_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81177fe0)
Location: kernel/rcu/tree.c:3925
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
```
**Symbols:**

```
ffffffff81177fe0-ffffffff81178016: poll_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b0456)
Location: kernel/rcu/tree.c:3730
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
```
**Symbols:**

```
ffffffff811af7b0-ffffffff811af7f4: poll_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c241f)
Location: kernel/rcu/tree.c:3730
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:kfree_rcu_monitor
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
```
**Symbols:**

```
ffffffff811c1820-ffffffff811c1864: poll_state_synchronize_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool poll_state_synchronize_rcu(long unsigned int oldstate);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d298f)
Location: kernel/rcu/tree.c:3802
Inline: True
Inline callers:
  - kernel/rcu/tree.c:start_poll_synchronize_rcu_expedited
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:sync_rcu_do_polled_gp
  - kernel/rcu/tree.c:kfree_rcu_monitor
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - lib/stackdepot.c:depot_alloc_stack
  - net/sched/sch_generic.c:mini_qdisc_pair_swap
```
**Symbols:**

```
ffffffff811d1d20-ffffffff811d1d64: poll_state_synchronize_rcu (STB_GLOBAL)
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
<b>Regular</b>
<ul>
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
