# Function: <code>check_cfs_rq_runtime</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b7be0)
Location: kernel/sched/fair.c:3921
Inline: True
Direct callers:
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:pick_next_task_fair
```
**Symbols:**

```
ffffffff810b7be0-ffffffff810b7c2a: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb630)
Location: kernel/sched/fair.c:4276
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810bb630-ffffffff810bb67b: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1cf0)
Location: kernel/sched/fair.c:4493
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810c1cf0-ffffffff810c1d3b: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc600)
Location: kernel/sched/fair.c:4616
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810bc600-ffffffff810bc64b: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4470)
Location: kernel/sched/fair.c:4955
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810c4470-ffffffff810c44ba: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cbe70)
Location: kernel/sched/fair.c:5128
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810cbe70-ffffffff810cbeba: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d4330)
Location: kernel/sched/fair.c:4833
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810d4330-ffffffff810d437a: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dc4e0)
Location: kernel/sched/fair.c:4949
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810dc4e0-ffffffff810dc529: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e6900)
Location: kernel/sched/fair.c:4881
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810e6900-ffffffff810e6949: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f0f30)
Location: kernel/sched/fair.c:5143
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810f0f30-ffffffff810f0f74: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810efbb0)
Location: kernel/sched/fair.c:5186
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810efbb0-ffffffff810efbf4: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f15e0)
Location: kernel/sched/fair.c:5249
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810f15e0-ffffffff810f1624: check_cfs_rq_runtime (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff8110f8c8)
Location: kernel/sched/fair.c:5281
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
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
In kernel/sched/fair.c (ffffffff8112b8bd)
Location: kernel/sched/fair.c:5328
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114ff50)
Location: kernel/sched/fair.c:5722
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff8114ff50-ffffffff8114ffb6: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8115eda0)
Location: kernel/sched/fair.c:5932
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff8115eda0-ffffffff8115ee06: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116d420)
Location: kernel/sched/fair.c:6293
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:pick_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff8116d420-ffffffff8116d486: check_cfs_rq_runtime (STB_LOCAL)
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
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010146810)
Location: kernel/sched/fair.c:4881
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffff800010146810-ffff800010146878: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c039a6b4)
Location: kernel/sched/fair.c:4881
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c000000000197b90)
Location: kernel/sched/fair.c:4881
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
c000000000197b90-c000000000197c10: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f5ef6)
Location: kernel/sched/fair.c:4881
Inline: True
Inline callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
  - kernel/sched/fair.c:put_prev_entity
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
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0ab0)
Location: kernel/sched/fair.c:4881
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810e0ab0-ffffffff810e0af9: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cfb30)
Location: kernel/sched/fair.c:4881
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810cfb30-ffffffff810cfb79: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dce30)
Location: kernel/sched/fair.c:4881
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810dce30-ffffffff810dce79: check_cfs_rq_runtime (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool check_cfs_rq_runtime(struct cfs_rq *cfs_rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8ba0)
Location: kernel/sched/fair.c:4881
Inline: True
Direct callers:
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:pick_next_task_fair
  - kernel/sched/fair.c:put_prev_entity
```
**Symbols:**

```
ffffffff810e8ba0-ffffffff810e8be9: check_cfs_rq_runtime (STB_LOCAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
