# Function: <code>iosf_mbi_modify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107a3b0)
Location: arch/x86/platform/intel/iosf_mbi.c:147
Inline: False
```
**Symbols:**

```
ffffffff8107a3b0-ffffffff8107a4b0: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107bc70)
Location: arch/x86/platform/intel/iosf_mbi.c:147
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
```
**Symbols:**

```
ffffffff8107bc70-ffffffff8107bd62: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81080210)
Location: arch/x86/platform/intel/iosf_mbi.c:147
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
```
**Symbols:**

```
ffffffff81080210-ffffffff81080302: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8107e4f0)
Location: arch/x86/platform/intel/iosf_mbi.c:149
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_runtime_resume
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff8107e4f0-ffffffff8107e5d3: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81084d20)
Location: arch/x86/platform/intel/iosf_mbi.c:149
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff81084d20-ffffffff81084e03: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81088020)
Location: arch/x86/platform/intel/iosf_mbi.c:149
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/i2c/busses/i2c-designware-baytrail.c:reset_semaphore
```
**Symbols:**

```
ffffffff81088020-ffffffff81088108: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff8108f780)
Location: arch/x86/platform/intel/iosf_mbi.c:151
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
```
**Symbols:**

```
ffffffff8108f780-ffffffff8108f868: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (0)
Location: arch/x86/platform/intel/iosf_mbi.c:142
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
```
**Symbols:**

```
ffffffff81093b74-ffffffff81093b8b: iosf_mbi_modify.cold (STB_LOCAL)
ffffffff81093440-ffffffff8109353a: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810942a0)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
```
**Symbols:**

```
ffffffff810942a0-ffffffff81094393: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81099550)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:lpss_iosf_enter_d3_state
  - drivers/acpi/acpi_lpss.c:lpss_iosf_enter_d3_state
  - drivers/acpi/acpi_lpss.c:lpss_iosf_enter_d3_state
```
**Symbols:**

```
ffffffff81099550-ffffffff8109963d: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098640)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:lpss_iosf_enter_d3_state
  - drivers/acpi/acpi_lpss.c:lpss_iosf_enter_d3_state
  - drivers/acpi/acpi_lpss.c:lpss_iosf_enter_d3_state
```
**Symbols:**

```
ffffffff81098640-ffffffff8109872d: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81098e80)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
```
**Symbols:**

```
ffffffff81098e80-ffffffff81098f6b: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810a8f90)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
```
**Symbols:**

```
ffffffff810a8f90-ffffffff810a907b: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810be710)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
```
**Symbols:**

```
ffffffff810be710-ffffffff810be807: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810da260)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
```
**Symbols:**

```
ffffffff810da260-ffffffff810da357: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810e57f0)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
```
**Symbols:**

```
ffffffff810e57f0-ffffffff810e58e7: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff810edbe0)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
  - drivers/acpi/acpi_lpss.c:acpi_lpss_suspend
```
**Symbols:**

```
ffffffff810edbe0-ffffffff810edcd7: iosf_mbi_modify (STB_GLOBAL)
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
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093260)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
```
**Symbols:**

```
ffffffff81093260-ffffffff81093353: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81081cf0)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
```
**Symbols:**

```
ffffffff81081cf0-ffffffff81081de3: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81093210)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
```
**Symbols:**

```
ffffffff81093210-ffffffff81093303: iosf_mbi_modify (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int iosf_mbi_modify(u8 port, u8 opcode, u32 offset, u32 mdr, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/intel/iosf_mbi.c (ffffffff81095760)
Location: arch/x86/platform/intel/iosf_mbi.c:143
Inline: False
Direct callers:
  - arch/x86/platform/intel/iosf_mbi.c:iosf_mbi_reset_semaphore
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
  - drivers/acpi/acpi_lpss.c:acpi_lpss_resume
```
**Symbols:**

```
ffffffff81095760-ffffffff81095853: iosf_mbi_modify (STB_GLOBAL)
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
