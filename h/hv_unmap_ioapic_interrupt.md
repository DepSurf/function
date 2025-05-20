# Function: <code>hv_unmap_ioapic_interrupt</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81033250)
Location: arch/x86/hyperv/irqdomain.c:362
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff81033250-ffffffff81033270: hv_unmap_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810383f0)
Location: arch/x86/hyperv/irqdomain.c:362
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff810383f0-ffffffff81038410: hv_unmap_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e6e0)
Location: arch/x86/hyperv/irqdomain.c:341
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff8103e6e0-ffffffff8103e707: hv_unmap_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810475e0)
Location: arch/x86/hyperv/irqdomain.c:341
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff810475e0-ffffffff81047607: hv_unmap_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047960)
Location: arch/x86/hyperv/irqdomain.c:341
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff81047960-ffffffff81047987: hv_unmap_ioapic_interrupt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hv_unmap_ioapic_interrupt(int ioapic_id, struct hv_interrupt_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e1d0)
Location: arch/x86/hyperv/irqdomain.c:341
Inline: False
Direct callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_free
  - drivers/iommu/hyperv-iommu.c:hyperv_root_ir_compose_msi_msg
```
**Symbols:**

```
ffffffff8104e1d0-ffffffff8104e1f7: hv_unmap_ioapic_interrupt (STB_GLOBAL)
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
