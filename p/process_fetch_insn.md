# Function: <code>process_fetch_insn</code>

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
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b5aa0)
Location: kernel/trace/trace_kprobe.c:907
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bbf80)
Location: kernel/trace/trace_uprobe.c:201
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811b5aa0-ffffffff811b5ef8: process_fetch_insn (STB_LOCAL)
ffffffff811bbf80-ffffffff811bc3b7: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c49e0)
Location: kernel/trace/trace_kprobe.c:942
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd410)
Location: kernel/trace/trace_uprobe.c:226
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811c49e0-ffffffff811c4f41: process_fetch_insn (STB_LOCAL)
ffffffff811cd410-ffffffff811cd9e5: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d0680)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d9a40)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811d0680-ffffffff811d0bec: process_fetch_insn (STB_LOCAL)
ffffffff811d9a40-ffffffff811da046: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ec110)
Location: kernel/trace/trace_kprobe.c:1308
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f64f0)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811ec110-ffffffff811ec842: process_fetch_insn (STB_LOCAL)
ffffffff811f64f0-ffffffff811f6af1: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Transformation ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ea260)
Location: kernel/trace/trace_kprobe.c:1328
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811ea260-ffffffff811ea992: process_fetch_insn (STB_LOCAL)
ffffffff811f4ed0-ffffffff811f5699: process_fetch_insn (STB_LOCAL)
ffffffff81be6503-ffffffff81be651b: process_fetch_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Transformation ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb6d0)
Location: kernel/trace/trace_kprobe.c:1333
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811eb6d0-ffffffff811ebd79: process_fetch_insn (STB_LOCAL)
ffffffff811f5dc0-ffffffff811f6583: process_fetch_insn (STB_LOCAL)
ffffffff81bd81eb-ffffffff81bd8203: process_fetch_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Transformation ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, void *rec, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:364
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:1327
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:216
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81209910-ffffffff81209eee: process_fetch_insn (STB_LOCAL)
ffffffff81cb691c-ffffffff81cb6a48: process_fetch_insn.cold (STB_LOCAL)
ffffffff8121c5d0-ffffffff8121cd12: process_fetch_insn (STB_LOCAL)
ffffffff81cb7304-ffffffff81cb7430: process_fetch_insn.cold (STB_LOCAL)
ffffffff81225f90-ffffffff812267d9: process_fetch_insn (STB_LOCAL)
ffffffff81cb767b-ffffffff81cb77bf: process_fetch_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Transformation ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, void *rec, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:421
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:1323
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:217
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81245780-ffffffff81245dc6: process_fetch_insn (STB_LOCAL)
ffffffff81e67970-ffffffff81e67a9e: process_fetch_insn.cold (STB_LOCAL)
ffffffff8125b3b0-ffffffff8125baff: process_fetch_insn (STB_LOCAL)
ffffffff81e683af-ffffffff81e684dd: process_fetch_insn.cold (STB_LOCAL)
ffffffff81265c30-ffffffff81266410: process_fetch_insn (STB_LOCAL)
ffffffff81e68761-ffffffff81e688c5: process_fetch_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Transformation ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, void *rec, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:427
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:1277
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:218
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff81294b90-ffffffff81295452: process_fetch_insn (STB_LOCAL)
ffffffff8205e37a-ffffffff8205e506: process_fetch_insn.cold (STB_LOCAL)
ffffffff812acc50-ffffffff812ad62d: process_fetch_insn (STB_LOCAL)
ffffffff8205ecc5-ffffffff8205ee51: process_fetch_insn.cold (STB_LOCAL)
ffffffff812b7580-ffffffff812b7ebb: process_fetch_insn (STB_LOCAL)
ffffffff8205f0cf-ffffffff8205f293: process_fetch_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Transformation ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, void *rec, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:389
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:1240
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:219
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
```
In kernel/trace/trace_fprobe.c (0)
Location: kernel/trace/trace_fprobe.c:132
Inline: False
Direct callers:
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
```
**Symbols:**

