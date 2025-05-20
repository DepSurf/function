# Function: <code>__gnet_stats_copy_queue</code>

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
In net/core/gen_stats.c (ffffffff8170f1c9)
Location: net/core/gen_stats.c:238
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff81776a37)
Location: net/core/gen_stats.c:257
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff817a3cb7)
Location: net/core/gen_stats.c:255
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff817c1d57)
Location: net/core/gen_stats.c:255
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
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
In net/core/gen_stats.c (ffffffff8183b779)
Location: net/core/gen_stats.c:255
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81885e0c)
Location: net/core/gen_stats.c:267
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81885cd0-ffffffff81885d18: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818a677c)
Location: net/core/gen_stats.c:301
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff818a6400-ffffffff818a6444: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818f1bec)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff818f17e0-ffffffff818f1828: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81923b3c)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81923730-ffffffff81923778: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f7260)
Location: net/core/gen_stats.c:302
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff819f7260-ffffffff819f72f5: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819f6cd0)
Location: net/core/gen_stats.c:302
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff819f6cd0-ffffffff819f6d65: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff819dce50)
Location: net/core/gen_stats.c:302
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff819dce50-ffffffff819dcee5: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81a8d090)
Location: net/core/gen_stats.c:302
Inline: False
Direct callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81a8d090-ffffffff81a8d153: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffff800010bbf088)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffff800010bbed10-ffff800010bbed98: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c0cdab58)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
c0cda728-c0cda788: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (c000000000c98494)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
c000000000c97e30-c000000000c97ecc: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffe00074cd86)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffe00074c720-ffffffe00074c786: __gnet_stats_copy_queue (STB_GLOBAL)
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
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff818c3b3c)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff818c3730-ffffffff818c3778: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff8187da7c)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff8187d670-ffffffff8187d6b8: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81914b3c)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81914730-ffffffff81914778: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __gnet_stats_copy_queue(struct gnet_stats_queue *qstats, const struct gnet_stats_queue *cpu, const struct gnet_stats_queue *q, __u32 qlen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/gen_stats.c (ffffffff81935d0c)
Location: net/core/gen_stats.c:298
Inline: True
Inline callers:
  - net/core/gen_stats.c:gnet_stats_copy_queue
Direct callers:
  - net/sched/sch_mq.c:mq_dump
```
**Symbols:**

```
ffffffff81935900-ffffffff81935948: __gnet_stats_copy_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
