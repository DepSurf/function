# Function: <code>x86_perf_event_set_period</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006940)
Location: arch/x86/events/core.c:1076
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006940-ffffffff81006ab4: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b30)
Location: arch/x86/events/core.c:1103
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006b30-ffffffff81006c99: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b30)
Location: arch/x86/events/core.c:1112
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006b30-ffffffff81006c99: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810068a0)
Location: arch/x86/events/core.c:1113
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810068a0-ffffffff810069f6: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006cb0)
Location: arch/x86/events/core.c:1119
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81006cb0-ffffffff81006e07: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007450)
Location: arch/x86/events/core.c:1125
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007450-ffffffff8100759e: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007330)
Location: arch/x86/events/core.c:1126
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007330-ffffffff8100747e: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007600)
Location: arch/x86/events/core.c:1165
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007600-ffffffff8100774e: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007780)
Location: arch/x86/events/core.c:1228
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007780-ffffffff81007910: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810087e0)
Location: arch/x86/events/core.c:1229
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810087e0-ffffffff81008973: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007850)
Location: arch/x86/events/core.c:1304
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_nhm_workaround
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007850-ffffffff81007a27: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008030)
Location: arch/x86/events/core.c:1357
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81008030-ffffffff81008207: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008bf0)
Location: arch/x86/events/core.c:1355
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81008bf0-ffffffff81008e21: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008260)
Location: arch/x86/events/core.c:1363
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:handle_pmi_common
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81008260-ffffffff810084a8: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007f00)
Location: arch/x86/events/core.c:1367
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_set_period
  - arch/x86/events/intel/p4.c:p4_pmu_set_period
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007f00-ffffffff810080d4: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810076f0)
Location: arch/x86/events/core.c:1367
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_set_period
  - arch/x86/events/intel/p4.c:p4_pmu_set_period
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff810076f0-ffffffff810078c4: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100ce10)
Location: arch/x86/events/core.c:1365
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_v2_handle_irq
  - arch/x86/events/intel/core.c:intel_pmu_set_period
  - arch/x86/events/intel/p4.c:p4_pmu_set_period
  - arch/x86/events/zhaoxin/core.c:zhaoxin_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100ce10-ffffffff8100cfe4: x86_perf_event_set_period (STB_GLOBAL)
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
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007780)
Location: arch/x86/events/core.c:1228
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007780-ffffffff81007910: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005f20)
Location: arch/x86/events/core.c:1228
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81005f20-ffffffff810060dc: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007740)
Location: arch/x86/events/core.c:1228
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff81007740-ffffffff810078d0: x86_perf_event_set_period (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int x86_perf_event_set_period(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810078a0)
Location: arch/x86/events/core.c:1228
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_handle_irq
  - arch/x86/events/core.c:x86_pmu_start
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_save_and_restart
  - arch/x86/events/intel/core.c:intel_pmu_nhm_enable_all
  - arch/x86/events/intel/p4.c:p4_pmu_handle_irq
```
**Symbols:**

```
ffffffff810078a0-ffffffff81007a30: x86_perf_event_set_period (STB_GLOBAL)
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
