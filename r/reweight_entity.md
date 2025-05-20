# Function: <code>reweight_entity</code>

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
In kernel/sched/fair.c (ffffffff810b4c2e)
Location: kernel/sched/fair.c:2418
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_shares
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
In kernel/sched/fair.c (ffffffff810b77a3)
Location: kernel/sched/fair.c:2542
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_shares
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
In kernel/sched/fair.c (ffffffff810bfab3)
Location: kernel/sched/fair.c:2674
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_shares
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
In kernel/sched/fair.c (ffffffff810bb4a2)
Location: kernel/sched/fair.c:2746
Inline: True
Inline callers:
  - kernel/sched/fair.c:update_cfs_shares
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2ff0)
Location: kernel/sched/fair.c:2782
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810c2ff0-ffffffff810c3185: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c94e0)
Location: kernel/sched/fair.c:2810
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810c94e0-ffffffff810c9690: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d38c0)
Location: kernel/sched/fair.c:2791
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810d38c0-ffffffff810d3a70: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dadc0)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810dadc0-ffffffff810daf70: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e4cd0)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810e4cd0-ffffffff810e4e80: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ee2e0)
Location: kernel/sched/fair.c:3082
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810ee2e0-ffffffff810ee414: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ec0e0)
Location: kernel/sched/fair.c:3096
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810ec0e0-ffffffff810ec218: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eea80)
Location: kernel/sched/fair.c:3093
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810eea80-ffffffff810eebb6: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811070e0)
Location: kernel/sched/fair.c:3083
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff811070e0-ffffffff811071ee: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81124290)
Location: kernel/sched/fair.c:3110
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff81124290-ffffffff811243f5: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114c250)
Location: kernel/sched/fair.c:3318
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff8114c250-ffffffff8114c3b5: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115a4e0)
Location: kernel/sched/fair.c:3375
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff8115a4e0-ffffffff8115a645: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116bdb0)
Location: kernel/sched/fair.c:3780
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff8116bdb0-ffffffff8116bfba: reweight_entity (STB_LOCAL)
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
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010144a40)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffff800010144a40-ffff800010144be4: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c03923d8)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
c03923d8-c0392734: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000195d10)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
c000000000195d10-c000000000195f28: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f1600)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffe0000f1600-ffffffe0000f17e0: reweight_entity (STB_LOCAL)
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
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dee80)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810dee80-ffffffff810df030: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cde90)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810cde90-ffffffff810ce040: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db200)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810db200-ffffffff810db3b0: reweight_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void reweight_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, long unsigned int weight, long unsigned int runnable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6ef0)
Location: kernel/sched/fair.c:2876
Inline: False
Direct callers:
  - kernel/sched/fair.c:update_cfs_group
  - kernel/sched/fair.c:reweight_task
```
**Symbols:**

```
ffffffff810e6ef0-ffffffff810e70a0: reweight_entity (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int runnable</code>
</li>
</ul>
</details>
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
