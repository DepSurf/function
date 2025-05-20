# Function: <code>irqd_cfg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81054d00)
Location: arch/x86/kernel/apic/vector.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:irq_cfg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
```
**Symbols:**

```
ffffffff81054d00-ffffffff81054d26: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81055736)
Location: arch/x86/kernel/apic/vector.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81054f40-ffffffff81054f66: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810586b6)
Location: arch/x86/kernel/apic/vector.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff81057d10-ffffffff81057d36: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irq_data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810576af)
Location: arch/x86/kernel/apic/vector.c:64
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_set_affinity
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - arch/x86/kernel/apic/htirq.c:htirq_domain_activate
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
```
**Symbols:**

```
ffffffff810574b0-ffffffff810574c8: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105ba6f)
Location: arch/x86/kernel/apic/vector.c:90
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
```
**Symbols:**

```
ffffffff8105b2f0-ffffffff8105b308: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8105f675)
Location: arch/x86/kernel/apic/vector.c:91
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
```
**Symbols:**

```
ffffffff8105e230-ffffffff8105e248: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810652e5)
Location: arch/x86/kernel/apic/vector.c:92
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
```
**Symbols:**

```
ffffffff81063ec0-ffffffff81063ed8: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810689c5)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81067580-ffffffff81067598: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81069335)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81067ec0-ffffffff81067ed8: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ec15)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff8106eae0-ffffffff8106eb04: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070165)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810700c0-ffffffff810700e4: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81070cb5)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_irqdomain_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81070c10-ffffffff81070c34: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8107c935)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff8107c890-ffffffff8107c8b4: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8108bd15)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff8108bc70-ffffffff8108bca0: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a01f5)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810a0130-ffffffff810a0160: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810a3175)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810a30b0-ffffffff810a30e0: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810aa0a5)
Location: arch/x86/kernel/apic/vector.c:100
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_msi_compose_msg
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:dmar_msi_compose_msg
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd/iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd/iommu.c:irq_remapping_activate
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/init.c:intcapxt_unmask_irq
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_activate
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_set_affinity
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810a9ff0-ffffffff810aa020: irqd_cfg (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81068e25)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff810679b0-ffffffff810679c8: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff81059195)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81057d20-ffffffff81057d38: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff810692d5)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81067e60-ffffffff81067e78: irqd_cfg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct irq_cfg *irqd_cfg(struct irq_data *irqd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106a9d5)
Location: arch/x86/kernel/apic/vector.c:89
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:apic_ack_edge
  - arch/x86/kernel/apic/vector.c:irq_cfg
Direct callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:check_timer
  - arch/x86/kernel/apic/io_apic.c:ioapic_configure_entry
  - arch/x86/kernel/apic/io_apic.c:ioapic_ack_level
  - arch/x86/kernel/apic/msi.c:msi_set_affinity
  - arch/x86/kernel/apic/msi.c:irq_msi_compose_msg
  - arch/x86/platform/uv/uv_irq.c:uv_domain_deactivate
  - arch/x86/platform/uv/uv_irq.c:uv_domain_activate
  - arch/x86/platform/uv/uv_irq.c:uv_set_irq_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_affinity
  - drivers/iommu/amd_iommu.c:amd_ir_set_vcpu_affinity
  - drivers/iommu/amd_iommu.c:irq_remapping_activate
  - drivers/iommu/amd_iommu.c:irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel_irq_remapping.c:intel_ir_set_affinity
  - drivers/iommu/intel_irq_remapping.c:intel_ir_reconfigure_irte
  - drivers/iommu/hyperv-iommu.c:hyperv_irq_remapping_activate
  - drivers/iommu/hyperv-iommu.c:hyperv_ir_set_affinity
```
**Symbols:**

```
ffffffff81069520-ffffffff81069538: irqd_cfg (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct irq_data *irqd</code>
</li>
<li>
<b>Param removed. </b>
<code>struct irq_data *irq_data</code>
</li>
</ul>
</details>
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
