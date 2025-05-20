# Function: <code>is_uv4a_hub</code>

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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bc0d5)
Location: arch/x86/include/asm/uv/uv_hub.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828c9518)
Location: arch/x86/include/asm/uv/uv_hub.h:286
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int is_uv4a_hub();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074eb7)
Location: arch/x86/include/asm/uv/uv_hub.h:249
Inline: True
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109d196)
Location: arch/x86/include/asm/uv/uv_hub.h:249
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:activation_descriptor_init
```
**Symbols:**

```
ffffffff81074eb7-ffffffff81074edf: is_uv4a_hub (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff828bd102)
Location: arch/x86/include/asm/uv/uv_hub.h:286
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
  - arch/x86/kernel/apic/x2apic_uv_x.c:map_mmioh_high_uv34
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff828ca555)
Location: arch/x86/include/asm/uv/uv_hub.h:286
Inline: True
Inline callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
