# Function: <code>mce_disable_bank</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046ae0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1980
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81046ae0-ffffffff81046b2e: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81046b30)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2059
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81046b30-ffffffff81046b7e: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff810486d0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:2122
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff810486d0-ffffffff8104871e: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff81048020)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1852
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81048020-ffffffff8104806e: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (ffffffff8104ba80)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1864
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8104ba80-ffffffff8104bace: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mcheck/mce.c (0)
Location: arch/x86/kernel/cpu/mcheck/mce.c:1860
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8104e826-ffffffff8104e837: mce_disable_bank.cold.47 (STB_LOCAL)
ffffffff8104e3c0-ffffffff8104e404: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1881
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8104befd-ffffffff8104bf0e: mce_disable_bank.cold.47 (STB_LOCAL)
ffffffff8104bab0-ffffffff8104baf4: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1914
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8104edfc-ffffffff8104ee0d: mce_disable_bank.cold (STB_LOCAL)
ffffffff8104e990-ffffffff8104e9d2: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1914
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8104f776-ffffffff8104f787: mce_disable_bank.cold (STB_LOCAL)
ffffffff8104f330-ffffffff8104f372: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2036
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81053c64-ffffffff81053c75: mce_disable_bank.cold (STB_LOCAL)
ffffffff81053850-ffffffff81053892: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2112
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81bd588a-ffffffff81bd589b: mce_disable_bank.cold (STB_LOCAL)
ffffffff81052970-ffffffff810529b2: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2124
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81bc7cee-ffffffff81bc7cff: mce_disable_bank.cold (STB_LOCAL)
ffffffff81054290-ffffffff810542db: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2187
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81c9b8e3-ffffffff81c9b8f4: mce_disable_bank.cold (STB_LOCAL)
ffffffff8105cb70-ffffffff8105cbbb: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:2203
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81e4ada0-ffffffff81e4adb1: mce_disable_bank.cold (STB_LOCAL)
ffffffff81069300-ffffffff8106935c: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81078f00)
Location: arch/x86/kernel/cpu/mce/core.c:2203
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81078f00-ffffffff81078f77: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff8107b1b0)
Location: arch/x86/kernel/cpu/mce/core.c:2219
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8107b1b0-ffffffff8107b227: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (ffffffff81082670)
Location: arch/x86/kernel/cpu/mce/core.c:2248
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81082670-ffffffff810826e7: mce_disable_bank (STB_GLOBAL)
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
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1914
Inline: False
```
**Symbols:**

```
ffffffff8104f87f-ffffffff8104f890: mce_disable_bank.cold (STB_LOCAL)
ffffffff8104f490-ffffffff8104f4d2: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1914
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8103edf6-ffffffff8103ee07: mce_disable_bank.cold (STB_LOCAL)
ffffffff8103e9b0-ffffffff8103e9f2: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1914
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff8104f726-ffffffff8104f737: mce_disable_bank.cold (STB_LOCAL)
ffffffff8104f2e0-ffffffff8104f322: mce_disable_bank (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void mce_disable_bank(int bank);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/mce/core.c (0)
Location: arch/x86/kernel/cpu/mce/core.c:1914
Inline: False
Direct callers:
  - arch/x86/kernel/acpi/apei.c:arch_apei_enable_cmcff
```
**Symbols:**

```
ffffffff81050b66-ffffffff81050b77: mce_disable_bank.cold (STB_LOCAL)
ffffffff81050720-ffffffff81050762: mce_disable_bank (STB_GLOBAL)
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
