# Function: <code>__call_rcu_nocb_wake</code>

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
In kernel/rcu/tree.c (ffffffff8112a07b)
Location: kernel/rcu/tree_plugin.h:2510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
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
In kernel/rcu/tree.c (ffffffff811384f3)
Location: kernel/rcu/tree_plugin.h:2478
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
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
Location: kernel/rcu/tree_plugin.h:2518
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
Location: kernel/rcu/tree_plugin.h:2915
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
Location: kernel/rcu/tree_nocb.h:1464
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
Location: kernel/rcu/tree_nocb.h:1501
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
Location: kernel/rcu/tree_nocb.h:1730
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
Location: kernel/rcu/tree_nocb.h:1776
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __call_rcu_nocb_wake(struct rcu_data *rdp, bool was_alldone, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_nocb.h:559
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu_common
```
**Symbols:**

```
ffffffff811e0060-ffffffff811e02f2: __call_rcu_nocb_wake (STB_LOCAL)
ffffffff821b41ad-ffffffff821b41d7: __call_rcu_nocb_wake.cold (STB_LOCAL)
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
In kernel/rcu/tree.c (ffff800010191e78)
Location: kernel/rcu/tree_plugin.h:2510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
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
In kernel/rcu/tree.c (c03df874)
Location: kernel/rcu/tree_plugin.h:2510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
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
In kernel/rcu/tree.c (c0000000001ed448)
Location: kernel/rcu/tree_plugin.h:2510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/rcu/tree.c (ffffffff8112265b)
Location: kernel/rcu/tree_plugin.h:2510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __call_rcu_nocb_wake(struct rcu_data *rdp, bool was_alldone, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81111f40)
Location: kernel/rcu/tree_plugin.h:1872
Inline: True
Direct callers:
  - kernel/rcu/tree.c:do_nocb_bypass_wakeup_timer
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81111f40-ffffffff81112089: __call_rcu_nocb_wake (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff8112054b)
Location: kernel/rcu/tree_plugin.h:2510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
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
In kernel/rcu/tree.c (ffffffff8112c7a9)
Location: kernel/rcu/tree_plugin.h:2510
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
