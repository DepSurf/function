# Function: <code>intel_pmu_bts_config</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c2a0)
Location: arch/x86/events/intel/core.c:3138
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100c2a0-ffffffff8100c335: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ca10)
Location: arch/x86/events/intel/core.c:3222
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100ca10-ffffffff8100caa5: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ce40)
Location: arch/x86/events/intel/core.c:3223
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100ce40-ffffffff8100ced5: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100dcf0)
Location: arch/x86/events/intel/core.c:3242
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100dcf0-ffffffff8100dd85: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cec0)
Location: arch/x86/events/intel/core.c:3529
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100cec0-ffffffff8100cf55: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100da10)
Location: arch/x86/events/intel/core.c:3639
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100da10-ffffffff8100daa2: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e040)
Location: arch/x86/events/intel/core.c:3646
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:adl_hw_config
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100e040-ffffffff8100e0d2: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f590)
Location: arch/x86/events/intel/core.c:3708
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_hw_config
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100f590-ffffffff8100f628: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012f80)
Location: arch/x86/events/intel/core.c:3781
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_hw_config
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff81012f80-ffffffff81013018: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81012550)
Location: arch/x86/events/intel/core.c:3799
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_hw_config
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff81012550-ffffffff810125e8: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81017e70)
Location: arch/x86/events/intel/core.c:3814
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:adl_hw_config
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff81017e70-ffffffff81017f08: intel_pmu_bts_config (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ce40)
Location: arch/x86/events/intel/core.c:3223
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100ce40-ffffffff8100ced5: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b640)
Location: arch/x86/events/intel/core.c:3223
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100b640-ffffffff8100b6d5: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ce00)
Location: arch/x86/events/intel/core.c:3223
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100ce00-ffffffff8100ce95: intel_pmu_bts_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int intel_pmu_bts_config(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d030)
Location: arch/x86/events/intel/core.c:3223
Inline: True
Direct callers:
  - arch/x86/events/intel/core.c:core_pmu_hw_config
```
**Symbols:**

```
ffffffff8100d030-ffffffff8100d0c5: intel_pmu_bts_config (STB_LOCAL)
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
