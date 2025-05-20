# Function: <code>hv_build_pci_dev_id</code>

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
union hv_device_id hv_build_pci_dev_id(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81033040)
Location: arch/x86/hyperv/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81033040-ffffffff81033169: hv_build_pci_dev_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
union hv_device_id hv_build_pci_dev_id(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff810381e0)
Location: arch/x86/hyperv/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_domain_free_irqs
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff810381e0-ffffffff81038309: hv_build_pci_dev_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
union hv_device_id hv_build_pci_dev_id(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8103e4b0)
Location: arch/x86/hyperv/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff8103e4b0-ffffffff8103e5fc: hv_build_pci_dev_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
union hv_device_id hv_build_pci_dev_id(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047390)
Location: arch/x86/hyperv/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81047390-ffffffff810474dc: hv_build_pci_dev_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
union hv_device_id hv_build_pci_dev_id(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff81047710)
Location: arch/x86/hyperv/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff81047710-ffffffff8104785c: hv_build_pci_dev_id (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
union hv_device_id hv_build_pci_dev_id(struct pci_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/irqdomain.c (ffffffff8104de50)
Location: arch/x86/hyperv/irqdomain.c:113
Inline: False
Direct callers:
  - arch/x86/hyperv/irqdomain.c:hv_msi_free_irq
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
**Symbols:**

```
ffffffff8104de50-ffffffff8104df9c: hv_build_pci_dev_id (STB_LOCAL)
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
