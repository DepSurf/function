# Function: <code>init_irq_alloc_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055760)
Location: arch/x86/kernel/apic/vector.c:288
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
**Symbols:**

```
ffffffff81055760-ffffffff8105578e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810559e0)
Location: arch/x86/kernel/apic/vector.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
**Symbols:**

```
ffffffff810559e0-ffffffff81055a0e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058780)
Location: arch/x86/kernel/apic/vector.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
**Symbols:**

```
ffffffff81058780-ffffffff810587ae: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81057f60)
Location: arch/x86/kernel/apic/vector.c:297
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
  - arch/x86/kernel/apic/htirq.c:arch_setup_ht_irq
```
**Symbols:**

```
ffffffff81057f60-ffffffff81057f8e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105c4c0)
Location: arch/x86/kernel/apic/vector.c:64
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff8105c4c0-ffffffff8105c4ee: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f490)
Location: arch/x86/kernel/apic/vector.c:65
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff8105f490-ffffffff8105f4be: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81065110)
Location: arch/x86/kernel/apic/vector.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff81065110-ffffffff8106513e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068800)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff81068800-ffffffff8106882e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069170)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
**Symbols:**

```
ffffffff81069170-ffffffff8106919e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070150)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
**Symbols:**

```
ffffffff81070150-ffffffff8107017e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81071580)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/init.c:iommu_setup_intcapxt
```
**Symbols:**

```
ffffffff81071580-ffffffff810715bb: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81072080)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff81072080-ffffffff810720bb: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107df30)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff8107df30-ffffffff8107df6b: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108d520)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff8108d520-ffffffff8108d569: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a1bb0)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:pci_msi_prepare
  - arch/x86/kernel/apic/msi.c:x86_msi_prepare
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff810a1bb0-ffffffff810a1bf9: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a4b90)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:pci_msi_prepare
  - arch/x86/kernel/apic/msi.c:x86_msi_prepare
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/init.c:amd_iommu_enable_interrupts
```
**Symbols:**

```
ffffffff810a4b90-ffffffff810a4bd9: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810abbe0)
Location: arch/x86/kernel/apic/vector.c:74
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:pci_msi_prepare
  - arch/x86/kernel/apic/msi.c:x86_msi_prepare
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
  - drivers/iommu/amd/init.c:__iommu_setup_intcapxt
```
**Symbols:**

```
ffffffff810abbe0-ffffffff810abc29: init_irq_alloc_info (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068c60)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff81068c60-ffffffff81068c8e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81058fd0)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff81058fd0-ffffffff81058ffe: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069110)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff81069110-ffffffff8106913e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_irq_alloc_info(struct irq_alloc_info *info, const struct cpumask *mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a820)
Location: arch/x86/kernel/apic/vector.c:63
Inline: False
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_create
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/msi.c:hpet_assign_irq
  - arch/x86/kernel/apic/msi.c:hpet_create_irq_domain
  - arch/x86/kernel/apic/msi.c:dmar_alloc_hwirq
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
  - arch/x86/platform/uv/uv_irq.c:uv_setup_irq
```
**Symbols:**

```
ffffffff8106a820-ffffffff8106a84e: init_irq_alloc_info (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
