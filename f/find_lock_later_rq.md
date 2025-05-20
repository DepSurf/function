# Function: <code>find_lock_later_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c2500)
Location: kernel/sched/deadline.c:1414
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c2500-ffffffff810c2643: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c5f20)
Location: kernel/sched/deadline.c:1369
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c5f20-ffffffff810c6068: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cbee0)
Location: kernel/sched/deadline.c:1358
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cbee0-ffffffff810cc023: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c5a00)
Location: kernel/sched/deadline.c:1883
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810c5a00-ffffffff810c5b4e: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810cd100)
Location: kernel/sched/deadline.c:1877
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810cd100-ffffffff810cd255: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d6fa9)
Location: kernel/sched/deadline.c:1944
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810d5440-ffffffff810d558f: find_lock_later_rq.part.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e14f9)
Location: kernel/sched/deadline.c:1949
Inline: True
Inline callers:
  - kernel/sched/deadline.c:dl_task_timer
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810dec70-ffffffff810dedbf: find_lock_later_rq.part.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e5e10)
Location: kernel/sched/deadline.c:1948
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810e5e10-ffffffff810e5f67: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f1330)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810f1330-ffffffff810f1487: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fc350)
Location: kernel/sched/deadline.c:1963
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810fc350-ffffffff810fc4a3: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fac40)
Location: kernel/sched/deadline.c:2061
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810fac40-ffffffff810fad90: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fce50)
Location: kernel/sched/deadline.c:2040
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810fce50-ffffffff810fcfa0: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff81115c30)
Location: kernel/sched/deadline.c:2052
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff81115c30-ffffffff81115e88: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81133fe0)
Location: kernel/sched/deadline.c:2212
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff81133fe0-ffffffff811341e9: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115e4d0)
Location: kernel/sched/deadline.c:2219
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff8115e4d0-ffffffff8115e6cd: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116ebb0)
Location: kernel/sched/deadline.c:2210
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff8116ebb0-ffffffff8116edb8: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8117c130)
Location: kernel/sched/deadline.c:2308
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:push_dl_task
  - kernel/sched/build_policy.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff8117c130-ffffffff8117c338: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff8000101530c8)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffff8000101530c8-ffff80001015332c: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c039f9ec)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
c039f9ec-c039fc14: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a6550)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
c0000000001a6550-c0000000001a6848: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fae7c)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffe0000fae7c-ffffffe0000fb0a6: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ea730)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810ea730-ffffffff810ea887: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810da760)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810da760-ffffffff810da8ae: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7860)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810e7860-ffffffff810e79b7: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rq *find_lock_later_rq(struct task_struct *task, struct rq *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f24b0)
Location: kernel/sched/deadline.c:1964
Inline: False
Direct callers:
  - kernel/sched/deadline.c:dl_task_offline_migration
```
**Symbols:**

```
ffffffff810f24b0-ffffffff810f2607: find_lock_later_rq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
