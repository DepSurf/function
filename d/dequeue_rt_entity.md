# Function: <code>dequeue_rt_entity</code>

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
In kernel/sched/rt.c (ffffffff810c06b9)
Location: kernel/sched/rt.c:1237
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810c40be)
Location: kernel/sched/rt.c:1299
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810ca11e)
Location: kernel/sched/rt.c:1298
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810c4d9e)
Location: kernel/sched/rt.c:1310
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810cc44e)
Location: kernel/sched/rt.c:1300
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810d38de)
Location: kernel/sched/rt.c:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810dcfde)
Location: kernel/sched/rt.c:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810e3f9e)
Location: kernel/sched/rt.c:1309
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810eecb0)
Location: kernel/sched/rt.c:1310
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
**Symbols:**

```
ffffffff810eecb0-ffffffff810eed1e: dequeue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f90ae)
Location: kernel/sched/rt.c:1351
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810f729e)
Location: kernel/sched/rt.c:1353
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff810f93ee)
Location: kernel/sched/rt.c:1353
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/rt.c (ffffffff811148d2)
Location: kernel/sched/rt.c:1368
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
In kernel/sched/build_policy.c (ffffffff8113234b)
Location: kernel/sched/rt.c:1518
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
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
In kernel/sched/build_policy.c (ffffffff8115c62b)
Location: kernel/sched/rt.c:1514
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
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
In kernel/sched/build_policy.c (ffffffff8116c4cb)
Location: kernel/sched/rt.c:1514
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
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
In kernel/sched/build_policy.c (ffffffff8117986b)
Location: kernel/sched/rt.c:1459
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
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
void dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff8000101503a8)
Location: kernel/sched/rt.c:1310
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
**Symbols:**

```
ffff8000101503a8-ffff800010150428: dequeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039dfe4)
Location: kernel/sched/rt.c:1310
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
**Symbols:**

```
c039dfe4-c039e060: dequeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a4330)
Location: kernel/sched/rt.c:1310
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
**Symbols:**

```
c0000000001a4330-c0000000001a43dc: dequeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f8b34)
Location: kernel/sched/rt.c:1310
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
**Symbols:**

```
ffffffe0000f8b34-ffffffe0000f8b9e: dequeue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810e906e)
Location: kernel/sched/rt.c:1310
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d8070)
Location: kernel/sched/rt.c:1310
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
**Symbols:**

```
ffffffff810d8070-ffffffff810d80de: dequeue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dequeue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e51e0)
Location: kernel/sched/rt.c:1310
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:update_curr_rt
```
**Symbols:**

```
ffffffff810e51e0-ffffffff810e524e: dequeue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f10ee)
Location: kernel/sched/rt.c:1310
Inline: True
Inline callers:
  - kernel/sched/rt.c:dequeue_task_rt
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
