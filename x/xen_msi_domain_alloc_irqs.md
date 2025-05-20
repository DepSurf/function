# Function: <code>xen_msi_domain_alloc_irqs</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xen_msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81bcb080)
Location: arch/x86/pci/xen.c:408
Inline: False
```
**Symbols:**

```
ffffffff81bcb080-ffffffff81bcb0ce: xen_msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xen_msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81bbe9c0)
Location: arch/x86/pci/xen.c:408
Inline: False
```
**Symbols:**

```
ffffffff81bbe9c0-ffffffff81bbea0d: xen_msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xen_msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81c8e920)
Location: arch/x86/pci/xen.c:408
Inline: False
```
**Symbols:**

```
ffffffff81c8e920-ffffffff81c8e96d: xen_msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xen_msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff81e3d9e0)
Location: arch/x86/pci/xen.c:408
Inline: False
```
**Symbols:**

```
ffffffff81e3d9e0-ffffffff81e3da3d: xen_msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xen_msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff82016f80)
Location: arch/x86/pci/xen.c:409
Inline: False
```
**Symbols:**

```
ffffffff82016f80-ffffffff82016fdd: xen_msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xen_msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff82097330)
Location: arch/x86/pci/xen.c:411
Inline: False
```
**Symbols:**

```
ffffffff82097330-ffffffff8209738d: xen_msi_domain_alloc_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xen_msi_domain_alloc_irqs(struct irq_domain *domain, struct device *dev, int nvec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff8216e810)
Location: arch/x86/pci/xen.c:411
Inline: False
```
**Symbols:**

```
ffffffff8216e810-ffffffff8216e86d: xen_msi_domain_alloc_irqs (STB_LOCAL)
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
