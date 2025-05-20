# Function: <code>fini_debug_store_on_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010240)
Location: arch/x86/events/intel/ds.c:252
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
**Symbols:**

```
ffffffff81010240-ffffffff81010277: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fc30)
Location: arch/x86/events/intel/ds.c:261
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
**Symbols:**

```
ffffffff8100fc30-ffffffff8100fc67: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100fda0)
Location: arch/x86/events/intel/ds.c:261
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
  - arch/x86/events/intel/ds.c:release_ds_buffers
```
**Symbols:**

```
ffffffff8100fda0-ffffffff8100fdd7: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100e40e)
Location: arch/x86/events/intel/ds.c:271
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100e3b0-ffffffff8100e3e8: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100ebbc)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100eb20-ffffffff8100eb56: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100f51b)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100f460-ffffffff8100f496: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8100faeb)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100fa30-ffffffff8100fa66: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff81010c0b)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81010b50-ffffffff81010b87: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810112eb)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81011230-ffffffff81011267: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101295b)
Location: arch/x86/events/intel/ds.c:276
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff810128a0-ffffffff810128d7: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810124fb)
Location: arch/x86/events/intel/ds.c:276
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81012440-ffffffff81012477: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810135db)
Location: arch/x86/events/intel/ds.c:341
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81013520-ffffffff81013557: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101482f)
Location: arch/x86/events/intel/ds.c:341
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81014740-ffffffff810147a0: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101661e)
Location: arch/x86/events/intel/ds.c:390
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81016520-ffffffff8101658d: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101a6f1)
Location: arch/x86/events/intel/ds.c:397
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8101a5f0-ffffffff8101a65d: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101a181)
Location: arch/x86/events/intel/ds.c:445
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8101a080-ffffffff8101a0ed: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101fce1)
Location: arch/x86/events/intel/ds.c:450
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8101fbe0-ffffffff8101fc4d: fini_debug_store_on_cpu (STB_GLOBAL)
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
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810112eb)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81011230-ffffffff81011267: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff8101008b)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff8100ffd0-ffffffff81010007: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810112ab)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff810111f0-ffffffff81011227: fini_debug_store_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fini_debug_store_on_cpu(int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/ds.c (ffffffff810114bb)
Location: arch/x86/events/intel/ds.c:275
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:release_ds_buffers
  - arch/x86/events/intel/ds.c:release_ds_buffers
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_cpu_dying
```
**Symbols:**

```
ffffffff81011400-ffffffff81011437: fini_debug_store_on_cpu (STB_GLOBAL)
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
