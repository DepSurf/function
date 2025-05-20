# Function: <code>perf_event_overflow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811844c0)
Location: kernel/events/core.c:6473
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff811844c0-ffffffff811844d6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81196230)
Location: kernel/events/core.c:7067
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81196230-ffffffff81196246: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a5cb0)
Location: kernel/events/core.c:7180
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff811a5cb0-ffffffff811a5cc6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811ad440)
Location: kernel/events/core.c:7403
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff811ad440-ffffffff811ad456: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811c0fa0)
Location: kernel/events/core.c:7400
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff811c0fa0-ffffffff811c0fb6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e1340)
Location: kernel/events/core.c:7782
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff811e1340-ffffffff811e1356: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f17a0)
Location: kernel/events/core.c:7791
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff811f17a0-ffffffff811f17b6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81209360)
Location: kernel/events/core.c:8095
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81209360-ffffffff81209376: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812166d0)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff812166d0-ffffffff812166e6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812425e0)
Location: kernel/events/core.c:8761
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff812425e0-ffffffff812425f6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8124cdd0)
Location: kernel/events/core.c:9027
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff8124cdd0-ffffffff8124cde6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81251430)
Location: kernel/events/core.c:9157
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81251430-ffffffff81251446: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8128c230)
Location: kernel/events/core.c:9276
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff8128c230-ffffffff8128c246: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812e0d60)
Location: kernel/events/core.c:9211
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff812e0d60-ffffffff812e0d87: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81349230)
Location: kernel/events/core.c:9536
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81349230-ffffffff81349257: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8137a230)
Location: kernel/events/core.c:9565
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff8137a230-ffffffff8137a257: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff813a3430)
Location: kernel/events/core.c:9635
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff813a3430-ffffffff813a3457: perf_event_overflow (STB_GLOBAL)
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
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102a0750)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/arm64/kernel/perf_event.c:armv8pmu_handle_irq
```
**Symbols:**

```
ffff8000102a0750-ffff8000102a0770: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04d068c)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/arm/kernel/perf_event_v7.c:armv7pmu_handle_irq
```
**Symbols:**

```
c04d068c-c04d06ac: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c0000000003520e0)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/powerpc/perf/core-book3s.c:record_and_restart
```
**Symbols:**

```
c0000000003520e0-c0000000003520fc: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001cfc64)
Location: kernel/events/core.c:8211
Inline: False
```
**Symbols:**

```
ffffffe0001cfc64-ffffffe0001cfc82: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ed20)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff8120ed20-ffffffff8120ed36: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201ad0)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81201ad0-ffffffff81201ae6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120cac0)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff8120cac0-ffffffff8120cad6: perf_event_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_event_overflow(struct perf_event *event, struct perf_sample_data *data, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8121b940)
Location: kernel/events/core.c:8211
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/amd/ibs.c:perf_ibs_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff8121b940-ffffffff8121b956: perf_event_overflow (STB_GLOBAL)
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
