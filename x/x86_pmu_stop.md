# Function: <code>x86_pmu_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005a00)
Location: arch/x86/events/core.c:1289
Inline: True
Direct callers:
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005a00-ffffffff81005ac2: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005ca0)
Location: arch/x86/events/core.c:1316
Inline: True
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005ca0-ffffffff81005d5e: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005be0)
Location: arch/x86/events/core.c:1336
Inline: True
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005be0-ffffffff81005c9e: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005970)
Location: arch/x86/events/core.c:1337
Inline: True
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005970-ffffffff81005a05: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005cd0)
Location: arch/x86/events/core.c:1343
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005cd0-ffffffff81005d6b: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006460)
Location: arch/x86/events/core.c:1346
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006460-ffffffff810064fb: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810063b0)
Location: arch/x86/events/core.c:1347
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810063b0-ffffffff8100644b: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810065e0)
Location: arch/x86/events/core.c:1386
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810065e0-ffffffff81006683: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006670)
Location: arch/x86/events/core.c:1456
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006670-ffffffff81006713: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810077d0)
Location: arch/x86/events/core.c:1457
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810077d0-ffffffff81007873: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006880)
Location: arch/x86/events/core.c:1534
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006880-ffffffff8100691e: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810069d0)
Location: arch/x86/events/core.c:1589
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810069d0-ffffffff81006a77: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810070d0)
Location: arch/x86/events/core.c:1587
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810070d0-ffffffff8100718e: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810065c0)
Location: arch/x86/events/core.c:1595
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810065c0-ffffffff81006692: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810062f0)
Location: arch/x86/events/core.c:1584
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810062f0-ffffffff810063c2: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005a90)
Location: arch/x86/events/core.c:1584
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005a90-ffffffff81005b62: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100b190)
Location: arch/x86/events/core.c:1582
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_icl
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_core
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100b190-ffffffff8100b262: x86_pmu_stop (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006670)
Location: arch/x86/events/core.c:1456
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006670-ffffffff81006713: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81004d90)
Location: arch/x86/events/core.c:1456
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81004d90-ffffffff81004e33: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006630)
Location: arch/x86/events/core.c:1456
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006630-ffffffff810066d3: x86_pmu_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void x86_pmu_stop(struct perf_event *event, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006790)
Location: arch/x86/events/core.c:1456
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_del
  - arch/x86/events/core.c:x86_pmu_enable
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/ds.c:intel_pmu_drain_pebs_nhm
  - arch/x86/events/intel/ds.c:__intel_pmu_pebs_event
  - arch/x86/events/intel/knc.c:knc_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006790-ffffffff81006833: x86_pmu_stop (STB_GLOBAL)
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
