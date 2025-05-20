# Function: <code>detach_entity_load_avg</code>

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
In kernel/sched/fair.c (ffffffff810b4105)
Location: kernel/sched/fair.c:2777
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
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
In kernel/sched/fair.c (ffffffff810b93da)
Location: kernel/sched/fair.c:3040
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
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
In kernel/sched/fair.c (ffffffff810c0994)
Location: kernel/sched/fair.c:3323
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
In kernel/sched/fair.c (ffffffff810ba86a)
Location: kernel/sched/fair.c:3428
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
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
In kernel/sched/fair.c (ffffffff810c2bdb)
Location: kernel/sched/fair.c:3756
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810cb8c5)
Location: kernel/sched/fair.c:3807
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810d1ffb)
Location: kernel/sched/fair.c:3481
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810dd989)
Location: kernel/sched/fair.c:3571
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8049)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810edac9)
Location: kernel/sched/fair.c:3753
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810eb8f9)
Location: kernel/sched/fair.c:3770
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810ed269)
Location: kernel/sched/fair.c:3812
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff81105f1d)
Location: kernel/sched/fair.c:3824
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff8112146a)
Location: kernel/sched/fair.c:3872
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void detach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4154
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
```
**Symbols:**

```
ffffffff81148980-ffffffff81148bfd: detach_entity_load_avg (STB_LOCAL)
ffffffff82056e2c-ffffffff82056e41: detach_entity_load_avg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void detach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4211
Inline: False
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
```
**Symbols:**

```
ffffffff81158830-ffffffff81158aad: detach_entity_load_avg (STB_LOCAL)
ffffffff820d5577-ffffffff820d558c: detach_entity_load_avg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void detach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4698
Inline: False
Direct callers:
  - kernel/sched/fair.c:switched_from_fair
```
**Symbols:**

```
ffffffff81164dd0-ffffffff8116504d: detach_entity_load_avg (STB_LOCAL)
ffffffff821b04ef-ffffffff821b0504: detach_entity_load_avg.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010145a40)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (c03936e0)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (c0000000001995f4)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffe0000f0798)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810e21f9)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d12d9)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810de579)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
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
In kernel/sched/fair.c (ffffffff810ea079)
Location: kernel/sched/fair.c:3568
Inline: True
Inline callers:
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
