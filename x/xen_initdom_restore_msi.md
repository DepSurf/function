# Function: <code>xen_initdom_restore_msi</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool xen_initdom_restore_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/xen.c (0)
Location: arch/x86/pci/xen.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff81f11299-ffffffff81f112d6: xen_initdom_restore_msi.cold (STB_LOCAL)
ffffffff81e3e370-ffffffff81e3e4d3: xen_initdom_restore_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool xen_initdom_restore_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/xen.c (0)
Location: arch/x86/pci/xen.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff820b725e-ffffffff820b729b: xen_initdom_restore_msi.cold (STB_LOCAL)
ffffffff82017af0-ffffffff82017c53: xen_initdom_restore_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool xen_initdom_restore_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/xen.c (0)
Location: arch/x86/pci/xen.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff821385f4-ffffffff82138631: xen_initdom_restore_msi.cold (STB_LOCAL)
ffffffff82097ee0-ffffffff82098043: xen_initdom_restore_msi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool xen_initdom_restore_msi(struct pci_dev *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/pci/xen.c (0)
Location: arch/x86/pci/xen.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/apic/msi.c:arch_restore_msi_irqs
```
**Symbols:**

```
ffffffff8221a525-ffffffff8221a562: xen_initdom_restore_msi.cold (STB_LOCAL)
ffffffff8216f3c0-ffffffff8216f523: xen_initdom_restore_msi (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
