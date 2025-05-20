# Function: <code>x86_perf_event_update</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005970)
Location: arch/x86/events/core.c:64
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005970-ffffffff810059fe: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005c00)
Location: arch/x86/events/core.c:65
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005c00-ffffffff81005c91: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005b40)
Location: arch/x86/events/core.c:66
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005b40-ffffffff81005bd1: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810058e0)
Location: arch/x86/events/core.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810058e0-ffffffff81005966: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005c40)
Location: arch/x86/events/core.c:67
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005c40-ffffffff81005cc6: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810063d0)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810063d0-ffffffff81006453: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006320)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006320-ffffffff810063a3: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006530)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006530-ffffffff810065b4: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810065c0)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810065c0-ffffffff81006644: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007720)
Location: arch/x86/events/core.c:69
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007720-ffffffff810077a4: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810067d0)
Location: arch/x86/events/core.c:98
Inline: False
Direct callers:
  - arch/x86/events/core.c:_x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810067d0-ffffffff81006878: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006920)
Location: arch/x86/events/core.c:107
Inline: False
Direct callers:
  - arch/x86/events/core.c:_x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006920-ffffffff810069cd: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:107
Inline: False
Direct callers:
  - arch/x86/events/core.c:_x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81c94f5c-ffffffff81c94f9f: x86_perf_event_update.cold (STB_LOCAL)
ffffffff81007000-ffffffff810070c2: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:109
Inline: False
Direct callers:
  - arch/x86/events/core.c:_x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81e44256-ffffffff81e44299: x86_perf_event_update.cold (STB_LOCAL)
ffffffff810064e0-ffffffff810065bc: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:115
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_update
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff8205012a-ffffffff8205016d: x86_perf_event_update.cold (STB_LOCAL)
ffffffff81005e70-ffffffff81005f29: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:115
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_update
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff820ce5d7-ffffffff820ce616: x86_perf_event_update.cold (STB_LOCAL)
ffffffff81005620-ffffffff810056ca: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/core.c (0)
Location: arch/x86/events/core.c:115
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_update
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff821a8e13-ffffffff821a8e52: x86_perf_event_update.cold (STB_LOCAL)
ffffffff8100ad20-ffffffff8100adcc: x86_perf_event_update (STB_GLOBAL)
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
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810065c0)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810065c0-ffffffff81006644: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81004cd0)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81004cd0-ffffffff81004d70: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006580)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006580-ffffffff81006604: x86_perf_event_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 x86_perf_event_update(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810066e0)
Location: arch/x86/events/core.c:68
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_read
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_stop
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_read_event
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810066e0-ffffffff81006764: x86_perf_event_update (STB_GLOBAL)
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
