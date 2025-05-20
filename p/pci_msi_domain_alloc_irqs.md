# Function: <code>pci_msi_domain_alloc_irqs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_domain_alloc_irqs(struct irq_domain *domain, struct pci_dev *dev, int nvec, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff81453fd2)
Location: drivers/pci/msi.c:1303
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
Direct callers:
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff814553a0-ffffffff814553b7: pci_msi_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_domain_alloc_irqs(struct irq_domain *domain, struct pci_dev *dev, int nvec, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814a08f2)
Location: drivers/pci/msi.c:1438
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
Direct callers:
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff814a1fe0-ffffffff814a1ff7: pci_msi_domain_alloc_irqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pci_msi_domain_alloc_irqs(struct irq_domain *domain, struct pci_dev *dev, int nvec, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/msi.c (ffffffff814c2582)
Location: drivers/pci/msi.c:1504
Inline: True
Inline callers:
  - drivers/pci/msi.c:pci_msi_setup_msi_irqs
Direct callers:
  - arch/x86/kernel/apic/msi.c:native_setup_msi_irqs
```
**Symbols:**

```
ffffffff814c3c30-ffffffff814c3c47: pci_msi_domain_alloc_irqs (STB_GLOBAL)
```
</details>
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
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
