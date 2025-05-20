# Function: <code>collect_percpu_times</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f6260)
Location: kernel/sched/psi.c:301
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff810f6260-ffffffff810f6458: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81102000)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff81102000-ffffffff811021f8: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110ce00)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff8110ce00-ffffffff8110cf49: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81109fa0)
Location: kernel/sched/psi.c:301
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff81109fa0-ffffffff8110a0e9: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8110bb80)
Location: kernel/sched/psi.c:310
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff8110bb80-ffffffff8110bdaf: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff8112a620)
Location: kernel/sched/psi.c:321
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_worker
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff8112a620-ffffffff8112aa45: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811436b0)
Location: kernel/sched/psi.c:307
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_avgs_work
```
**Symbols:**

```
ffffffff811436b0-ffffffff81143b27: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116f100)
Location: kernel/sched/psi.c:332
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_poll_worker
  - kernel/sched/build_utility.c:psi_avgs_work
```
**Symbols:**

```
ffffffff8116f100-ffffffff8116f41d: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81180920)
Location: kernel/sched/psi.c:336
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
```
**Symbols:**

```
ffffffff81180920-ffffffff81180be2: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118e670)
Location: kernel/sched/psi.c:336
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_rtpoll_work
  - kernel/sched/build_utility.c:psi_avgs_work
```
**Symbols:**

```
ffffffff8118e670-ffffffff8118e932: collect_percpu_times (STB_LOCAL)
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
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffff800010166c90)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffff800010166c90-ffff800010166eb8: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c03b2acc)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
c03b2acc-c03b2d4c: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (c0000000001bde00)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
c0000000001bde00-c0000000001be0b4: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffe000108a56)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffe000108a56-ffffffe000108c26: collect_percpu_times (STB_LOCAL)
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
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810fb310)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff810fb310-ffffffff810fb508: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810eb530)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff810eb530-ffffffff810eb728: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff810f84d0)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff810f84d0-ffffffff810f86c8: collect_percpu_times (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void collect_percpu_times(struct psi_group *group, enum psi_aggregators aggregator, u32 *pchanged_states);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/psi.c (ffffffff81103610)
Location: kernel/sched/psi.c:302
Inline: False
Direct callers:
  - kernel/sched/psi.c:psi_poll_work
  - kernel/sched/psi.c:psi_avgs_work
```
**Symbols:**

```
ffffffff81103610-ffffffff81103808: collect_percpu_times (STB_LOCAL)
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
