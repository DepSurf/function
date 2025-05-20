# Function: <code>intel_pmu_auto_reload_read</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010060)
Location: arch/x86/events/intel/ds.c:1331
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81010060-ffffffff8101009a: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010640)
Location: arch/x86/events/intel/ds.c:1342
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81010640-ffffffff8101067a: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/ds.c (0)
Location: arch/x86/events/intel/ds.c:1610
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81011865-ffffffff81011878: intel_pmu_auto_reload_read.cold (STB_LOCAL)
ffffffff810117d0-ffffffff8101180a: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011fd0)
Location: arch/x86/events/intel/ds.c:1653
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81011fd0-ffffffff8101200a: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81013440)
Location: arch/x86/events/intel/ds.c:1654
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81013440-ffffffff8101347d: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81012ff0)
Location: arch/x86/events/intel/ds.c:1659
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81012ff0-ffffffff8101302d: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81014200)
Location: arch/x86/events/intel/ds.c:1779
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81014200-ffffffff8101423d: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81015560)
Location: arch/x86/events/intel/ds.c:1788
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81015560-ffffffff8101559d: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81017560)
Location: arch/x86/events/intel/ds.c:1846
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81017560-ffffffff810175a3: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101b740)
Location: arch/x86/events/intel/ds.c:1905
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff8101b740-ffffffff8101b783: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101b410)
Location: arch/x86/events/intel/ds.c:1959
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff8101b410-ffffffff8101b453: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81020f70)
Location: arch/x86/events/intel/ds.c:1964
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81020f70-ffffffff81020fb3: intel_pmu_auto_reload_read (STB_GLOBAL)
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
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011fd0)
Location: arch/x86/events/intel/ds.c:1653
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81011fd0-ffffffff8101200a: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010e30)
Location: arch/x86/events/intel/ds.c:1653
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81010e30-ffffffff81010e6a: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81011f90)
Location: arch/x86/events/intel/ds.c:1653
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff81011f90-ffffffff81011fca: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pmu_auto_reload_read(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810121b0)
Location: arch/x86/events/intel/ds.c:1653
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_read_event
```
**Symbols:**

```
ffffffff810121b0-ffffffff810121ea: intel_pmu_auto_reload_read (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
