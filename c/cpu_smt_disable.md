# Function: <code>cpu_smt_disable</code>

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
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff826f3097)
Location: kernel/cpu.c:352
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff826f3097-ffffffff826f30d7: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828a9e97)
Location: kernel/cpu.c:380
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff828a9e97-ffffffff828a9ee4: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828c2682)
Location: kernel/cpu.c:390
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff828c2682-ffffffff828c26cf: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828cac81)
Location: kernel/cpu.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff828cac81-ffffffff828cacce: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff82ced09e)
Location: kernel/cpu.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff82ced09e-ffffffff82ced0eb: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff82fd96f8)
Location: kernel/cpu.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff82fd96f8-ffffffff82fd9745: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff831e404c)
Location: kernel/cpu.c:406
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff831e404c-ffffffff831e4099: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff832c7c29)
Location: kernel/cpu.c:417
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff832c7c29-ffffffff832c7c76: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8347ac37)
Location: kernel/cpu.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff8347ac37-ffffffff8347ac94: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff83ea5558)
Location: kernel/cpu.c:418
Inline: True
Inline callers:
  - kernel/cpu.c:smt_cmdline_disable
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
```
**Symbols:**

```
ffffffff83ea5770-ffffffff83ea57d5: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff836c9928)
Location: kernel/cpu.c:597
Inline: True
Inline callers:
  - kernel/cpu.c:smt_cmdline_disable
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
```
**Symbols:**

```
ffffffff836c9de0-ffffffff836c9e45: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff838fa578)
Location: kernel/cpu.c:600
Inline: True
Inline callers:
  - kernel/cpu.c:smt_cmdline_disable
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
```
**Symbols:**

```
ffffffff838faa50-ffffffff838faab3: cpu_smt_disable (STB_GLOBAL)
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
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828b3a74)
Location: kernel/cpu.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff828b3a74-ffffffff828b3ac1: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828abbf5)
Location: kernel/cpu.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff828abbf5-ffffffff828abc42: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828c6973)
Location: kernel/cpu.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff828c6973-ffffffff828c69c0: cpu_smt_disable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpu_smt_disable(bool force);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff828cbcbe)
Location: kernel/cpu.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - kernel/cpu.c:smt_cmdline_disable
```
**Symbols:**

```
ffffffff828cbcbe-ffffffff828cbd0b: cpu_smt_disable (STB_GLOBAL)
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
