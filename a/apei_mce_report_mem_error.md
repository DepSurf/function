# Function: <code>apei_mce_report_mem_error</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff81049c70)
Location: arch/x86/kernel/cpu/mcheck/mce-apei.c:41
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81049c70-ffffffff81049d0b: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff81049dd0)
Location: arch/x86/kernel/cpu/mcheck/mce-apei.c:41
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81049dd0-ffffffff81049e6b: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff8104c1d0)
Location: arch/x86/kernel/cpu/mcheck/mce-apei.c:41
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff8104c1d0-ffffffff8104c270: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff8104c270-ffffffff8104c286: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff8104b830)
Location: arch/x86/kernel/cpu/mcheck/mce-apei.c:41
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff8104b830-ffffffff8104b8e4: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff8104b8f0-ffffffff8104b907: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff8104f250)
Location: arch/x86/kernel/cpu/mcheck/mce-apei.c:41
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff8104f250-ffffffff8104f304: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff8104f310-ffffffff8104f327: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce-apei.c (ffffffff81051fc0)
Location: arch/x86/kernel/cpu/mcheck/mce-apei.c:41
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81051fc0-ffffffff81052074: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81052080-ffffffff81052096: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8104f620)
Location: arch/x86/kernel/cpu/mce/apei.c:41
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff8104f620-ffffffff8104f6d4: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff8104f6e0-ffffffff8104f6f6: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81052780)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81052780-ffffffff81052834: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81052840-ffffffff81052856: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81053070)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81053070-ffffffff81053124: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81053130-ffffffff81053146: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81058060)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81058060-ffffffff8105811d: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81058120-ffffffff81058136: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81056d30)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81056d30-ffffffff81056ded: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81056df0-ffffffff81056e06: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81057670)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81057670-ffffffff8105772d: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81057730-ffffffff81057746: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810604c0)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff810604c0-ffffffff81060586: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81060590-ffffffff810605a6: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8106ccb0)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff8106ccb0-ffffffff8106cda2: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107cdc0)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff8107cdc0-ffffffff8107ced7: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff8107f170)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff8107f170-ffffffff8107f287: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81086c80)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81086c80-ffffffff81086d97: apei_mce_report_mem_error (STB_GLOBAL)
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
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81042cc0)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81042cc0-ffffffff81042d74: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81042d80-ffffffff81042d96: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff81053020)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff81053020-ffffffff810530d4: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff810530e0-ffffffff810530f6: apei_mce_report_mem_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apei_mce_report_mem_error(int severity, struct cper_sec_mem_err *mem_err);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/apei.c (ffffffff810544a0)
Location: arch/x86/kernel/cpu/mce/apei.c:29
Inline: True
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_report_mem_error
```
**Symbols:**

```
ffffffff810544a0-ffffffff81054554: apei_mce_report_mem_error.part.0 (STB_LOCAL)
ffffffff81054560-ffffffff81054576: apei_mce_report_mem_error (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
