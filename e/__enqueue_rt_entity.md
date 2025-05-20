# Function: <code>__enqueue_rt_entity</code>

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
In kernel/sched/rt.c (ffffffff810c07a8)
Location: kernel/sched/rt.c:1169
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
In kernel/sched/rt.c (ffffffff810c41bf)
Location: kernel/sched/rt.c:1220
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
In kernel/sched/rt.c (ffffffff810ca21c)
Location: kernel/sched/rt.c:1219
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
In kernel/sched/rt.c (ffffffff810c3d73)
Location: kernel/sched/rt.c:1231
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
In kernel/sched/rt.c (ffffffff810cb543)
Location: kernel/sched/rt.c:1221
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
In kernel/sched/rt.c (ffffffff810d2e83)
Location: kernel/sched/rt.c:1230
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
In kernel/sched/rt.c (ffffffff810dd0c3)
Location: kernel/sched/rt.c:1230
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
In kernel/sched/rt.c (ffffffff810e4083)
Location: kernel/sched/rt.c:1230
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
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810ee520)
Location: kernel/sched/rt.c:1231
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffff810ee520-ffffffff810ee8ad: __enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8210)
Location: kernel/sched/rt.c:1272
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810f8210-ffffffff810f83de: __enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f6420)
Location: kernel/sched/rt.c:1274
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810f6420-ffffffff810f65ee: __enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810f8440)
Location: kernel/sched/rt.c:1274
Inline: False
Direct callers:
  - kernel/sched/rt.c:enqueue_task_rt
```
**Symbols:**

```
ffffffff810f8440-ffffffff810f860b: __enqueue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff81113a13)
Location: kernel/sched/rt.c:1289
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
In kernel/sched/build_policy.c (ffffffff811310b7)
Location: kernel/sched/rt.c:1434
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
In kernel/sched/build_policy.c (ffffffff8115b02f)
Location: kernel/sched/rt.c:1430
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
In kernel/sched/build_policy.c (ffffffff8116b229)
Location: kernel/sched/rt.c:1430
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
In kernel/sched/build_policy.c (ffffffff81178bc9)
Location: kernel/sched/rt.c:1375
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
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffff80001014f6f0)
Location: kernel/sched/rt.c:1231
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffff80001014f6f0-ffff80001014fa30: __enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c039ce90)
Location: kernel/sched/rt.c:1231
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
c039ce90-c039d21c: __enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (c0000000001a2d30)
Location: kernel/sched/rt.c:1231
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
c0000000001a2d30-c0000000001a317c: __enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffe0000f7fe2)
Location: kernel/sched/rt.c:1231
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffe0000f7fe2-ffffffe0000f829a: __enqueue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810e8473)
Location: kernel/sched/rt.c:1231
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
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810d78e0)
Location: kernel/sched/rt.c:1231
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffff810d78e0-ffffffff810d7c6d: __enqueue_rt_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __enqueue_rt_entity(struct sched_rt_entity *rt_se, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/rt.c (ffffffff810e4a50)
Location: kernel/sched/rt.c:1231
Inline: False
Direct callers:
  - kernel/sched/rt.c:dequeue_rt_entity
  - kernel/sched/rt.c:enqueue_rt_entity
```
**Symbols:**

```
ffffffff810e4a50-ffffffff810e4ddd: __enqueue_rt_entity (STB_LOCAL)
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
In kernel/sched/rt.c (ffffffff810f11d3)
Location: kernel/sched/rt.c:1231
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
</ul>
