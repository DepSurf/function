# Function: <code>uv_stringify</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1187)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:241
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uv_stringify(int len, char *to, char *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcd3bf)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff82fcd3bf-ffffffff82fcd3e5: uv_stringify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uv_stringify(int len, char *to, char *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d7ed0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff831d7ed0-ffffffff831d7ef6: uv_stringify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uv_stringify(int len, char *to, char *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bade6)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff832bade6-ffffffff832bae0c: uv_stringify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uv_stringify(int len, char *to, char *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346c8ac)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:295
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_arch_type
```
**Symbols:**

```
ffffffff8346c8ac-ffffffff8346c8e0: uv_stringify (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e917f1)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b6061)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:295
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uv_stringify(int len, char *to, char *from);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e52a0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:297
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff838e52a0-ffffffff838e52d5: uv_stringify (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
