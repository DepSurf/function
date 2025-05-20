# Function: <code>print_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810c65e0)
Location: kernel/sched/debug.c:267
Inline: False
Direct callers:
  - kernel/sched/debug.c:sched_debug_show
  - kernel/sched/debug.c:sysrq_sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff810f8fb0)
Location: kernel/time/timer_list.c:143
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810c65e0-ffffffff810c7382: print_cpu (STB_LOCAL)
ffffffff810f8fb0-ffffffff810f932d: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810ca530)
Location: kernel/sched/debug.c:577
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81100230)
Location: kernel/time/timer_list.c:143
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
```
**Symbols:**

```
ffffffff810ca530-ffffffff810cb310: print_cpu (STB_LOCAL)
ffffffff81100230-ffffffff811005ad: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d0560)
Location: kernel/sched/debug.c:583
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81102fd0)
Location: kernel/time/timer_list.c:143
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
```
**Symbols:**

```
ffffffff810d0560-ffffffff810d1334: print_cpu (STB_LOCAL)
ffffffff81102fd0-ffffffff8110334d: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810cf5d0)
Location: kernel/sched/debug.c:597
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81104fb0)
Location: kernel/time/timer_list.c:137
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
```
**Symbols:**

```
ffffffff810cf5d0-ffffffff810d02d7: print_cpu (STB_LOCAL)
ffffffff81104fb0-ffffffff81105469: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffff810d6f20)
Location: kernel/sched/debug.c:647
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81110110)
Location: kernel/time/timer_list.c:137
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
```
**Symbols:**

```
ffffffff810d6f20-ffffffff810d7c82: print_cpu (STB_LOCAL)
ffffffff81110110-ffffffff811105c9: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:628
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff8111bb20)
Location: kernel/time/timer_list.c:135
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
```
**Symbols:**

```
ffffffff810de9f0-ffffffff810df266: print_cpu (STB_LOCAL)
ffffffff810e1821-ffffffff810e1dd7: print_cpu.cold.11 (STB_LOCAL)
ffffffff8111bb20-ffffffff8111bfe5: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:627
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff811272d0)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
  - kernel/time/timer_list.c:timer_list_show
```
**Symbols:**

```
ffffffff810e9170-ffffffff810e99e6: print_cpu (STB_LOCAL)
ffffffff810ebf71-ffffffff810ec527: print_cpu.cold.12 (STB_LOCAL)
ffffffff811272d0-ffffffff81127795: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81131d10)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810f02a0-ffffffff810f0790: print_cpu (STB_LOCAL)
ffffffff810f2fb0-ffffffff810f323f: print_cpu.cold (STB_LOCAL)
ffffffff81131d10-ffffffff811321cb: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff8113dc60)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810fc0e0-ffffffff810fc5d0: print_cpu (STB_LOCAL)
ffffffff810fec56-ffffffff810feee5: print_cpu.cold (STB_LOCAL)
ffffffff8113dc60-ffffffff8113e11b: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:612
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff8114d010)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff81106840-ffffffff81106d1e: print_cpu (STB_LOCAL)
ffffffff811093a1-ffffffff8110961d: print_cpu.cold (STB_LOCAL)
ffffffff8114d010-ffffffff8114d2eb: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:666
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81149170)
Location: kernel/time/timer_list.c:115
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff81104e90-ffffffff81105373: print_cpu (STB_LOCAL)
ffffffff81bdd785-ffffffff81bdda01: print_cpu.cold (STB_LOCAL)
ffffffff81149170-ffffffff811494c1: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:691
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff8114a520)
Location: kernel/time/timer_list.c:115
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff811072d0-ffffffff8110777f: print_cpu (STB_LOCAL)
ffffffff81bcf8fa-ffffffff81bcfb66: print_cpu.cold (STB_LOCAL)
ffffffff8114a520-ffffffff8114a99e: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:707
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff8116e220)
Location: kernel/time/timer_list.c:115
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff81125370-ffffffff81125840: print_cpu (STB_LOCAL)
ffffffff81ca8129-ffffffff81ca8395: print_cpu.cold (STB_LOCAL)
ffffffff8116e220-ffffffff8116e6c0: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/build_utility.c (0)
Location: kernel/sched/debug.c:715
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff811a24e0)
Location: kernel/time/timer_list.c:115
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff81140850-ffffffff81140d28: print_cpu (STB_LOCAL)
ffffffff81e575fb-ffffffff81e5788b: print_cpu.cold (STB_LOCAL)
ffffffff811a24e0-ffffffff811a296b: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116b390)
Location: kernel/sched/debug.c:716
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff811e1a30)
Location: kernel/time/timer_list.c:115
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff8116b390-ffffffff8116bba0: print_cpu (STB_LOCAL)
ffffffff811e1a30-ffffffff811e1ebb: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117ba70)
Location: kernel/sched/debug.c:762
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff811f5f90)
Location: kernel/time/timer_list.c:115
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff8117ba70-ffffffff8117c280: print_cpu (STB_LOCAL)
ffffffff811f5f90-ffffffff811f6420: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81189750)
Location: kernel/sched/debug.c:763
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:sysrq_sched_debug_show
  - kernel/sched/build_utility.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff8120c130)
