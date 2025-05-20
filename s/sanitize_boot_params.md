# Function: <code>sanitize_boot_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f59276)
Location: arch/x86/include/asm/bootparam_utils.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81f81213)
Location: arch/x86/include/asm/bootparam_utils.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:copy_bootdata
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
In arch/x86/kernel/head64.c (ffffffff81fbd213)
Location: arch/x86/include/asm/bootparam_utils.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:copy_bootdata
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
In arch/x86/kernel/head64.c (ffffffff8209d213)
Location: arch/x86/include/asm/bootparam_utils.h:20
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:copy_bootdata
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
In arch/x86/kernel/head64.c (ffffffff826a3232)
Location: arch/x86/include/asm/bootparam_utils.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:copy_bootdata
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
In arch/x86/kernel/head64.c (ffffffff826cc22f)
Location: arch/x86/include/asm/bootparam_utils.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:copy_bootdata
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
In arch/x86/kernel/head64.c (ffffffff8288222f)
Location: arch/x86/include/asm/bootparam_utils.h:21
Inline: True
Inline callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002008)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81002008-ffffffff810020a8: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002008)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81002008-ffffffff810020a8: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81003008)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81003008-ffffffff810030a8: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81bd1617)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81bd1617-ffffffff81bd1696: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81bc3627)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81bc3627-ffffffff81bc36a6: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81c94637)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81c94637-ffffffff81c9471e: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81e43688)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81e43688-ffffffff81e437f6: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81000ba0)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81000ba0-ffffffff81000de5: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff8104a080)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff8104a080-ffffffff8104a311: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810512e0)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff810512e0-ffffffff81051571: sanitize_boot_params.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002008)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81002008-ffffffff810020a8: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff810004f8)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff810004f8-ffffffff81000598: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002008)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81002008-ffffffff810020a8: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/head64.c (ffffffff81002008)
Location: arch/x86/include/asm/bootparam_utils.h:35
Inline: True
Direct callers:
  - arch/x86/kernel/head64.c:copy_bootdata
```
**Symbols:**

```
ffffffff81002008-ffffffff810020a8: sanitize_boot_params.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
