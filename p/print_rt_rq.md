# Function: <code>print_rt_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c7c80)
Location: kernel/sched/debug.c:237
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810c7c80-ffffffff810c7ec1: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cc1c0)
Location: kernel/sched/debug.c:538
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810cc1c0-ffffffff810cc401: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d21f0)
Location: kernel/sched/debug.c:544
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810d21f0-ffffffff810d2431: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d12e0)
Location: kernel/sched/debug.c:545
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810d12e0-ffffffff810d155a: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d8e20)
Location: kernel/sched/debug.c:595
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810d8e20-ffffffff810d909a: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:573
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810e2150-ffffffff810e2245: print_rt_rq.cold.14 (STB_LOCAL)
ffffffff810dff70-ffffffff810e011b: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
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
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810ec8a0-ffffffff810ec995: print_rt_rq.cold.15 (STB_LOCAL)
ffffffff810ea6f0-ffffffff810ea89b: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
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
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810f35d4-ffffffff810f36c3: print_rt_rq.cold (STB_LOCAL)
ffffffff810f14f0-ffffffff810f1695: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
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
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810ff24d-ffffffff810ff34b: print_rt_rq.cold (STB_LOCAL)
ffffffff810fd1a0-ffffffff810fd354: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:559
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff8110996e-ffffffff81109a5d: print_rt_rq.cold (STB_LOCAL)
ffffffff81107940-ffffffff81107ae5: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:613
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff81bddd52-ffffffff81bdde41: print_rt_rq.cold (STB_LOCAL)
ffffffff81106150-ffffffff811062f5: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:638
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff81bcfef1-ffffffff81bcffe0: print_rt_rq.cold (STB_LOCAL)
ffffffff81108190-ffffffff81108335: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:654
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff81ca8745-ffffffff81ca8833: print_rt_rq.cold (STB_LOCAL)
ffffffff811262f0-ffffffff81126494: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:662
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_rt_stats
```
**Symbols:**

```
ffffffff81e586b5-ffffffff81e587aa: print_rt_rq.cold (STB_LOCAL)
ffffffff811469f0-ffffffff81146ba4: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81174160)
Location: kernel/sched/debug.c:663
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_rt_stats
```
**Symbols:**

```
ffffffff81174160-ffffffff81174482: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184d70)
Location: kernel/sched/debug.c:709
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_rt_stats
```
**Symbols:**

```
ffffffff81184d70-ffffffff81185092: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81193550)
Location: kernel/sched/debug.c:714
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_rt_stats
```
**Symbols:**

```
ffffffff81193550-ffffffff81193839: print_rt_rq (STB_GLOBAL)
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
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010162838)
Location: kernel/sched/debug.c:561
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffff800010162838-ffff800010162ad0: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03aef6c)
Location: kernel/sched/debug.c:561
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
c03aef6c-c03af1d4: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b8dd0)
Location: kernel/sched/debug.c:561
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
c0000000001b8dd0-c0000000001b915c: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe000106502)
Location: kernel/sched/debug.c:561
Inline: False
Direct callers:
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffe000106502-ffffffe000106762: print_rt_rq (STB_GLOBAL)
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
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
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
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810f856d-ffffffff810f865c: print_rt_rq.cold (STB_LOCAL)
ffffffff810f64d0-ffffffff810f6675: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
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
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810e873d-ffffffff810e883b: print_rt_rq.cold (STB_LOCAL)
ffffffff810e6690-ffffffff810e6844: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
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
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff810f577d-ffffffff810f587b: print_rt_rq.cold (STB_LOCAL)
ffffffff810f36d0-ffffffff810f3884: print_rt_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_rt_rq(struct seq_file *m, int cpu, struct rt_rq *rt_rq);
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
  - kernel/sched/rt.c:print_rt_stats
```
**Symbols:**

```
ffffffff8110077d-ffffffff8110086c: print_rt_rq.cold (STB_LOCAL)
ffffffff810fe6d0-ffffffff810fe875: print_rt_rq (STB_GLOBAL)
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
