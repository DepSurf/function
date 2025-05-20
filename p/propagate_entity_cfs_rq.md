# Function: <code>propagate_entity_cfs_rq</code>

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
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bff30)
Location: kernel/sched/fair.c:9030
Inline: True
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810bff30-ffffffff810c0951: propagate_entity_cfs_rq.isra.66 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ba2a0)
Location: kernel/sched/fair.c:9054
Inline: True
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810ba2a0-ffffffff810ba823: propagate_entity_cfs_rq.isra.74 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c2370)
Location: kernel/sched/fair.c:9527
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810c2370-ffffffff810c2a28: propagate_entity_cfs_rq.isra.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810caf50)
Location: kernel/sched/fair.c:10034
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810caf50-ffffffff810cb479: propagate_entity_cfs_rq.isra.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d1a60)
Location: kernel/sched/fair.c:10138
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810d1a60-ffffffff810d1fcd: propagate_entity_cfs_rq.isra.92 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dbc00)
Location: kernel/sched/fair.c:10078
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810dbc00-ffffffff810dbc48: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e62a0)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810e62a0-ffffffff810e62e8: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ed890)
Location: kernel/sched/fair.c:10748
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810ed890-ffffffff810ed8de: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb6c0)
Location: kernel/sched/fair.c:10862
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810eb6c0-ffffffff810eb70e: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void propagate_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ecf00)
Location: kernel/sched/fair.c:10922
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810ecf00-ffffffff810ed240: propagate_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void propagate_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81105bb0)
Location: kernel/sched/fair.c:11288
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81105bb0-ffffffff81105ef0: propagate_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void propagate_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81120670)
Location: kernel/sched/fair.c:11406
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81120670-ffffffff81120a03: propagate_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void propagate_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81149ee0)
Location: kernel/sched/fair.c:11933
Inline: True
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81149ee0-ffffffff8114a19f: propagate_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void propagate_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81159d90)
Location: kernel/sched/fair.c:12251
Inline: True
Direct callers:
  - kernel/sched/fair.c:detach_task_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81159d90-ffffffff8115a06d: propagate_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void propagate_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811663c0)
Location: kernel/sched/fair.c:12688
Inline: True
Direct callers:
  - kernel/sched/fair.c:switched_from_fair
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff811663c0-ffffffff811666a9: propagate_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffff8000101459b8)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffff8000101459b8-ffff800010145a10: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void propagate_entity_cfs_rq(struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0393664)
Location: kernel/sched/fair.c:10063
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
c0393664-c03936b0: propagate_entity_cfs_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (c000000000196f90)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
c000000000196f90-c000000000197010: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffe0000f072e)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffe0000f072e-ffffffe0000f076c: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e0450)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810e0450-ffffffff810e0498: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cf450)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810cf450-ffffffff810cf498: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dc7d0)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810dc7d0-ffffffff810dc818: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e8530)
Location: kernel/sched/fair.c:10063
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:detach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810e8530-ffffffff810e8578: propagate_entity_cfs_rq.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
