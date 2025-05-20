# Function: <code>rcu_spawn_tasks_rude_kthread</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int rcu_spawn_tasks_rude_kthread();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff82cf03ae)
Location: kernel/rcu/tasks.h:678
Inline: False
```
**Symbols:**

```
ffffffff82cf03ae-ffffffff82cf03c7: rcu_spawn_tasks_rude_kthread (STB_LOCAL)
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
In kernel/rcu/update.c (ffffffff82fdcd4e)
Location: kernel/rcu/tasks.h:688
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
In kernel/rcu/update.c (ffffffff831e7aac)
Location: kernel/rcu/tasks.h:688
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
In kernel/rcu/update.c (ffffffff832cbbad)
Location: kernel/rcu/tasks.h:732
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
In kernel/rcu/update.c (ffffffff8347f40b)
Location: kernel/rcu/tasks.h:1076
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
In kernel/rcu/update.c (ffffffff83eab789)
Location: kernel/rcu/tasks.h:1139
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
In kernel/rcu/update.c (ffffffff836d0749)
Location: kernel/rcu/tasks.h:1176
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
In kernel/rcu/update.c (ffffffff83901bbf)
Location: kernel/rcu/tasks.h:1283
Inline: True
Inline callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
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
</ul>
