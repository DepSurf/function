# Function: <code>rcu_lockdep_assert_cblist_protected</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2448
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2488
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2885
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_nocb.h:1434
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_nocb.h:1471
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_nocb.h:1695
Inline: True
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
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_nocb.h:1741
Inline: True
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
In kernel/rcu/tree.c (ffffffff811deccb)
Location: kernel/rcu/tree_nocb.h:188
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nocb_rdp_deoffload
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcu_barrier_entrain
  - kernel/rcu/tree.c:__note_gp_changes
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81112494)
Location: kernel/rcu/tree_plugin.h:1602
Inline: True
Inline callers:
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
Direct callers:
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
  - kernel/rcu/tree.c:rcu_advance_cbs_nowake
  - kernel/rcu/tree.c:rcu_advance_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811100e0-ffffffff811100f9: rcu_lockdep_assert_cblist_protected.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:2480
Inline: True
```
</details>
</li>
</ul>

## Differences
