# Function: <code>x86_cpu_has_min_microcode_rev</code>

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
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81047210)
Location: arch/x86/kernel/cpu/match.c:72
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81047210-ffffffff81047284: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81047990)
Location: arch/x86/kernel/cpu/match.c:72
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81047990-ffffffff81047a04: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8104b730)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_check_pebs_isolation
```
**Symbols:**

```
ffffffff8104b730-ffffffff8104b7a5: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8104ac70)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_check_pebs_isolation
```
**Symbols:**

```
ffffffff8104ac70-ffffffff8104ace5: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8104c550)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_check_pebs_isolation
```
**Symbols:**

```
ffffffff8104c550-ffffffff8104c5c4: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81053820)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_check_pebs_isolation
```
**Symbols:**

```
ffffffff81053820-ffffffff81053894: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8105f1f0)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_check_pebs_isolation
```
**Symbols:**

```
ffffffff8105f1f0-ffffffff8105f28e: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8106d990)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8106d990-ffffffff8106da2e: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff8106f2a0)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff8106f2a0-ffffffff8106f33e: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81076660)
Location: arch/x86/kernel/cpu/match.c:82
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81076660-ffffffff810766fe: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
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
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81047b00)
Location: arch/x86/kernel/cpu/match.c:72
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81047b00-ffffffff81047b74: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81036e00)
Location: arch/x86/kernel/cpu/match.c:72
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81036e00-ffffffff81036e74: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81047940)
Location: arch/x86/kernel/cpu/match.c:72
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81047940-ffffffff810479b4: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool x86_cpu_has_min_microcode_rev(const struct x86_cpu_desc *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/match.c (ffffffff81048d50)
Location: arch/x86/kernel/cpu/match.c:72
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_counter_freezing_quirk
  - arch/x86/events/intel/core.c:intel_pebs_isolation_quirk
```
**Symbols:**

```
ffffffff81048d50-ffffffff81048dc4: x86_cpu_has_min_microcode_rev (STB_GLOBAL)
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
