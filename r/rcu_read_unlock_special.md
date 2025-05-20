# Function: <code>rcu_read_unlock_special</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_read_unlock_special(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:624
Inline: False
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:strict_work_handler
```
**Symbols:**

```
ffffffff8117d040-ffffffff8117d204: rcu_read_unlock_special (STB_LOCAL)
ffffffff81e5fc37-ffffffff81e5fc67: rcu_read_unlock_special.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_read_unlock_special(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:624
Inline: False
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:strict_work_handler
```
**Symbols:**

```
ffffffff811b6910-ffffffff811b6b0a: rcu_read_unlock_special (STB_LOCAL)
ffffffff8205a11c-ffffffff8205a14c: rcu_read_unlock_special.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_read_unlock_special(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:626
Inline: False
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:strict_work_handler
```
**Symbols:**

```
ffffffff811c7340-ffffffff811c753a: rcu_read_unlock_special (STB_LOCAL)
ffffffff820d88ac-ffffffff820d88dc: rcu_read_unlock_special.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_read_unlock_special(struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_plugin.h:626
Inline: False
Direct callers:
  - kernel/rcu/tree.c:exit_rcu
  - kernel/rcu/tree.c:strict_work_handler
```
**Symbols:**

```
ffffffff811d7860-ffffffff811d7a5a: rcu_read_unlock_special (STB_LOCAL)
ffffffff821b3be9-ffffffff821b3c19: rcu_read_unlock_special.cold (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112a5c1)
Location: kernel/rcu/tree_plugin.h:595
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__rcu_read_unlock
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
