# Function: <code>uv_early_read_mmr</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828ba96f)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
**Symbols:**

```
ffffffff828ba96f-ffffffff828baa01: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce05d3)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:71
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff82ce05d3-ffffffff82ce061a: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fcd071)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_tsc_check_sync
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff82fcd071-ffffffff82fcd0ff: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d7aed)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff831d7aed-ffffffff831d7b78: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff832ba9b2)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff832ba9b2-ffffffff832baa3d: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8346c4f8)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff8346c4f8-ffffffff8346c563: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e90d30)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff83e90d30-ffffffff83e90d93: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff836b4700)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:73
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff836b4700-ffffffff836b4763: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e5040)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:75
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_set_system_type
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_apic_socketid_shift
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
  - arch/x86/kernel/apic/x2apic_uv_x.c:early_get_pnodeid
```
**Symbols:**

```
ffffffff838e5040-ffffffff838e50a3: uv_early_read_mmr (STB_LOCAL)
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
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int uv_early_read_mmr(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bb99c)
Location: arch/x86/kernel/apic/x2apic_uv_x.c:68
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_acpi_madt_oem_check
```
**Symbols:**

```
ffffffff828bb99c-ffffffff828bba2e: uv_early_read_mmr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
