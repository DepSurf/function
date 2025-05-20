# Function: <code>get_sb_mode</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ima_arch.c (ffffffff81078c31)
Location: arch/x86/kernel/ima_arch.c:10
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
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
In arch/x86/kernel/ima_arch.c (ffffffff8107c7a1)
Location: arch/x86/kernel/ima_arch.c:11
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
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
In arch/x86/kernel/ima_arch.c (ffffffff8107d891)
Location: arch/x86/kernel/ima_arch.c:11
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum efi_secureboot_mode get_sb_mode();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_efi.c (0)
Location: security/integrity/ima/ima_efi.c:14
Inline: False
Direct callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
**Symbols:**

```
ffffffff81648820-ffffffff81648904: get_sb_mode (STB_LOCAL)
ffffffff81e8a707-ffffffff81e8a782: get_sb_mode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum efi_secureboot_mode get_sb_mode();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_efi.c (ffffffff81701560)
Location: security/integrity/ima/ima_efi.c:14
Inline: False
Direct callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
**Symbols:**

```
ffffffff81701560-ffffffff817016b6: get_sb_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum efi_secureboot_mode get_sb_mode();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_efi.c (ffffffff8173b600)
Location: security/integrity/ima/ima_efi.c:14
Inline: False
Direct callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
**Symbols:**

```
ffffffff8173b600-ffffffff8173b756: get_sb_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum efi_secureboot_mode get_sb_mode();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_efi.c (ffffffff8177c1c0)
Location: security/integrity/ima/ima_efi.c:14
Inline: False
Direct callers:
  - security/integrity/ima/ima_efi.c:arch_get_ima_policy
```
**Symbols:**

```
ffffffff8177c1c0-ffffffff8177c316: get_sb_mode (STB_LOCAL)
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
In arch/x86/kernel/ima_arch.c (ffffffff8107c891)
Location: arch/x86/kernel/ima_arch.c:11
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
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
In arch/x86/kernel/ima_arch.c (ffffffff8106c001)
Location: arch/x86/kernel/ima_arch.c:11
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
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
In arch/x86/kernel/ima_arch.c (ffffffff8107c841)
Location: arch/x86/kernel/ima_arch.c:11
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
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
In arch/x86/kernel/ima_arch.c (ffffffff8107e941)
Location: arch/x86/kernel/ima_arch.c:11
Inline: True
Inline callers:
  - arch/x86/kernel/ima_arch.c:arch_ima_get_secureboot
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
