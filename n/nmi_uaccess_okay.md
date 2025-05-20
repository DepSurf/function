# Function: <code>nmi_uaccess_okay</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810080c7)
Location: arch/x86/include/asm/tlbflush.h:264
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/lib/usercopy.c (ffffffff819e1469)
Location: arch/x86/include/asm/tlbflush.h:264
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007fa7)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1c419)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100829a)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In kernel/trace/bpf_trace.c (ffffffff811c23a9)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a8c0c9)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810084ba)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In kernel/trace/bpf_trace.c (ffffffff811cdb19)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81ac3389)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bae0)
Location: arch/x86/mm/tlb.c:1224
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
**Symbols:**

```
ffffffff8108bae0-ffffffff8108bb06: nmi_uaccess_okay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108bb30)
Location: arch/x86/mm/tlb.c:1160
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
**Symbols:**

```
ffffffff8108bb30-ffffffff8108bb56: nmi_uaccess_okay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c740)
Location: arch/x86/mm/tlb.c:1200
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
**Symbols:**

```
ffffffff8108c740-ffffffff8108c766: nmi_uaccess_okay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8109bf80)
Location: arch/x86/mm/tlb.c:1259
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
**Symbols:**

```
ffffffff8109bf80-ffffffff8109bfa6: nmi_uaccess_okay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810af550)
Location: arch/x86/mm/tlb.c:1229
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff810af550-ffffffff810af57c: nmi_uaccess_okay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c99c0)
Location: arch/x86/mm/tlb.c:1254
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
**Symbols:**

```
ffffffff810c99c0-ffffffff810c99ec: nmi_uaccess_okay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cd040)
Location: arch/x86/mm/tlb.c:1275
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - mm/maccess.c:copy_from_user_nofault
```
**Symbols:**

```
ffffffff810cd040-ffffffff810cd06c: nmi_uaccess_okay (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool nmi_uaccess_okay();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d5710)
Location: arch/x86/mm/tlb.c:1284
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - kernel/trace/bpf_trace.c:bpf_send_signal_common
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
  - mm/maccess.c:copy_from_user_nofault
```
**Symbols:**

```
ffffffff810d5710-ffffffff810d573c: nmi_uaccess_okay (STB_GLOBAL)
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810084ba)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In kernel/trace/bpf_trace.c (ffffffff811c6139)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a621d9)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006caa)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In kernel/trace/bpf_trace.c (ffffffff811b8f19)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81a1f249)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100847a)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In kernel/trace/bpf_trace.c (ffffffff811c3f09)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81ace5c9)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810085da)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/events/core.c:perf_callchain_user
```
```
In kernel/trace/bpf_trace.c (ffffffff811d17e9)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_send_signal
  - kernel/trace/bpf_trace.c:bpf_probe_write_user
```
```
In arch/x86/lib/usercopy.c (ffffffff81adaad9)
Location: arch/x86/include/asm/tlbflush.h:252
Inline: True
Inline callers:
  - arch/x86/lib/usercopy.c:copy_from_user_nmi
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
