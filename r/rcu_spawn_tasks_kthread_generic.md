# Function: <code>rcu_spawn_tasks_kthread_generic</code>

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
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff82cf02ea)
Location: kernel/rcu/tasks.h:237
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_spawn_tasks_trace_kthread
  - kernel/rcu/update.c:rcu_spawn_tasks_rude_kthread
  - kernel/rcu/update.c:rcu_spawn_tasks_kthread
```
**Symbols:**

```
ffffffff82cf02ea-ffffffff82cf035e: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff82fdccd5)
Location: kernel/rcu/tasks.h:245
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
**Symbols:**

```
ffffffff82fdccd5-ffffffff82fdcd49: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff831e7a33)
Location: kernel/rcu/tasks.h:245
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
**Symbols:**

```
ffffffff831e7a33-ffffffff831e7aa7: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff832cbb16)
Location: kernel/rcu/tasks.h:244
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
**Symbols:**

```
ffffffff832cbb16-ffffffff832cbba8: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8347f2fd)
Location: kernel/rcu/tasks.h:543
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
**Symbols:**

```
ffffffff8347f2fd-ffffffff8347f3a2: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff83eab650)
Location: kernel/rcu/tasks.h:579
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
**Symbols:**

```
ffffffff83eab650-ffffffff83eab70c: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff836d0620)
Location: kernel/rcu/tasks.h:591
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
**Symbols:**

```
ffffffff836d0620-ffffffff836d06c8: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_spawn_tasks_kthread_generic(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff83901a80)
Location: kernel/rcu/tasks.h:649
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
  - kernel/rcu/update.c:rcu_init_tasks_generic
```
**Symbols:**

```
ffffffff83901a80-ffffffff83901b28: rcu_spawn_tasks_kthread_generic (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
