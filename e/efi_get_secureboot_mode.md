# Function: <code>efi_get_secureboot_mode</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81bd2de1)
Location: include/linux/efi.h:1110
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_get_secureboot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81bc5129)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_get_secureboot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81c97c9b)
Location: include/linux/efi.h:1105
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_get_secureboot
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81e470c6)
Location: include/linux/efi.h:1172
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_get_secureboot
```
```
In security/integrity/ima/ima_efi.c (ffffffff81648884)
Location: include/linux/efi.h:1172
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81044b72)
Location: include/linux/efi.h:1127
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_get_secureboot
```
```
In security/integrity/ima/ima_efi.c (ffffffff817015c4)
Location: include/linux/efi.h:1127
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81044cb2)
Location: include/linux/efi.h:1161
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_get_secureboot
```
```
In security/integrity/ima/ima_efi.c (ffffffff8173b664)
Location: include/linux/efi.h:1161
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff8104b1e2)
Location: include/linux/efi.h:1155
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_get_secureboot
```
```
In security/integrity/ima/ima_efi.c (ffffffff8177c224)
Location: include/linux/efi.h:1155
Inline: True
Inline callers:
  - security/integrity/ima/ima_efi.c:get_sb_mode
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