Location: kernel/time/timer_list.c:115
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff81189750-ffffffff81189f60: print_cpu (STB_LOCAL)
ffffffff8120c130-ffffffff8120c5c0: print_cpu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffff800010161358)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffff8000101a7d10)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffff800010161358-ffff8000101619e4: print_cpu (STB_LOCAL)
ffff8000101a7d10-ffff8000101a80c4: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c03adb28)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (c03f2b50)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
c03adb28-c03ae1cc: print_cpu (STB_LOCAL)
c03f2b50-c03f3154: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (c0000000001b6fd0)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (c00000000020a560)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
c0000000001b6fd0-c0000000001b788c: print_cpu (STB_LOCAL)
c00000000020a560-c00000000020aaf8: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/debug.c (ffffffe00010515e)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffe000133722)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffe00010515e-ffffffe000105802: print_cpu (STB_LOCAL)
ffffffe000133722-ffffffe000133c18: print_cpu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81136410)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810f5410-ffffffff810f5900: print_cpu (STB_LOCAL)
ffffffff810f7f76-ffffffff810f8205: print_cpu.cold (STB_LOCAL)
ffffffff81136410-ffffffff811368cb: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81128e60)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810e55d0-ffffffff810e5ac0: print_cpu (STB_LOCAL)
ffffffff810e8146-ffffffff810e83d5: print_cpu.cold (STB_LOCAL)
ffffffff81128e60-ffffffff8112931b: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81134130)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810f2610-ffffffff810f2b00: print_cpu (STB_LOCAL)
ffffffff810f5186-ffffffff810f5415: print_cpu.cold (STB_LOCAL)
ffffffff81134130-ffffffff811345eb: print_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Transformation ⚠️</summary>

```c
void print_cpu(struct seq_file *m, int cpu);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/sched/debug.c (0)
Location: kernel/sched/debug.c:614
Inline: False
Direct callers:
  - kernel/sched/debug.c:sysrq_sched_debug_show
  - kernel/sched/debug.c:sched_debug_show
```
```
In kernel/time/timer_list.c (ffffffff81140b50)
Location: kernel/time/timer_list.c:130
Inline: False
Direct callers:
  - kernel/time/timer_list.c:timer_list_show
  - kernel/time/timer_list.c:sysrq_timer_list_show
```
**Symbols:**

```
ffffffff810fd600-ffffffff810fdafa: print_cpu (STB_LOCAL)
ffffffff81100186-ffffffff81100415: print_cpu.cold (STB_LOCAL)
ffffffff81140b50-ffffffff8114100b: print_cpu (STB_LOCAL)
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
