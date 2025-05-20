# Function: <code>detach_entity_cfs_rq</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c098a)
Location: kernel/sched/fair.c:9050
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
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
In kernel/sched/fair.c (ffffffff810ba863)
Location: kernel/sched/fair.c:9074
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2bb0)
Location: kernel/sched/fair.c:9547
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810c2bb0-ffffffff810c2d4f: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cb600)
Location: kernel/sched/fair.c:10054
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810cb600-ffffffff810cbc14: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1fd0)
Location: kernel/sched/fair.c:10158
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810d1fd0-ffffffff810d2175: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dd960)
Location: kernel/sched/fair.c:10098
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810dd960-ffffffff810ddb56: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8020)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810e8020-ffffffff810e8216: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810edaa0)
Location: kernel/sched/fair.c:10768
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810edaa0-ffffffff810edcd3: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb8d0)
Location: kernel/sched/fair.c:10882
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810eb8d0-ffffffff810ebaf2: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed240)
Location: kernel/sched/fair.c:10948
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810ed240-ffffffff810ed463: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11314
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff81105ef0-ffffffff81106114: detach_entity_cfs_rq (STB_LOCAL)
ffffffff81ca634b-ffffffff81ca6366: detach_entity_cfs_rq.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:11432
Inline: False
Direct callers:
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff81121440-ffffffff8112171d: detach_entity_cfs_rq (STB_LOCAL)
ffffffff81e55cc1-ffffffff81e55cdc: detach_entity_cfs_rq.cold (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffff8114a82e)
Location: kernel/sched/fair.c:11962
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
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
In kernel/sched/fair.c (ffffffff8115c5ae)
Location: kernel/sched/fair.c:12280
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
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
In kernel/sched/fair.c (ffffffff811666c5)
Location: kernel/sched/fair.c:12717
Inline: True
Inline callers:
  - kernel/sched/fair.c:switched_from_fair
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
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010145a10)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffff800010145a10-ffff800010145c04: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c03936b0)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
c03936b0-c03938f8: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001995b0)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
c0000000001995b0-c000000000199858: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f076c)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffe0000f076c-ffffffe0000f08aa: detach_entity_cfs_rq (STB_LOCAL)
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
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e21d0)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810e21d0-ffffffff810e23c6: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d12b0)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810d12b0-ffffffff810d14a6: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de550)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810de550-ffffffff810de746: detach_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void detach_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ea050)
Location: kernel/sched/fair.c:10083
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:migrate_task_rq_fair
```
**Symbols:**

```
ffffffff810ea050-ffffffff810ea25f: detach_entity_cfs_rq (STB_LOCAL)
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
