# Function: <code>attach_entity_load_avg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b2c40)
Location: kernel/sched/fair.c:2750
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810b2c40-ffffffff810b2e44: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b7100)
Location: kernel/sched/fair.c:3001
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_task_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
  - kernel/sched/fair.c:post_init_entity_util_avg
```
**Symbols:**

```
ffffffff810b7100-ffffffff810b731d: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bd900)
Location: kernel/sched/fair.c:3303
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810bd900-ffffffff810bd994: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810b8890)
Location: kernel/sched/fair.c:3408
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
  - kernel/sched/fair.c:enqueue_entity
```
**Symbols:**

```
ffffffff810b8890-ffffffff810b894e: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810bf7f0)
Location: kernel/sched/fair.c:3709
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810bf7f0-ffffffff810bf926: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810c9be0)
Location: kernel/sched/fair.c:3760
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810c9be0-ffffffff810c9d3b: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810d0280)
Location: kernel/sched/fair.c:3434
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810d0280-ffffffff810d03c9: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810db440)
Location: kernel/sched/fair.c:3522
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810db440-ffffffff810db5dc: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e5b00)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810e5b00-ffffffff810e5c9c: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810ebcb0)
Location: kernel/sched/fair.c:3698
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810ebcb0-ffffffff810ebe93: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e9a90)
Location: kernel/sched/fair.c:3715
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810e9a90-ffffffff810e9c63: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810eb330)
Location: kernel/sched/fair.c:3757
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810eb330-ffffffff810eb4fe: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3769
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81103d90-ffffffff81103f8e: attach_entity_load_avg (STB_LOCAL)
ffffffff81ca62c7-ffffffff81ca62dc: attach_entity_load_avg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:3817
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff8111fc90-ffffffff8111feb1: attach_entity_load_avg (STB_LOCAL)
ffffffff81e55bb1-ffffffff81e55bc6: attach_entity_load_avg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4099
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81148c10-ffffffff81148e31: attach_entity_load_avg (STB_LOCAL)
ffffffff82056e41-ffffffff82056e56: attach_entity_load_avg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4156
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81158ac0-ffffffff81158ce1: attach_entity_load_avg (STB_LOCAL)
ffffffff820d558c-ffffffff820d55a1: attach_entity_load_avg.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/fair.c (0)
Location: kernel/sched/fair.c:4643
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff81165060-ffffffff81165281: attach_entity_load_avg (STB_LOCAL)
ffffffff821b0504-ffffffff821b0519: attach_entity_load_avg.cold (STB_LOCAL)
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
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffff800010142830)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffff800010142830-ffff8000101429f0: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0392c98)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
c0392c98-c0392ef8: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (c0000000001965f0)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
c0000000001965f0-c000000000196854: attach_entity_load_avg (STB_LOCAL)
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
In kernel/sched/fair.c (ffffffe0000efc8c)
Location: kernel/sched/fair.c:3519
Inline: True
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffe0000efc8c-ffffffe0000efd9c: attach_entity_load_avg.isra.0 (STB_LOCAL)
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
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dfcb0)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810dfcb0-ffffffff810dfe4c: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810cecb0)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810cecb0-ffffffff810cee4c: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810dc030)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810dc030-ffffffff810dc1cc: attach_entity_load_avg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void attach_entity_load_avg(struct cfs_rq *cfs_rq, struct sched_entity *se, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810e7d30)
Location: kernel/sched/fair.c:3519
Inline: False
Direct callers:
  - kernel/sched/fair.c:attach_entity_cfs_rq
```
**Symbols:**

```
ffffffff810e7d30-ffffffff810e7ee2: attach_entity_load_avg (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
<code>int flags</code>
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
