# Function: <code>enqueue_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b7c30)
Location: kernel/sched/fair.c:3015
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810b7c30-ffffffff810b8893: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bb680)
Location: kernel/sched/fair.c:3347
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810bb680-ffffffff810bbf25: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c1e60)
Location: kernel/sched/fair.c:3562
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810c1e60-ffffffff810c2492: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bca00)
Location: kernel/sched/fair.c:3667
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810bca00-ffffffff810bd0ef: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c4600)
Location: kernel/sched/fair.c:4006
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810c4600-ffffffff810c4ca9: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4177
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810cc000-ffffffff810cc633: enqueue_entity (STB_LOCAL)
ffffffff810d227d-ffffffff810d2295: enqueue_entity.cold.108 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3868
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810d4760-ffffffff810d4d74: enqueue_entity (STB_LOCAL)
ffffffff810dbbed-ffffffff810dbc05: enqueue_entity.cold.115 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3963
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810dcba0-ffffffff810dd1b6: enqueue_entity (STB_LOCAL)
ffffffff810e2b6a-ffffffff810e2b82: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810e6fd0-ffffffff810e75e6: enqueue_entity (STB_LOCAL)
ffffffff810ed21a-ffffffff810ed232: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4182
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810f1f20-ffffffff810f2365: enqueue_entity (STB_LOCAL)
ffffffff810f712e-ffffffff810f7146: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4216
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810f0050-ffffffff810f0514: enqueue_entity (STB_LOCAL)
ffffffff81bdc7b3-ffffffff81bdc7cb: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4279
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810f1820-ffffffff810f1ce4: enqueue_entity (STB_LOCAL)
ffffffff81bce92e-ffffffff81bce946: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4291
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff8110b370-ffffffff8110b85a: enqueue_entity (STB_LOCAL)
ffffffff81ca65a9-ffffffff81ca65f1: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4326
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff81126db0-ffffffff811272b4: enqueue_entity (STB_LOCAL)
ffffffff81e55dec-ffffffff81e55e19: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4727
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff81150260-ffffffff81150788: enqueue_entity (STB_LOCAL)
ffffffff82057062-ffffffff82057077: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4824
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff8115f0e0-ffffffff8115f636: enqueue_entity (STB_LOCAL)
ffffffff820d578b-ffffffff820d57a0: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:5264
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff8116d680-ffffffff8116dbc5: enqueue_entity (STB_LOCAL)
ffffffff821b07c5-ffffffff821b0804: enqueue_entity.cold (STB_LOCAL)
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
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010146ed8)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffff800010146ed8-ffff80001014746c: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0395128)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
c0395128-c03959d0: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001984e0)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
c0000000001984e0-c000000000198c08: enqueue_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f2750)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffe0000f2750-ffffffe0000f2cca: enqueue_entity (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810e1180-ffffffff810e1796: enqueue_entity (STB_LOCAL)
ffffffff810e737a-ffffffff810e7392: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810d0260-ffffffff810d0876: enqueue_entity (STB_LOCAL)
ffffffff810d651a-ffffffff810d6532: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810dd500-ffffffff810ddb16: enqueue_entity (STB_LOCAL)
ffffffff810e374a-ffffffff810e3762: enqueue_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void enqueue_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3962
Inline: False
Direct callers:
  - kernel/sched/fair.c:enqueue_task_fair
  - kernel/sched/fair.c:unthrottle_cfs_rq
```
**Symbols:**

```
ffffffff810e9280-ffffffff810e9600: enqueue_entity (STB_LOCAL)
ffffffff810ef337-ffffffff810ef34f: enqueue_entity.cold (STB_LOCAL)
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
