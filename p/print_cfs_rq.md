# Function: <code>print_cfs_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c73c0)
Location: kernel/sched/debug.c:166
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810c73c0-ffffffff810c7c78: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cb900)
Location: kernel/sched/debug.c:467
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810cb900-ffffffff810cc1b8: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d1930)
Location: kernel/sched/debug.c:473
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810d1930-ffffffff810d21e8: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d0a30)
Location: kernel/sched/debug.c:474
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810d0a30-ffffffff810d12d2: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d8500)
Location: kernel/sched/debug.c:521
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810d8500-ffffffff810d8e14: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:495
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810e1de3-ffffffff810e2150: print_cfs_rq.cold.13 (STB_LOCAL)
ffffffff810df970-ffffffff810dff70: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:496
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810ec533-ffffffff810ec8a0: print_cfs_rq.cold.14 (STB_LOCAL)
ffffffff810ea0f0-ffffffff810ea6f0: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810f3278-ffffffff810f35d4: print_cfs_rq.cold (STB_LOCAL)
ffffffff810f0ee0-ffffffff810f14ed: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810feef1-ffffffff810ff24d: print_cfs_rq.cold (STB_LOCAL)
ffffffff810fcb90-ffffffff810fd19d: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:482
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff81109629-ffffffff8110996e: print_cfs_rq.cold (STB_LOCAL)
ffffffff81107320-ffffffff8110793f: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:536
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff81bdda0d-ffffffff81bddd52: print_cfs_rq.cold (STB_LOCAL)
ffffffff81105b30-ffffffff8110614f: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:561
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff81bcfb72-ffffffff81bcfef1: print_cfs_rq.cold (STB_LOCAL)
ffffffff81107a50-ffffffff81108187: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:574
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff81ca83a1-ffffffff81ca8745: print_cfs_rq.cold (STB_LOCAL)
ffffffff81125b40-ffffffff811262ee: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:580
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff81e58286-ffffffff81e586b5: print_cfs_rq.cold (STB_LOCAL)
ffffffff81146280-ffffffff811469e1: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811734d0)
Location: kernel/sched/debug.c:581
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff811734d0-ffffffff8117414e: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811840e0)
Location: kernel/sched/debug.c:627
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff811840e0-ffffffff81184d5e: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81192790)
Location: kernel/sched/debug.c:629
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff81192790-ffffffff8119353c: print_cfs_rq (STB_GLOBAL)
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
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010161fb8)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffff800010161fb8-ffff800010162834: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03ae7ac)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
c03ae7ac-c03aef6c: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b82c0)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
c0000000001b82c0-c0000000001b8dcc: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe000105d0e)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffe000105d0e-ffffffe000106502: print_cfs_rq (STB_GLOBAL)
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
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810f8211-ffffffff810f856d: print_cfs_rq.cold (STB_LOCAL)
ffffffff810f5ec0-ffffffff810f64cd: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810e83e1-ffffffff810e873d: print_cfs_rq.cold (STB_LOCAL)
ffffffff810e6080-ffffffff810e668d: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff810f5421-ffffffff810f577d: print_cfs_rq.cold (STB_LOCAL)
ffffffff810f30c0-ffffffff810f36cd: print_cfs_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_cfs_rq(struct seq_file *m, int cpu, struct cfs_rq *cfs_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:483
Inline: False
Direct callers:
  - kernel/sched/fair.c:print_cfs_stats
```
**Symbols:**

```
ffffffff81100421-ffffffff8110077d: print_cfs_rq.cold (STB_LOCAL)
ffffffff810fe0c0-ffffffff810fe6cd: print_cfs_rq (STB_GLOBAL)
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
