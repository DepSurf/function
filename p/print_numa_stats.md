# Function: <code>print_numa_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c7f90)
Location: kernel/sched/debug.c:512
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810c7f90-ffffffff810c802b: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cc580)
Location: kernel/sched/debug.c:823
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810cc580-ffffffff810cc61b: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d25a0)
Location: kernel/sched/debug.c:826
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810d25a0-ffffffff810d263b: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d16f0)
Location: kernel/sched/debug.c:840
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810d16f0-ffffffff810d178b: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d9230)
Location: kernel/sched/debug.c:890
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810d9230-ffffffff810d92cb: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:842
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810e22d8-ffffffff810e230d: print_numa_stats.cold.16 (STB_LOCAL)
ffffffff810e0240-ffffffff810e02ad: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:841
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810eca28-ffffffff810eca5d: print_numa_stats.cold.17 (STB_LOCAL)
ffffffff810ea9c0-ffffffff810eaa2d: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810f3755-ffffffff810f378a: print_numa_stats.cold (STB_LOCAL)
ffffffff810f17c0-ffffffff810f182d: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810ff3dd-ffffffff810ff412: print_numa_stats.cold (STB_LOCAL)
ffffffff810fd480-ffffffff810fd4ed: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:827
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff81109aef-ffffffff81109b24: print_numa_stats.cold (STB_LOCAL)
ffffffff81107c20-ffffffff81107c8d: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:881
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff81bdded3-ffffffff81bddf08: print_numa_stats.cold (STB_LOCAL)
ffffffff81106430-ffffffff8110649d: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:895
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff81bd0072-ffffffff81bd00a7: print_numa_stats.cold (STB_LOCAL)
ffffffff81108470-ffffffff811084dd: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:911
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff81ca88df-ffffffff81ca8914: print_numa_stats.cold (STB_LOCAL)
ffffffff811265e0-ffffffff8112664d: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:920
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff81e58857-ffffffff81e5888c: print_numa_stats.cold (STB_LOCAL)
ffffffff81146d00-ffffffff81146d81: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811746f0)
Location: kernel/sched/debug.c:921
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff811746f0-ffffffff811747bc: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81185300)
Location: kernel/sched/debug.c:967
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff81185300-ffffffff811853cc: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81193a60)
Location: kernel/sched/debug.c:964
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff81193a60-ffffffff81193b2c: print_numa_stats (STB_GLOBAL)
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
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010162cc8)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffff800010162cc8-ffff800010162d94: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b93f0)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
c0000000001b93f0-c0000000001b94f0: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810f86ee-ffffffff810f8723: print_numa_stats.cold (STB_LOCAL)
ffffffff810f67a0-ffffffff810f680d: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810e88cd-ffffffff810e8902: print_numa_stats.cold (STB_LOCAL)
ffffffff810e6970-ffffffff810e69dd: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff810f590d-ffffffff810f5942: print_numa_stats.cold (STB_LOCAL)
ffffffff810f39b0-ffffffff810f3a1d: print_numa_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_numa_stats(struct seq_file *m, int node, long unsigned int tsf, long unsigned int tpf, long unsigned int gsf, long unsigned int gpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:821
Inline: False
Direct callers:
  - kernel/sched/fair.c:show_numa_stats
```
**Symbols:**

```
ffffffff811008fe-ffffffff81100933: print_numa_stats.cold (STB_LOCAL)
ffffffff810fe9a0-ffffffff810fea0d: print_numa_stats (STB_GLOBAL)
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
