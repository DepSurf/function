# Function: <code>arch_ima_get_secureboot</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ima_arch.c (0)
Location: arch/x86/kernel/ima_arch.c:42
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff81078cdd-ffffffff81078d2b: arch_ima_get_secureboot.cold.0 (STB_LOCAL)
ffffffff81078bc0-ffffffff81078cc5: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ima_arch.c (0)
Location: arch/x86/kernel/ima_arch.c:56
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8107c8ad-ffffffff8107c91e: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8107c730-ffffffff8107c899: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ima_arch.c (0)
Location: arch/x86/kernel/ima_arch.c:54
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8107d95d-ffffffff8107d9ce: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8107d820-ffffffff8107d947: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/ima.h:38
Inline: True
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/ima.h:38
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/ima.h:49
Inline: True
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/ima.h:49
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/ima.h:55
Inline: True
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/ima.h:55
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/ima.h:57
Inline: True
```
```
In security/integrity/ima/ima_appraise.c (0)
Location: include/linux/ima.h:57
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (ffffffff81648995)
Location: security/integrity/ima/ima_efi.c:33
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/ima/ima_main.c:ima_load_data
  - security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline
```
**Symbols:**

```
ffffffff81e8a782-ffffffff81e8a796: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff81648910-ffffffff8164898d: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (ffffffff81701765)
Location: security/integrity/ima/ima_efi.c:33
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/ima/ima_main.c:ima_load_data
  - security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline
```
**Symbols:**

```
ffffffff82075628-ffffffff8207563c: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff817016d0-ffffffff8170174d: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (ffffffff8173b805)
Location: security/integrity/ima/ima_efi.c:33
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/ima/ima_main.c:ima_load_data
  - security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline
```
**Symbols:**

```
ffffffff820f518a-ffffffff820f519e: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8173b770-ffffffff8173b7ed: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (ffffffff8177c3c5)
Location: security/integrity/ima/ima_efi.c:33
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
Direct callers:
  - security/integrity/platform_certs/load_uefi.c:load_uefi_certs
  - security/integrity/ima/ima_main.c:ima_load_data
  - security/integrity/ima/ima_appraise.c:ima_appraise_parse_cmdline
```
**Symbols:**

```
ffffffff821d2334-ffffffff821d2348: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8177c330-ffffffff8177c3ad: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_main.c (0)
Location: include/linux/ima.h:37
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ima_arch.c (c000000000085590)
Location: arch/powerpc/kernel/ima_arch.c:10
Inline: False
```
**Symbols:**

```
c000000000085590-c0000000000855c4: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
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
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ima_arch.c (0)
Location: arch/x86/kernel/ima_arch.c:54
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8107c95d-ffffffff8107c9ce: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8107c820-ffffffff8107c947: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ima_arch.c (0)
Location: arch/x86/kernel/ima_arch.c:54
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8106c0cd-ffffffff8106c13e: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8106bf90-ffffffff8106c0b7: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ima_arch.c (0)
Location: arch/x86/kernel/ima_arch.c:54
Inline: False
```
**Symbols:**

```
ffffffff8107c90d-ffffffff8107c97e: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8107c7d0-ffffffff8107c8f7: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool arch_ima_get_secureboot();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/ima_arch.c (0)
Location: arch/x86/kernel/ima_arch.c:54
Inline: False
Direct callers:
  - security/integrity/ima/ima_main.c:ima_load_data
```
**Symbols:**

```
ffffffff8107ea0d-ffffffff8107ea7e: arch_ima_get_secureboot.cold (STB_LOCAL)
ffffffff8107e8d0-ffffffff8107e9f7: arch_ima_get_secureboot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