```
ffffffff812b12c0-ffffffff812b1ab8: process_fetch_insn (STB_LOCAL)
ffffffff820dcc65-ffffffff820dcdf1: process_fetch_insn.cold (STB_LOCAL)
ffffffff812ceae0-ffffffff812cf32b: process_fetch_insn (STB_LOCAL)
ffffffff820dd857-ffffffff820dd9e3: process_fetch_insn.cold (STB_LOCAL)
ffffffff812dabe0-ffffffff812db4ed: process_fetch_insn (STB_LOCAL)
ffffffff820ddc85-ffffffff820dde39: process_fetch_insn.cold (STB_LOCAL)
ffffffff812e0e70-ffffffff812e1691: process_fetch_insn (STB_LOCAL)
ffffffff820ddf87-ffffffff820de113: process_fetch_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, void *rec, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_eprobe.c (0)
Location: kernel/trace/trace_eprobe.c:393
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:__eprobe_trace_func
```
```
In kernel/trace/trace_kprobe.c (0)
Location: kernel/trace/trace_kprobe.c:1306
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (0)
Location: kernel/trace/trace_uprobe.c:214
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
```
In kernel/trace/trace_fprobe.c (0)
Location: kernel/trace/trace_fprobe.c:132
Inline: False
Direct callers:
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fexit_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
  - kernel/trace/trace_fprobe.c:fentry_perf_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fexit_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
  - kernel/trace/trace_fprobe.c:fentry_trace_func
```
**Symbols:**

```
ffffffff812cd870-ffffffff812ce068: process_fetch_insn (STB_LOCAL)
ffffffff821b8a69-ffffffff821b8bf5: process_fetch_insn.cold (STB_LOCAL)
ffffffff812ec4e0-ffffffff812ecd2b: process_fetch_insn (STB_LOCAL)
ffffffff821b9683-ffffffff821b980f: process_fetch_insn.cold (STB_LOCAL)
ffffffff812f8e30-ffffffff812f95b5: process_fetch_insn (STB_LOCAL)
ffffffff821b9aa3-ffffffff821b9c57: process_fetch_insn.cold (STB_LOCAL)
ffffffff812feec0-ffffffff812ff6e1: process_fetch_insn (STB_LOCAL)
ffffffff821b9e05-ffffffff821b9f91: process_fetch_insn.cold (STB_LOCAL)
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
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff80001024eef8)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffff800010259f60)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffff80001024eef8-ffff80001024f478: process_fetch_insn (STB_LOCAL)
ffff800010259f60-ffff80001025a54c: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0481e44)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (c048d0f4)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
c0481e44-c048238c: process_fetch_insn (STB_LOCAL)
c048d0f4-c048d7d4: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002eb5e0)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (c0000000002fd890)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
c0000000002eb5e0-c0000000002ebc80: process_fetch_insn (STB_LOCAL)
c0000000002fd890-c0000000002fe104: process_fetch_insn (STB_LOCAL)
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
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c8ca0)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d2060)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811c8ca0-ffffffff811c920c: process_fetch_insn (STB_LOCAL)
ffffffff811d2060-ffffffff811d2666: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811bba80)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c4e30)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811bba80-ffffffff811bbfec: process_fetch_insn (STB_LOCAL)
ffffffff811c4e30-ffffffff811c5436: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c6a70)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cfe30)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811c6a70-ffffffff811c6fdc: process_fetch_insn (STB_LOCAL)
ffffffff811cfe30-ffffffff811d0436: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int process_fetch_insn(struct fetch_insn *code, struct pt_regs *regs, void *dest, void *base);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d4cd0)
Location: kernel/trace/trace_kprobe.c:1126
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kprobe_perf_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kretprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
  - kernel/trace/trace_kprobe.c:kprobe_trace_func
```
```
In kernel/trace/trace_uprobe.c (ffffffff811de0d0)
Location: kernel/trace/trace_uprobe.c:220
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uretprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
  - kernel/trace/trace_uprobe.c:uprobe_dispatcher
```
**Symbols:**

```
ffffffff811d4cd0-ffffffff811d523c: process_fetch_insn (STB_LOCAL)
ffffffff811de0d0-ffffffff811de6d6: process_fetch_insn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *rec</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pt_regs *regs</code>
</li>
</ul>
</details>
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
