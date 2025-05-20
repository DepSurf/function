# Function: <code>rcu_tasks_need_gpcb</code>

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
int rcu_tasks_need_gpcb(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:386
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_kthread
```
**Symbols:**

```
ffffffff81173940-ffffffff81173b75: rcu_tasks_need_gpcb (STB_LOCAL)
ffffffff81e5e546-ffffffff81e5e5b3: rcu_tasks_need_gpcb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_need_gpcb(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:383
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
```
**Symbols:**

```
ffffffff811a9820-ffffffff811a9b0f: rcu_tasks_need_gpcb (STB_LOCAL)
ffffffff82059d0c-ffffffff82059d53: rcu_tasks_need_gpcb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_need_gpcb(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:392
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
```
**Symbols:**

```
ffffffff811bb710-ffffffff811bb9fc: rcu_tasks_need_gpcb (STB_LOCAL)
ffffffff820d84ed-ffffffff820d8534: rcu_tasks_need_gpcb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rcu_tasks_need_gpcb(struct rcu_tasks *rtp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/update.c (0)
Location: kernel/rcu/tasks.h:432
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_one_gp
```
**Symbols:**

```
ffffffff811cbba0-ffffffff811cbedc: rcu_tasks_need_gpcb (STB_LOCAL)
ffffffff821b37a3-ffffffff821b37ea: rcu_tasks_need_gpcb.cold (STB_LOCAL)
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
