# Function: <code>x86_cpuid_vendor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104cfe6)
Location: arch/x86/include/asm/microcode.h:107
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f506)
Location: arch/x86/include/asm/microcode.h:111
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8104f456)
Location: arch/x86/include/asm/microcode.h:110
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81052ea6)
Location: arch/x86/include/asm/microcode.h:117
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81055b75)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81053215)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810563d5)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056c85)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int x86_cpuid_vendor();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105be35)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
**Symbols:**

```
ffffffff8105b310-ffffffff8105b368: x86_cpuid_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int x86_cpuid_vendor();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105a885)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:check_loader_disabled_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
**Symbols:**

```
ffffffff81059d60-ffffffff81059db8: x86_cpuid_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int x86_cpuid_vendor();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8105b225)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
**Symbols:**

```
ffffffff8105a700-ffffffff8105a758: x86_cpuid_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int x86_cpuid_vendor();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810647c5)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
**Symbols:**

```
ffffffff81063c50-ffffffff81063ca8: x86_cpuid_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int x86_cpuid_vendor();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810710b5)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
**Symbols:**

```
ffffffff81070930-ffffffff810709a0: x86_cpuid_vendor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81081185)
Location: arch/x86/include/asm/microcode.h:99
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81083605)
Location: arch/x86/include/asm/microcode.h:100
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff8108addc)
Location: arch/x86/kernel/cpu/microcode/internal.h:71
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:microcode_bsp_resume
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056805)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81046a15)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff81056c35)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/core.c (ffffffff810580d5)
Location: arch/x86/include/asm/microcode.h:103
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_early_microcode
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_ap
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
  - arch/x86/kernel/cpu/microcode/core.c:load_ucode_bsp
```
</details>
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
</ul>
