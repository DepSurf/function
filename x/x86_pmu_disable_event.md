# Function: <code>x86_pmu_disable_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007940)
Location: arch/x86/events/perf_event.h:754
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100a770)
Location: arch/x86/events/perf_event.h:754
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff81007940-ffffffff81007960: x86_pmu_disable_event (STB_LOCAL)
ffffffff8100a770-ffffffff8100a790: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007b90)
Location: arch/x86/events/perf_event.h:763
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100b3eb)
Location: arch/x86/events/perf_event.h:763
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff81007b90-ffffffff81007bb0: x86_pmu_disable_event (STB_LOCAL)
ffffffff8100a900-ffffffff8100a920: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007ba0)
Location: arch/x86/events/perf_event.h:766
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100b4bd)
Location: arch/x86/events/perf_event.h:766
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff81007ba0-ffffffff81007bc0: x86_pmu_disable_event (STB_LOCAL)
ffffffff8100a940-ffffffff8100a960: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810078f0)
Location: arch/x86/events/perf_event.h:771
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100afbd)
Location: arch/x86/events/perf_event.h:771
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff810078f0-ffffffff81007910: x86_pmu_disable_event (STB_LOCAL)
ffffffff8100a570-ffffffff8100a590: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007d70)
Location: arch/x86/events/perf_event.h:781
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100c60d)
Location: arch/x86/events/perf_event.h:781
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff81007d70-ffffffff81007d90: x86_pmu_disable_event (STB_LOCAL)
ffffffff8100c2b0-ffffffff8100c2d0: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008500)
Location: arch/x86/events/perf_event.h:784
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100cd6d)
Location: arch/x86/events/perf_event.h:784
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff81008500-ffffffff81008520: x86_pmu_disable_event (STB_LOCAL)
ffffffff8100ca00-ffffffff8100ca20: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810083e0)
Location: arch/x86/events/perf_event.h:802
Inline: False
```
```
In arch/x86/events/intel/core.c (ffffffff8100d119)
Location: arch/x86/events/perf_event.h:802
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff810083e0-ffffffff81008400: x86_pmu_disable_event (STB_LOCAL)
ffffffff8100ca60-ffffffff8100ca80: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008c55)
Location: arch/x86/events/perf_event.h:839
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100d971)
Location: arch/x86/events/perf_event.h:839
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff8100d2a0-ffffffff8100d2c0: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f75)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100df15)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff8100d710-ffffffff8100d773: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a665)
Location: arch/x86/events/perf_event.h:877
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100f975)
Location: arch/x86/events/perf_event.h:877
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8101fb1f)
Location: arch/x86/events/perf_event.h:877
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff8100ea90-ffffffff8100eafc: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810094e5)
Location: arch/x86/events/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100e859)
Location: arch/x86/events/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810205bf)
Location: arch/x86/events/perf_event.h:1008
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff8100de60-ffffffff8100decc: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009ea5)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100f09d)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102294f)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff8100e480-ffffffff8100e4f9: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100afb5)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100fe3d)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810267df)
Location: arch/x86/events/perf_event.h:1131
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff8100ec70-ffffffff8100ece9: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100ad85)
Location: arch/x86/events/perf_event.h:1157
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8101141d)
Location: arch/x86/events/perf_event.h:1157
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff8102a913)
Location: arch/x86/events/perf_event.h:1157
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff810102c0-ffffffff8101036b: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100cbf5)
Location: arch/x86/events/perf_event.h:1165
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff81014c7d)
Location: arch/x86/events/perf_event.h:1165
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810314f3)
Location: arch/x86/events/perf_event.h:1165
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff81013ff0-ffffffff8101409b: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100c3b5)
Location: arch/x86/events/perf_event.h:1170
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff810144dd)
Location: arch/x86/events/perf_event.h:1170
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810314f3)
Location: arch/x86/events/perf_event.h:1170
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff81013850-ffffffff810138fb: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81011b95)
Location: arch/x86/events/perf_event.h:1185
Inline: True
```
```
In arch/x86/events/intel/core.c (ffffffff8101969d)
Location: arch/x86/events/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
```
In arch/x86/events/zhaoxin/core.c (ffffffff810377e3)
Location: arch/x86/events/perf_event.h:1185
Inline: True
Inline callers:
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_disable_event
```
**Symbols:**

```
ffffffff81018ee0-ffffffff81018f8b: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f75)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100df15)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff8100d710-ffffffff8100d773: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81007ce5)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100c927)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff8100c1d0-ffffffff8100c251: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81008f35)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100ded5)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff8100d6d0-ffffffff8100d733: x86_pmu_disable_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void x86_pmu_disable_event(struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff81009095)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_disable_event
```
```
In arch/x86/events/intel/core.c (ffffffff8100e0a5)
Location: arch/x86/events/perf_event.h:868
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff8100d8a0-ffffffff8100d903: x86_pmu_disable_event (STB_LOCAL)
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
