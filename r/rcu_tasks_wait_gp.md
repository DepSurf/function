# Function: <code>rcu_tasks_wait_gp</code>

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
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811301e0)
Location: kernel/rcu/tasks.h:294
Inline: False
```
**Symbols:**

```
ffffffff811301e0-ffffffff811303d5: rcu_tasks_wait_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c020)
Location: kernel/rcu/tasks.h:304
Inline: False
```
**Symbols:**

```
ffffffff8112c020-ffffffff8112c223: rcu_tasks_wait_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8112c550)
Location: kernel/rcu/tasks.h:304
Inline: False
```
**Symbols:**

```
ffffffff8112c550-ffffffff8112c753: rcu_tasks_wait_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff8114d250)
Location: kernel/rcu/tasks.h:303
Inline: False
```
**Symbols:**

```
ffffffff8114d250-ffffffff8114d453: rcu_tasks_wait_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:620
Inline: False
```
**Symbols:**

```
ffffffff81173ef0-ffffffff81174193: rcu_tasks_wait_gp (STB_LOCAL)
ffffffff81e5e5ff-ffffffff81e5e63a: rcu_tasks_wait_gp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811a9f40)
Location: kernel/rcu/tasks.h:656
Inline: False
```
**Symbols:**

```
ffffffff811a9f40-ffffffff811aa243: rcu_tasks_wait_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811bbe70)
Location: kernel/rcu/tasks.h:668
Inline: False
```
**Symbols:**

```
ffffffff811bbe70-ffffffff811bc173: rcu_tasks_wait_gp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_tasks_wait_gp(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/update.c (ffffffff811cc2d0)
Location: kernel/rcu/tasks.h:735
Inline: False
```
**Symbols:**

```
ffffffff811cc2d0-ffffffff811cc5d6: rcu_tasks_wait_gp (STB_LOCAL)
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
