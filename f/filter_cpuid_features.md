# Function: <code>filter_cpuid_features</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040190)
Location: arch/x86/kernel/cpu/common.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81040190-ffffffff81040212: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040000)
Location: arch/x86/kernel/cpu/common.c:373
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81040000-ffffffff81040085: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103fa40)
Location: arch/x86/kernel/cpu/common.c:376
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8103fa40-ffffffff8103fac5: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8103d9c0)
Location: arch/x86/kernel/cpu/common.c:378
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8103d9c0-ffffffff8103da45: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81040680)
Location: arch/x86/kernel/cpu/common.c:422
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81040680-ffffffff81040708: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:432
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81041de0-ffffffff81041e55: filter_cpuid_features (STB_LOCAL)
ffffffff81043412-ffffffff8104342c: filter_cpuid_features.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:432
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81043400-ffffffff81043475: filter_cpuid_features (STB_LOCAL)
ffffffff81044a92-ffffffff81044aac: filter_cpuid_features.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81045900-ffffffff81045978: filter_cpuid_features (STB_LOCAL)
ffffffff81047017-ffffffff81047035: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81046050-ffffffff810460c8: filter_cpuid_features (STB_LOCAL)
ffffffff810477c0-ffffffff810477de: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:513
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81049ea0-ffffffff81049f0f: filter_cpuid_features (STB_LOCAL)
ffffffff8104b520-ffffffff8104b53e: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:531
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff81049340-ffffffff810493af: filter_cpuid_features (STB_LOCAL)
ffffffff81bd4eee-ffffffff81bd4f0c: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:530
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff8104ac10-ffffffff8104ac7f: filter_cpuid_features (STB_LOCAL)
ffffffff81bc72a2-ffffffff81bc72c0: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81051b20)
Location: arch/x86/kernel/cpu/common.c:533
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81051b20-ffffffff81051bd3: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8105d2d0)
Location: arch/x86/kernel/cpu/common.c:641
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8105d2d0-ffffffff8105d38e: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106b740)
Location: arch/x86/kernel/cpu/common.c:643
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8106b740-ffffffff8106b7fd: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff8106d0f0)
Location: arch/x86/kernel/cpu/common.c:632
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff8106d0f0-ffffffff8106d1a8: filter_cpuid_features (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff810741e0)
Location: arch/x86/kernel/cpu/common.c:629
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
```
**Symbols:**

```
ffffffff810741e0-ffffffff81074298: filter_cpuid_features (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff810461d0-ffffffff81046248: filter_cpuid_features (STB_LOCAL)
ffffffff81047930-ffffffff8104794e: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81035480-ffffffff810354f8: filter_cpuid_features (STB_LOCAL)
ffffffff81036c30-ffffffff81036c4e: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81046010-ffffffff81046088: filter_cpuid_features (STB_LOCAL)
ffffffff81047770-ffffffff8104778e: filter_cpuid_features.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void filter_cpuid_features(struct cpuinfo_x86 *c, bool warn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:509
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/common.c:identify_cpu
  - arch/x86/kernel/cpu/common.c:early_cpu_init
```
**Symbols:**

```
ffffffff81047410-ffffffff81047488: filter_cpuid_features (STB_LOCAL)
ffffffff81048b80-ffffffff81048b9e: filter_cpuid_features.cold (STB_LOCAL)
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
