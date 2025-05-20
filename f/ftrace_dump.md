# Function: <code>ftrace_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81153190)
Location: kernel/trace/trace.c:7086
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81153190-ffffffff8115340e: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115c3b0)
Location: kernel/trace/trace.c:7494
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff8115c3b0-ffffffff8115c643: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81166be0)
Location: kernel/trace/trace.c:7780
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81166be0-ffffffff81166e82: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116a0b0)
Location: kernel/trace/trace.c:8152
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff8116a0b0-ffffffff8116a34b: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81177050)
Location: kernel/trace/trace.c:8163
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81177050-ffffffff811772c3: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:8266
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811865dc-ffffffff81186708: ftrace_dump.cold.84 (STB_LOCAL)
ffffffff81186190-ffffffff811862e0: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193b15)
Location: kernel/trace/trace.c:8340
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81193f6c-ffffffff81194076: ftrace_dump.cold.84 (STB_LOCAL)
ffffffff81193af0-ffffffff81193c63: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1770)
Location: kernel/trace/trace.c:8849
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811a1630-ffffffff811a1765: ftrace_dump.part.0 (STB_LOCAL)
ffffffff811a1c2a-ffffffff811a1d5c: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811a1770-ffffffff811a1794: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad220)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811ad0e0-ffffffff811ad215: ftrace_dump.part.0 (STB_LOCAL)
ffffffff811ad615-ffffffff811ad747: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811ad220-ffffffff811ad244: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c4f30)
Location: kernel/trace/trace.c:9188
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811c4de0-ffffffff811c4f2a: ftrace_dump.part.0 (STB_LOCAL)
ffffffff811c565f-ffffffff811c5775: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811c4f30-ffffffff811c4f54: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c2b70)
Location: kernel/trace/trace.c:9321
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811c2a20-ffffffff811c2b6a: ftrace_dump.part.0 (STB_LOCAL)
ffffffff81be597c-ffffffff81be5a92: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811c2b70-ffffffff811c2b94: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c3c10)
Location: kernel/trace/trace.c:9660
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811c3a90-ffffffff811c3c0d: ftrace_dump.part.0 (STB_LOCAL)
ffffffff81bd7824-ffffffff81bd7948: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811c3c10-ffffffff811c3c34: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811eee80)
Location: kernel/trace/trace.c:9824
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811eecc0-ffffffff811eee7f: ftrace_dump.part.0 (STB_LOCAL)
ffffffff81cb5754-ffffffff81cb5872: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811eee80-ffffffff811eeea4: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff812272f0)
Location: kernel/trace/trace.c:9875
Inline: True
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_panic_handler
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81227140-ffffffff812272e8: ftrace_dump.part.0 (STB_LOCAL)
ffffffff81e6675c-ffffffff81e66874: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff812272f0-ffffffff81227324: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81272490)
Location: kernel/trace/trace.c:9970
Inline: True
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_die_panic_handler
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81272490-ffffffff81272767: ftrace_dump.part.0 (STB_LOCAL)
ffffffff81272780-ffffffff812727b4: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81289790)
Location: kernel/trace/trace.c:10135
Inline: True
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_die_panic_handler
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81289790-ffffffff81289a67: ftrace_dump.part.0 (STB_LOCAL)
ffffffff81289a80-ffffffff81289ab4: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a4b10)
Location: kernel/trace/trace.c:10330
Inline: True
Direct callers:
  - kernel/rcu/tree.c:check_cpu_stall
  - kernel/trace/trace.c:trace_die_panic_handler
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff812a4b10-ffffffff812a4de6: ftrace_dump.part.0 (STB_LOCAL)
ffffffff812a4e00-ffffffff812a4e34: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001022a120)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffff80001022a120-ffff80001022a494: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04677e0)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
c04677e0-c0467b2c: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002b1d00)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - arch/powerpc/xmon/xmon.c:dump
  - arch/powerpc/xmon/xmon.c:dump
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
c0000000002b1d00-c0000000002b20d4: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffe000184aa6)
Location: kernel/trace/trace.c:8905
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_panic_handler
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffe000184770-ffffffe000184a24: ftrace_dump.part.0 (STB_LOCAL)
ffffffe000184a24-ffffffe000184a56: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5840)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811a5700-ffffffff811a5835: ftrace_dump.part.0 (STB_LOCAL)
ffffffff811a5c35-ffffffff811a5d67: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811a5840-ffffffff811a5864: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811986d3)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff81198bc5-ffffffff81198cf1: ftrace_dump.cold (STB_LOCAL)
ffffffff811986b0-ffffffff811987f6: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a3610)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811a34d0-ffffffff811a3605: ftrace_dump.part.0 (STB_LOCAL)
ffffffff811a3a05-ffffffff811a3b37: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811a3610-ffffffff811a3634: ftrace_dump (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ftrace_dump(enum ftrace_dump_mode oops_dump_mode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b13a0)
Location: kernel/trace/trace.c:8905
Inline: True
Direct callers:
  - kernel/panic.c:panic
  - kernel/rcu/tree.c:rcu_sched_clock_irq
  - kernel/trace/trace.c:trace_panic_handler
  - kernel/trace/trace_functions.c:ftrace_cpudump_probe
  - kernel/trace/trace_functions.c:ftrace_dump_probe
  - drivers/tty/sysrq.c:sysrq_ftrace_dump
```
**Symbols:**

```
ffffffff811b1260-ffffffff811b1395: ftrace_dump.part.0 (STB_LOCAL)
ffffffff811b1795-ffffffff811b18c7: ftrace_dump.part.0.cold (STB_LOCAL)
ffffffff811b13a0-ffffffff811b13c4: ftrace_dump (STB_GLOBAL)
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
