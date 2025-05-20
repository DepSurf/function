# Function: <code>print_dl_rq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c7ed0)
Location: kernel/sched/debug.c:259
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810c7ed0-ffffffff810c7f3b: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cc410)
Location: kernel/sched/debug.c:560
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810cc410-ffffffff810cc526: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d2440)
Location: kernel/sched/debug.c:566
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810d2440-ffffffff810d254a: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d1560)
Location: kernel/sched/debug.c:573
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810d1560-ffffffff810d169e: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d90a0)
Location: kernel/sched/debug.c:623
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810d90a0-ffffffff810d91de: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:603
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810e2245-ffffffff810e22d8: print_dl_rq.cold.15 (STB_LOCAL)
ffffffff810e0120-ffffffff810e01e6: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:604
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810ec995-ffffffff810eca28: print_dl_rq.cold.16 (STB_LOCAL)
ffffffff810ea8a0-ffffffff810ea966: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810f36c3-ffffffff810f3755: print_dl_rq.cold (STB_LOCAL)
ffffffff810f16a0-ffffffff810f1763: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810ff34b-ffffffff810ff3dd: print_dl_rq.cold (STB_LOCAL)
ffffffff810fd360-ffffffff810fd423: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:589
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff81109a5d-ffffffff81109aef: print_dl_rq.cold (STB_LOCAL)
ffffffff81107af0-ffffffff81107bb3: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:643
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff81bdde41-ffffffff81bdded3: print_dl_rq.cold (STB_LOCAL)
ffffffff81106300-ffffffff811063c3: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:668
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff81bcffe0-ffffffff81bd0072: print_dl_rq.cold (STB_LOCAL)
ffffffff81108340-ffffffff81108403: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:684
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff81ca8833-ffffffff81ca88df: print_dl_rq.cold (STB_LOCAL)
ffffffff811264a0-ffffffff8112657d: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:692
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_dl_stats
```
**Symbols:**

```
ffffffff81e587aa-ffffffff81e58857: print_dl_rq.cold (STB_LOCAL)
ffffffff81146bb0-ffffffff81146c9e: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811744a0)
Location: kernel/sched/debug.c:693
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_dl_stats
```
**Symbols:**

```
ffffffff811744a0-ffffffff81174652: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811850b0)
Location: kernel/sched/debug.c:739
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_dl_stats
```
**Symbols:**

```
ffffffff811850b0-ffffffff81185262: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81193850)
Location: kernel/sched/debug.c:741
Inline: False
Direct callers:
  - kernel/sched/build_policy.c:print_dl_stats
```
**Symbols:**

```
ffffffff81193850-ffffffff811939cd: print_dl_rq (STB_GLOBAL)
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
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010162ad0)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffff800010162ad0-ffff800010162c54: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03af1d4)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
c03af1d4-c03af354: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b9160)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
c0000000001b9160-c0000000001b9344: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe000106762)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffe000106762-ffffffe000106902: print_dl_rq (STB_GLOBAL)
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
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810f865c-ffffffff810f86ee: print_dl_rq.cold (STB_LOCAL)
ffffffff810f6680-ffffffff810f6743: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810e883b-ffffffff810e88cd: print_dl_rq.cold (STB_LOCAL)
ffffffff810e6850-ffffffff810e6913: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff810f587b-ffffffff810f590d: print_dl_rq.cold (STB_LOCAL)
ffffffff810f3890-ffffffff810f3953: print_dl_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_dl_rq(struct seq_file *m, int cpu, struct dl_rq *dl_rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:591
Inline: False
Direct callers:
  - kernel/sched/deadline.c:print_dl_stats
```
**Symbols:**

```
ffffffff8110086c-ffffffff811008fe: print_dl_rq.cold (STB_LOCAL)
ffffffff810fe880-ffffffff810fe943: print_dl_rq (STB_GLOBAL)
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
