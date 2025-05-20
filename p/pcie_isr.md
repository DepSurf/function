# Function: <code>pcie_isr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
irqreturn_t pcie_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff81450550)
Location: drivers/pci/hotplug/pciehp_hpc.c:538
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff81450550-ffffffff814508b2: pcie_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
irqreturn_t pcie_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8149cd20)
Location: drivers/pci/hotplug/pciehp_hpc.c:538
Inline: False
Direct callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff8149cd20-ffffffff8149d0c3: pcie_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t pcie_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814bec5f)
Location: drivers/pci/hotplug/pciehp_hpc.c:652
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff814bec20-ffffffff814bec4c: pcie_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t pcie_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff814c93ef)
Location: drivers/pci/hotplug/pciehp_hpc.c:660
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff814c93b0-ffffffff814c93dc: pcie_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t pcie_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff815099c3)
Location: drivers/pci/hotplug/pciehp_hpc.c:657
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff81509980-ffffffff815099ac: pcie_isr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
irqreturn_t pcie_isr(int irq, void *dev_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8153a9b3)
Location: drivers/pci/hotplug/pciehp_hpc.c:630
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:int_poll_timeout
```
**Symbols:**

```
ffffffff8153a970-ffffffff8153a99f: pcie_isr (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
