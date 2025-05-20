# Function: <code>x86_setup_perfctr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006170)
Location: arch/x86/events/core.c:386
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006170-ffffffff810062db: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006380)
Location: arch/x86/events/core.c:397
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006380-ffffffff81006507: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006390)
Location: arch/x86/events/core.c:402
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006390-ffffffff810064fb: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006130)
Location: arch/x86/events/core.c:403
Inline: True
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006130-ffffffff8100629c: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff810064b0)
Location: arch/x86/events/core.c:403
Inline: True
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff810064b0-ffffffff81006622: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006c20)
Location: arch/x86/events/core.c:407
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006c20-ffffffff81006dc4: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006b60)
Location: arch/x86/events/core.c:407
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006b60-ffffffff81006c90: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006d70)
Location: arch/x86/events/core.c:407
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006d70-ffffffff81006eab: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006df0)
Location: arch/x86/events/core.c:412
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006df0-ffffffff81006f2b: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007e50)
Location: arch/x86/events/core.c:413
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81007e50-ffffffff81007f8f: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006f00)
Location: arch/x86/events/core.c:445
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006f00-ffffffff8100703f: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007620)
Location: arch/x86/events/core.c:471
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81007620-ffffffff810077be: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007ef0)
Location: arch/x86/events/core.c:471
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81007ef0-ffffffff810081cf: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81007470)
Location: arch/x86/events/core.c:473
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81007470-ffffffff8100776d: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008d10)
Location: arch/x86/events/core.c:476
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81008d10-ffffffff8100900b: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81008540)
Location: arch/x86/events/core.c:476
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81008540-ffffffff8100883d: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff8100dc60)
Location: arch/x86/events/core.c:474
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff8100dc60-ffffffff8100df5d: x86_setup_perfctr (STB_GLOBAL)
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
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006df0)
Location: arch/x86/events/core.c:412
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006df0-ffffffff81006f2b: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81005510)
Location: arch/x86/events/core.c:412
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81005510-ffffffff8100564b: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006db0)
Location: arch/x86/events/core.c:412
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006db0-ffffffff81006eeb: x86_setup_perfctr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int x86_setup_perfctr(struct perf_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/core.c (ffffffff81006f10)
Location: arch/x86/events/core.c:412
Inline: False
Direct callers:
  - arch/x86/events/core.c:x86_pmu_hw_config
  - arch/x86/events/intel/p4.c:p4_hw_config
```
**Symbols:**

```
ffffffff81006f10-ffffffff8100704b: x86_setup_perfctr (STB_GLOBAL)
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
