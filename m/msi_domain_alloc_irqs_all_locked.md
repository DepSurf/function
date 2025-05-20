# Function: <code>msi_domain_alloc_irqs_all_locked</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int msi_domain_alloc_irqs_all_locked(struct device *dev, unsigned int domid, int nirqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811a59c0)
Location: kernel/irq/msi.c:1435
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
```
**Symbols:**

```
ffffffff811a59c0-ffffffff811a5a6c: msi_domain_alloc_irqs_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int msi_domain_alloc_irqs_all_locked(struct device *dev, unsigned int domid, int nirqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811b7c20)
Location: kernel/irq/msi.c:1432
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
```
**Symbols:**

```
ffffffff811b7c20-ffffffff811b7d0f: msi_domain_alloc_irqs_all_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int msi_domain_alloc_irqs_all_locked(struct device *dev, unsigned int domid, int nirqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/msi.c (ffffffff811c7ae0)
Location: kernel/irq/msi.c:1422
Inline: False
Direct callers:
  - drivers/pci/msi/irqdomain.c:pci_msi_setup_msi_irqs
```
**Symbols:**

```
ffffffff811c7ae0-ffffffff811c7bcf: msi_domain_alloc_irqs_all_locked (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
