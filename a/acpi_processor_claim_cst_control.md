# Function: <code>acpi_processor_claim_cst_control</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:713
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff8168e605-ffffffff8168e616: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff8168d730-ffffffff8168d791: acpi_processor_claim_cst_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:712
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81c0141b-ffffffff81c0142c: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff816ab3e0-ffffffff816ab441: acpi_processor_claim_cst_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:695
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81bf2cb0-ffffffff81bf2cc1: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff8168dc40-ffffffff8168dca1: acpi_processor_claim_cst_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (ffffffff8170398b)
Location: drivers/acpi/acpi_processor.c:695
Inline: True
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81cef69b-ffffffff81cef6c1: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff81703950-ffffffff817039c0: acpi_processor_claim_cst_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:695
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff81eb7227-ffffffff81eb724c: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff81831990-ffffffff818319f7: acpi_processor_claim_cst_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:695
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff820919be-ffffffff820919d2: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff819650b0-ffffffff81965121: acpi_processor_claim_cst_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:733
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff821122de-ffffffff821122f2: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff819ab560-ffffffff819ab5d1: acpi_processor_claim_cst_control (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool acpi_processor_claim_cst_control();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_processor.c (0)
Location: drivers/acpi/acpi_processor.c:776
Inline: False
Direct callers:
  - drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
**Symbols:**

```
ffffffff821f0046-ffffffff821f005a: acpi_processor_claim_cst_control.cold (STB_LOCAL)
ffffffff819f5990-ffffffff819f5a01: acpi_processor_claim_cst_control (STB_GLOBAL)
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
