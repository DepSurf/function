# Function: <code>early_get_apic_socketid_shift</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bac94)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:225
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1369)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:215
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fced18)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:278
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void early_get_apic_socketid_shift();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d7b78)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff831d7b78-ffffffff831d7cf4: early_get_apic_socketid_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void early_get_apic_socketid_shift();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832baa3d)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:278
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff832baa3d-ffffffff832babb9: early_get_apic_socketid_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void early_get_apic_socketid_shift();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346c563)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:284
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff8346c563-ffffffff8346c6db: early_get_apic_socketid_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void early_get_apic_socketid_shift();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e90f90)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:284
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff83e90f90-ffffffff83e9115c: early_get_apic_socketid_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void early_get_apic_socketid_shift();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b4960)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:284
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff836b4960-ffffffff836b4b3c: early_get_apic_socketid_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void early_get_apic_socketid_shift();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e52f0)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:286
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff838e52f0-ffffffff838e54cc: early_get_apic_socketid_shift (STB_LOCAL)
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
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bbcc1)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:225
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
