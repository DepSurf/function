# Function: <code>call_rcu_tasks_generic</code>

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
In kernel/rcu/update.c (ffffffff81130d05)
Location: kernel/rcu/tasks.h:144
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks
  - kernel/rcu/update.c:call_rcu_tasks
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
In kernel/rcu/update.c (ffffffff8112c53f)
Location: kernel/rcu/tasks.h:152
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks_rude
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
In kernel/rcu/update.c (ffffffff8112ca6f)
Location: kernel/rcu/tasks.h:152
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks_rude
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
In kernel/rcu/update.c (ffffffff8114d76f)
Location: kernel/rcu/tasks.h:152
Inline: True
Inline callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks_rude
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void call_rcu_tasks_generic(struct callback_head *rhp, rcu_callback_t func, struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:273
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks
```
**Symbols:**

```
ffffffff81173640-ffffffff811738a1: call_rcu_tasks_generic (STB_LOCAL)
ffffffff81e5e511-ffffffff81e5e546: call_rcu_tasks_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void call_rcu_tasks_generic(struct callback_head *rhp, rcu_callback_t func, struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:281
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks
```
**Symbols:**

```
ffffffff811aaa70-ffffffff811aacde: call_rcu_tasks_generic (STB_LOCAL)
ffffffff82059dc8-ffffffff82059dfd: call_rcu_tasks_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void call_rcu_tasks_generic(struct callback_head *rhp, rcu_callback_t func, struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:290
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks
```
**Symbols:**

```
ffffffff811bc9a0-ffffffff811bcc0e: call_rcu_tasks_generic (STB_LOCAL)
ffffffff820d85bf-ffffffff820d85f4: call_rcu_tasks_generic.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void call_rcu_tasks_generic(struct callback_head *rhp, rcu_callback_t func, struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:322
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_trace
  - kernel/rcu/update.c:call_rcu_tasks_rude
  - kernel/rcu/update.c:call_rcu_tasks
```
**Symbols:**

```
ffffffff811cb7c0-ffffffff811cbad0: call_rcu_tasks_generic (STB_LOCAL)
ffffffff821b376e-ffffffff821b37a3: call_rcu_tasks_generic.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
