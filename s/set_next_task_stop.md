# Function: <code>set_next_task_stop</code>

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
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810f95b1)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff810f9520-ffffffff810f9577: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff811036c2)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff81103640-ffffffff81103696: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff81101de2)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff81101d60-ffffffff81101db6: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff81104152)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff811040d0-ffffffff81104126: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff81121254)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff811211c0-ffffffff81121222: set_next_task_stop (STB_LOCAL)
ffffffff81ca779b-ffffffff81ca77b0: set_next_task_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811443e9)
Location: kernel/sched/stop_task.c:31
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff81142a60-ffffffff81142acc: set_next_task_stop (STB_LOCAL)
ffffffff81e57d13-ffffffff81e57d28: set_next_task_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811701e9)
Location: kernel/sched/stop_task.c:31
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff8116e150-ffffffff8116e1bc: set_next_task_stop (STB_LOCAL)
ffffffff82057e16-ffffffff82057e2b: set_next_task_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117edd9)
Location: kernel/sched/stop_task.c:31
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff8117dd40-ffffffff8117ddac: set_next_task_stop (STB_LOCAL)
ffffffff820d657b-ffffffff820d6590: set_next_task_stop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c459)
Location: kernel/sched/stop_task.c:31
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff8118b510-ffffffff8118b57c: set_next_task_stop (STB_LOCAL)
ffffffff821b16e5-ffffffff821b16fa: set_next_task_stop.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffff80001015dee8)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffff80001015df58-ffff80001015dfbc: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (c03a9ccc)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
c03a9db0-c03a9e24: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (c0000000001b2a90)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
c0000000001b2b50-c0000000001b2bdc: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffe0001023ac)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffe000102462-ffffffe0001024c8: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810f29b1)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff810f2920-ffffffff810f2977: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810e2ac1)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff810e2a30-ffffffff810e2a87: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810efae1)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff810efa50-ffffffff810efaa7: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_next_task_stop(struct rq *rq, struct task_struct *stop, bool first);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/stop_task.c (ffffffff810fab31)
Location: kernel/sched/stop_task.c:32
Inline: True
Inline callers:
  - kernel/sched/stop_task.c:pick_next_task_stop
```
**Symbols:**

```
ffffffff810faaa0-ffffffff810faaf7: set_next_task_stop (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
