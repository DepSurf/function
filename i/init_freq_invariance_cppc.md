# Function: <code>init_freq_invariance_cppc</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_freq_invariance_cppc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106d3c0)
Location: arch/x86/kernel/smpboot.c:2141
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8106d3c0-ffffffff8106d3fb: init_freq_invariance_cppc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_freq_invariance_cppc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/smpboot.c (ffffffff8106de30)
Location: arch/x86/kernel/smpboot.c:2137
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff8106de30-ffffffff8106de6b: init_freq_invariance_cppc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void init_freq_invariance_cppc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/smpboot.c (0)
Location: arch/x86/kernel/smpboot.c:2144
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81c9d6a8-ffffffff81c9d6bc: init_freq_invariance_cppc.cold (STB_LOCAL)
ffffffff81079640-ffffffff8107968e: init_freq_invariance_cppc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void init_freq_invariance_cppc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cppc.c (0)
Location: arch/x86/kernel/acpi/cppc.c:103
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81e4c645-ffffffff81e4c659: init_freq_invariance_cppc.cold (STB_LOCAL)
ffffffff810844f0-ffffffff81084619: init_freq_invariance_cppc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void init_freq_invariance_cppc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cppc.c (0)
Location: arch/x86/kernel/acpi/cppc.c:103
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff82053adf-ffffffff82053af3: init_freq_invariance_cppc.cold (STB_LOCAL)
ffffffff81097460-ffffffff81097589: init_freq_invariance_cppc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void init_freq_invariance_cppc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cppc.c (0)
Location: arch/x86/kernel/acpi/cppc.c:103
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff820d20cd-ffffffff820d20e1: init_freq_invariance_cppc.cold (STB_LOCAL)
ffffffff8109a530-ffffffff8109a661: init_freq_invariance_cppc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void init_freq_invariance_cppc();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/acpi/cppc.c (0)
Location: arch/x86/kernel/acpi/cppc.c:103
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff821acd31-ffffffff821acd45: init_freq_invariance_cppc.cold (STB_LOCAL)
ffffffff810a1d60-ffffffff810a1e91: init_freq_invariance_cppc (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
