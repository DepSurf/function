# Function: <code>check_cb_ovld_locked</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81136ac0)
Location: kernel/rcu/tree.c:2818
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132120)
Location: kernel/rcu/tree.c:2955
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81132947)
Location: kernel/rcu/tree.c:2973
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81154b77)
Location: kernel/rcu/tree.c:2924
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117dea5)
Location: kernel/rcu/tree.c:3025
Inline: True
Inline callers:
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811ba796)
Location: kernel/rcu/tree.c:2693
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
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
In kernel/rcu/tree.c (ffffffff811cd0cd)
Location: kernel/rcu/tree.c:2586
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
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
In kernel/rcu/tree.c (ffffffff811e1a94)
Location: kernel/rcu/tree.c:2652
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:rcu_gp_cleanup
  - kernel/rcu/tree.c:rcu_gp_cleanup
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
