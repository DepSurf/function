# Function: <code>dequeue_rt_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c0470)
Location: kernel/sched/rt.c:1210
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810c0470-ffffffff810c0699: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c3e00)
Location: kernel/sched/rt.c:1272
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810c3e00-ffffffff810c4093: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c9e70)
Location: kernel/sched/rt.c:1271
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810c9e70-ffffffff810ca0f4: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810c3aa0)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810c3aa0-ffffffff810c3d07: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810cb270)
Location: kernel/sched/rt.c:1273
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810cb270-ffffffff810cb4d9: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d2960)
Location: kernel/sched/rt.c:1282
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810d2960-ffffffff810d2bc4: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810dc2d0)
Location: kernel/sched/rt.c:1282
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810dc2d0-ffffffff810dc534: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/rt.c (0)
Location: kernel/sched/rt.c:1282
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810e3290-ffffffff810e34d9: dequeue_rt_stack (STB_LOCAL)
ffffffff810e528c-ffffffff810e52db: dequeue_rt_stack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810edb50)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffff810edb50-ffffffff810ede46: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7710)
Location: kernel/sched/rt.c:1324
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810f7710-ffffffff810f77d6: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f5870)
Location: kernel/sched/rt.c:1326
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810f5870-ffffffff810f5902: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f7780)
Location: kernel/sched/rt.c:1326
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810f7780-ffffffff810f79d4: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff81111db0)
Location: kernel/sched/rt.c:1341
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff81111db0-ffffffff81112066: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8112ef00)
Location: kernel/sched/rt.c:1486
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff8112ef00-ffffffff8112f21e: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81158cd0)
Location: kernel/sched/rt.c:1482
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff81158cd0-ffffffff81158fed: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81168fb0)
Location: kernel/sched/rt.c:1482
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff81168fb0-ffffffff811692e0: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/rt.c:1427
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:dequeue_task_rt
  - kernel/sched/build_policy.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff811770b0-ffffffff81177449: dequeue_rt_stack (STB_LOCAL)
ffffffff821b0bbe-ffffffff821b0bd3: dequeue_rt_stack.cold (STB_LOCAL)
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
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014eb48)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffff80001014eb48-ffff80001014edc8: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039cb94)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
c039cb94-c039ce90: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a29c0)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
c0000000001a29c0-c0000000001a2d28: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f752c)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffe0000f752c-ffffffe0000f778e: dequeue_rt_stack (STB_LOCAL)
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
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e7ac0)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810e7ac0-ffffffff810e7d25: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d6ea0)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffff810d6ea0-ffffffff810d7196: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4080)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffff810e4080-ffffffff810e4376: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dequeue_rt_stack(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f02d0)
Location: kernel/sched/rt.c:1283
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_task_rt
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810f02d0-ffffffff810f0535: dequeue_rt_stack (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
