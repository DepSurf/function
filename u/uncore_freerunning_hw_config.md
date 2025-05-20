# Function: <code>uncore_freerunning_hw_config</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81019f50)
Location: arch/x86/events/intel/uncore.h:435
Inline: False
```
**Symbols:**

```
ffffffff81019f50-ffffffff81019f81: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a8d0)
Location: arch/x86/events/intel/uncore.h:435
Inline: False
```
**Symbols:**

```
ffffffff8101a8d0-ffffffff8101a901: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101ba10)
Location: arch/x86/events/intel/uncore.h:438
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c480)
Location: arch/x86/events/intel/uncore.h:438
Inline: False
```
**Symbols:**

```
ffffffff8101ba10-ffffffff8101ba41: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff8101c480-ffffffff8101c4b1: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101bf10)
Location: arch/x86/events/intel/uncore.h:475
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101c9f0)
Location: arch/x86/events/intel/uncore.h:475
Inline: False
```
**Symbols:**

```
ffffffff8101bf10-ffffffff8101bf41: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff8101c9f0-ffffffff8101ca21: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8101d2c0)
Location: arch/x86/events/intel/uncore.h:488
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101dea0)
Location: arch/x86/events/intel/uncore.h:488
Inline: False
```
**Symbols:**

```
ffffffff8101d2c0-ffffffff8101d2f1: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff8101dea0-ffffffff8101ded1: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810203c0)
Location: arch/x86/events/intel/uncore.h:489
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81020fa0)
Location: arch/x86/events/intel/uncore.h:489
Inline: False
```
**Symbols:**

```
ffffffff810203c0-ffffffff810203f1: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff81020fa0-ffffffff81020fd1: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81023340)
Location: arch/x86/events/intel/uncore.h:489
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81024550)
Location: arch/x86/events/intel/uncore.h:489
Inline: False
```
**Symbols:**

```
ffffffff81023340-ffffffff81023377: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff81024550-ffffffff81024587: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff81028080)
Location: arch/x86/events/intel/uncore.h:505
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81029700)
Location: arch/x86/events/intel/uncore.h:505
Inline: False
```
**Symbols:**

```
ffffffff81028080-ffffffff810280b7: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff81029700-ffffffff81029737: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff810280b0)
Location: arch/x86/events/intel/uncore.h:508
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff81029730)
Location: arch/x86/events/intel/uncore.h:508
Inline: False
```
**Symbols:**

```
ffffffff810280b0-ffffffff810280ed: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff81029730-ffffffff8102976d: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snb.c (ffffffff8102e210)
Location: arch/x86/events/intel/uncore.h:508
Inline: False
```
```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8102f890)
Location: arch/x86/events/intel/uncore.h:508
Inline: False
```
**Symbols:**

```
ffffffff8102e210-ffffffff8102e24d: uncore_freerunning_hw_config (STB_LOCAL)
ffffffff8102f890-ffffffff8102f8cd: uncore_freerunning_hw_config (STB_LOCAL)
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
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a8d0)
Location: arch/x86/events/intel/uncore.h:435
Inline: False
```
**Symbols:**

```
ffffffff8101a8d0-ffffffff8101a901: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a030)
Location: arch/x86/events/intel/uncore.h:435
Inline: False
```
**Symbols:**

```
ffffffff8101a030-ffffffff8101a061: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101a890)
Location: arch/x86/events/intel/uncore.h:435
Inline: False
```
**Symbols:**

```
ffffffff8101a890-ffffffff8101a8c1: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uncore_freerunning_hw_config(struct intel_uncore_box *box, struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/uncore_snbep.c (ffffffff8101aad0)
Location: arch/x86/events/intel/uncore.h:435
Inline: False
```
**Symbols:**

```
ffffffff8101aad0-ffffffff8101ab01: uncore_freerunning_hw_config (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
