# Function: <code>uv_soc_phys_ram_to_nasid</code>

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
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd548)
Location: arch/x86/include/asm/uv/uv_hub.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097d5b)
Location: arch/x86/include/asm/uv/uv_hub.h:483
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_soc_phys_ram_to_gpa
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82ce1a7a)
Location: arch/x86/include/asm/uv/uv_hub.h:429
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109d090)
Location: arch/x86/include/asm/uv/uv_hub.h:429
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_gpa
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff82fce819)
Location: arch/x86/include/asm/uv/uv_hub.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff831d928a)
Location: arch/x86/include/asm/uv/uv_hub.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81c9e536)
Location: arch/x86/include/asm/uv/uv_hub.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81e4d97c)
Location: arch/x86/include/asm/uv/uv_hub.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff810a88f8)
Location: arch/x86/include/asm/uv/uv_hub.h:419
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828be575)
Location: arch/x86/include/asm/uv/uv_hub.h:483
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109921b)
Location: arch/x86/include/asm/uv/uv_hub.h:483
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_soc_phys_ram_to_gpa
```
</details>
</li>
</ul>

## Differences
