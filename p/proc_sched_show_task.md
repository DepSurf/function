# Function: <code>proc_sched_show_task</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c8030)
Location: kernel/sched/debug.c:547
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810c8030-ffffffff810c9629: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cc620)
Location: kernel/sched/debug.c:858
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810cc620-ffffffff810cdca5: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d2640)
Location: kernel/sched/debug.c:861
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810d2640-ffffffff810d3cbd: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d1790)
Location: kernel/sched/debug.c:875
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810d1790-ffffffff810d2e53: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d92d0)
Location: kernel/sched/debug.c:925
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810d92d0-ffffffff810daa4c: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:877
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810e230d-ffffffff810e2c0c: proc_sched_show_task.cold.17 (STB_LOCAL)
ffffffff810e02b0-ffffffff810e11b1: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:876
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810eca5d-ffffffff810ed33f: proc_sched_show_task.cold.18 (STB_LOCAL)
ffffffff810eaa30-ffffffff810eb90d: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810f378a-ffffffff810f40dd: proc_sched_show_task.cold (STB_LOCAL)
ffffffff810f1830-ffffffff810f2724: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810ff412-ffffffff810ffd65: proc_sched_show_task.cold (STB_LOCAL)
ffffffff810fd4f0-ffffffff810fe3e4: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:862
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff81109b24-ffffffff8110a3fe: proc_sched_show_task.cold (STB_LOCAL)
ffffffff81107c90-ffffffff81108abb: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:916
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff81bddf08-ffffffff81bde7e2: proc_sched_show_task.cold (STB_LOCAL)
ffffffff811064a0-ffffffff811072cb: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:930
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff81bd00a7-ffffffff81bd098a: proc_sched_show_task.cold (STB_LOCAL)
ffffffff811084e0-ffffffff81109311: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:946
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff81ca8914-ffffffff81ca91f7: proc_sched_show_task.cold (STB_LOCAL)
ffffffff81126650-ffffffff81127481: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:945
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff81e5888c-ffffffff81e59288: proc_sched_show_task.cold (STB_LOCAL)
ffffffff81146d90-ffffffff81147cfa: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811747d0)
Location: kernel/sched/debug.c:946
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff811747d0-ffffffff81176430: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811853e0)
Location: kernel/sched/debug.c:992
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff811853e0-ffffffff81187059: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81193b40)
Location: kernel/sched/debug.c:989
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff81193b40-ffffffff81195784: proc_sched_show_task (STB_GLOBAL)
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
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010162d98)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffff800010162d98-ffff800010164150: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03af3b0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
c03af3b0-c03b07b8: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b94f0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
c0000000001b94f0-c0000000001bafb0: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe00010696c)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffe00010696c-ffffffe000107af6: proc_sched_show_task (STB_GLOBAL)
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
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810f8723-ffffffff810f9076: proc_sched_show_task.cold (STB_LOCAL)
ffffffff810f6810-ffffffff810f7704: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810e8902-ffffffff810e9255: proc_sched_show_task.cold (STB_LOCAL)
ffffffff810e69e0-ffffffff810e78d4: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff810f5942-ffffffff810f6295: proc_sched_show_task.cold (STB_LOCAL)
ffffffff810f3a20-ffffffff810f4914: proc_sched_show_task (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void proc_sched_show_task(struct task_struct *p, struct pid_namespace *ns, struct seq_file *m);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:856
Inline: False
Direct callers:
  - fs/proc/base.c:sched_show
```
**Symbols:**

```
ffffffff81100933-ffffffff811012b9: proc_sched_show_task.cold (STB_LOCAL)
ffffffff810fea10-ffffffff810ff91b: proc_sched_show_task (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct pid_namespace *ns</code>
</li>
<li>
<b>Param reordered. </b>
<code>p, m</code> ➡️ <code>p, ns, m</code>
</li>
</ul>
</details>
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
