# Function: <code>enqueue_rt_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c0773)
Location: kernel/sched/rt.c:1227
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c4183)
Location: kernel/sched/rt.c:1289
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ca1e3)
Location: kernel/sched/rt.c:1288
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c3d46)
Location: kernel/sched/rt.c:1300
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cb516)
Location: kernel/sched/rt.c:1290
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d2e56)
Location: kernel/sched/rt.c:1299
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dd096)
Location: kernel/sched/rt.c:1299
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4056)
Location: kernel/sched/rt.c:1299
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ee8b0)
Location: kernel/sched/rt.c:1300
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
```
**Symbols:**

```
ffffffff810ee8b0-ffffffff810ee900: enqueue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f8412)
Location: kernel/sched/rt.c:1341
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
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
In kernel/sched/rt.c (ffffffff810f6622)
Location: kernel/sched/rt.c:1343
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
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
In kernel/sched/rt.c (ffffffff810f8642)
Location: kernel/sched/rt.c:1343
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
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
In kernel/sched/rt.c (ffffffff811139d6)
Location: kernel/sched/rt.c:1358
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
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
In kernel/sched/build_policy.c (ffffffff81131070)
Location: kernel/sched/rt.c:1506
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
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
In kernel/sched/build_policy.c (ffffffff8115afe2)
Location: kernel/sched/rt.c:1502
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
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
In kernel/sched/build_policy.c (ffffffff8116b1e4)
Location: kernel/sched/rt.c:1502
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
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
In kernel/sched/build_policy.c (ffffffff81178b84)
Location: kernel/sched/rt.c:1447
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_rt
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
void enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014fa30)
Location: kernel/sched/rt.c:1300
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
```
**Symbols:**

```
ffff80001014fa30-ffff80001014fa94: enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039d728)
Location: kernel/sched/rt.c:1300
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
```
**Symbols:**

```
c039d728-c039d77c: enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a3760)
Location: kernel/sched/rt.c:1300
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
```
**Symbols:**

```
c0000000001a3760-c0000000001a37e8: enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f829a)
Location: kernel/sched/rt.c:1300
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
```
**Symbols:**

```
ffffffe0000f829a-ffffffe0000f82f4: enqueue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810e8446)
Location: kernel/sched/rt.c:1300
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d7c70)
Location: kernel/sched/rt.c:1300
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
```
**Symbols:**

```
ffffffff810d7c70-ffffffff810d7cc0: enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4de0)
Location: kernel/sched/rt.c:1300
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
  - kernel/sched/rt.c:sched_rt_rq_enqueue
```
**Symbols:**

```
ffffffff810e4de0-ffffffff810e4e30: enqueue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f11a6)
Location: kernel/sched/rt.c:1300
Inline: True
Inline callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
