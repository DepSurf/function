# Function: <code>enqueue_dl_entity</code>

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
In kernel/sched/deadline.c (ffffffff810c1c19)
Location: kernel/sched/deadline.c:933
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810c5775)
Location: kernel/sched/deadline.c:913
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810cb765)
Location: kernel/sched/deadline.c:902
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810c7724)
Location: kernel/sched/deadline.c:1364
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810cecd7)
Location: kernel/sched/deadline.c:1353
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810d65cf)
Location: kernel/sched/deadline.c:1412
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
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
In kernel/sched/deadline.c (ffffffff810e0b0f)
Location: kernel/sched/deadline.c:1411
Inline: True
Inline callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:1410
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810e7570-ffffffff810e7a89: enqueue_dl_entity (STB_LOCAL)
ffffffff810e96e9-ffffffff810e9741: enqueue_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f2b90)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810f2b90-ffffffff810f30c8: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fc1d0)
Location: kernel/sched/deadline.c:1445
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810fc1d0-ffffffff810fc34d: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fa740)
Location: kernel/sched/deadline.c:1522
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810fa740-ffffffff810fa8ad: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fc670)
Location: kernel/sched/deadline.c:1501
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810fc670-ffffffff810fcab5: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/deadline.c (0)
Location: kernel/sched/deadline.c:1501
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff81118bb0-ffffffff81119042: enqueue_dl_entity (STB_LOCAL)
ffffffff81ca6d59-ffffffff81ca6dea: enqueue_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1639
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff81135020-ffffffff811356b4: enqueue_dl_entity (STB_LOCAL)
ffffffff81e5657b-ffffffff81e5660e: enqueue_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1640
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff8115f570-ffffffff8115fc21: enqueue_dl_entity (STB_LOCAL)
ffffffff820577a5-ffffffff82057838: enqueue_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1631
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff8116fc60-ffffffff81170340: enqueue_dl_entity (STB_LOCAL)
ffffffff820d5fcb-ffffffff820d605e: enqueue_dl_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_policy.c (0)
Location: kernel/sched/deadline.c:1705
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
  - kernel/sched/build_policy.c:dl_server_start
  - kernel/sched/build_policy.c:update_curr_dl_se
  - kernel/sched/build_policy.c:dl_task_timer
```
**Symbols:**

```
ffffffff8117d1b0-ffffffff8117ddfb: enqueue_dl_entity (STB_LOCAL)
ffffffff821b10da-ffffffff821b127d: enqueue_dl_entity.cold (STB_LOCAL)
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
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff800010154df8)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffff800010154df8-ffff800010155344: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a2224)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
c03a2224-c03a2b04: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a8cb0)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
c0000000001a8cb0-c0000000001a93ac: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fc8b0)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffe0000fc8b0-ffffffe0000fcda4: enqueue_dl_entity (STB_LOCAL)
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
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ebf90)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810ebf90-ffffffff810ec4c8: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810dbfb0)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810dbfb0-ffffffff810dc561: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e90c0)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810e90c0-ffffffff810e95f8: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void enqueue_dl_entity(struct sched_dl_entity *dl_se, struct sched_dl_entity *pi_se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f4070)
Location: kernel/sched/deadline.c:1443
Inline: False
Direct callers:
  - kernel/sched/deadline.c:enqueue_task_dl
```
**Symbols:**

```
ffffffff810f4070-ffffffff810f45a8: enqueue_dl_entity (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct sched_dl_entity *pi_se</code>
</li>
<li>
<b>Param reordered. </b>
<code>dl_se, pi_se, flags</code> ➡️ <code>dl_se, flags</code>
</li>
</ul>
</details>
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
