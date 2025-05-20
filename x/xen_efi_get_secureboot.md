# Function: <code>xen_efi_get_secureboot</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff826d86a2)
Location: arch/x86/xen/efi.c:124
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
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
In arch/x86/xen/efi.c (ffffffff8288e6e1)
Location: arch/x86/xen/efi.c:112
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
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
In arch/x86/xen/efi.c (ffffffff828a5c87)
Location: arch/x86/xen/efi.c:112
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
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
In arch/x86/xen/efi.c (ffffffff828a8c8f)
Location: arch/x86/xen/efi.c:100
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff8102f892)
Location: arch/x86/xen/efi.c:100
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff8102f892-ffffffff8102f9ae: xen_efi_get_secureboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81bd2d90)
Location: arch/x86/xen/efi.c:97
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff81bd2d90-ffffffff81bd2ecf: xen_efi_get_secureboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81bc50df)
Location: arch/x86/xen/efi.c:97
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff81bc50df-ffffffff81bc5237: xen_efi_get_secureboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81c97c51)
Location: arch/x86/xen/efi.c:97
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff81c97c51-ffffffff81c97da9: xen_efi_get_secureboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81e4706b)
Location: arch/x86/xen/efi.c:97
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff81e4706b-ffffffff81e471e2: xen_efi_get_secureboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81044b10)
Location: arch/x86/xen/efi.c:97
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff81044b10-ffffffff81044c88: xen_efi_get_secureboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff81044c50)
Location: arch/x86/xen/efi.c:99
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff81044c50-ffffffff81044dc8: xen_efi_get_secureboot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum efi_secureboot_mode xen_efi_get_secureboot();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff8104b180)
Location: arch/x86/xen/efi.c:99
Inline: False
Direct callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
**Symbols:**

```
ffffffff8104b180-ffffffff8104b2f8: xen_efi_get_secureboot (STB_LOCAL)
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
In arch/x86/xen/efi.c (ffffffff82896c9f)
Location: arch/x86/xen/efi.c:100
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/efi.c (ffffffff828a9c8f)
Location: arch/x86/xen/efi.c:100
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
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
In arch/x86/xen/efi.c (ffffffff828a9c9f)
Location: arch/x86/xen/efi.c:100
Inline: True
Inline callers:
  - arch/x86/xen/efi.c:xen_efi_init
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
