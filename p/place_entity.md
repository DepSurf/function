# Function: <code>place_entity</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b4050)
Location: kernel/sched/fair.c:2981
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810b4050-ffffffff810b40c2: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b6ac0)
Location: kernel/sched/fair.c:3262
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810b6ac0-ffffffff810b6b32: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bc390)
Location: kernel/sched/fair.c:3477
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810bc390-ffffffff810bc402: place_entity (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff810ba985)
Location: kernel/sched/fair.c:3582
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810c2d92)
Location: kernel/sched/fair.c:3921
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffff810cbc55)
Location: kernel/sched/fair.c:4092
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ce7a0)
Location: kernel/sched/fair.c:3783
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810ce7a0-ffffffff810ce812: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d6b50)
Location: kernel/sched/fair.c:3878
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d6b50-ffffffff810d6bbf: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e1130)
Location: kernel/sched/fair.c:3877
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e1130-ffffffff810e119f: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810edd14)
Location: kernel/sched/fair.c:4096
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
```
**Symbols:**

```
ffffffff810e9410-ffffffff810e947f: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebb34)
Location: kernel/sched/fair.c:4130
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
```
**Symbols:**

```
ffffffff810e71c0-ffffffff810e722f: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed4a4)
Location: kernel/sched/fair.c:4193
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
```
**Symbols:**

```
ffffffff810e90b0-ffffffff810e911c: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81106152)
Location: kernel/sched/fair.c:4205
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
```
**Symbols:**

```
ffffffff81100940-ffffffff811009a6: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811229c0)
Location: kernel/sched/fair.c:4255
Inline: False
Direct callers:
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff811229c0-ffffffff81122a5c: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8114a720)
Location: kernel/sched/fair.c:4656
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff8114a720-ffffffff8114a7bc: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4732
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff8115c400-ffffffff8115c53c: place_entity (STB_LOCAL)
ffffffff820d56f4-ffffffff820d5709: place_entity.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116bbc0)
Location: kernel/sched/fair.c:5158
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff8116bbc0-ffffffff8116bcbc: place_entity (STB_LOCAL)
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
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010141618)
Location: kernel/sched/fair.c:3877
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffff800010141618-ffff8000101416bc: place_entity (STB_LOCAL)
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
In kernel/sched/fair.c (c0393950)
Location: kernel/sched/fair.c:3877
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001998a0)
Location: kernel/sched/fair.c:3877
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
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
In kernel/sched/fair.c (ffffffe0000f08de)
Location: kernel/sched/fair.c:3877
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
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
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db2e0)
Location: kernel/sched/fair.c:3877
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810db2e0-ffffffff810db34f: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ca2f0)
Location: kernel/sched/fair.c:3877
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810ca2f0-ffffffff810ca35f: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d7660)
Location: kernel/sched/fair.c:3877
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810d7660-ffffffff810d76cf: place_entity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void place_entity(struct cfs_rq *cfs_rq, struct sched_entity *se, int initial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e3100)
Location: kernel/sched/fair.c:3877
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:task_fork_fair
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810e3100-ffffffff810e316f: place_entity (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int initial</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
