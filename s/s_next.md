# Function: <code>s_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff81046d10)
Location: arch/x86/kernel/cpu/mcheck/mce-severity.c:291
Inline: False
```
```
In kernel/kallsyms.c (ffffffff8110b1c0)
Location: kernel/kallsyms.c:508
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8114ff70)
Location: kernel/trace/trace.c:2390
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff8115d6d0)
Location: kernel/trace/trace_events.c:900
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff811cc810)
Location: mm/vmalloc.c:2574
Inline: False
```
**Symbols:**

```
ffffffff81046d10-ffffffff81046d39: s_next (STB_LOCAL)
ffffffff8110b1c0-ffffffff8110b1f1: s_next (STB_LOCAL)
ffffffff8114ff70-ffffffff81150026: s_next (STB_LOCAL)
ffffffff8115d6d0-ffffffff8115d704: s_next (STB_LOCAL)
ffffffff811cc810-ffffffff811cc837: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff81046be0)
Location: arch/x86/kernel/cpu/mcheck/mce-severity.c:339
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81112a10)
Location: kernel/kallsyms.c:532
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81158f50)
Location: kernel/trace/trace.c:2727
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff81168625)
Location: kernel/trace/trace_events.c:935
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff811e9880)
Location: mm/vmalloc.c:2595
Inline: False
```
**Symbols:**

```
ffffffff81046be0-ffffffff81046c0f: s_next (STB_LOCAL)
ffffffff81112a10-ffffffff81112a41: s_next (STB_LOCAL)
ffffffff81158f50-ffffffff81159006: s_next (STB_LOCAL)
ffffffff81168020-ffffffff8116805b: s_next (STB_LOCAL)
ffffffff811e9880-ffffffff811e98a7: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff81048780)
Location: arch/x86/kernel/cpu/mcheck/mce-severity.c:339
Inline: False
```
```
In kernel/kallsyms.c (ffffffff8111a130)
Location: kernel/kallsyms.c:532
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81163780)
Location: kernel/trace/trace.c:2951
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811739d2)
Location: kernel/trace/trace_events.c:904
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff811fafd0)
Location: mm/vmalloc.c:2596
Inline: False
```
**Symbols:**

```
ffffffff81048780-ffffffff810487af: s_next (STB_LOCAL)
ffffffff8111a130-ffffffff8111a15e: s_next (STB_LOCAL)
ffffffff81163780-ffffffff81163833: s_next (STB_LOCAL)
ffffffff81173470-ffffffff811734a8: s_next (STB_LOCAL)
ffffffff811fafd0-ffffffff811fafea: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff81048120)
Location: arch/x86/kernel/cpu/mcheck/mce-severity.c:339
Inline: False
```
```
In kernel/kallsyms.c (ffffffff8111bc40)
Location: kernel/kallsyms.c:563
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81166b90)
Location: kernel/trace/trace.c:3163
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff81176661)
Location: kernel/trace/trace_events.c:944
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff81205cf0)
Location: mm/vmalloc.c:2666
Inline: False
```
**Symbols:**

```
ffffffff81048120-ffffffff81048149: s_next (STB_LOCAL)
ffffffff8111bc40-ffffffff8111bc6e: s_next (STB_LOCAL)
ffffffff81166b90-ffffffff81166c00: s_next (STB_LOCAL)
ffffffff81176210-ffffffff81176241: s_next (STB_LOCAL)
ffffffff81205cf0-ffffffff81205d0a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff8104bb80)
Location: arch/x86/kernel/cpu/mcheck/mce-severity.c:338
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81127260)
Location: kernel/kallsyms.c:595
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81173b20)
Location: kernel/trace/trace.c:3172
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff81183e21)
Location: kernel/trace/trace_events.c:944
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff8121ea10)
Location: mm/vmalloc.c:2658
Inline: False
```
**Symbols:**

```
ffffffff8104bb80-ffffffff8104bba9: s_next (STB_LOCAL)
ffffffff81127260-ffffffff8112728e: s_next (STB_LOCAL)
ffffffff81173b20-ffffffff81173b90: s_next (STB_LOCAL)
ffffffff811839a0-ffffffff811839d1: s_next (STB_LOCAL)
ffffffff8121ea10-ffffffff8121ea2a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-severity.c (ffffffff8104e870)
Location: arch/x86/kernel/cpu/mcheck/mce-severity.c:351
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81135130)
Location: kernel/kallsyms.c:549
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81182b10)
Location: kernel/trace/trace.c:3178
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff81192f61)
Location: kernel/trace/trace_events.c:942
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff812406e0)
Location: mm/vmalloc.c:2645
Inline: False
```
**Symbols:**

```
ffffffff8104e870-ffffffff8104e899: s_next (STB_LOCAL)
ffffffff81135130-ffffffff81135161: s_next (STB_LOCAL)
ffffffff81182b10-ffffffff81182b85: s_next (STB_LOCAL)
ffffffff81192b10-ffffffff81192b41: s_next (STB_LOCAL)
ffffffff812406e0-ffffffff812406fa: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104bf40)
Location: arch/x86/kernel/cpu/mce/severity.c:352
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81140d70)
Location: kernel/kallsyms.c:572
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81190470)
Location: kernel/trace/trace.c:3180
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811a10d1)
Location: kernel/trace/trace_events.c:943
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff81254fd0)
Location: mm/vmalloc.c:2647
Inline: False
```
**Symbols:**

```
ffffffff8104bf40-ffffffff8104bf69: s_next (STB_LOCAL)
ffffffff81140d70-ffffffff81140da1: s_next (STB_LOCAL)
ffffffff81190470-ffffffff811904e5: s_next (STB_LOCAL)
ffffffff811a0c80-ffffffff811a0cb1: s_next (STB_LOCAL)
ffffffff81254fd0-ffffffff81254fea: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104ee40)
Location: arch/x86/kernel/cpu/mce/severity.c:353
Inline: False
```
```
In kernel/kallsyms.c (ffffffff8114c170)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8119dd70)
Location: kernel/trace/trace.c:3355
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811af051)
Location: kernel/trace/trace_events.c:936
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff81267130)
Location: mm/vmalloc.c:3420
Inline: False
```
**Symbols:**

```
ffffffff8104ee40-ffffffff8104ee6f: s_next (STB_LOCAL)
ffffffff8114c170-ffffffff8114c1a3: s_next (STB_LOCAL)
ffffffff8119dd70-ffffffff8119dde6: s_next (STB_LOCAL)
ffffffff811aeb10-ffffffff811aeb3e: s_next (STB_LOCAL)
ffffffff81267130-ffffffff8126714a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104f7c0)
Location: arch/x86/kernel/cpu/mce/severity.c:353
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81157e40)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811a9740)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811baab1)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff81275d20)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
ffffffff8104f7c0-ffffffff8104f7ef: s_next (STB_LOCAL)
ffffffff81157e40-ffffffff81157e73: s_next (STB_LOCAL)
ffffffff811a9740-ffffffff811a97b6: s_next (STB_LOCAL)
ffffffff811ba240-ffffffff811ba26e: s_next (STB_LOCAL)
ffffffff81275d20-ffffffff81275d3a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81053cb0)
Location: arch/x86/kernel/cpu/mce/severity.c:357
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81168a60)
Location: kernel/kallsyms.c:574
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811c1c70)
Location: kernel/trace/trace.c:3546
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811d33d1)
Location: kernel/trace/trace_events.c:1011
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff812a7070)
Location: mm/vmalloc.c:3478
Inline: False
```
**Symbols:**

```
ffffffff81053cb0-ffffffff81053ce2: s_next (STB_LOCAL)
ffffffff81168a60-ffffffff81168a95: s_next (STB_LOCAL)
ffffffff811c1c70-ffffffff811c1ce6: s_next (STB_LOCAL)
ffffffff811d30d0-ffffffff811d30fe: s_next (STB_LOCAL)
ffffffff812a7070-ffffffff812a708a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81052a20)
Location: arch/x86/kernel/cpu/mce/severity.c:433
Inline: False
```
```
In kernel/kallsyms.c (ffffffff811650e0)
Location: kernel/kallsyms.c:608
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811bf880)
Location: kernel/trace/trace.c:3614
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811d0521)
Location: kernel/trace/trace_events.c:1012
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff812b22e0)
Location: mm/vmalloc.c:3466
Inline: False
```
**Symbols:**

```
ffffffff81052a20-ffffffff81052a4b: s_next (STB_LOCAL)
ffffffff811650e0-ffffffff81165115: s_next (STB_LOCAL)
ffffffff811bf880-ffffffff811bf8f6: s_next (STB_LOCAL)
ffffffff811d0220-ffffffff811d024e: s_next (STB_LOCAL)
ffffffff812b22e0-ffffffff812b22fa: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81054340)
Location: arch/x86/kernel/cpu/mce/severity.c:429
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81165eb0)
Location: kernel/kallsyms.c:659
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811c0560)
Location: kernel/trace/trace.c:3947
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811d16d1)
Location: kernel/trace/trace_events.c:1219
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff812b79d0)
Location: mm/vmalloc.c:3733
Inline: False
```
**Symbols:**

```
ffffffff81054340-ffffffff8105436b: s_next (STB_LOCAL)
ffffffff81165eb0-ffffffff81165ee5: s_next (STB_LOCAL)
ffffffff811c0560-ffffffff811c05d6: s_next (STB_LOCAL)
ffffffff811d14d0-ffffffff811d14fe: s_next (STB_LOCAL)
ffffffff812b79d0-ffffffff812b79ea: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8105cc40)
Location: arch/x86/kernel/cpu/mce/severity.c:429
Inline: False
```
```
In kernel/kallsyms.c (ffffffff8118b670)
Location: kernel/kallsyms.c:723
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811eaf70)
Location: kernel/trace/trace.c:4019
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811fe431)
Location: kernel/trace/trace_events.c:1220
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff812fa100)
Location: mm/vmalloc.c:3844
Inline: False
```
**Symbols:**

```
ffffffff8105cc40-ffffffff8105cc8b: s_next (STB_LOCAL)
ffffffff8118b670-ffffffff8118b6a5: s_next (STB_LOCAL)
ffffffff811eaf70-ffffffff811eafe6: s_next (STB_LOCAL)
ffffffff811fe1a0-ffffffff811fe1ce: s_next (STB_LOCAL)
ffffffff812fa100-ffffffff812fa11a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81069400)
Location: arch/x86/kernel/cpu/mce/severity.c:418
Inline: False
```
```
In kernel/kallsyms.c (ffffffff811ba9c0)
Location: kernel/kallsyms.c:747
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81222fc0)
Location: kernel/trace/trace.c:4022
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff81238e01)
Location: kernel/trace/trace_events.c:1240
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff81360480)
Location: mm/vmalloc.c:4013
Inline: False
```
**Symbols:**

```
ffffffff81069400-ffffffff8106945f: s_next (STB_LOCAL)
ffffffff811ba9c0-ffffffff811ba9fb: s_next (STB_LOCAL)
ffffffff81222fc0-ffffffff81223046: s_next (STB_LOCAL)
ffffffff81238b90-ffffffff81238bd2: s_next (STB_LOCAL)
ffffffff81360480-ffffffff813604a4: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81079050)
Location: arch/x86/kernel/cpu/mce/severity.c:420
Inline: False
```
```
In kernel/kallsyms.c (ffffffff811fc660)
Location: kernel/kallsyms.c:820
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8126e060)
Location: kernel/trace/trace.c:4046
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff81285d61)
Location: kernel/trace/trace_events.c:1255
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff813dc030)
Location: mm/vmalloc.c:4072
Inline: False
```
**Symbols:**

```
ffffffff81079050-ffffffff810790af: s_next (STB_LOCAL)
ffffffff811fc660-ffffffff811fc69b: s_next (STB_LOCAL)
ffffffff8126e060-ffffffff8126e0e6: s_next (STB_LOCAL)
ffffffff81285aa0-ffffffff81285ae2: s_next (STB_LOCAL)
ffffffff813dc030-ffffffff813dc054: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8107b300)
Location: arch/x86/kernel/cpu/mce/severity.c:420
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81210c70)
Location: kernel/kallsyms.c:761
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81285280)
Location: kernel/trace/trace.c:4140
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff812a2a21)
Location: kernel/trace/trace_events.c:1251
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff81410920)
Location: mm/vmalloc.c:4323
Inline: False
```
**Symbols:**

```
ffffffff8107b300-ffffffff8107b35f: s_next (STB_LOCAL)
ffffffff81210c70-ffffffff81210cab: s_next (STB_LOCAL)
ffffffff81285280-ffffffff81285306: s_next (STB_LOCAL)
ffffffff812a2760-ffffffff812a27a2: s_next (STB_LOCAL)
ffffffff81410920-ffffffff81410944: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff810827c0)
Location: arch/x86/kernel/cpu/mce/severity.c:420
Inline: False
```
```
In kernel/kallsyms.c (ffffffff812282f0)
Location: kernel/kallsyms.c:759
Inline: False
```
```
In kernel/trace/trace.c (ffffffff812a0380)
Location: kernel/trace/trace.c:4108
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff812be3f1)
Location: kernel/trace/trace_events.c:1260
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff8143d280)
Location: mm/vmalloc.c:4323
Inline: False
```
**Symbols:**

```
ffffffff810827c0-ffffffff8108281f: s_next (STB_LOCAL)
ffffffff812282f0-ffffffff8122832b: s_next (STB_LOCAL)
ffffffff812a0380-ffffffff812a0406: s_next (STB_LOCAL)
ffffffff812bdf60-ffffffff812bdfa2: s_next (STB_LOCAL)
ffffffff8143d280-ffffffff8143d2a4: s_next (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *m, void *p, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffff8000101c7378)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffff8000102263b8)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffff800010239100)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffff80001030c190)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
ffff8000101c7378-ffff8000101c73c8: s_next (STB_LOCAL)
ffff8000102263b8-ffff800010226470: s_next (STB_LOCAL)
ffff800010238b08-ffff800010238b50: s_next (STB_LOCAL)
ffff80001030c190-ffff80001030c1d0: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *m, void *p, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c040e2c4)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (c0463a64)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (c0474d08)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (c05281a4)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
c040e2c4-c040e310: s_next (STB_LOCAL)
c0463a64-c0463b54: s_next (STB_LOCAL)
c04746b4-c0474710: s_next (STB_LOCAL)
c05281a4-c05281cc: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *m, void *p, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (c00000000022f600)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (c0000000002ac120)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (c0000000002c6518)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (c0000000003dc200)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
c00000000022f600-c00000000022f658: s_next (STB_LOCAL)
c0000000002ac120-c0000000002ac228: s_next (STB_LOCAL)
c0000000002c5070-c0000000002c50b0: s_next (STB_LOCAL)
c0000000003dc200-c0000000003dc240: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *m, void *p, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kallsyms.c (ffffffe00014764a)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffffffe000181198)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffe0001900d2)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffe0002154e2)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
ffffffe00014764a-ffffffe000147696: s_next (STB_LOCAL)
ffffffe000181198-ffffffe000181226: s_next (STB_LOCAL)
ffffffe00018f8bc-ffffffe00018f8f4: s_next (STB_LOCAL)
ffffffe0002154e2-ffffffe00021551c: s_next (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104f8c0)
Location: arch/x86/kernel/cpu/mce/severity.c:353
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81150460)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811a1d60)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811b30d1)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff8126e370)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
ffffffff8104f8c0-ffffffff8104f8ef: s_next (STB_LOCAL)
ffffffff81150460-ffffffff81150493: s_next (STB_LOCAL)
ffffffff811a1d60-ffffffff811a1dd6: s_next (STB_LOCAL)
ffffffff811b2860-ffffffff811b288e: s_next (STB_LOCAL)
ffffffff8126e370-ffffffff8126e38a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8103ee40)
Location: arch/x86/kernel/cpu/mce/severity.c:353
Inline: False
```
```
In kernel/kallsyms.c (ffffffff81143710)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffffffff81194d30)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811a5ed1)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff81260320)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
ffffffff8103ee40-ffffffff8103ee6f: s_next (STB_LOCAL)
ffffffff81143710-ffffffff81143743: s_next (STB_LOCAL)
ffffffff81194d30-ffffffff81194da6: s_next (STB_LOCAL)
ffffffff811a5670-ffffffff811a569e: s_next (STB_LOCAL)
ffffffff81260320-ffffffff8126033a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff8104f770)
Location: arch/x86/kernel/cpu/mce/severity.c:353
Inline: False
```
```
In kernel/kallsyms.c (ffffffff8114e310)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffffffff8119fb30)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811b0ea1)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff8126c110)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
ffffffff8104f770-ffffffff8104f79f: s_next (STB_LOCAL)
ffffffff8114e310-ffffffff8114e343: s_next (STB_LOCAL)
ffffffff8119fb30-ffffffff8119fba6: s_next (STB_LOCAL)
ffffffff811b0630-ffffffff811b065e: s_next (STB_LOCAL)
ffffffff8126c110-ffffffff8126c12a: s_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void *s_next(struct seq_file *f, void *data, loff_t *pos);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/severity.c (ffffffff81050bb0)
Location: arch/x86/kernel/cpu/mce/severity.c:353
Inline: False
```
```
In kernel/kallsyms.c (ffffffff8115b0f0)
Location: kernel/kallsyms.c:575
Inline: False
```
```
In kernel/trace/trace.c (ffffffff811ad8c0)
Location: kernel/trace/trace.c:3381
Inline: False
Direct callers:
  - kernel/trace/trace.c:s_start
  - kernel/trace/trace.c:s_start
```
```
In kernel/trace/trace_events.c (ffffffff811bef31)
Location: kernel/trace/trace_events.c:937
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:s_start
```
```
In mm/vmalloc.c (ffffffff8127bc50)
Location: mm/vmalloc.c:3431
Inline: False
```
**Symbols:**

```
ffffffff81050bb0-ffffffff81050bdf: s_next (STB_LOCAL)
ffffffff8115b0f0-ffffffff8115b123: s_next (STB_LOCAL)
ffffffff811ad8c0-ffffffff811ad936: s_next (STB_LOCAL)
ffffffff811be6c0-ffffffff811be6ee: s_next (STB_LOCAL)
ffffffff8127bc50-ffffffff8127bc6a: s_next (STB_LOCAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file *m</code>
</li>
<li>
<b>Param added. </b>
<code>void *p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file *f</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file *m</code>
</li>
<li>
<b>Param added. </b>
<code>void *p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file *f</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file *m</code>
</li>
<li>
<b>Param added. </b>
<code>void *p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file *f</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct seq_file *m</code>
</li>
<li>
<b>Param added. </b>
<code>void *p</code>
</li>
<li>
<b>Param removed. </b>
<code>struct seq_file *f</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
</ul>
</details>
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
