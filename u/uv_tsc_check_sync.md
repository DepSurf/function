# Function: <code>uv_tsc_check_sync</code>

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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828baee7)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:141
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uv_tsc_check_sync();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce072f)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
**Symbols:**

```
ffffffff82ce072f-ffffffff82ce07d6: uv_tsc_check_sync (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uv_tsc_check_sync();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcd2db)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:195
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
**Symbols:**

```
ffffffff82fcd2db-ffffffff82fcd3bf: uv_tsc_check_sync (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d97b2)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832bc0d1)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346da13)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e9145e)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:195
Inline: True
Inline callers:
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b5cdf)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:195
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e586b)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:197
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bbf14)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:141
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
