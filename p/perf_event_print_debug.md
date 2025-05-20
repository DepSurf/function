# Function: <code>perf_event_print_debug</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006f40)
Location: arch/x86/events/core.c:1229
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81006f40-ffffffff81007207: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810070f0)
Location: arch/x86/events/core.c:1256
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff810070f0-ffffffff81007368: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810070f0)
Location: arch/x86/events/core.c:1276
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff810070f0-ffffffff81007368: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006e00)
Location: arch/x86/events/core.c:1277
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81006e00-ffffffff81007079: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007230)
Location: arch/x86/events/core.c:1283
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81007230-ffffffff810074a6: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff811dbc20)
Location: arch/x86/events/core.c:1286
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff810083bd-ffffffff810084f6: perf_event_print_debug.cold.26 (STB_LOCAL)
ffffffff81007990-ffffffff81007ad1: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff811ebfe0)
Location: arch/x86/events/core.c:1287
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff8100829d-ffffffff810083d6: perf_event_print_debug.cold.27 (STB_LOCAL)
ffffffff81007870-ffffffff810079b1: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81203970)
Location: arch/x86/events/core.c:1326
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff8100849d-ffffffff810085e1: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81007b50-ffffffff81007c93: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81210560)
Location: arch/x86/events/core.c:1396
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff8100879d-ffffffff810088e1: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81007d70-ffffffff81007ebc: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8123c760)
Location: arch/x86/events/core.c:1397
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff8100995c-ffffffff81009a57: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81008de0-ffffffff81008f1d: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81246a00)
Location: arch/x86/events/core.c:1474
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81bd1f43-ffffffff81bd203e: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81007e90-ffffffff81007fcd: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8124a780)
Location: arch/x86/events/core.c:1526
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81bc3f05-ffffffff81bc4021: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81008670-ffffffff8100883c: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff812840b0)
Location: arch/x86/events/core.c:1524
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81c95126-ffffffff81c952ab: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81009460-ffffffff8100965a: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff812d8410)
Location: arch/x86/events/core.c:1532
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81e4440d-ffffffff81e44562: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81008af0-ffffffff81008ce1: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81340900)
Location: arch/x86/events/core.c:1521
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff82050300-ffffffff82050325: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81009cb0-ffffffff8100a082: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff813718a0)
Location: arch/x86/events/core.c:1521
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff820ce783-ffffffff820ce797: perf_event_print_debug.cold (STB_LOCAL)
ffffffff810094d0-ffffffff81009896: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff8139aba0)
Location: arch/x86/events/core.c:1519
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff821a8fbf-ffffffff821a8fd3: perf_event_print_debug.cold (STB_LOCAL)
ffffffff8100ebf0-ffffffff8100efb6: perf_event_print_debug (STB_GLOBAL)
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
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102991c0)
Location: kernel/events/core.c:574
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffff8000102991c0-ffff8000102991c4: perf_event_print_debug (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c8458)
Location: kernel/events/core.c:574
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
c04c8458-c04c8468: perf_event_print_debug (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/perf/core-book3s.c (c0000000001297b0)
Location: arch/powerpc/perf/core-book3s.c:805
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
c0000000001297b0-c000000000129a2c: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cac46)
Location: kernel/events/core.c:574
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffe0001cac46-ffffffe0001cac52: perf_event_print_debug (STB_WEAK)
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
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81208bb0)
Location: arch/x86/events/core.c:1396
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff8100879d-ffffffff810088e1: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81007d70-ffffffff81007ebc: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff811fb940)
Location: arch/x86/events/core.c:1396
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff81006fbc-ffffffff810070fa: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81006580-ffffffff810066b0: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff81206950)
Location: arch/x86/events/core.c:1396
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff8100875d-ffffffff810088a1: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81007d30-ffffffff81007e7c: perf_event_print_debug (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void perf_event_print_debug();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (ffffffff812156c0)
Location: arch/x86/events/core.c:1396
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - drivers/tty/sysrq.c:sysrq_handle_showregs
```
**Symbols:**

```
ffffffff810088bd-ffffffff81008a01: perf_event_print_debug.cold (STB_LOCAL)
ffffffff81007e90-ffffffff81007fdc: perf_event_print_debug (STB_GLOBAL)
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
