# Function: <code>uv_gam_range</code>

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
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct uv_gam_range_s *uv_gam_range(long unsigned int pa);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106d97d)
Location: arch/x86/include/asm/uv/uv_hub.h:454
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff810962b6)
Location: arch/x86/include/asm/uv/uv_hub.h:454
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_soc_phys_ram_to_gpa
```
**Symbols:**

```
ffffffff8106d97d-ffffffff8106d9f2: uv_gam_range (STB_LOCAL)
ffffffff81094ee0-ffffffff81094f59: uv_gam_range (STB_LOCAL)
ffffffff81097c8e-ffffffff81097ca2: uv_gam_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct uv_gam_range_s *uv_gam_range(long unsigned int pa);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81074d5f)
Location: arch/x86/include/asm/uv/uv_hub.h:400
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff8109b903)
Location: arch/x86/include/asm/uv/uv_hub.h:400
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_gpa
```
**Symbols:**

```
ffffffff81074d5f-ffffffff81074dd4: uv_gam_range (STB_LOCAL)
ffffffff8109a240-ffffffff8109a2b5: uv_gam_range (STB_LOCAL)
ffffffff8109cfa0-ffffffff8109cfb4: uv_gam_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct uv_gam_range_s *uv_gam_range(long unsigned int pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bd7760)
Location: arch/x86/include/asm/uv/uv_hub.h:390
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff81bd7760-ffffffff81bd77d5: uv_gam_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct uv_gam_range_s *uv_gam_range(long unsigned int pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81bc97de)
Location: arch/x86/include/asm/uv/uv_hub.h:390
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
**Symbols:**

```
ffffffff81bc97de-ffffffff81bc9853: uv_gam_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct uv_gam_range_s *uv_gam_range(long unsigned int pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81c9e350)
Location: arch/x86/include/asm/uv/uv_hub.h:390
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa
```
**Symbols:**

```
ffffffff81c9e350-ffffffff81c9e3c5: uv_gam_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct uv_gam_range_s *uv_gam_range(long unsigned int pa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff81e4d7fa)
Location: arch/x86/include/asm/uv/uv_hub.h:390
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_soc_phys_ram_to_gpa
```
**Symbols:**

```
ffffffff81e4d7fa-ffffffff81e4d862: uv_gam_range (STB_LOCAL)
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
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff83e9405e)
Location: arch/x86/include/asm/uv/uv_hub.h:390
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
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
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct uv_gam_range_s *uv_gam_range(long unsigned int pa);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff8106f04d)
Location: arch/x86/include/asm/uv/uv_hub.h:454
Inline: False
Direct callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/platform/uv/tlb_uv.c (ffffffff81097796)
Location: arch/x86/include/asm/uv/uv_hub.h:454
Inline: True
Direct callers:
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_bau_init
  - arch/x86/platform/uv/tlb_uv.c:uv_soc_phys_ram_to_gpa
```
**Symbols:**

```
ffffffff8106f04d-ffffffff8106f0c2: uv_gam_range (STB_LOCAL)
ffffffff810963a0-ffffffff81096419: uv_gam_range (STB_LOCAL)
ffffffff8109914e-ffffffff81099162: uv_gam_range.cold (STB_LOCAL)
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
