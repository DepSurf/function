# Function: <code>xen_create_pci_msi_domain</code>

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
struct irq_domain *xen_create_pci_msi_domain();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff83020a72)
Location: arch/x86/pci/xen.c:450
Inline: False
```
**Symbols:**

```
ffffffff83020a72-ffffffff83020aaf: xen_create_pci_msi_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_domain *xen_create_pci_msi_domain();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff8322bc40)
Location: arch/x86/pci/xen.c:450
Inline: False
```
**Symbols:**

```
ffffffff8322bc40-ffffffff8322bc7d: xen_create_pci_msi_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_domain *xen_create_pci_msi_domain();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff83316465)
Location: arch/x86/pci/xen.c:450
Inline: False
```
**Symbols:**

```
ffffffff83316465-ffffffff833164a2: xen_create_pci_msi_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *xen_create_pci_msi_domain();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff834d0dd4)
Location: arch/x86/pci/xen.c:447
Inline: False
```
**Symbols:**

```
ffffffff834d0dd4-ffffffff834d0e1d: xen_create_pci_msi_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *xen_create_pci_msi_domain();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff83f14f30)
Location: arch/x86/pci/xen.c:449
Inline: False
```
**Symbols:**

```
ffffffff83f14f30-ffffffff83f14f79: xen_create_pci_msi_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *xen_create_pci_msi_domain();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff8373b6b0)
Location: arch/x86/pci/xen.c:451
Inline: False
```
**Symbols:**

```
ffffffff8373b6b0-ffffffff8373b6f9: xen_create_pci_msi_domain (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *xen_create_pci_msi_domain();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/xen.c (ffffffff83970030)
Location: arch/x86/pci/xen.c:451
Inline: False
```
**Symbols:**

```
ffffffff83970030-ffffffff83970079: xen_create_pci_msi_domain (STB_LOCAL)
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
